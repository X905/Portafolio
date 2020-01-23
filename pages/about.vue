<template>
  <section class="container">
    <h2 class="subtitle">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Similique totam voluptas aspernatur cum. Dignissimos perspiciatis saepe, eaque, quasi debitis nulla odio incidunt dolore nesciunt, enim non tempora voluptates quis delectus.
    </h2>
    <nuxt-link  to="/?back=true" id="fixed-btn" class="button--green">Regresar</nuxt-link>
  </section>
</template>


<script>
  export default{
    layout: 'secondary',
     asyncData () {
    return new Promise((resolve) => {
      setTimeout(function () {
        resolve({})
      }, 900)
    })
  }
  }
  
</script>
