<template>
 <div class="row mb-2">
    <div class="col-md-6" v-for="n in 6" :key="n" >
      <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        <div class="col p-4 d-flex flex-column position-static">
          <strong class="d-inline-block mb-2 text-primary-emphasis">หัวข้อที่{{ n }}></strong>
          
          <img src="https://www.pinclipart.com/picdir/big/218-2185409_new-new-logo-new-sign-new-new-png.png" width=50 href="#">
          <h3 class="col-0 justify-content-end ">กิจกรรมเเนะนำ</h3>
          <div class="mb-1 text-body-secondary">Nov 12</div>
          <p class="card-text mb-auto">
              ติดต่อผู้เพาะพันธุ์สัตว์เลี้ยง <br>

              tel.093 580 9356 <br>

              ยังไม่มีคะแนน (0 รีวิว) 
          </p>
          
          <RouterLink :to="{name: 'news', params: {id: n}}" class="icon-link gap-1 icon-link-hover stretched-link">
            Continue reading {{ n }} 

            <svg class="bi"><use xlink:href="#chevron-right"/></svg>
          </RouterLink>
        </div>
        
        <div class="col-auto d-none d-lg-block">
          <svg class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: Thumbnail" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#55595c"/><text x="5%" y="50%" fill="#eceeef" dy=".3em">PR-sweetie cattery House</text></svg>
        </div>
      </div>
    </div>
 </div>
</template>
<script setup>
import { RouterLink } from 'vue-router'
</script>



