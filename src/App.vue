<script setup>
import dialogModel from './components/dialog.vue'
import chacoal from './components/chacoal.vue'
import {ref} from "vue"
const visible = ref(false)
const openDialog = (value = true) => {
  visible.value = value
}
const mode = ref(true)
</script>

<template>
  <button @click="mode=!mode">change mode</button>
  <div v-if="mode" class="wrap">
    <div >
      <div>
        <svg id="sidebarBox1" viewBox="0 0 1230 720">
          <g>
            //song huong
            <g transform="translate(0 15)">
              <path
                fill="#56b8e7"
                stroke="none"
                d="m20,130q-35 105,0 210t0 210h130q35 -105,0 -210t0 -210z"
              ></path>
              <path
                fill="none"
                stroke="#2881ab"
                stroke-width="3"
                d="m20,130q-35 105,0 210t0 210"
              ></path>
              <path
                fill="none"
                stroke="#2881ab"
                stroke-width="3"
                d="m150,130q-35 105,0 210t0 210"
              ></path>
              <text
                transform="translate(90,400) rotate(-90)"
                fill="#444"
                class="fz-16 bold"
                x="0"
                y="0"
              >
                SÔNG HƯƠNG
              </text>
            </g>
            <g transform="translate(200 160)">
              <path
                fill="#bbb"
                stroke="#4c4c4c"
                d="m10,50h170v300h-170z"
              ></path>
              <path
                fill="#fff"
                stroke="#4C4C4C"
                d="m15,55h160v142.5h-160z"
              ></path>
              <path
                fill="#fff"
                stroke="#4C4C4C"
                d="m15,202.5h160v142.5h-160z"
              ></path>
              <path
                fill="#56b8e7"
                stroke="none"
                opacity="0.7"
                d="m15,55h159v142.5h-159z"
              ></path>
              <path
                fill="#56b8e7"
                stroke="none"
                opacity="0.7"
                d="m15,202.5h159v142.5h-159z"
              ></path>
              <text fill="#555" class="ft-105 bold" x="50" y="42">
                BỂ LẮNG CÁT 1
              </text>
              <text fill="#555" class="ft-105 bold" x="50" y="369">
                BỂ LẮNG CÁT 2
              </text>
              <path
                fill="none"
                stroke="#0080ff"
                stroke-width="2.5"
                d="m-65,125h75"
              ></path>
              <path
                fill="none"
                stroke="#0080ff"
                stroke-width="2.5"
                d="m-32,275h42"
              ></path>
              <path fill="#bbb" stroke="#4C4C4C" d="m-70,114h9v23h-9z"></path>
              <path fill="#bbb" stroke="#4C4C4C" d="m-38,264h9v23h-9z"></path>
              <path
                fill="none"
                stroke="#9b957f"
                stroke-width="2.5"
                d="m120,273v-175a3,3 0 0 0 -3-3h-176"
              ></path>
              <path
                fill="none"
                stroke="#9b957f"
                stroke-width="2.5"
                d="m85,129v-33"
              ></path>
              <path
                fill="none"
                stroke="#56b8e7"
                stroke-width="3"
                d="m180,128h48"
              ></path>
              <path
                fill="none"
                stroke="#56b8e7"
                stroke-width="3"
                d="m180,271h48"
              ></path>
            </g>
            <g transform="translate(420 10)">
              <path fill="#bbb" stroke="#4c4c4c" d="m10,0h210v700h-210z"></path>
              <path
                fill="#fff"
                stroke="#4C4C4C"
                d="m15,5h200v342.5h-200z"
              ></path>
              <path
                fill="#fff"
                stroke="#4C4C4C"
                d="m15,352.5h200v342.5h-200z"
              ></path>
              <path
                fill="#56b8e7"
                stroke="none"
                opacity="0.7"
                d="m15,5h199v342.5h-199z"
              ></path>
              <path
                fill="#56b8e7"
                stroke="none"
                opacity="0.7"
                d="m15,352.5h199v342.5h-199z"
              ></path>
              <path
                fill="#ceca00"
                stroke="#4C4C4C"
                d="m87,345h55v10h-55z"
              ></path>
              <path
                fill="#ceca00"
                stroke="#4C4C4C"
                d="m7,408h10v26h-10z"
              ></path>
              <path
                fill="#ceca00"
                stroke="#4C4C4C"
                d="m7,265h10v26h-10z"
              ></path>
              <text fill="#555" class="ft-105 bold" x="60" y="180">
                BỂ NƯỚC THÔ 1
              </text>
              <text fill="#555" class="ft-105 bold" x="60" y="520">
                BỂ NƯỚC THÔ 2
              </text>
              <path
                fill="none"
                stroke="#56b8e7"
                stroke-width="3"
                d="m220,672h100v-18h229a3,3 0 0 0 3-3v-634a3,3 0 0 1 3-3h240"
              ></path>
              <path
                fill="none"
                stroke="#56b8e7"
                stroke-width="3"
                d="m221,86h100v-18h231 m0,95h-231v18h-100 m0,95h100v-18h231"
              ></path>
              <path
                fill="none"
                stroke="#56b8e7"
                stroke-width="3"
                d="m221,577h100v-18h231 m0-95h-231v18h-100"
              ></path>
            </g>
            <g transform="translate(660 80.5) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="12"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m1,10v13l21-13v13z"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m11.5,17v-12"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m4,5h15"
                ></path>
              </g>
            </g>
            <g transform="translate(660 175.5) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="12"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m1,10v13l21-13v13z"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m11.5,17v-12"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m4,5h15"
                ></path>
              </g>
            </g>
            <g transform="translate(660 270.5) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="12"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m1,10v13l21-13v13z"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m11.5,17v-12"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m4,5h15"
                ></path>
              </g>
            </g>
            <g transform="translate(660 476.5) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="12"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m1,10v13l21-13v13z"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m11.5,17v-12"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m4,5h15"
                ></path>
              </g>
            </g>
            <g transform="translate(660 571.5) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="12"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m1,10v13l21-13v13z"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m11.5,17v-12"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m4,5h15"
                ></path>
              </g>
            </g>
            <g transform="translate(660 666.5) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="12"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m1,10v13l21-13v13z"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m11.5,17v-12"
                ></path>
                <path
                  stroke-width="0.5"
                  fill="#c0c0c0"
                  stroke="#000"
                  d="m4,5h15"
                ></path>
              </g>
            </g>
            <g transform="translate(865 63) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="10"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#fff"
                  stroke="#000"
                  d="m1,23v-13l21 13v-13"
                ></path>
              </g>
            </g>
            <g transform="translate(865 158) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="10"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#fff"
                  stroke="#000"
                  d="m1,23v-13l21 13v-13"
                ></path>
              </g>
            </g>
            <g transform="translate(865 253) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="10"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#fff"
                  stroke="#000"
                  d="m1,23v-13l21 13v-13"
                ></path>
              </g>
            </g>
            <g transform="translate(865 458) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="10"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#fff"
                  stroke="#000"
                  d="m1,23v-13l21 13v-13"
                ></path>
              </g>
            </g>
            <g transform="translate(865 553) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="10"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#fff"
                  stroke="#000"
                  d="m1,23v-13l21 13v-13"
                ></path>
              </g>
            </g>
            <g transform="translate(865 648) scale(0.9 0.9)">
              <g>
                <rect
                  x="5"
                  y="12"
                  fill="#fff"
                  stroke="none"
                  width="15"
                  height="10"
                ></rect>
                <path
                  stroke-width="0.5"
                  fill="#fff"
                  stroke="#000"
                  d="m1,23v-13l21 13v-13"
                ></path>
              </g>
            </g>
            <path
              transform="translate(1205 19)"
              fill="#999"
              stroke="#999"
              d="m10,10l8,-5l-8,-5"
            ></path>
            <path
              transform="translate(132 240)"
              fill="#999"
              stroke="#999"
              d="m10,10l-8,5l8,5"
            ></path>
            <text fill="#555" class="ft-11" x="1070" y="15">
              Đến thiết bị trộn tĩnh
            </text>
            <text fill="#555" class="ft-11" x="210" y="150">Javen</text>
            <text fill="#555" class="ft-11" x="210" y="580">Javen</text>
            <text fill="#555" class="ft-11" x="145" y="248">Xả bùn</text>
            <text fill="#777" class="ft-105" x="731" y="132">NT1</text>
            <text fill="#777" class="ft-105" x="731" y="227">NT2</text>
            <text fill="#777" class="ft-105" x="731" y="322">NT3</text>
            <text fill="#777" class="ft-105" x="731" y="851">NT4</text>
            <text fill="#777" class="ft-105" x="731" y="946">NT5</text>
            <text fill="#777" class="ft-105" x="731" y="719">NT6</text>
            <text fill="#777" class="ft-11" x="1085" y="400">BƠM RÒ RỈ</text>
            <text fill="#777" class="ft-11" x="1060" y="60">
              <tspan text-anchor="end">Vôi</tspan>
            </text>
            <text fill="#777" class="ft-11" x="1060" y="85">
              <tspan text-anchor="end">PAC</tspan>
            </text>
            <text fill="#777" class="ft-11" x="1060" y="110">
              <tspan text-anchor="end">Than</tspan>
            </text>
            <text fill="#777" class="ft-11" x="1060" y="135">
              <tspan text-anchor="end">Polymer</tspan>
            </text>
            <text fill="#777" class="ft-11" x="1060" y="160">
              <tspan text-anchor="end">Lưu lượng</tspan>
            </text>
            <text fill="#777" class="ft-11" x="1060" y="185">
              <tspan text-anchor="end">Nước Thô</tspan>
            </text>
          </g>
          <g
            id="yfh9raAPMiSym38cJ"
            transform="translate(1053 125)"
            class="cursor"
          >
            <g transform="translate(-24 -24)">
              <g>
                <rect x="55" y="48" fill="#000" width="100" height="18"></rect>
                <text
                  transform="translate(30 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(39 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">bar</tspan>
                </text>
                <rect x="55" y="68" fill="#000" width="100" height="18"></rect>
                <text
                  transform="translate(30 25)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">3824.63</tspan>
                </text>
                <text
                  transform="translate(39 25)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">m3/h</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="qeL6qufsMEvfDdfwh"
            transform="translate(465 172)"
            class="cursor"
          >
            <g transform="translate(-19 -22)">
              <g>
                <rect x="55" y="48" fill="#000" width="75" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(14 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">m</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="Nkgou2YpBpBkeguAi"
            transform="translate(465 510)"
            class="cursor"
          >
            <g transform="translate(-19 -22)">
              <g>
                <rect x="55" y="48" fill="#000" width="75" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(14 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">m</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="GJggBPabvCGazxqyv"
            transform="translate(675 -1)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(35 68)">
              <g transform="scale(0.1 0.1)">
                <g transform="rotate(0)">
                  <path
                    fill="#989898"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M135,479h82l84-125l84 125h82l-41-145 h-247l-41 145z"
                  ></path>
                  <g transform="translate(480 335)">
                    <rect
                      x="-434"
                      y="-136"
                      fill="#BEBEBE"
                      stroke="#000"
                      width="106"
                      height="158"
                    ></rect>
                  </g>
                  <g>
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="translate(-295 178)">
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="rotate(-45,162,-260)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#E5E5E5"></path>
                  </g>
                  <g transform="rotate(135,100,288)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#CCC"></path>
                  </g>
                  <circle cx="302.6" cy="230" r="188" fill="#f86c6b"></circle>
                  <circle fill="#BEBEBE" cx="302.6" cy="230" r="107"></circle>
                  <circle fill="#4C4C4C" cx="302.6" cy="230" r="80"></circle>
                  <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  <g transform="rotate(60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <g transform="rotate(-60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <circle fill="#E5E5E5" cx="302.6" cy="230" r="18"></circle>
                  <g transform="rotate(-45,162,-260)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(135,100,290)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,0,0)">
                    <path
                      d="M238,376a50,50 0 1,0 -375,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,189,452)">
                    <path
                      d="M238,376a50,50 0 1,0 375,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-140,191,68)">
                    <path
                      d="M125,185a210,210 0 1,0 -249,1l-38 32l103 122l190-160"
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                    ></path>
                  </g>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M93,480h146v-21h-146z"
                  ></path>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M365,480h146v-21h-146z"
                  ></path>
                  <g>
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                  <g transform="translate(-544 176)">
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <g transform="translate(44 -11)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">Hz</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 8)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">kW</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 37)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">A</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 56)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">V</tspan>
                </text>
              </g>
            </g>
            <rect
              x="35"
              y="68"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
              @click="openDialog"
            ></rect>
          </g>
          <g
            id="WpbXT9P4LCWNt9ozs"
            transform="translate(254 266)"
            class="cursor"
          >
            <g transform="translate(26 17)">
              <g transform="scale(0.4 0.4)">
                <g transform="rotate(0)">
                  <g id="Group_Upstream_Pipe_Flange">
                    <lineargradient
                      id="SVGID_1_Obj_1_WpbXT9P4LCWNt9ozs"
                      gradientUnits="userSpaceOnUse"
                      x1="6.1948"
                      y1="106.8125"
                      x2="15.8789"
                      y2="106.8125"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="url(#SVGID_1_Obj_1_WpbXT9P4LCWNt9ozs)"
                      d="M15.879,1.464V9.91H6.195V1.464H15.879"
                    ></path>
                    <path
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M2.141,0h19.37v1.464H2.141V0z"
                      fill="#f86c6b"
                    ></path>
                  </g>
                  <g id="Group_Volute_Chamber">
                    <lineargradient
                      id="SVGID_2_Obj_1_WpbXT9P4LCWNt9ozs"
                      gradientUnits="userSpaceOnUse"
                      x1="3.042"
                      y1="67.3984"
                      x2="48.0859"
                      y2="67.3984"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="#fff"
                      d="M48.086,9.91v70.383H3.042V9.91H48.086"
                    ></path>
                    <path
                      fill="url(#SVGID_2_Obj_1_WpbXT9P4LCWNt9ozs)"
                      d="M48.086,9.91v70.383H3.042V9.91H48.086"
                    ></path>
                  </g>
                  <g id="Group_Filter">
                    <path
                      fill="#333333"
                      d="M0.001,93.131l3.041-12.838h45.045l3.153,12.838H0.001z"
                    ></path>
                    <path
                      opacity="0.5"
                      d="M0.001,93.131l3.041-12.838h45.045l3.153,12.838H0.001z"
                      fill="#f86c6b"
                    ></path>
                  </g>
                  <g id="Group_Humidifier">
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M0.001,93.131l3.041-12.838h3.153L3.042,93.131H0.001z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M11.825,93.131l0.338-1.689l0.225-1.575l0.113-1.577l0.225-1.576   l0.226-1.577l0.112-1.688l0.226-1.576l0.112-1.576h3.378l-0.113,1.576l-0.225,1.576l-0.225,1.688l-0.225,1.577l-0.226,1.576   l-0.112,1.577l-0.225,1.575l-0.226,1.689H11.825z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M17.906,93.131l0.226-1.689l0.112-1.575l0.113-1.577l0.113-1.576   l0.112-1.577l0.113-1.688l0.112-1.576v-1.576h3.153v1.576l-0.113,1.576l-0.112,1.688l-0.113,1.577l-0.112,1.576l-0.113,1.577   l-0.113,1.575l-0.225,1.689H17.906z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M23.987,93.131v-0.789V80.293h3.153v12.838H23.987z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M30.068,93.131l-0.112-1.689v-1.575l-0.113-1.577l-0.112-1.576   l-0.113-1.577l-0.113-1.688l-0.112-1.576l-0.226-1.576h3.153l0.225,1.576l0.113,1.576l0.113,1.688l0.112,1.577l0.113,1.576   l0.113,1.577v1.575l0.112,1.689H30.068z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M36.15,93.131l-0.226-1.689l-0.225-1.575l-0.225-1.577l-0.225-1.576   l-0.226-1.577l-0.225-1.688l-0.225-1.576l-0.226-1.576h3.378l0.226,1.576l0.112,1.576l0.226,1.688l0.225,1.577l0.225,1.576   l0.225,1.577l0.226,1.575l0.112,1.689H36.15z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M48.086,93.131l-3.378-12.838h3.378l3.152,12.838H48.086z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M42.005,93.131l-0.225-1.689l-0.338-1.575l-0.225-1.577l-0.338-1.576   l-0.338-1.577l-0.338-1.688l-0.338-1.576l-0.338-1.576h3.377l0.339,1.576l0.338,1.576l0.226,1.688l0.338,1.577l0.338,1.576   l0.227,1.577l0.338,1.575l0.338,1.689H42.005z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M5.97,93.131l0.337-1.689l0.338-1.575l0.338-1.577l0.225-1.576   l0.338-1.577l0.226-1.688l0.225-1.576l0.225-1.576H11.6l-0.225,1.576l-0.338,1.576l-0.338,1.688l-0.338,1.577l-0.225,1.576   l-0.338,1.577L9.46,91.441L9.122,93.13L5.97,93.131L5.97,93.131z"
                    ></path>
                  </g>
                  <g id="Group_Holder">
                    <lineargradient
                      id="SVGID_3_Obj_1_WpbXT9P4LCWNt9ozs"
                      gradientUnits="userSpaceOnUse"
                      x1="9.765625e-004"
                      y1="92.4551"
                      x2="51.2402"
                      y2="92.4551"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="url(#SVGID_3_Obj_1_WpbXT9P4LCWNt9ozs)"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M51.24,17.68v4.73H0.001v-4.73H51.24"
                    ></path>
                    <path
                      fill="#B2B2B2"
                      d="M6.195,22.41h4.842v-6.307H6.195V22.41z"
                    ></path>
                    <path
                      fill="#7F7F7F"
                      d="M14.303,22.41h-3.266v-6.307h3.266V22.41z"
                    ></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M6.195,22.41h8.108v-6.307H6.195V22.41"
                    ></path>
                    <path
                      fill="#B2B2B2"
                      d="M36.825,22.41h4.73v-6.307h-4.73V22.41z"
                    ></path>
                    <path
                      fill="#7F7F7F"
                      d="M44.708,22.41h-3.153v-6.307h3.153V22.41z"
                    ></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M36.825,22.41h7.883v-6.307h-7.883V22.41"
                    ></path>
                  </g>
                  <g id="Group_Label2">
                    <path
                      fill="#E5E5E5"
                      d="M6.195,36.824h25.676V53.04H6.195V36.824z"
                    ></path>
                  </g>
                  <g id="Group_Label1">
                    <path
                      fill="#E5E5E5"
                      d="M6.195,35.248h25.676v-3.153H6.195V35.248z"
                    ></path>
                  </g>
                  <g id="Group_MakeUp_Tank">
                    <path
                      fill="#666666"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M51.24,93.131l3.152-7.883h25.901l3.151,7.883H51.24z"
                    ></path>
                    <lineargradient
                      id="SVGID_4_Obj_1_WpbXT9P4LCWNt9ozs"
                      gradientUnits="userSpaceOnUse"
                      x1="54.3926"
                      y1="27.3643"
                      x2="80.2939"
                      y2="27.3643"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="#fff"
                      d="M80.294,77.141v15.99H54.393v-15.99H80.294"
                    ></path>
                    <path
                      fill="url(#SVGID_4_Obj_1_WpbXT9P4LCWNt9ozs)"
                      d="M80.294,77.141v15.99H54.393v-15.99H80.294"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M67.23,93.131v-7.883l1.803,7.883H67.23z"
                    ></path>
                  </g>
                  <g id="Group_Base">
                    <lineargradient
                      id="SVGID_5_Obj_1_WpbXT9P4LCWNt9ozs"
                      gradientUnits="userSpaceOnUse"
                      x1="9.765625e-004"
                      y1="9.6846"
                      x2="83.4473"
                      y2="9.6846"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="#fff"
                      d="M83.447,93.131V112.5H0.001V93.131H83.447"
                    ></path>
                    <path
                      fill="url(#SVGID_5_Obj_1_WpbXT9P4LCWNt9ozs)"
                      d="M83.447,93.131V112.5H0.001V93.131H83.447"
                    ></path>
                    <path
                      fill="none"
                      stroke="#E5E5E5"
                      stroke-width="0.25"
                      d="M0.001,99.662h83.446"
                    ></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M0.001,98.762h83.446"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="eAEWkRCGpNWCP66qT"
            transform="translate(676 96)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(35 68)">
              <g transform="scale(0.1 0.1)">
                <g transform="rotate(0)">
                  <path
                    fill="#989898"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M135,479h82l84-125l84 125h82l-41-145 h-247l-41 145z"
                  ></path>
                  <g transform="translate(480 335)">
                    <rect
                      x="-434"
                      y="-136"
                      fill="#BEBEBE"
                      stroke="#000"
                      width="106"
                      height="158"
                    ></rect>
                  </g>
                  <g>
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="translate(-295 178)">
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="rotate(-45,162,-260)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#E5E5E5"></path>
                  </g>
                  <g transform="rotate(135,100,288)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#CCC"></path>
                  </g>
                  <circle cx="302.6" cy="230" r="188" fill="#f86c6b"></circle>
                  <circle fill="#BEBEBE" cx="302.6" cy="230" r="107"></circle>
                  <circle fill="#4C4C4C" cx="302.6" cy="230" r="80"></circle>
                  <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  <g transform="rotate(60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <g transform="rotate(-60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <circle fill="#E5E5E5" cx="302.6" cy="230" r="18"></circle>
                  <g transform="rotate(-45,162,-260)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(135,100,290)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,0,0)">
                    <path
                      d="M238,376a50,50 0 1,0 -375,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,189,452)">
                    <path
                      d="M238,376a50,50 0 1,0 375,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-140,191,68)">
                    <path
                      d="M125,185a210,210 0 1,0 -249,1l-38 32l103 122l190-160"
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                    ></path>
                  </g>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M93,480h146v-21h-146z"
                  ></path>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M365,480h146v-21h-146z"
                  ></path>
                  <g>
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                  <g transform="translate(-544 176)">
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <g transform="translate(44 -11)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">Hz</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 8)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">kW</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 37)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">A</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 56)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">V</tspan>
                </text>
              </g>
            </g>
            <rect
              x="35"
              y="68"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="jPqSf5dSztwQXBK2D"
            transform="translate(289 411)"
            class="cursor"
          >
            <g transform="translate(26 17)">
              <g transform="scale(0.4 0.4)">
                <g transform="rotate(0)">
                  <g id="Group_Upstream_Pipe_Flange">
                    <lineargradient
                      id="SVGID_1_Obj_1_jPqSf5dSztwQXBK2D"
                      gradientUnits="userSpaceOnUse"
                      x1="6.1948"
                      y1="106.8125"
                      x2="15.8789"
                      y2="106.8125"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="url(#SVGID_1_Obj_1_jPqSf5dSztwQXBK2D)"
                      d="M15.879,1.464V9.91H6.195V1.464H15.879"
                    ></path>
                    <path
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M2.141,0h19.37v1.464H2.141V0z"
                      fill="#f86c6b"
                    ></path>
                  </g>
                  <g id="Group_Volute_Chamber">
                    <lineargradient
                      id="SVGID_2_Obj_1_jPqSf5dSztwQXBK2D"
                      gradientUnits="userSpaceOnUse"
                      x1="3.042"
                      y1="67.3984"
                      x2="48.0859"
                      y2="67.3984"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="#fff"
                      d="M48.086,9.91v70.383H3.042V9.91H48.086"
                    ></path>
                    <path
                      fill="url(#SVGID_2_Obj_1_jPqSf5dSztwQXBK2D)"
                      d="M48.086,9.91v70.383H3.042V9.91H48.086"
                    ></path>
                  </g>
                  <g id="Group_Filter">
                    <path
                      fill="#333333"
                      d="M0.001,93.131l3.041-12.838h45.045l3.153,12.838H0.001z"
                    ></path>
                    <path
                      opacity="0.5"
                      d="M0.001,93.131l3.041-12.838h45.045l3.153,12.838H0.001z"
                      fill="#f86c6b"
                    ></path>
                  </g>
                  <g id="Group_Humidifier">
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M0.001,93.131l3.041-12.838h3.153L3.042,93.131H0.001z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M11.825,93.131l0.338-1.689l0.225-1.575l0.113-1.577l0.225-1.576   l0.226-1.577l0.112-1.688l0.226-1.576l0.112-1.576h3.378l-0.113,1.576l-0.225,1.576l-0.225,1.688l-0.225,1.577l-0.226,1.576   l-0.112,1.577l-0.225,1.575l-0.226,1.689H11.825z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M17.906,93.131l0.226-1.689l0.112-1.575l0.113-1.577l0.113-1.576   l0.112-1.577l0.113-1.688l0.112-1.576v-1.576h3.153v1.576l-0.113,1.576l-0.112,1.688l-0.113,1.577l-0.112,1.576l-0.113,1.577   l-0.113,1.575l-0.225,1.689H17.906z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M23.987,93.131v-0.789V80.293h3.153v12.838H23.987z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M30.068,93.131l-0.112-1.689v-1.575l-0.113-1.577l-0.112-1.576   l-0.113-1.577l-0.113-1.688l-0.112-1.576l-0.226-1.576h3.153l0.225,1.576l0.113,1.576l0.113,1.688l0.112,1.577l0.113,1.576   l0.113,1.577v1.575l0.112,1.689H30.068z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M36.15,93.131l-0.226-1.689l-0.225-1.575l-0.225-1.577l-0.225-1.576   l-0.226-1.577l-0.225-1.688l-0.225-1.576l-0.226-1.576h3.378l0.226,1.576l0.112,1.576l0.226,1.688l0.225,1.577l0.225,1.576   l0.225,1.577l0.226,1.575l0.112,1.689H36.15z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M48.086,93.131l-3.378-12.838h3.378l3.152,12.838H48.086z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M42.005,93.131l-0.225-1.689l-0.338-1.575l-0.225-1.577l-0.338-1.576   l-0.338-1.577l-0.338-1.688l-0.338-1.576l-0.338-1.576h3.377l0.339,1.576l0.338,1.576l0.226,1.688l0.338,1.577l0.338,1.576   l0.227,1.577l0.338,1.575l0.338,1.689H42.005z"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M5.97,93.131l0.337-1.689l0.338-1.575l0.338-1.577l0.225-1.576   l0.338-1.577l0.226-1.688l0.225-1.576l0.225-1.576H11.6l-0.225,1.576l-0.338,1.576l-0.338,1.688l-0.338,1.577l-0.225,1.576   l-0.338,1.577L9.46,91.441L9.122,93.13L5.97,93.131L5.97,93.131z"
                    ></path>
                  </g>
                  <g id="Group_Holder">
                    <lineargradient
                      id="SVGID_3_Obj_1_jPqSf5dSztwQXBK2D"
                      gradientUnits="userSpaceOnUse"
                      x1="9.765625e-004"
                      y1="92.4551"
                      x2="51.2402"
                      y2="92.4551"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="url(#SVGID_3_Obj_1_jPqSf5dSztwQXBK2D)"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M51.24,17.68v4.73H0.001v-4.73H51.24"
                    ></path>
                    <path
                      fill="#B2B2B2"
                      d="M6.195,22.41h4.842v-6.307H6.195V22.41z"
                    ></path>
                    <path
                      fill="#7F7F7F"
                      d="M14.303,22.41h-3.266v-6.307h3.266V22.41z"
                    ></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M6.195,22.41h8.108v-6.307H6.195V22.41"
                    ></path>
                    <path
                      fill="#B2B2B2"
                      d="M36.825,22.41h4.73v-6.307h-4.73V22.41z"
                    ></path>
                    <path
                      fill="#7F7F7F"
                      d="M44.708,22.41h-3.153v-6.307h3.153V22.41z"
                    ></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M36.825,22.41h7.883v-6.307h-7.883V22.41"
                    ></path>
                  </g>
                  <g id="Group_Label2">
                    <path
                      fill="#E5E5E5"
                      d="M6.195,36.824h25.676V53.04H6.195V36.824z"
                    ></path>
                  </g>
                  <g id="Group_Label1">
                    <path
                      fill="#E5E5E5"
                      d="M6.195,35.248h25.676v-3.153H6.195V35.248z"
                    ></path>
                  </g>
                  <g id="Group_MakeUp_Tank">
                    <path
                      fill="#666666"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M51.24,93.131l3.152-7.883h25.901l3.151,7.883H51.24z"
                    ></path>
                    <lineargradient
                      id="SVGID_4_Obj_1_jPqSf5dSztwQXBK2D"
                      gradientUnits="userSpaceOnUse"
                      x1="54.3926"
                      y1="27.3643"
                      x2="80.2939"
                      y2="27.3643"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="#fff"
                      d="M80.294,77.141v15.99H54.393v-15.99H80.294"
                    ></path>
                    <path
                      fill="url(#SVGID_4_Obj_1_jPqSf5dSztwQXBK2D)"
                      d="M80.294,77.141v15.99H54.393v-15.99H80.294"
                    ></path>
                    <path
                      fill="#999999"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M67.23,93.131v-7.883l1.803,7.883H67.23z"
                    ></path>
                  </g>
                  <g id="Group_Base">
                    <lineargradient
                      id="SVGID_5_Obj_1_jPqSf5dSztwQXBK2D"
                      gradientUnits="userSpaceOnUse"
                      x1="9.765625e-004"
                      y1="9.6846"
                      x2="83.4473"
                      y2="9.6846"
                      gradientTransform="matrix(1 0 0 -1 0 112.5)"
                    >
                      <stop
                        offset="0.01"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                      <stop
                        offset="0.51"
                        style="
                          stop-opacity: 0.6;
                          stop-color: rgb(248, 108, 107);
                        "
                      ></stop>
                      <stop
                        offset="1"
                        style="stop-color: rgb(248, 108, 107)"
                      ></stop>
                    </lineargradient>
                    <path
                      fill="#fff"
                      d="M83.447,93.131V112.5H0.001V93.131H83.447"
                    ></path>
                    <path
                      fill="url(#SVGID_5_Obj_1_jPqSf5dSztwQXBK2D)"
                      d="M83.447,93.131V112.5H0.001V93.131H83.447"
                    ></path>
                    <path
                      fill="none"
                      stroke="#E5E5E5"
                      stroke-width="0.25"
                      d="M0.001,99.662h83.446"
                    ></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="0.25"
                      d="M0.001,98.762h83.446"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="NxXDvz7Q39xEAEpiS"
            transform="translate(676 189)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(35 68)">
              <g transform="scale(0.1 0.1)">
                <g transform="rotate(0)">
                  <path
                    fill="#989898"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M135,479h82l84-125l84 125h82l-41-145 h-247l-41 145z"
                  ></path>
                  <g transform="translate(480 335)">
                    <rect
                      x="-434"
                      y="-136"
                      fill="#BEBEBE"
                      stroke="#000"
                      width="106"
                      height="158"
                    ></rect>
                  </g>
                  <g>
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="translate(-295 178)">
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="rotate(-45,162,-260)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#E5E5E5"></path>
                  </g>
                  <g transform="rotate(135,100,288)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#CCC"></path>
                  </g>
                  <circle cx="302.6" cy="230" r="188" fill="#f86c6b"></circle>
                  <circle fill="#BEBEBE" cx="302.6" cy="230" r="107"></circle>
                  <circle fill="#4C4C4C" cx="302.6" cy="230" r="80"></circle>
                  <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  <g transform="rotate(60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <g transform="rotate(-60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <circle fill="#E5E5E5" cx="302.6" cy="230" r="18"></circle>
                  <g transform="rotate(-45,162,-260)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(135,100,290)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,0,0)">
                    <path
                      d="M238,376a50,50 0 1,0 -375,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,189,452)">
                    <path
                      d="M238,376a50,50 0 1,0 375,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-140,191,68)">
                    <path
                      d="M125,185a210,210 0 1,0 -249,1l-38 32l103 122l190-160"
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                    ></path>
                  </g>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M93,480h146v-21h-146z"
                  ></path>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M365,480h146v-21h-146z"
                  ></path>
                  <g>
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                  <g transform="translate(-544 176)">
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <g transform="translate(44 -11)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">Hz</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 8)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">kW</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 37)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">A</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 56)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">V</tspan>
                </text>
              </g>
            </g>
            <rect
              x="35"
              y="68"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="EEHwuAAtAKC4HLpuq"
            transform="translate(675 394)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(35 68)">
              <g transform="scale(0.1 0.1)">
                <g transform="rotate(0)">
                  <path
                    fill="#989898"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M135,479h82l84-125l84 125h82l-41-145 h-247l-41 145z"
                  ></path>
                  <g transform="translate(480 335)">
                    <rect
                      x="-434"
                      y="-136"
                      fill="#BEBEBE"
                      stroke="#000"
                      width="106"
                      height="158"
                    ></rect>
                  </g>
                  <g>
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="translate(-295 178)">
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="rotate(-45,162,-260)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#E5E5E5"></path>
                  </g>
                  <g transform="rotate(135,100,288)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#CCC"></path>
                  </g>
                  <circle cx="302.6" cy="230" r="188" fill="#f86c6b"></circle>
                  <circle fill="#BEBEBE" cx="302.6" cy="230" r="107"></circle>
                  <circle fill="#4C4C4C" cx="302.6" cy="230" r="80"></circle>
                  <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  <g transform="rotate(60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <g transform="rotate(-60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <circle fill="#E5E5E5" cx="302.6" cy="230" r="18"></circle>
                  <g transform="rotate(-45,162,-260)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(135,100,290)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,0,0)">
                    <path
                      d="M238,376a50,50 0 1,0 -375,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,189,452)">
                    <path
                      d="M238,376a50,50 0 1,0 375,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-140,191,68)">
                    <path
                      d="M125,185a210,210 0 1,0 -249,1l-38 32l103 122l190-160"
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                    ></path>
                  </g>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M93,480h146v-21h-146z"
                  ></path>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M365,480h146v-21h-146z"
                  ></path>
                  <g>
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                  <g transform="translate(-544 176)">
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <g transform="translate(44 -11)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">Hz</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 8)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">kW</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 37)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">A</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 56)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">V</tspan>
                </text>
              </g>
            </g>
            <rect
              x="35"
              y="68"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="EGd4HFjjnBEcaiHPm"
            transform="translate(676 488)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(35 68)">
              <g transform="scale(0.1 0.1)">
                <g transform="rotate(0)">
                  <path
                    fill="#989898"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M135,479h82l84-125l84 125h82l-41-145 h-247l-41 145z"
                  ></path>
                  <g transform="translate(480 335)">
                    <rect
                      x="-434"
                      y="-136"
                      fill="#BEBEBE"
                      stroke="#000"
                      width="106"
                      height="158"
                    ></rect>
                  </g>
                  <g>
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="translate(-295 178)">
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="rotate(-45,162,-260)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#E5E5E5"></path>
                  </g>
                  <g transform="rotate(135,100,288)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#CCC"></path>
                  </g>
                  <circle cx="302.6" cy="230" r="188" fill="#f86c6b"></circle>
                  <circle fill="#BEBEBE" cx="302.6" cy="230" r="107"></circle>
                  <circle fill="#4C4C4C" cx="302.6" cy="230" r="80"></circle>
                  <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  <g transform="rotate(60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <g transform="rotate(-60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <circle fill="#E5E5E5" cx="302.6" cy="230" r="18"></circle>
                  <g transform="rotate(-45,162,-260)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(135,100,290)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,0,0)">
                    <path
                      d="M238,376a50,50 0 1,0 -375,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,189,452)">
                    <path
                      d="M238,376a50,50 0 1,0 375,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-140,191,68)">
                    <path
                      d="M125,185a210,210 0 1,0 -249,1l-38 32l103 122l190-160"
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                    ></path>
                  </g>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M93,480h146v-21h-146z"
                  ></path>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M365,480h146v-21h-146z"
                  ></path>
                  <g>
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                  <g transform="translate(-544 176)">
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <g transform="translate(44 -11)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">Hz</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 8)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">kW</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 37)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">A</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 56)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">V</tspan>
                </text>
              </g>
            </g>
            <rect
              x="35"
              y="68"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="TxwSR6j7FfKMR3KdS"
            transform="translate(676 584)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(35 68)">
              <g transform="scale(0.1 0.1)">
                <g transform="rotate(0)">
                  <path
                    fill="#989898"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M135,479h82l84-125l84 125h82l-41-145 h-247l-41 145z"
                  ></path>
                  <g transform="translate(480 335)">
                    <rect
                      x="-434"
                      y="-136"
                      fill="#BEBEBE"
                      stroke="#000"
                      width="106"
                      height="158"
                    ></rect>
                  </g>
                  <g>
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="translate(-295 178)">
                    <path fill="#E5E5E5" d="M594,22h-290v40h290z"></path>
                    <path fill="#D8D8D8" d="M594,62h-250v40h250z"></path>
                    <path fill="#CCCCCC" d="M594,102h-250v40h250z"></path>
                    <path fill="#BEBEBE" d="M594,140h-250v38h250z"></path>
                  </g>
                  <g transform="rotate(-45,162,-260)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#E5E5E5"></path>
                  </g>
                  <g transform="rotate(135,100,288)">
                    <path d="M125,185a50,50 0 1,0 -420,0" fill="#CCC"></path>
                  </g>
                  <circle cx="302.6" cy="230" r="188" fill="#f86c6b"></circle>
                  <circle fill="#BEBEBE" cx="302.6" cy="230" r="107"></circle>
                  <circle fill="#4C4C4C" cx="302.6" cy="230" r="80"></circle>
                  <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  <g transform="rotate(60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <g transform="rotate(-60,304,231)">
                    <path fill="#BEBEBE" d="M223,226v12h161v-12z"></path>
                  </g>
                  <circle fill="#E5E5E5" cx="302.6" cy="230" r="18"></circle>
                  <g transform="rotate(-45,162,-260)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(135,100,290)">
                    <path
                      d="M21,186a50,50 0 1,0 -214,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,0,0)">
                    <path
                      d="M238,376a50,50 0 1,0 -375,0"
                      stroke="#fff"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-45,189,452)">
                    <path
                      d="M238,376a50,50 0 1,0 375,0"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      fill="none"
                    ></path>
                  </g>
                  <g transform="rotate(-140,191,68)">
                    <path
                      d="M125,185a210,210 0 1,0 -249,1l-38 32l103 122l190-160"
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                    ></path>
                  </g>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M93,480h146v-21h-146z"
                  ></path>
                  <path
                    fill="#BEBEBE"
                    stroke="#4C4C4C"
                    stroke-width="2"
                    d="M365,480h146v-21h-146z"
                  ></path>
                  <g>
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                  <g transform="translate(-544 176)">
                    <path fill="#BEBEBE" d="M545,1v199h50v-199z"></path>
                    <path fill="#CCCCCC" d="M545,12v177h50v-177z"></path>
                    <path fill="#D8D8D8" d="M545,34v133h50v-133z"></path>
                    <path fill="#E5E5E5" d="M545,55v91h50v-91z"></path>
                    <path fill="#F1F1F1" d="M545,70v61h50v-61z"></path>
                    <path fill="#FFFFFF" d="M545,88v25h50v-25z"></path>
                    <path
                      fill="none"
                      stroke="#4C4C4C"
                      stroke-width="2"
                      d="M545,1v199h50v-199z"
                    ></path>
                  </g>
                </g>
              </g>
            </g>
            <g transform="translate(44 -11)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">Hz</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 8)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">kW</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 37)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">A</tspan>
                </text>
              </g>
            </g>
            <g transform="translate(44 56)">
              <g>
                <rect x="55" y="48" fill="#000" width="60" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text class="ft-8" x="112" y="61.2" fill="#ddd">
                  <tspan text-anchor="end">V</tspan>
                </text>
              </g>
            </g>
            <rect
              x="35"
              y="68"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="qwbG6XafMgCXwojTJ"
            transform="translate(900 34)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(18 8)">
              <g transform="scale(0.6 0.6)">
                <g transform="rotate(0)">
                  <path
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M1,48 l40,22 v-22 l-40,22z"
                    fill="#ff6b6c"
                  ></path>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M21,41 v18"
                  ></path>
                  <circle
                    fill="#dfdfdf"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    cx="21"
                    cy="29"
                    r="18"
                  ></circle>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M13,38 v-17 l8,17 l8,-17 v17"
                  ></path>
                </g>
              </g>
            </g>
            <rect
              x="18"
              y="8"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="PodakbYoX4QLBQcFK"
            transform="translate(900 129)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(18 8)">
              <g transform="scale(0.6 0.6)">
                <g transform="rotate(0)">
                  <path
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M1,48 l40,22 v-22 l-40,22z"
                    fill="#ff6b6c"
                  ></path>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M21,41 v18"
                  ></path>
                  <circle
                    fill="#dfdfdf"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    cx="21"
                    cy="29"
                    r="18"
                  ></circle>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M13,38 v-17 l8,17 l8,-17 v17"
                  ></path>
                </g>
              </g>
            </g>
            <rect
              x="18"
              y="8"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="pahatDD9brqcMbb66"
            transform="translate(902 225)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(18 8)">
              <g transform="scale(0.6 0.6)">
                <g transform="rotate(0)">
                  <path
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M1,48 l40,22 v-22 l-40,22z"
                    fill="#ff6b6c"
                  ></path>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M21,41 v18"
                  ></path>
                  <circle
                    fill="#dfdfdf"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    cx="21"
                    cy="29"
                    r="18"
                  ></circle>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M13,38 v-17 l8,17 l8,-17 v17"
                  ></path>
                </g>
              </g>
            </g>
            <rect
              x="18"
              y="8"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="t8NAcE4rpyzT9WDdk"
            transform="translate(900 430)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(18 8)">
              <g transform="scale(0.6 0.6)">
                <g transform="rotate(0)">
                  <path
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M1,48 l40,22 v-22 l-40,22z"
                    fill="#ff6b6c"
                  ></path>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M21,41 v18"
                  ></path>
                  <circle
                    fill="#dfdfdf"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    cx="21"
                    cy="29"
                    r="18"
                  ></circle>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M13,38 v-17 l8,17 l8,-17 v17"
                  ></path>
                </g>
              </g>
            </g>
            <rect
              x="18"
              y="8"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="888WdxgjZHouJK2Lc"
            transform="translate(900 525)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(18 8)">
              <g transform="scale(0.6 0.6)">
                <g transform="rotate(0)">
                  <path
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M1,48 l40,22 v-22 l-40,22z"
                    fill="#ff6b6c"
                  ></path>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M21,41 v18"
                  ></path>
                  <circle
                    fill="#dfdfdf"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    cx="21"
                    cy="29"
                    r="18"
                  ></circle>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M13,38 v-17 l8,17 l8,-17 v17"
                  ></path>
                </g>
              </g>
            </g>
            <rect
              x="18"
              y="8"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="Tohmnr8mgeDeamgLd"
            transform="translate(900 621)"
            class="cursor"
          >
            <g id="Obj_1" transform="translate(18 8)">
              <g transform="scale(0.6 0.6)">
                <g transform="rotate(0)">
                  <path
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M1,48 l40,22 v-22 l-40,22z"
                    fill="#ff6b6c"
                  ></path>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M21,41 v18"
                  ></path>
                  <circle
                    fill="#dfdfdf"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    cx="21"
                    cy="29"
                    r="18"
                  ></circle>
                  <path
                    fill="none"
                    stroke="#4c4c4c"
                    stroke-width="1"
                    d="M13,38 v-17 l8,17 l8,-17 v17"
                  ></path>
                </g>
              </g>
            </g>
            <rect
              x="18"
              y="8"
              width="66.48663330078125"
              height="67.20913696289062"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="xSX45jmgzDqA9uJRg"
            transform="translate(1048 16)"
            class="cursor"
          >
            <g transform="translate(-19 -22)">
              <g>
                <rect x="55" y="48" fill="#000" width="75" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(14 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">l/h</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="L53j2BdpHfTrbHCqP"
            transform="translate(1048 41)"
            class="cursor"
          >
            <g transform="translate(-19 -22)">
              <g>
                <rect x="55" y="48" fill="#000" width="75" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(14 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">l/h</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="SCMTLqrTJEHgt8HEf"
            transform="translate(1048 68)"
            class="cursor"
          >
            <g transform="translate(-19 -22)">
              <g>
                <rect x="55" y="48" fill="#000" width="75" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(14 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">l/h</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="WSrtCtMFgJaXLf9ZK"
            transform="translate(1048 93)"
            class="cursor"
          >
            <g transform="translate(-19 -22)">
              <g>
                <rect x="55" y="48" fill="#000" width="75" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(14 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">l/h</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
          <g
            id="NgpMbb5qGBWaurjhK"
            transform="translate(175 132)"
            class="cursor"
          >
            <g transform="translate(-19 -22)">
              <g>
                <rect x="55" y="48" fill="#000" width="75" height="18"></rect>
                <text
                  transform="translate(11 5)"
                  class="ft-10_5"
                  x="65"
                  y="57.2"
                  fill="#fff"
                >
                  <tspan text-anchor="middle">0</tspan>
                </text>
                <text
                  transform="translate(14 5)"
                  class="ft-8"
                  x="113.5"
                  y="56.2"
                  fill="#ddd"
                >
                  <tspan text-anchor="end">l/h</tspan>
                </text>
              </g>
            </g>
            <rect
              x="0"
              y="0"
              width="50"
              height="50"
              fill="#fff"
              stroke="#none"
              opacity="0"
            ></rect>
          </g>
        </svg>
      </div>
      <div class="" style="">
        <div class="">
          <canvas
            role="img"
            height="350"
            width="579"
            style="
              display: block;
              box-sizing: border-box;
              height: 350px;
              width: 579px;
            "
          ></canvas>
        </div>
        <div class="col-md-6 col-lg-12 tools-trend mt-3 px-0">
          <canvas
            role="img"
            height="350"
            width="579"
            style="
              display: block;
              box-sizing: border-box;
              height: 350px;
              width: 579px;
            "
          ></canvas>
        </div>
      </div>
      <div class="" style="display:none">
      </div>
    </div>
  </div>
  <dialogModel :visible="visible" @update:visible="openDialog"/>
  <chacoal v-if="!mode"/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.wrap {
  zoom: 2;
  height: 600px;
}
</style>
