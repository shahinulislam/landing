<script setup>

  const client = '90K+'
  const code ='45M'
  const download = '190'
  const sub = '380K'

</script>

<template>
  <!-- MILESTONE -->
  <section id="milestone">
    <div class="container">
      <div class="row text-center justify-content-center gy-4">
        <div class="col-lg-2 col-sm-6">
          <h1 class="display-4">{{ client }}</h1>
          <p class="mb-0">Happy Clients</p>
        </div>
        <div class="col-lg-2 col-sm-6">
          <h1 class="display-4">{{ code }}</h1>
          <p class="mb-0">Lines of code</p>
        </div>
        <div class="col-lg-2 col-sm-6">
          <h1 class="display-4">{{ download }}</h1>
          <p class="mb-0">Total Downloads</p>
        </div>
        <div class="col-lg-2 col-sm-6">
          <h1 class="display-4">{{ sub }}</h1>
          <p class="mb-0">YouTube Subscribers</p>
        </div>
      </div>
    </div>
  </section>
</template>
