<template>
  <div>
    <vue-scrollbar custom-class="my-scrollbar" ref="Scrollbar">
      <div class="scroll-me">
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="kolom"></div>
        <div class="clearfix"></div>
      </div>
    </vue-scrollbar>
  </div>
</template>

<script>

  import VueScrollbar from 'vue2-scrollbar'
  require('../../node_modules/vue2-scrollbar/dist/style/vue2-scrollbar.css')

  // It's required to set min height of the scrollbar wrapper
  require('../../node_modules/vue2-scrollbar/dist/style/app.css')

  export default {
    components: { VueScrollbar }
  }

</script>
