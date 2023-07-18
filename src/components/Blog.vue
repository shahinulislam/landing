<script setup>

  const blog = [
    {
      img : '/img/project5.jpg',
      title: 'Web Design trends in 2023',
      content : 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from',
      postDate:'01 Feb, 2023',
      category:'Web Design'
    },

    {
      img : '/img/project4.jpg',
      title: 'Vue Js 3 trends in 2023',
      postDate:'15 Mar, 2023',
      category:'Programming'
    },

    {
      img : '/img/project2.jpg',
      title: 'Marketing trends in 2023',
      postDate:'19 May, 2023',
      category:'Marketing'
    }
  ]

</script>


<template>
  <section id="blog">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="intro">
            <h6>Blog</h6>
            <h1>Blog Posts</h1>
            <p class="mx-auto">Contrary to popular belief, Lorem Ipsum is not simply random text. It has
              roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old</p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-4">
          <article class="blog-post">
            <img :src="blog[0].img" alt="">
            <a href="#" class="tag">{{ blog[0].category }}</a>
            <div class="content">
              <small>{{ blog[0].postDate }}</small>
              <h5>{{ blog[0].title }}</h5>
              <p>{{blog[0].content}}</p>
            </div>
          </article>
        </div>
        <div class="col-md-4">
          <article class="blog-post">
            <img :src="blog[1].img" alt="">
            <a href="#" class="tag">{{ blog[1].category }}</a>
            <div class="content">
              <small>{{ blog[1].postDate }}</small>
              <h5>{{ blog[1].title }}</h5>
              <p>{{blog[0].content}}</p>
            </div>
          </article>
        </div>
        <div class="col-md-4">
          <article class="blog-post">
            <img :src="blog[2].img" alt="">
            <a href="#" class="tag">{{ blog[2].category }}</a>
            <div class="content">
              <small>{{ blog[2].postDate }}</small>
              <h5>{{ blog[2].title }}</h5>
              <p>{{blog[0].content}}</p>
            </div>
          </article>
        </div>
      </div>
    </div>
  </section>
</template>
