<template>
  <div
    v-if="visible"
    tabindex="-1"
    style="position: relative; z-index: 1050; display: block"
  >
    <div class="">
      <div
        class="modal fade show"
        role="dialog"
        tabindex="-1"
        style="display: block"
      >
        <div id="modal01" class="modal-dialog modal-popupMotor" role="document">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title">1P01 - Bơm nước thô</h5>
              <button
                type="button"
                class="close"
                aria-label="Close"
                @click="closeDialog"
              >
                <span aria-hidden="true">×</span>
              </button>
            </div>
            <div class="modal-body">
              <div class="grid gapPopup">
                <div class="g-col-6 bg-grid-layout p-1">
                  <div class="row">
                    <div class="col-12 pb-1">
                      <h6 class="text-center bold fz-12">TRẠNG THÁI</h6>
                    </div>
                    <div class="col-2"></div>
                    <div class="col-5 py-1">
                      <svg
                        id="sidebarBox1"
                        width="100"
                        height="52"
                        viewBox="0 0 100 60"
                      >
                        <g>
                          <g id="Group_Shaft">
                            <lineargradient
                              id="SVGID_1_"
                              gradientUnits="userSpaceOnUse"
                              x1="103.1523"
                              y1="31.4185"
                              x2="103.1523"
                              y2="26.6895"
                            >
                              <stop offset="0" stop-color="#4D4D4D"></stop>
                              <stop offset="0.03" stop-color="#5F5F5F"></stop>
                              <stop offset="0.1" stop-color="#848484"></stop>
                              <stop offset="0.17" stop-color="#A3A3A3"></stop>
                              <stop offset="0.25" stop-color="#BBBBBB"></stop>
                              <stop offset="0.33" stop-color="#CCCCCC"></stop>
                              <stop offset="0.41" stop-color="#D6D6D6"></stop>
                              <stop offset="0.52" stop-color="#D9D9D9"></stop>
                              <stop offset="0.63" stop-color="#D6D6D6"></stop>
                              <stop offset="0.72" stop-color="#CCCCCC"></stop>
                              <stop offset="0.8" stop-color="#BBBBBB"></stop>
                              <stop offset="0.87" stop-color="#A3A3A3"></stop>
                              <stop offset="0.94" stop-color="#858585"></stop>
                              <stop offset="1" stop-color="#666666"></stop>
                            </lineargradient>
                            <path
                              fill="url(#SVGID_1_)"
                              d="M93.806,26.689H112.5v4.729H93.806V26.689"
                            ></path>
                          </g>
                          <g id="Group_ShaftFacePlate">
                            <lineargradient
                              id="SVGID_2_"
                              gradientUnits="userSpaceOnUse"
                              x1="95.4951"
                              y1="54.8413"
                              x2="95.4951"
                              y2="1.0142"
                            >
                              <stop offset="0" stop-color="#4D4D4D"></stop>
                              <stop offset="0.52" stop-color="#B2B2B2"></stop>
                              <stop offset="1" stop-color="#666666"></stop>
                            </lineargradient>
                            <path
                              fill="url(#SVGID_2_)"
                              d="M94.932,1.014h1.127v53.828h-1.127V1.014z"
                            ></path>
                          </g>
                          <g id="Group_MotorBody">
                            <lineargradient
                              id="SVGID_3_"
                              gradientUnits="userSpaceOnUse"
                              x1="42.1606"
                              y1="57.3208"
                              x2="42.1606"
                              y2="1.001"
                            >
                              <stop
                                offset="0.17"
                                style="stop-color: red; stop-opacity: 0.95"
                              ></stop>
                              <stop
                                offset="0.23"
                                style="stop-color: red; stop-opacity: 0.9"
                              ></stop>
                              <stop
                                offset="0.34"
                                style="stop-color: red; stop-opacity: 0.8"
                              ></stop>
                              <stop
                                offset="0.48"
                                style="stop-color: red; stop-opacity: 0.6"
                              ></stop>
                              <stop
                                offset="0.57"
                                style="stop-color: red; stop-opacity: 0.65"
                              ></stop>
                              <stop
                                offset="0.73"
                                style="stop-color: red; stop-opacity: 0.75"
                              ></stop>
                              <stop
                                offset="0.94"
                                style="stop-color: red; stop-opacity: 0.9"
                              ></stop>
                              <stop
                                offset="1"
                                style="stop-color: red; stop-opacity: 0.95"
                              ></stop>
                            </lineargradient>
                            <path
                              fill="url(#SVGID_3_)"
                              d="M14.077,57.32V1.014c0,0-13.035-0.479-14.077,4.392c0,0-0.06,46.843,0,47.184   C0.875,57.536,11.6,57.32,11.6,57.32h72.747V1.014h-70.27"
                            ></path>
                            <path
                              fill="#B2B2B2"
                              d="M18.582,7.996h7.207V1.014h-7.207V7.996z"
                            ></path>
                            <path
                              fill="red"
                              opacity="0.5"
                              d="M18.582,7.996h7.207V1.014h-7.207V7.996z"
                            ></path>
                            <circle
                              fill="#333333"
                              cx="22.185"
                              cy="4.505"
                              r="2.252"
                            ></circle>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,44.482l-3.604-1.352v-4.505l3.604-2.478V44.482z"
                            ></path>
                            <path
                              fill="#666666"
                              d="M13.952,1.008h0.251v56.306h-0.251V1.008z"
                            ></path>
                            <path
                              fill="#666666"
                              d="M84.221,1.008h0.251v56.306h-0.251V1.008z"
                            ></path>
                            <lineargradient
                              id="SVGID_4_"
                              gradientUnits="userSpaceOnUse"
                              x1="89.0762"
                              y1="54.8413"
                              x2="89.0762"
                              y2="3.3789"
                            >
                              <stop offset="0" style="stop-color: red"></stop>
                              <stop
                                offset="0.52"
                                style="stop-color: red; stop-opacity: 0.5"
                              ></stop>
                              <stop offset="1" style="stop-color: red"></stop>
                            </lineargradient>
                            <path
                              fill="url(#SVGID_4_)"
                              d="M84.347,54.841h3.491c5.203,0,5.968-2.252,5.968-2.252V5.856c0,0-1.138-2.478-6.869-2.478h-2.59"
                            ></path>
                          </g>
                          <g id="Group_BodySupport">
                            <path
                              fill="#999999"
                              d="M28.041,0h54.053v5.856H28.041V0z"
                            ></path>
                            <path
                              fill="red"
                              opacity="0.5"
                              d="M28.041,0h54.053v5.856H28.041V0z"
                            ></path>
                          </g>
                          <g id="Group_HeatSink">
                            <path
                              fill="#4C4C4C"
                              d="M14.077,7.996h70.27v2.252h-70.27V7.996z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,12.725h70.27v2.252h-70.27V12.725z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,17.455h70.27v2.252h-70.27V17.455z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,22.185h70.27v2.252h-70.27V22.185z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,26.689h70.27v2.478h-70.27V26.689z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,31.418h70.27v2.478h-70.27V31.418z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,36.148h70.27V38.4h-70.27V36.148z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,40.878h70.27v2.252h-70.27V40.878z"
                            ></path>
                            <path
                              fill="#4C4C4C"
                              d="M14.077,45.607h70.27v2.253h-70.27V45.607z"
                            ></path>
                          </g>
                          <g id="Group_Wiring_Box">
                            <path
                              fill="#999999"
                              d="M46.734,24.437h35.359V57.32H46.734V24.437z"
                            ></path>
                            <path
                              fill="#B2B2B2"
                              d="M50.338,28.04H78.49v25.676H50.338V28.04z"
                            ></path>
                            <polygon
                              fill="#4D4D4D"
                              points="50.338,53.716 50.338,28.04 49.212,27.013 49.212,54.561"
                            ></polygon>
                            <polygon
                              fill="#C6C6C6"
                              points="50.338,28.04 78.49,28.04 79.416,27.013 49.212,27.013"
                            ></polygon>
                            <polygon
                              fill="#C6C6C6"
                              points="78.29,27.858 78.29,53.534 79.416,54.561 79.416,27.013"
                            ></polygon>
                            <polygon
                              fill="#4D4D4D"
                              points="78.29,53.534 50.138,53.535 49.212,54.561 79.416,54.561"
                            ></polygon>
                            <path
                              fill="red"
                              opacity="0.5"
                              d="M46.734,24.437h35.359V57.32H46.734V24.437z"
                            ></path>
                          </g>
                        </g>
                      </svg>
                    </div>
                    <div class="col-5 pb-1">
                      <p class="bold blue fz-10 pt-1 mb-2 pb-2">TẠI TỦ</p>
                      <p class="bold green fz-10 mb-2">DỪNG</p>
                    </div>
                    <div class="col-6 pl-4 mb-1 pr-2">
                      <button
                        id="mainternance"
                        class="btn btn-block btn-coreui btn-warning fw-5 fz-10 py-1 btn-sm"
                        type="button"
                      >
                        BẢO TRÌ
                      </button>
                    </div>
                    <div class="col-6 pr-4 pl-2">
                      <button
                        id="mainternance"
                        class="btn btn-block btn-coreui btn-success fw-5 fz-10 py-1 btn-sm"
                        type="button"
                      >
                        MÔ PHỎNG
                      </button>
                    </div>
                    <div class="col-12 px-4 mb-1">
                      <button
                        id="mainternance"
                        class="btn btn-block btn-coreui btn-secondary fw-5 fz-10 py-1 btn-sm"
                        type="button"
                      >
                        ĐỒ THỊ
                      </button>
                    </div>
                  </div>
                </div>
                <div class="g-col-6 bg-grid-layout p-1">
                  <div class="row">
                    <div class="col-12">
                      <h6 class="text-center bold fz-12">
                        ĐIỀU KHIỂN CHẠY/DỪNG
                      </h6>
                    </div>
                    <div class="col-1 circle-w">
                      <svg
                        id="sidebarBox1"
                        width="24"
                        height="18"
                        viewBox="0 0 30 30"
                      >
                        <g>
                          <circle fill="#0f0" cx="18" cy="9" r="9"></circle>
                        </g>
                      </svg>
                    </div>
                    <div class="col-10">
                      <p class="mb-0 fw-5 fz-10">
                        KHÓA LIÊN ĐỘNG THEO QUY TRÌNH
                      </p>
                    </div>
                    <div class="col-1 circle-w">
                      <svg
                        id="sidebarBox1"
                        width="24"
                        height="18"
                        viewBox="0 0 30 30"
                      >
                        <g>
                          <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                        </g>
                      </svg>
                    </div>
                    <div class="col-10">
                      <p class="mb-0 fw-5 fz-10">KHÓA KHỞI ĐỘNG LIÊN TIẾP</p>
                    </div>
                    <div class="col-1 circle-w">
                      <svg
                        id="sidebarBox1"
                        width="24"
                        height="18"
                        viewBox="0 0 30 30"
                      >
                        <g>
                          <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                        </g>
                      </svg>
                    </div>
                    <div class="col-10">
                      <p class="mb-0 pb-1 fw-5 fz-10">KHÓA CHẠY KHỞI ĐỘNG</p>
                    </div>
                    <div class="col-6 pr-0">
                      <div class="row">
                        <div class="col-7 pl-3 pr-0 mb-0">
                          <p class="mb-0 fw-5 pl-1 gray8 fz-10">TỰ ĐỘNG</p>
                        </div>
                        <div class="col-5 px-0 mb-0">
                          <p class="mb-0 fw-5 blue fz-10">BẰNG TAY</p>
                        </div>
                        <div class="col-12 px-4 mb-0 ml-2">
                          <div class="img-Rswitch"></div>
                        </div>
                      </div>
                    </div>
                    <div class="col-6 mt-2 pt-1">
                      <div class="row">
                        <div class="col-12 px-4 mb-1">
                          <button
                            id="start"
                            class="btn btn-block btn-coreui btn-gray fw-5 fz-10 btn-sm"
                            type="button"
                          >
                            CHẠY
                          </button>
                        </div>
                        <div class="col-12 px-4 mb-1">
                          <button
                            id="stop"
                            class="btn btn-block btn-coreui btn-danger fw-5 fz-10 btn-sm"
                            type="button"
                          >
                            DỪNG
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="g-col-6 bg-grid-layout p-1">
                  <div class="row">
                    <div class="col-12 mb-1">
                      <h6 class="text-center bold fz-12">ĐIỀU KHIỂN TỐC ĐỘ</h6>
                    </div>
                    <div class="col-6 pl-4 mb-1 pr-2">
                      <button
                        id="mainternance"
                        class="btn btn-block btn-coreui btn-gray fw-5 fz-10 btn-sm"
                        type="button"
                      >
                        TỰ ĐỘNG
                      </button>
                    </div>
                    <div class="col-6 pr-4 pl-2">
                      <button
                        id="mainternance"
                        class="btn btn-block btn-coreui btn-success fw-5 fz-10 btn-sm"
                        type="button"
                      >
                        BẰNG TAY
                      </button>
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        TỐC ĐỘ TỐI ĐA <span class="gray8 fw-4">(Hz)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="S_MaxSpeed"
                        step="any"
                        min="0.00"
                        max="50.00"
                        class="form-control input-sm fz-10"
                        value=""
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        TỐC ĐỘ TỐI THIỂU <span class="gray8 fw-4">(Hz)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="S_MinSpeed"
                        step="any"
                        min="0.00"
                        max="50.00"
                        class="form-control input-sm fz-10"
                        value=""
                      />
                    </div>
                    <div class="col-8 pl-4 pr-0">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        TỐC ĐỘ C.ĐẶT B.TAY
                        <span class="gray8 fw-4">(Hz)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="S_ManSpeedSP"
                        step="any"
                        min="0.00"
                        max="50.00"
                        class="form-control input-sm fz-10"
                        value=""
                      />
                    </div>
                    <div class="col-12 px-4"><hr class="my-1" /></div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        TỐC ĐỘ THỰC TẾ <span class="gray8 fw-4">(Hz)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="A_SpeedSP"
                        class="form-control input-sm fz-10"
                        value=""
                      />
                    </div>
                  </div>
                </div>
                <div class="g-col-6 bg-grid-layout p-1">
                  <div class="row">
                    <div class="col-12 mb-1">
                      <h6 class="text-center bold fz-12">DỮ LIỆU ĐIỆN</h6>
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        ĐIỆN ÁP <span class="gray8 fw-4">(V)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="0"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        DÒNG ĐIỆN <span class="gray8 fw-4">(A)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="0"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        CÔNG SUẤT <span class="gray8 fw-4">(kW)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="0"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        TẦN SỐ <span class="gray8 fw-4">(Hz)</span>
                      </p>
                    </div>
                    <div class="col-4 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value=""
                      />
                    </div>
                  </div>
                </div>
                <div class="g-col-12 bg-grid-layout p-1">
                  <div class="row">
                    <div class="col-8 mb-1">
                      <h6 class="text-center bold fz-12">THÔNG SỐ</h6>
                    </div>
                    <div class="col-2 mb-1">
                      <p class="mb-0 fw-5 gray9 fz-10">CÀI ĐẶT</p>
                    </div>
                    <div class="col-2 mb-1 pl-0">
                      <p class="mb-0 fw-5 gray9 fz-10">G.TRỊ</p>
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">SỐ LẦN KHỞI ĐỘNG</p>
                    </div>
                    <div class="col-2"></div>
                    <div class="col-2 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="20"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        TỔNG THỜI GIAN CHẠY/NGÀY
                        <span class="gray8 fw-4">(h)</span>
                      </p>
                    </div>
                    <div class="col-2"></div>
                    <div class="col-2 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="20"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        TỔNG THỜI GIAN CHẠY
                        <span class="gray8 fw-4">(h)</span>
                      </p>
                    </div>
                    <div class="col-2"></div>
                    <div class="col-2 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="10"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        KHOẢNG T.GIAN TỐI THIỂU GIỮA 1 LẦN KHỞI ĐỘNG
                        <span class="gray8 fw-4">(s)</span>
                      </p>
                    </div>
                    <div class="col-2">
                      <input
                        type="number"
                        name="timeTotal"
                        min="0"
                        max="1000"
                        class="form-control input-sm fz-10"
                        value="5"
                      />
                    </div>
                    <div class="col-2 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="10"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        THỜI GIAN DỪNG TỐI THIỂU
                        <span class="gray8 fw-4">(s)</span>
                      </p>
                    </div>
                    <div class="col-2">
                      <input
                        type="number"
                        name="timeTotal"
                        min="0"
                        max="1000"
                        class="form-control input-sm fz-10"
                        value="5"
                      />
                    </div>
                    <div class="col-2 pr-4 pl-0">
                      <input
                        type="number"
                        name="timeTotal"
                        class="form-control input-sm fz-10"
                        value="10"
                      />
                    </div>
                    <div class="col-8 pl-4">
                      <p class="mb-0 fw-5 p-20 fz-10">
                        THỜI GIAN PHẢN HỒI <span class="gray8 fw-4">(s)</span>
                      </p>
                    </div>
                    <div class="col-2 pb-2">
                      <input
                        type="number"
                        name="timeTotal"
                        min="0"
                        max="1000"
                        class="form-control input-sm fz-10"
                        value="5"
                      />
                    </div>
                    <div class="col-2 pr-4 pb-2"></div>
                  </div>
                </div>
                <div class="g-col-12 bg-grid-layout p-1">
                  <div class="row">
                    <div class="col-12 mb-1">
                      <h6 class="text-center bold fz-12">CẢNH BÁO</h6>
                    </div>
                    <div class="col-6 mb-1 pl-3">
                      <div class="row">
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI ĐIỆN</p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI NGUỒN</p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI HỞ MẠCH CÁCH LY</p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI DỪNG KHẨN CẤP</p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI TRUYỀN THÔNG</p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI BIẾN TẦN</p>
                        </div>
                      </div>
                    </div>
                    <div class="col-6 mb-1">
                      <div class="row">
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">
                            LỖI CHẠY KO CÓ TÍN HIỆU P.HỒI
                          </p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">
                            LỖI DỪNG KO CÓ TÍN HIỆU P.HỒI
                          </p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI CHẠY CẠN</p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI PLC</p>
                        </div>
                        <div class="col-1 circle-w">
                          <svg
                            id="sidebarBox1"
                            width="24"
                            height="18"
                            viewBox="0 0 30 30"
                          >
                            <g>
                              <circle fill="#bbb" cx="18" cy="9" r="9"></circle>
                            </g>
                          </svg>
                        </div>
                        <div class="col-10">
                          <p class="mb-0 fw-5 fz-10">LỖI DÒNG RÒ</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="footer-popMoter modal-footer">
              <div class="row mb-0">
                <div class="col-1 pl-3">
                  <i class="fa-solid fz-20 fa-square-check gray8"></i>
                </div>
                <div class="col-4 pl-0">
                  <p class="mb-0 fw-5 p-20 fz-10">TỰ ĐỘNG XÓA LỖI</p>
                </div>
                <div class="col-3"></div>
                <div class="col-4 pr-3">
                  <button
                    id="stop"
                    class="btn btn-block btn-coreui btn-gray fw-5 btn-sm"
                    type="button"
                  >
                    XÓA LỖI BẰNG TAY
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="modal-backdrop fade show"></div>
    </div>
  </div>
</template>
<script setup>
const props = defineProps({
  visible: Boolean
})
const emit = defineEmits(["update:visible"])
const closeDialog = () => {
  emit("update:visible", false)
}
</script>
