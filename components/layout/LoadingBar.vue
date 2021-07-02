<template>
  <div v-if="loading" class="loading-page">
    <p style=" display: flex; align-items: center; justify-content: center;">
        <img src="~/assets/imge/logo.png" alt="" width="50">
    </p>
    
    <div class="spinner-grow text-success"></div>
    <div class="spinner-grow text-success"></div>
    <div class="spinner-grow text-success"></div>

  </div>
</template>

<script>
  export default {
    data: () => ({
      loading: false
    }),
    methods: {
      start() {
        this.loading = true
      },
      finish() {
        this.loading = false
      }
    }
  }
</script>

<style scoped>
  .loading-page {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.8);
    text-align: center;
    padding-top: 200px;
    z-index: 5;
    font-size: 30px;
    font-family: sans-serif;
  }
</style>