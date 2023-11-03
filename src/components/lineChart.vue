<template>
    <Line :data="chartConfig.data" :options="{...chartConfig.options,  plugins: {
    title: {
      display: true,
      text: props.title,
    },
    }}" />
</template>

<script setup lang="ts">
import {
  Chart as ChartJS,
  CategoryScale,
  LinearScale,
  PointElement,
  LineElement,
  Title,
  Tooltip,
  Legend
} from 'chart.js'
import { Line } from 'vue-chartjs'
import * as chartConfig from './dataChart'

ChartJS.register(
  CategoryScale,
  LinearScale,
  PointElement,
  LineElement,
  Title,
  Tooltip,
  Legend
)
const props = defineProps({
  title: String
})

</script>
