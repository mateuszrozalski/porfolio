<template>
<div>
  <div class="full-flex top-bar">

    <!-- <h4> I believe that good design can give a feeling of  order and expedience. Nn crowded, massy environment  in global communication era deliberate medium is a way to achieve goals and success.  I see design as a stepwise process – ideas become clear and message is sharpen to perfection. </h4> -->
    <!-- <img style="order: 4;" class="logo" :src="logo" /> -->
    <!-- <div style="background-color: black; width: 22px; height: 18px; order: 1; z-index: 1000;" class="menu-button"></div> -->
  </div>

  <div style="position: absolute; top: 0; left: 0;">
    <div class="container space-between hello Barlow justify-txt">
      <h1 style="font-size: 160%;" class="Barlow">{{name}}<br class="mobile-only"><span class="txt4"> DESIGN</span></h1>
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
        name: 'MATEUSZ RÓŻALSKI',
        logo: './src/assets/img/logo.svg'
      }
    }
  }
</script>
