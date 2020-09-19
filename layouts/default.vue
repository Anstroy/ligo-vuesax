<template>
  <div>
    <sidebar />
    <div class="container flex items-center center">
      <h1>you see me?</h1>
      <Nuxt />
    </div>
  </div>
</template>

<script>
import sidebar from '~/components/sidebar'
export default {
  components: {
    sidebar,
  },
}
</script>

<style>
*,
html,
body {
  font-family: 'Poppins', sans-serif !important;
}
</style>
