<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="container mx-auto p-2">
      <div class="card" style="background-color: rgba(0, 0, 0, 0.5)">
        <div
          class="card-body"
          style="
            border: 2px solid limegreen;
            border-radius: 0.25rem;
            color: antiquewhite;
          "
        >
          <div class="row">
            <div class="col-12 col-sm-12 col-md-6 col-lg-2 mb-2 px-2">
              <div class="flex pb-2">
                <div class="flex-1 flex items-center">
                  <div>
                    <img
                      src="~/assets/imge/user.png"
                      class="inline-block"
                      width="35"
                    />
                    <label>UserName</label>
                  </div>
                </div>
                <div class="flex-1">
                  <span> <i class="fas fa-credit-card"></i> : เครดิต </span>
                  <br />
                  <h3 style="font-size: 18px">320.25 THB</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="topbox">
        <div class="row mx-0">
          <div class="col-12 col-sm-12 col-md-12 col-lg-6 mb-2">
            <div class="gradient-border rounded boxjackpot">
              <div
                class="
                  d-flex
                  justify-content-center
                  align-items-center
                  h-100
                  boxjackpot
                  rounded
                "
                style="position: inherit; z-index: 1; background: none"
              >
                <img
                  class="mb-2 mr-2 mt-2"
                  src="https://i.pinimg.com/originals/87/5d/e8/875de811d27f743fe6491b3c4e8b43bd.gif"
                  width="20"
                />
                <h2>
                  <small class="jackpot">Jackpot สะสม </small
                  ><span class="gold-text" id="odometer1">1,000,000</span>
                </h2>
                <img
                  class="mb-2 ml-2 mt-2"
                  src="https://i.pinimg.com/originals/87/5d/e8/875de811d27f743fe6491b3c4e8b43bd.gif"
                  width="20"
                />
              </div>
            </div>
          </div>

          <div
            class="
              col-12 col-sm-12 col-md-6 col-lg-6
              d-flex
              flex-row
              justify-content-between
              justify-content-sm-between
              justify-content-md-between
              justify-content-lg-end
              align-items-center
              my-2
            "
          >
            <a class="ml-2 mr-3">อัตราจ่าย</a>
            <a class="mr-2 ml-3">กฎและกติกา</a>
          </div>
        </div>
      </div>

      <div class="bg-white shadow-sm rounded p-2 h-100">
        <div class="flex pb-2">
          <div class="flex-1">
            <button class="btn-success w-11/12 rounded h-8">
              <i class="fas fa-plus"></i>
              <nuxt-link to="deposit"> เติมเงิน</nuxt-link>
            </button>
          </div>
          <div class="flex-1">
            <button class="btn-danger w-11/12 rounded h-8">
              <i class="fas fa-minus"></i>
              <nuxt-link to="withdraw"> ถอนเงิน</nuxt-link>
            </button>
          </div>
        </div>

        <div class="flex text-center pb-2">
          <div class="flex-1">
            <nuxt-link to="lotto" style="width: 100%">
              <a
                class="menu-grid hot no-underline"
                style="vertical-align: -webkit-baseline-middle"
              >
                <div
                  class="
                    rounded
                    border border-black-600
                    h-20
                    w-11/12
                    pt-3
                    card-menu
                  "
                >
                  <span class="fa-layers fa-fw">
                    <i
                      class="fas fa-circle-notch fa-spin position-relative"
                      style="font-size: 23px"
                    ></i>
                    <i
                      class="fas fa-star fa-sm position-absolute"
                      style="
                        font-size: 0.5rem;
                        margin-left: -17px;
                        margin-top: 6px;
                      "
                    ></i>
                  </span>
                  <br />แทงหวย
                </div>
              </a>
            </nuxt-link>
          </div>
          <div class="flex-1">
            <div
              class="
                rounded
                border border-black-600
                h-20
                w-11/12
                pt-3
                card-menu
              "
            >
              <i class="ic-size fas fa-dice"></i>
              <br />
              <button>คาสิโน</button>
            </div>
          </div>
          <div class="flex-1">
            <div
              class="rounded border border-black-600 h-20 pt-3 card-menu"
              style="width: 88%"
            >
              <i class="ic-size fas fa-gamepad"></i>
              <br />
              <button>เกม</button>
            </div>
          </div>
        </div>

        <div class="flex text-center pb-2">
          <div class="flex-1">
            <div
              class="
                rounded
                border border-black-600
                h-20
                pt-3
                card-menu
                w-11/12
              "
            >
              <i class="ic-size fas fa-medal"></i>
              <br />
              <button>ผลรางวัล</button>
            </div>
          </div>
          <div class="flex-1">
            <div
              class="
                rounded
                border border-black-600
                h-20
                w-11/12
                pt-3
                card-menu
              "
            >
              <i class="ic-size fas fa-clipboard-list"></i>
              <br />
              <button>โพยหวย</button>
            </div>
          </div>
          <div class="flex-1">
            <div
              class="
                rounded
                border border-black-600
                h-20
                w-11/12
                pt-3
                card-menu
              "
              style="width: 88%"
            >
              <i class="ic-size fas fa-folder-plus"></i>
              <br />
              <button>สร้างชุดเลขชุด</button>
            </div>
          </div>
        </div>

        <div class="flex pb-2">
          <div class="flex-1">
            <!-- <button class="btn-primary w-11/12 rounded h-8">
              <nuxt-link to="deposit"> รายงานการฝาก-ถอน</nuxt-link>
            </button> -->
            <a
              class="
                text-light
                btn btn-labeled btn-secondary btn-block
                align-items-stretch
              "
              style="width: 90%"
            >
              <span class="btn-label">
                <i class="fas fa-hand-holding-usd"></i>
              </span>
              <div class="txt-labeled">
                <span>รายการแจ้ง</span>
                <span>ฝาก/ถอน</span>
              </div>
            </a>
          </div>

          <div class="flex-1">
            <!-- <button class="btn-secondary w-11/12 rounded h-8">
              <nuxt-link to="withdraw"> รายงานการเงิน</nuxt-link>
            </button> -->

            <a
              class="
                text-light
                btn btn-labeled btn-dark btn-block
                align-items-stretch
              "
              style="width: 92%"
            >
              <span class="btn-label">
                <i class="fas fa-money-check-alt"></i>
              </span>
              <div class="txt-labeled">
                <span>รายงาน</span>
                <span>การเงิน</span>
              </div>
            </a>
          </div>
        </div>

        <div class="topbox px-2 text-center d-flex">
            <marquee behavior="left" direction="2" onmouseover="this.stop()" onmouseout="this.start()" class="rounded px-1 pt-2 pb-1 mb-0 mr-1 marqueemain">ยินดีต้อนรับเข้าสู่ Lotto</marquee>

            <a style="width: 58%;" class="btn btn-dark border border-secondary pb-0 btn-download-app">
                <i class="fas fa-arrow-circle-down"></i> ดาวน์โหลดแอป
            </a>
        </div>

        <!-- <div class="flex pb-2">
          <div class="flex-1">
            <button>ระบบแนะนำ</button>
          </div>
          <div class="flex-1">
            <button>ค่าคอมแนะนำเพื่อน</button>
            <br />
            0.00THB
          </div>
        </div> -->
      </div>

      <!-- <div class="flex p-2 bg-white text-center">
        <div class="flex-1">
          <button class="btn-success w-11/12 rounded h-8">
            <i class="fas fa-plus"></i>
            <nuxt-link tag="button" to="deposit">รายงานการฝาก-ถอน</nuxt-link>
          </button>
        </div>
        <div class="flex-1">
          <button class="bg-blue-500 text-white font-bold py-2 px-4 rounded">
            รายงานการเงิน
          </button>
        </div>
      </div> -->
    </div>
  </div>
</template>

<style>
.card-menu {
  overflow: hidden;
  border: 1px solid #00ff1f;
  border: 1px solid #ade49a;
  color: #246314;
  box-shadow: inset 0 0px 10px rgb(0 255 55 / 20%);
}

.ic-size {
  font-size: 23px;
}

.btn-label {
  position: relative;
  left: -12px;
  display: inline-flex;
  align-items: center;
  padding: 6px 12px;
  background: rgba(0, 0, 0, 0.15);
  border-radius: 3px 0 0 3px;
  font-size: 25px;
}

.txt-labeled {
  width: 100%;
  line-height: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-left: -12px;
  margin-right: -12px;
}

.btn-labeled {
  padding-top: 0;
  padding-bottom: 0;
  min-height: 50px;
  display: inline-flex;
}

.gold-text {
  background: -webkit-linear-gradient(rgb(229, 255, 0), rgb(255, 255, 255));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.topbox h2 > span {
  font-family: fantasy;
  vertical-align: bottom;
  font-size: 23px;
}

#box {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 400px;
  height: 200px;
  color: white;
  font-family: 'Raleway';
  font-size: 2.5rem;
}
.gradient-border {
  --borderWidth: 3px;
  background: #1d1f20;
  position: relative;
  border-radius: var(--borderWidth);
}
.gradient-border:after {
  content: '';
  position: absolute;
  top: calc(-1 * var(--borderWidth));
  left: calc(-1 * var(--borderWidth));
  height: calc(100% + var(--borderWidth) * 2);
  width: calc(100% + var(--borderWidth) * 2);
  background: linear-gradient(
    60deg,
    #f79533,
    #f37055,
    #ef4e7b,
    #a166ab,
    #5073b8,
    #1098ad,
    #07b39b,
    #6fba82
  );
  border-radius: calc(2 * var(--borderWidth));
  z-index: 0;
  animation: animatedgradient 3s ease alternate infinite;
  background-size: 300% 300%;
}

@keyframes animatedgradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

.topbox {
  border: 1px #333 solid;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
  display: block;
  margin-top: 10px;
  padding: 10px 0;
  background: #222;
  color: lightgoldenrodyellow;
  font-family: SukhumvitReg;
}

.jackpot {
  font-size: 60%;
  vertical-align: baseline;
  font-family: 'Kanit';
  margin-right: 5px;
  font-size: 21px;
}

.bgwhitealpha {
  /* background: rgba(179, 227, 236, 0.6); */
  background: rgba(255, 255, 255, 0.9);
  /* margin-bottom: 10px; */
  border: rgba(255, 255, 255, 1) 2px solid;
}

.bgwhitealpha h6 span.flag-icon {
  font-size: 26px;
  margin-top: -15px;
  margin-left: -10px;
  border-top-left-radius: 4px;
  border-bottom-right-radius: 8px;
  max-width: 50px;
  background-size: cover;
  border: #555 1px solid;
  border-top-color: #ccc;
  border-left-color: #ccc;
}

.flag-icon-baac {
  background-color: #13007d;
}

.flag-icon-gsb {
  background-color: #f90a86;
}

.cil-star {
  background: gold;
  border: 1px solid;
  border-radius: 9px;
  padding: 3px;
}

.card-header span.flag-icon {
  font-size: 26px;
  top: -5px;
  left: -5px;
  border-top-left-radius: 4px;
  border-bottom-right-radius: 8px;
  max-width: 50px;
  background-size: cover;
  display: flex;
  border: #555 1px solid;
  border-top-color: #333;
  border-left-color: #333;
}

.topbox a {
    color: blanchedalmond;
    text-decoration: none;
}
</style>
