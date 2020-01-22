<template>
  <section class="container">
    <div>
      <h1 class="title">
         Hola!
      </h1>
      <h2 class="subtitle">
        Soy Daniel, Puedes echarle un vistazo a mi portafolio :)
      </h2>
      <div class="links">
        <nuxt-link to="/about" class="button--green">Sobre Mí</nuxt-link>
        <a
          href="https://nuxtjs.org/"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  },
  mounted() {
    var back = this.$route.params.slug
    console.log(back);
  }
}
</script>

<style>

</style>
