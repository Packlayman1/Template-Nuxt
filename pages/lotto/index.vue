<template>
  <div>
    <div class="bar-back  d-flex justify-content-between  align-items-center bg-white rounded-t-lg rounded-b-lg m-2 p-2">
      <nuxt-link to="/">
        <a><i class="fas fa-chevron-left"></i> 
            หน้าหลัก
        </a>
    </nuxt-link>
      <div class="col-4">
        <select class="form-control">
          <option value="open">กำลังเปิดเเทง</option>
          <option value="all">หวยทั้งหมด</option>
        </select>
      </div>
    </div>

    <div class="p-2 m-2 bg-light main-content align-self-stretch rounded-t-lg rounded-b-lg">
      <div
        class="
          bgwhitealpha
          text-secondary
          shadow-sm
          rounded
          p-2
          px-3
          xtarget
          col-lotto
        "
      >
        <h3>หวย</h3>
        <div class="row">
          <div class="col-6 col-sm-6 col-md-6 col-lg-3">

          <nuxt-link to="lottery/government">
            <a>
                <div class="lotto-card">
                    <div class="ribbon-lotto">
                    <i class="fas fa-crown"></i>
                    </div>
                    <div class="lotto-head lotto-government">
                    <h5>รัฐบาลไทย</h5>
                    <span class="badge badge-dark">ปิดรับ 15:15</span>
                    </div>
                    <div class="lotto-time text-success time-government">
                    <i class="sn-icon sn-icon--daily2"></i>
                    <span class="countdown">
                        <div class="font_time">
                        <b><b>ปิดรับ </b> <b>1วัน</b> <b><b>0</b>3:</b>
                            <b><b>0</b>0:</b> <b>55</b></b>
                        </div></span>
                    </div>
                </div>
            </a>
        </nuxt-link>

          </div>

          <div class="col-6 col-sm-6 col-md-6 col-lg-3">
            <a><div class="lotto-card">
                <div class="ribbon-lotto"><i class="fas fa-trophy"></i></div>
                <div class="lotto-head lotto-yeekee">
                  <h5>จับยี่กี</h5>
                  <span class="badge badge-dark">เปิดแทง 88 รอบ</span>
                </div>
                <div class="lotto-time">
                  <div class="txt-24">
                    <i class="far fa-check-circle"></i>
                    <span id="offset">24 ชม.</span>
                  </div>
                </div>
              </div></a>
          </div>
        </div>
      </div>
      <div
        class="
          bgwhitealpha
          text-secondary
          shadow-sm
          rounded
          p-2
          px-3
          xtarget
          col-lotto
        "
      >
        <h3>หวยหุ้น</h3>
        <div class="row">
          <div class="col-6 col-sm-6 col-md-6 col-lg-3">
            <a
              ><div class="lotto-card">
                <div class="ribbon-lotto">
                  <span class="flag-icon flag-icon-th"></span>
                </div>
                <div class="lotto-head color_stock">
                  <h5>&lt;&lt;&lt; หวยหุ้นไทย รอบปิดเย็น &gt;&gt;&gt;</h5>
                  <span class="badge badge-dark">ปิดรับ 10:15 </span>
                </div>
                <div class="lotto-time text-success time-government">
                  <i class="sn-icon sn-icon--daily2"></i>
                  <span class="countdown"
                    ><div class="font_time">
                      <b
                        ><b>ปิดรับ </b> <b>0วัน</b> <b><!---->21:</b>
                        <b><!---->55:</b> <b><!---->55</b></b
                      >
                    </div></span
                  >
                </div>
              </div></a
            >
          </div>
        </div>
      </div>
      <div
        class="
          bgwhitealpha
          text-secondary
          shadow-sm
          rounded
          p-2
          px-3
          xtarget
          col-lotto
          mb-5
        "
      >
        <h3>หวยชุด</h3>
        <div class="row">
          <div class="col-4">
            <a class="btn btn-outline-danger btn-block btn-contactbox"
              ><span>หวยชุดลาว</span>
              <h3 class="flag-icon flag-icon-la"></h3
            ></a>
          </div>
          <div class="col-4">
            <a class="btn btn-outline-primary btn-block btn-contactbox"
              ><span>หวยชุดฮานอย</span>
              <h3 class="flag-icon flag-icon-vn"></h3
            ></a>
          </div>
          <div class="col-4">
            <a class="btn btn-outline-success btn-block btn-contactbox"
              ><span>หวยชุดมาเลย์</span>
              <h3 class="flag-icon flag-icon-my"></h3
            ></a>
          </div>
        </div>
      </div>
    </div>


  </div>
</template>

<script>
export default {
  layout : 'default'
}
</script>

<style>
.color_vn {
  background-color: #e83e8c;
  border: #b1185f 1px solid;
}
.color_la {
  background-color: #fd7e14;
  border: #c45b06 1px solid;
}
.color_stock {
  background-color: #6610f2;
  border: #4f06c5 1px solid;
}
.close_huay {
  background-color: #28a745;
  border: #1c8b36 1px solid;
}

.lotto-card {
  border: 2px solid white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: rgb(255 255 255 / 50%) 0 0 10px;
}

.ribbon-lotto {
  background: rgba(0, 0, 0, 0.3);
  height: 20px;
  width: auto;
  display: inline-block;
  position: absolute;
  color: #fff;
  line-height: 20px;
  padding: 0px 5px;
  margin-top: 5px;
  border-left: rgba(0, 0, 0, 0.3) 1px solid;
  font-size: 16px;
}

.lotto-head {
  width: 100%;
  display: block;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
  padding: 5px;
  color: white;
  text-align: right;
  text-shadow: rgb(0 0 0 / 30%) 1px 1px 0;
}

.badge-dark {
  color: #fff;
  background-color: #343a40;
}

.lotto-time {
  width: 100%;
  display: flex;
  border-bottom-left-radius: 5px;
  border-bottom-right-radius: 5px;
  padding: 5px;
  background: white;
  border: #ccc 1px solid;
  border-top: none;
  text-align: right;
  font-size: 13px;
  line-height: 30px;
  color: #bbb;
  flex-direction: row;
  justify-content: space-between;
}

.lotto-head.lotto-government {
  background-color: #17a2b8;
  border: #108496 1px solid;
}

.lotto-head.lotto-yeekee {
  background-color: #dc3545;
  border: #aa1423 1px solid;
}

.ribbon-lotto:after {
    content: "";
    position: absolute;
    display: block;
    bottom: 0;
    border: 10px solid rgba(0, 0, 0, .3);
    right: -10px;
    height: 20px;
    border-left-width: 0px;
    border-right-color: transparent;
    filter: drop-shadow(6px 6px 3px rgba(0, 0, 0, 0.04));
}
</style>