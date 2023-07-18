<script setup>

  const sLink = [
    {
      fbLink : 'https://www.facebook.com/shahinsalafi',
      ttLink : 'https://twitter.com/shahinulislam73',
      instLink : 'https://www.instagram.com/shahinulislam73/',
      inLink : 'https://www.linkedin.com/in/shahinul-islam-8814901a3/',
      mail : 'support@shahinulislam.com',
      tel : '+8801745301890'
    }
  ]

</script>

<template>
  <!-- TOP NAV -->
  <div class="top-nav" id="home">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-auto">
          <p> <i class='bx bxs-envelope'></i> <a >{{sLink[0].mail}}</a></p>
          <p> <i class='bx bxs-phone-call'></i> <a >{{sLink[0].tel}}</a> </p>
        </div>
        <div class="col-auto social-icons">
          <a :href="sLink[0].fbLink"><i class='bx bxl-facebook'></i></a>
          <a :href="sLink[0].ttLink"><i class='bx bxl-twitter'></i></a>
          <a :href="sLink[0].instLink"><i class='bx bxl-instagram'></i></a>
          <a :href="sLink[0].inLink"><i class='bx bxl-linkedin'></i></a>
        </div>
      </div>
    </div>
  </div>
</template>
