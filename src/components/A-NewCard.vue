<script setup>

import { useRoute } from 'vue-router';

const route = useRoute()
const id = parseInt(route.params.id)

</script>
<template>
 <div class="row mb-2">
    <div class="col-md-6" >
      <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        <div class="col p-4 d-flex flex-column position-static">
          <strong class="d-inline-block mb-2 text-primary-emphasis">หัวข้อ{{ n }}>.</strong>

          <img src="https://www.pinclipart.com/picdir/big/218-2185409_new-new-logo-new-sign-new-new-png.png" width=50 href="#">

          <h3 class="mb-0">กิจกรรมเเนะนำ {{ id }}.</h3>
          <div class="mb-1 text-body-secondary">Nov 12</div>
          <p >
              <img src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t39.30808-6/320315426_1579472242511179_2105333197071377454_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=a2f6c7&_nc_ohc=MF_F0wHE0f8AX8qd8Xf&_nc_ht=scontent.fcnx4-1.fna&oh=00_AfBuA51Fy-AkksWKFrUvuw1H2iRKahDOhNl19phzQ74gdw&oe=6513FFDD" width=90 href="#">

              <img src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t39.30808-6/362608212_607464948167316_5738751714436040860_n.jpg?stp=cp6_dst-jpg&_nc_cat=105&ccb=1-7&_nc_sid=5614bc&_nc_ohc=KHU2xucDGjUAX-FmBQT&_nc_ht=scontent.fcnx4-1.fna&oh=00_AfAHL661QttvmrA6BQDZPlSZ0ozfM66KF_9MQWCs1zjB4g&oe=651404D2" width=150 href="#">

              <img src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t39.30808-6/362889309_607464954833982_8289465561056161584_n.jpg?stp=cp6_dst-jpg&_nc_cat=107&ccb=1-7&_nc_sid=5614bc&_nc_ohc=U58mm3pNvQ0AX9IpbQx&_nc_ht=scontent.fcnx4-1.fna&oh=00_AfBQSCUpyMEPOD4i0xWQ6nGcEL2e2LpD5FAi-bHitR4SIw&oe=65159DCD" width=150 href="#">

              <img src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t39.30808-6/320315426_1579472242511179_2105333197071377454_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=a2f6c7&_nc_ohc=MF_F0wHE0f8AX8qd8Xf&_nc_ht=scontent.fcnx4-1.fna&oh=00_AfBuA51Fy-AkksWKFrUvuw1H2iRKahDOhNl19phzQ74gdw&oe=6513FFDD" width=90 href="#">
            </p>
          <p class="card-text mb-auto">
            ดช.บริติชสีบลู วัย1ขวบ💙🐻
            ฟอร์มหมี ✅
            รัฐบาลบริติช #wcf<br>

            ติดต่อผู้เพาะพันธุ์สัตว์เลี้ยง <br>

            tel.093 580 9356 <br>

            ยังไม่มีคะแนน (0 รีวิว) 
          </p>

            <div class="col-4 ">
            <a class="link-secondary" href="#" aria-label="Search">
            <svg xmlns="http://www.w3.org/2000/svg" width="5" height="5" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="mx-3" role="img" viewBox="0 0 24 24"><title>Search</title><circle cx="10.5" cy="10.5" r="7.5"/><path d="M21 21l-5.2-5.2"/></svg>
            </a>
          </div>
        </div>
        <div class="col-auto d-none d-lg-block">
          <img src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t39.30808-6/320315426_1579472242511179_2105333197071377454_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=a2f6c7&_nc_ohc=MF_F0wHE0f8AX8qd8Xf&_nc_ht=scontent.fcnx4-1.fna&oh=00_AfBuA51Fy-AkksWKFrUvuw1H2iRKahDOhNl19phzQ74gdw&oe=6513FFDD" width=100 href="#">
        </div>
      </div>
    </div>
 </div>
</template>
