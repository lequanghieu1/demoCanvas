<script setup>
import { ref, watch } from "vue";
const props = defineProps({
  type: {
    type: String,
    default: "",
  },
  modelValue: [String, Number],
});
const val = ref(props.modelValue);
const emit = defineEmits(["update:modelValue"]);
const typeOnlyNumber = ["zip", "phone"];
const formatMac = () => {
  const result = (
    val.value?.replace(/[^\d|a-f0-9A-F]/g, "").match(/.{1,2}/g) || []
  )
    .join("-")
    .substr(0, 50);
  val.value = result;
};
const checkNumber = () => {
  if (props.type === "mac") {
    formatMac();
  }
  if (!typeOnlyNumber.includes(props.type)) return;
  const regNumber = RegExp(/[^0-9]/g);
  val.value = val.value?.replace(regNumber, "").replace(/(\..*)\./g, "$1");
};

const formatInput = () => {
  if (!typeOnlyNumber.includes(props.type)) return;
  if (!val.value?.includes("-")) {
    const length = val.value?.length;
    const replacer = `$1${length > 7 ? "-$2-$3" : length > 3 ? "-$2" : ""}`;

    const REG = {
      10: new RegExp(/^(\d{2})?(\d{1,4})?(\d{1,4})?/g),
      11: new RegExp(/^(\d{3})?(\d{1,4})?(\d{1,4})?/g),
    };
    val.value =
      props.type === "zip"
        ? val.value?.replace(/^(\d{3})(\d{1,4})?/g, replacer).substr(0, 8)
        : val.value
            ?.replace(REG[val.value.length === 10 ? 10 : 11], replacer)
            .substr(0, 13);
  }
};

const cleanFormat = () => {
  if (!typeOnlyNumber.includes(props.type)) return;
  val.value = val.value?.replaceAll("-", "");
};
watch(
  () => val.value,
  () => {
    if ([typeOnlyNumber, "mac"].includes(props.type)) {
      emit("update:modelValue", val.value.replaceAll("-", ""));
    }
    emit("update:modelValue", val.value);
  }
);
</script>
<template>
  <input
    v-model="val"
    v-bind="props"
    class="input"
    @blur="formatInput"
    @focus="cleanFormat"
    @input="checkNumber"
  />
</template>
<style>
.input {
  padding: 0px 5px;
}
</style>
