<script setup>

  const folioMainContent = 'An approachable, performant and versatile framework for building web user interfaces. Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.'

  const folio = [
    {
      img : "/img/project1.jpg",
      title : "Consulting Marketing",
      category : "Website Design"
    },
    {
      img : "/img/project2.jpg",
      title : "Consulting Marketing",
      category : "Website Design"
    },
    {
      img : "/img/project3.jpg",
      title : "Consulting Marketing",
      category : "Website Design"
    },
    {
      img : "/img/project4.jpg",
      title : "Consulting Marketing",
      category : "Website Design"
    },
    {
      img : "/img/project5.jpg",
      title : "Consulting Marketing",
      category : "Website Design"
    }
  ]


</script>

<template>
  <!-- Portfolio -->
  <section class="bg-light" id="portfolio">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="intro">
            <h6>Work</h6>
            <h1>Successful Projects</h1>
            <p class="mx-auto">{{folioMainContent}}</p>
          </div>
        </div>
      </div>
    </div>
    <div id="projects-slider" class="owl-theme owl-carousel">
      <div class="project">
        <div class="overlay"></div>
        <img :src="folio[0].img" :title="folio[0].category" alt="">
        <div class="content">
          <h2>{{folio[0].title}}</h2>
          <h6>{{folio[0].category}}</h6>
        </div>
      </div>
    </div>
  </section>
</template>
