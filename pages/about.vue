<template>
  <section class="container">
    <div>
    <h2 class="subtitle">
        Aún estoy trabajando en ello
    </h2>
    <div class="links">
      <a target="_blank" href="https://github.com/x905" class="button--grey" >GitHub</a>
      <a target="_blank" href="https://www.linkedin.com/in/angeldanielcastillo/" class="button--grey">LinkedIn</a>
    </div>

    </div>

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
    },
    head: {
    title: 'Sobre mi - Angel Castillo',
    meta: [
      { hid: 'portafolio', name: 'portafolio', content: 'Descripcion' }
    ]
  }


  }

</script>
