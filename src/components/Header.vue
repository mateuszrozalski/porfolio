<template>
  <div>
    <div class="container space-between hello justify-txt">
      <div class="business-card">
        <p class="serif" style="font-size: 80%">
          branding, web development, web design, print design...
        </p>
        <img class="logo" :src="logo">
        <!-- <h4 class="barlow-semi-condensed">(+48) 531 051 434</h4>
        <a href="mailto:olivetum@gmail.com"><h4 class="barlow-semi-condensed">MATEUSZROZALSKI@GMAIL.COM</h4></a>
        <h4 class="barlow-semi-condensed">MATEUSZROZALSKI.GITHUB.IO/PORTFOLIO/</h4>
        <i style="float: right;" class="fa fa-level-down fa-2x txt3" aria-hidden="true"></i> -->
      </div>
    </div>
    <div style="width:100%; height: 8px; display: flex;">
      <div style="width: 20% !important; height: 100% !important;" class="bg4">  </div>
      <div style="width: 20% !important; height: 100% !important;" class="bg1">  </div>
      <div style="width: 20% !important; height: 100% !important;" class="bg2">  </div>
      <div style="width: 20% !important; height: 100% !important;" class="bg5">  </div>
      <div style="width: 20% !important; height: 100% !important;" class="bg3">  </div>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        name: 'Mateusz Rozalski',
        logo: './src/assets/img/logo.svg'
      }
    }
  }
</script>
