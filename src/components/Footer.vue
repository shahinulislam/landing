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
  <footer>
    <div class="footer-top text-center">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6 text-center">
            <h4 class="navbar-brand"><span class="text-success">Vue</span>Max<span class="dot">.</span></h4>
            <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of
              classical Latin literature from</p>
            <div class="col-auto social-icons">
              <a :href="sLink[0].fbLink"><i class='bx bxl-facebook'></i></a>
              <a :href="sLink[0].ttLink"><i class='bx bxl-twitter'></i></a>
              <a :href="sLink[0].instLink"><i class='bx bxl-instagram'></i></a>
              <a :href="sLink[0].inLink"><i class='bx bxl-linkedin'></i></a>
            </div>
            <div class="col-auto conditions-section">
              <a href="https://shahinulislam.com/privacy-policy/">Privacy</a>
              <a href="https://shahinulislam.com/privacy-policy/">Terms</a>
              <a href="https://shahinulislam.com/privacy-policy/">Disclaimer</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bottom text-center">
      <p class="mb-0">Copyright ©2023. All rights Reserved</p> Made With Love By
      <a class="text-secondary" href="https://shahinulislam.com">Shahinul Islam</a>
    </div>
  </footer>
</template>