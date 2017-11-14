<template>
<div>
  <div style="position: absolute; top: 0; left: 0;">
    <div class="container space-between hello justify-txt">
      <h1 class="barlow-condensed site-name">{{name}}<br class="mobile-only"><span class="txt4"> DESIGN</span></h1>
      <p class="serif desktop-only">
        <!-- <strong></strong><br /> -->
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </p>
    </div>
  </div>


</div>

</template>

<script>
  export default {
    data () {
      return {
        name: 'Mateusz Różalski',
        logo: './src/assets/img/logo.svg'
      }
    }
  }
</script>
