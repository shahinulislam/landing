<script setup>
  const teamInfo = [
    {
      img:'/img/team_1.jpg',
      name:'Marvin McKinney',
      desi: 'Marketing Coordinator',
      fb : 'https://www.facebook.com/',
      tt : 'https://twitter.com/',
      ins: 'https://www.instagram.com/',
      pin: 'https://www.pinterest.com/'
    },

    {
      img:'/img/team_2.jpg',
      name:'Kathryn Murphy',
      desi: 'Ethical Hacker',
    },

    {
      img:'/img/team_3.jpg',
      name:'Darrell Steward',
      desi: 'Software Developer'
    }
  ]
</script>


<template>
  <!-- Team -->
  <section id="team">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="intro">
            <h6>Team</h6>
            <h1>Team Members</h1>
            <p class="mx-auto">Our Team in Web Development excels in crafting innovative websites and applications. With a passion for coding and design, we deliver exceptional digital experiences that drive success.</p>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-4 col-md-8">
          <div class="team-member">
            <div class="image">
              <img :src="teamInfo[0].img" alt="">
              <div class="social-icons">
                <a :href="teamInfo[0].fb"><i class='bx bxl-facebook'></i></a>
                <a :href="teamInfo[0].tt"><i class='bx bxl-twitter'></i></a>
                <a :href="teamInfo[0].ins"><i class='bx bxl-instagram'></i></a>
                <a :href="teamInfo[0].pin"><i class='bx bxl-pinterest'></i></a>
              </div>
              <div class="overlay"></div>
            </div>
            <h5>{{teamInfo[0].name}}</h5>
            <p>{{teamInfo[0].desi}}</p>
          </div>
        </div>
        <div class="col-lg-4 col-md-8">
          <div class="team-member">
            <div class="image">
              <img :src="teamInfo[1].img" alt="">
              <div class="social-icons">
                <a :href="teamInfo[0].fb"><i class='bx bxl-facebook'></i></a>
                <a :href="teamInfo[0].tt"><i class='bx bxl-twitter'></i></a>
                <a :href="teamInfo[0].ins"><i class='bx bxl-instagram'></i></a>
                <a :href="teamInfo[0].pin"><i class='bx bxl-pinterest'></i></a>
              </div>
              <div class="overlay"></div>
            </div>
            <h5>{{teamInfo[1].name}}</h5>
            <p>{{teamInfo[1].desi}}</p>
          </div>
        </div>
        <div class="col-lg-4 col-md-8">
          <div class="team-member">
            <div class="image">
              <img :src="teamInfo[2].img" alt="">
              <div class="social-icons">
                <a :href="teamInfo[0].fb"><i class='bx bxl-facebook'></i></a>
                <a :href="teamInfo[0].tt"><i class='bx bxl-twitter'></i></a>
                <a :href="teamInfo[0].ins"><i class='bx bxl-instagram'></i></a>
                <a :href="teamInfo[0].pin"><i class='bx bxl-pinterest'></i></a>
              </div>
              <div class="overlay"></div>
            </div>
            <h5>{{teamInfo[2].name}}</h5>
            <p>{{teamInfo[2].desi}}</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>