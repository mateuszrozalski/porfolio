<template>
<div>
  <div style="position: absolute; top: 0; left: 0;">
    <div class="container space-between hello justify-txt">
      <h1 class="barlow-semi-condensed site-name">{{name}}<br class="mobile-only"><span class="txt4 serif" style="font-weight: 400; font-size: 100%;"> Design</span></h1>
      <p class="serif desktop-only txt5" style="line-height: 240%; font-size: 100%">
        branding, web development, web design, print design...
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
