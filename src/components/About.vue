<script setup >
  const about = [
    {
      title : 'Digital Marketing',
      content: 'It is a long established fact that a reader will be distracted by the readable content of a page',
      icon  : '/img/icon6.png'
    },
    {
      title : 'E-mail Marketing',
      content: 'It is a long established fact that a reader will be distracted by the readable content of a page ',
      icon  : '/img/icon4.png'
    },
    {
      title : 'Buisness Marketing',
      content: 'It is a long established fact that a reader will be distracted by the readable content of a page',
      icon  : '/img/icon5.png'
    },
  ]
</script>

<template>
  <!-- ABOUT -->
  <section id="about">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-5 py-5">
          <div class="row">
            <div class="col-12">
              <div class="info-box">
                <img :src="about[0].icon" alt="">
                <div class="ms-4">
                  <h5>{{ about[0].title }}</h5>
                  <p>{{ about[0].content }}</p>
                </div>
              </div>
            </div>
            <div class="col-12 mt-4">
              <div class="info-box">
                <img :src="about[1].icon" alt="">
                <div class="ms-4">
                  <h5>{{ about[1].title }}</h5>
                  <p>{{ about[1].content }}</p>
                </div>
              </div>
            </div>
            <div class="col-12 mt-4">
              <div class="info-box">
                <img :src="about[2].icon" alt="">
                <div class="ms-4">
                  <h5>{{ about[2].title }}</h5>
                  <p>{{ about[2].content }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-5">
          <img src="/img/about.png" alt="">
        </div>
      </div>
    </div>
  </section>
</template>
