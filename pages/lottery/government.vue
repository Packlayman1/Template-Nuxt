<template>
  <div>
    <div class="bg-white p-2 m-2">
        <div class="bar-back align-items-center navbar-s">
                <div id="top"></div>

                <nuxt-link to="/lotto">
                    <a class="mr-auto" ><i class="fas fa-chevron-left"></i> ย้อนกลับ</a>
                </nuxt-link>
                <a  class="btn btn-outline-primary btn-sm mr-1 text-primary text-nx">ดูรายการเเทง</a>
                <a  class="btn btn-outline-primary btn-sm mr-1 text-primary text-nx">โพยหวย</a>
                <a  class="btn btn-outline-secondary btn-sm mr-1 text-dark text-nx">กติกา</a>
        </div>

        <div
        class="
            bgwhitealpha
            text-secondary
            shadow-sm
            rounded
            p-2
            px-2
            xtarget
            col-lotto
            d-flex
            flex-row
            mb-0
            bg-white
            pb-0
        "
        >
        <div
            class="
            d-flex
            justify-content-between
            align-items-center
            mb-0
            flex-fill
            lotto-title
            "
        >
            <h5 class="tanghuay-h4">
            หวยรัฐบาลไทย
            <span
                class="badge badge-pill badge-primary font-weight-light"
                style="font-size: 15px"
                >2021-07-01</span
            >
            </h5>
            <div class="tanghuay-time_day">
            <i class="sn-icon sn-icon--daily2"></i>
            <span class="countdown-number countdown" style="font-size: 15px"
                ><div>
                <b
                    ><b>ปิดรับ </b> <b>1วัน</b> <b><b>0</b>1:</b> <b><!---->23:</b>
                    <b><!---->14</b></b
                >
                </div></span
            >
            </div>
        </div>
        </div>

        <div class="bg-white">
        <nav>
            <div
            id="nav-tab1"
            role="tablist"
            class="nav nav-tabs nav-pills nav-justified"
            >
            <a
                id="nav-keyboard-tab"
                data-toggle="tab"
                href="#nav-keyboard"
                role="tab"
                aria-controls="nav-keyboard"
                aria-selected="true"
                class="nav-item nav-link p-1 active show"
                >กดเลขเอง</a
            >
            <a
                id="nav-panghuay-tab"
                data-toggle="tab"
                href="#nav-panghuay"
                role="tab"
                aria-controls="nav-panghuay"
                aria-selected="false"
                class="nav-item nav-link p-1"
                >เลือกจากแผง</a
            >
            <a
                data-toggle="tab"
                role="tab"
                aria-controls="nav-panghuay"
                aria-selected="true"
                class="nav-item nav-link p-1"
                >เวอร์ชั่น PC</a
            >
            </div>
        </nav>
        </div>

        <div
        class="row-menu-grid"
        style="min-height: calc((100vh - 293.75px) - 59px)"
        >
        <div
            id="numpage_1"
            class="
            d-flex
            flex-row
            justify-content-between
            align-items-stretch
            p-1
            mt-1
            pr-2
            bg-white
            rounded
            shadow-sm
            flex-fill
            cart-item-lists
            "
        >
            <div
            id="show_poy_list"
            class="d-flex flex-column flex-fill box__play"
            style=""
            >
            <div
                id="sidebar-huay"
                class="sidebar-huay d-flex flex-column flex-fill"
                style=""
            >
                <button
                class="btn btn-light btn-sm btn-block number-sets triggerPoy"
                >
                <i class="fas fa-list-ol"></i> ดึงโพย
                </button>
                <button
                class="btn btn-primary btn-sm btn-block show-lists triggerPrice"
                >
                <i class="fas fa-edit"></i> ใส่ราคา
                </button>
                <h5 class="title-huay mt-2">
                <i class="fas fa-receipt"></i> รายการแทง
                </h5>
                <span class="bet_num_count">0 รายการ</span>
                <div class="list-huay flex-fill"></div>
            </div>
            </div>
            <!---->
            <div
            id="page_tang"
            class="sidebar-tanghuay box__play"
            style="z-index: 0"
            >
            <div id="nav-tabContent" class="tab-content">
                <div
                id="nav-keyboard"
                role="tabpanel"
                aria-labelledby="nav-keyboard-tab"
                class="tab-pane fade active show"
                >
                <div>
                    <div class="row px-2 row-btn-tanghuay setting__number">
                    <div class="col-6 col-sm-6 col-md-4 col-lg-3 p-1">
                        <button
                        id="teng_bon_3"
                        class="
                            btn btn-outline-red btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-danger text-white">
                            <i><small>3</small></i
                            ><i>ตัวบน</i>
                        </div>
                        <div style="font-size: 10px" class="ml-2">850/3.00</div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-4 col-lg-3 p-1">
                        <button
                        id="tode_3"
                        class="
                            btn btn-outline-red btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-danger text-white">
                            <i><small>3</small></i
                            ><i>ตัวโต๊ด</i>
                        </div>
                        <div style="font-size: 10px" class="ml-2">135/3.00</div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-4 col-lg-3 p-1">
                        <button
                        id="teng_lang_nha_3"
                        class="
                            btn btn-outline-red btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-danger text-white">
                            <i><small>3</small></i
                            ><i>ตัวหน้า</i> <br />
                        </div>
                        <div class="text-center ml-2" style="font-size: 10px">
                            850/12.00
                        </div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-4 col-lg-3 p-1">
                        <button
                        id="teng_lang_3"
                        class="
                            btn btn-outline-red btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-danger text-white">
                            <i><small>3</small></i
                            ><i>ตัวท้าย</i>
                        </div>
                        <div class="text-center ml-2" style="font-size: 10px">
                            850/12.00
                        </div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-4 col-lg-3 p-1">
                        <button
                        id="teng_bon_2"
                        class="
                            btn btn-outline-blue btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                            bet_two
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-primary text-white">
                            <i><small>2</small></i
                            ><i>ตัวบน</i>
                        </div>
                        <div class="text-center ml-2" style="font-size: 10px">
                            95/3.00
                        </div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-4 col-lg-3 p-1">
                        <button
                        id="teng_lang_2"
                        class="
                            btn btn-outline-blue btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                            bet_two
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-primary text-white">
                            <i><small>2</small></i
                            ><i>ตัวล่าง</i>
                        </div>
                        <div class="text-center ml-2" style="font-size: 10px">
                            95/3.00
                        </div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-4 col-lg-3 p-1">
                        <button
                        id="teng_tod_2"
                        class="
                            btn btn-outline-blue btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                            bet_two
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-primary text-white">
                            <i><small>2</small></i
                            ><i>ตัวโต๊ด</i>
                        </div>
                        <div class="text-center ml-2" style="font-size: 10px">
                            12/28.00
                        </div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-6 col-lg-3 p-1">
                        <button
                        id="teng_bon_1"
                        class="
                            btn btn-outline-green btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                            bet_run
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-success text-white">
                            <i>วิ่ง</i><i>บน</i>
                        </div>
                        <div class="text-center ml-2" style="font-size: 10px">
                            3.00/12.00
                        </div>
                        </button>
                    </div>
                    <div class="col-6 col-sm-6 col-md-6 col-lg-3 p-1">
                        <button
                        id="teng_lang_1"
                        class="
                            btn btn-outline-green btn-sm btn-block
                            h-100
                            d-flex
                            justify-content-between
                            align-items-center
                            btn-tanghuay
                            bet_run
                        "
                        style="padding-right: 20px"
                        >
                        <div class="bg-success text-white">
                            <i>วิ่ง</i><i>ล่าง</i>
                        </div>
                        <div class="text-center ml-2" style="font-size: 10px">
                            4.00/12.00
                        </div>
                        </button>
                    </div>
                    </div>
                    <!---->
                    <div class="w-100 bg-light px-1 pb-1 text-center border my-1">
                    <p class="border-bottom mb-1">
                        <small>รายการที่เลือก</small>
                    </p>
                    <div id="resultoption">
                        <!---->
                        <!---->
                        <span
                        id="shuffle_3_label"
                        class="badge badge-danger font-weight-light d-none"
                        >กลับ<br />3ตัว</span
                        >
                        <!---->
                        <!---->
                        <!---->
                        <!---->
                        <!---->
                        <span
                        id="shuffle_2_label"
                        class="badge badge-primary font-weight-light d-none"
                        >กลับ<br />2ตัว</span
                        >
                        <!---->
                        <!---->
                        <!---->
                        <!---->
                        <!---->
                    </div>
                    </div>
                    <div class="group__keyboard" style="display: none">
                    <div class="num-pad box__show-number">
                        <h4 class="text-center">ระบุตัวเลข</h4>
                        <div class="label-number">
                        <div>
                            <!---->
                            <div class="number"></div>
                            <div class="number"></div>
                        </div>
                        </div>
                        <div class="key-pad box__keyboard">
                        <div class="row p-2">
                            <div class="col-3">
                            <button
                                data-id="1"
                                class="btn btn-outline-primary btn-block"
                            >
                                1
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="2"
                                class="btn btn-outline-primary btn-block"
                            >
                                2
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="3"
                                class="btn btn-outline-primary btn-block"
                            >
                                3
                            </button>
                            </div>
                            <div class="col-3">
                            <button class="btn btn-danger btn-block">
                                <i class="fas fa-backspace"></i>
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="4"
                                class="btn btn-outline-primary btn-block"
                            >
                                4
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="5"
                                class="btn btn-outline-primary btn-block"
                            >
                                5
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="6"
                                class="btn btn-outline-primary btn-block"
                            >
                                6
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                class="
                                btn btn-secondary btn-block btn-cancel
                                warning
                                btn-cancle-last-add-num
                                "
                            >
                                <span>ยกเลิก</span><span>ล่าสุด</span>
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="7"
                                class="btn btn-outline-primary btn-block"
                            >
                                7
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="8"
                                class="btn btn-outline-primary btn-block"
                            >
                                8
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="9"
                                class="btn btn-outline-primary btn-block"
                            >
                                9
                            </button>
                            </div>
                            <div class="col-3">
                            <button class="btn btn-dark btn-block btn-reset">
                                <span>ล้าง</span><span>ข้อมูล</span>
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                disabled="disabled"
                                class="btn btn-blank"
                            ></button>
                            </div>
                            <div class="col-3">
                            <button
                                data-id="0"
                                class="btn btn-outline-primary btn-block"
                            >
                                0
                            </button>
                            </div>
                            <div class="col-3">
                            <button
                                disabled="disabled"
                                class="btn btn-blank"
                            ></button>
                            </div>
                            <div class="col-3"></div>
                        </div>
                        </div>
                    </div>
                    </div>
                </div>
                </div>
                <div
                id="nav-panghuay"
                role="tabpanel"
                aria-labelledby="nav-panghuay-tab"
                class="tab-pane fade"
                ></div>
            </div>
            <div class="w-100">
                <div class="row mb-2 py-3 mx-0 bg-dark rounded">
                <div class="col pr-1">
                    <button
                    class="btn btn-light btn-sm btn-block number-sets border"
                    >
                    <i class="fas fa-list-ol"></i> ดึงโพย
                    </button>
                </div>
                <div class="col pl-1">
                    <button
                    class="
                        btn btn-primary btn-sm btn-block
                        show-lists
                        triggerPrice
                    "
                    >
                    <i class="fas fa-edit"></i> ใส่ราคา
                    </button>
                </div>
                </div>
            </div>
            <div class="w-100">
                <div class="row mb-2 py-3 mx-0 bg-dark rounded">
                <div class="col pl-2">
                    <button
                    class="
                        btn btn-primary btn-sm btn-block
                        show-lists
                        triggerPrice
                    "
                    >
                    <i class="fas fa-edit"></i> เงื่อนไขการแทง
                    </button>
                </div>
                </div>
            </div>
            </div>
        </div>
        </div>
    </div>
  </div>
</template>

<script>
import NumPad from './components/num_pad.vue'

export default {
  layout : 'default',
   mounted() {
    this.$nextTick(() => {
      this.$nuxt.$loading.start()
      setTimeout(() => this.$nuxt.$loading.finish(), 1000)
    })
  },
  data() {
    return {
      tabIndex: 0,
    }
  },
  components: {
    'num-pad': NumPad,
  },
  methods: {
    linkClass(idx) {
      if (this.tabIndex === idx) {
        return ['bg-primary', 'text-light']
      } else {
        return ['bg-light', 'text-info']
      }
    },
  },
}
</script>

<style>
.bar-back {
  border-top: #ddd 1px solid;
  border-bottom: #ddd 1px solid;
  line-height: 20px;
  padding: 10px;
  background: white;
  font-size: 20px;
}

.navbar-s {
  display: flex;
}

.sidebar-huay {
  width: 100%;
  background: #111;
  border-radius: 3px;
  padding: 3px;
  height: 80vmin;
  transition: 1s;
}

.sidebar-huay .list-huay {
    overflow-y: scroll;
    overflow-x: hidden;
    background: transparent;
    color: white;
    height: 100vmin;
    
}

.sidebar-tanghuay {
    width: 100%;
    padding-left: 7px;
}

.sidebar-huay .title-huay {
    /* color: #dc3545; */
    color: #007bff;
    font-family: inherit;
    /* background: #790000; */
    height: 25px;
    line-height: 1;
    width: 100%;
    padding-left: 5px;
    border-bottom: #333 1px dashed;
}

#show_poy_list {
    opacity: 1;
    width: 32%;
    transition: all 1s;
}


.btn-outline-blue {
    color: #007bff;
    /* background-color: transparent; */
    background-color: rgba(0, 89, 255, 0.05);
    background-image: none;
    border-color: #007bff;
}

.btn-outline-green {
    color: #28A745;
    /* background-color: transparent; */
    background-color: rgba(0, 89, 255, 0.05);
    background-image: none;
    border-color: #28A745;
}


.bet_num_count {
    font-size: 90%;
    text-align: center;
    line-height: 1;
    margin-bottom: 5px;
    font-weight: 500;
    text-shadow: #000 1px 1px 0px;
    color: #fff;
}


#nav-tab1.nav-pills .nav-link.active {
    color: #fff;
    text-shadow: rgb(105 21 21) 1px 1px 0;
    /* background-color: #dc3545; */
    background-color: #007bff;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0;
    line-height: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: 600;
    padding: 20px 0 !important;
    border-bottom-width: 8px;
}

#nav-tab1.nav-pills .nav-link {
    display: flex;
    justify-content: center;
    align-items: center;
    /* border: #95111e 1px solid; */
    border: #007bff 1px solid;
    border-radius: 10px;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0;
    font-weight: 600;
    text-shadow: rgb(255 255 255) 1px 1px;
    background-color: rgb(199, 199, 199);
    /* color: #dc3545; */
    color: #007bff;
}

.tanghuay-time_day {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 5px;
    padding-bottom: 0px;
    background: rgba(0, 0, 0, .1);
    border: #ccc 1px solid;
    text-align: right;
    font-size: 15px;
    line-height: 20px;
    /* color: #dc3545; */
    color: #aa1423;
    text-shadow: #fff 1px 1px 0;
    border-radius: 5px;
    overflow: hidden;
}

  .navbar-s {
      display: flex;
  }
   @media screen and (min-width: 200px) and (max-width: 455px) {
         .navbar-s {
            display: block;
        }
        .text-nx{
            display: block;
            margin: 12px 0;
        }
 }

</style>