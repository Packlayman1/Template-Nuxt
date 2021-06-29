<!-- Please remove this file from your project -->
<template>
  <div>
    <nav class="relative w-full bg-white">
      <div class="flex h-12">
        <a href="#" class="py-2 px-4 no-underline w-full">
          <img src="~/assets/imge/logo.png" class="inline-block" width="35" />
          <label>LOTTO</label>
        </a>
        <div class="w-full text-right">
          <button class="btn-sm mt-2 mb-2 align-text-top">
            <i class="cil-reload mr-2" style="vertical-align: middle"></i>
            <span>320.25 ฿</span>
          </button>
        </div>
        <div class="text-right">
          <button class="cursor-pointer h-12 pl-2 pr-2">
            <i class="far fa-bell"></i>
          </button>
        </div>

        <button class="cursor-pointer ml-auto relative w-12 pl-2 pr-4 h-12">
          <i class="fas fa-bars"></i>
        </button>
      </div>
    </nav>

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
          <button class="btn-success w-11/12">
          <i class="fas fa-plus"></i>
            เติมเงิน
          </button>
        </div>
        <div class="flex-1">
          <button class="btn-danger w-11/12">
          <i class="fas fa-minus"></i>
            ถอนเงิน
          </button>
        </div>
      </div>


       <div class="flex p-2 bg-white text-center">
        <div class="flex-1">
          <button>แทงหวย</button>
        </div>
        <div class="flex-1">
          <button>คาสิโน</button>
        </div>
        <div class="flex-1">
          <button>เกม</button>
        </div>
      </div>

      <!--
      <div class="flex">
        <div class="flex-1">
          <button>ผลรางวัล</button>
        </div>
        <div class="flex-1">
          <button>โพยหวย</button>
        </div>
        <div class="flex-1">
          <button>สร้างเลขชุด</button>
        </div>
      </div>

      <div class="flex">
        <div class="flex-1">
          <button>รายงานการฝาก-ถอน</button>
        </div>
        <div class="flex-1">
          <button>รายงานการเงิน</button>
        </div>
      </div>


      <div class="flex">
        <div class="flex-1">
          <button>ระบบแนะนำ</button>
        </div>
        <div class="flex-1">
          <button>ค่าคอมแนะนำเพื่อน</button>
          <br>
          0.00THB
        </div>
      </div> -->


    </div>



    <div class="flex footerstyle bg-white">
      <div class="flex-1">
        <i class="fas fa-home"></i>
        <br />
        <span>หน้าหลัก</span> 
      </div>
      <div class="flex-1">
        <i class="fas fa-clipboard-list"></i>
        <br />
        โพยหวย
      </div>
      <div class="flex-1">แทงหวย</div>
      <div class="flex-1">
        <i class="fas fa-trophy"></i>
        <br />
        ผลรางวัล
      </div>
      <div class="flex-1">
        <i class="fas fa-gamepad"></i>
        <br />
        เกม/คาสิโน
      </div>
    </div>
  </div>
</template>

<style>
.footerstyle {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  text-align: center;
}

/* body {
	font-family: 'Nunito', sans-serif;
 } */

</style>
