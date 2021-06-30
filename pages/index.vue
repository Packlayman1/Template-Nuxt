<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="container mx-auto p-2">
      <div class="flex p-2 bg-white rounded-t-lg">
        <div class="flex-1 flex items-center">
          <div>
            <img src="~/assets/imge/user.png" class="inline-block" width="35" />
            <label>UserName</label>
          </div>
        </div>
        <div class="flex-1">
          เครดิต
          <br />
          320.25THB
        </div>
      </div>

      <div class="flex p-2 bg-white">
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

      <div class="flex p-2 bg-white text-center">
        <div class="flex-1">
             <nuxt-link to="lotto" style="width: 100%;">
              <a class="menu-grid hot no-underline" style="vertical-align: -webkit-baseline-middle;">
                <div class="rounded border border-black-600 h-20 w-11/12 pt-3">
                        <span class="fa-layers fa-fw">
                            <i class="fas fa-circle-notch fa-spin position-relative" style="font-size: 20px;"></i>
                            <i class="fas fa-star fa-sm position-absolute"
                            style="font-size: 0.5rem;margin-left: -16px;margin-top: 5px;"></i>
                        </span>
                        <br>แทงหวย 
                </div>
              </a>
             </nuxt-link>
        </div>
        <div class="flex-1">
          <div class="rounded border border-black-600 h-20 w-11/12 pt-3">
            <i class="fas fa-dice"></i>
            <br>
            <button>คาสิโน</button>
          </div>
        </div>
        <div class="flex-1">
          <div class="rounded border border-black-600 h-20 pt-3" style="width: 88%">
            <i class="fas fa-gamepad"></i>
            <br>
            <button>เกม</button>
          </div>
        </div>
      </div>

      <div class="flex p-2 bg-white text-center">
        <div class="flex-1">
          <div class="rounded border border-black-600 h-20 pt-3 w-11/12">
            <i class="fas fa-money-check-alt"></i>
            <br>
            <button>ผลรางวัล</button>
          </div>
        </div>
        <div class="flex-1">
          <div class="rounded border border-black-600 h-20 w-11/12 pt-3">
            <i class="fas fa-money-check-alt"></i>
            <br>
            <button>โพยหวย</button>
          </div>
        </div>
        <div class="flex-1">
          <div class="rounded border border-black-600 h-20 w-11/12 pt-3" style="width: 88%">
            <i class="fas fa-money-check-alt"></i>
            <br>
            <button>สร้างชุดเลขชุด</button>
          </div>
        </div>
      </div>




      <div class="flex p-2 bg-white">
        <div class="flex-1">
          <button class="btn-primary w-11/12 rounded h-8">
            <i class="fas fa-plus"></i>
            <nuxt-link to="deposit"> รายงานการฝาก-ถอน</nuxt-link>
          </button>
        </div>
        <div class="flex-1">
          <button class="btn-secondary w-11/12 rounded h-8">
            <i class="fas fa-minus"></i>
            <nuxt-link to="withdraw"> รายงานการเงิน</nuxt-link>
          </button>
        </div>
      </div>


       <div class="flex p-2 bg-white rounded-b-lg">
        <div class="flex-1">
          <button>ระบบแนะนำ</button>
        </div>
        <div class="flex-1">
          <button>ค่าคอมแนะนำเพื่อน</button>
          <br>
          0.00THB
        </div>
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
/* body {
	font-family: 'Nunito', sans-serif;
 } */
</style>
