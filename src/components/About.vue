<template>
  <div class="wraper">
   <h2>About <span class="txt1">/</span> Contact</h2>
   <div class="boxes">
     <div class="box-tall nohover" style="transform: translate3d(-10px, -10px, 0)">
       <div>
         <div class="work-bg" ></div>
         <div class="justify-txt" style="position: relative; padding: 0 40px;">
             <h3 class="site-name barlow-condensed txt4">Pleased to meet you.</h3>
             <p class="serif">I am a graphic designer and web developer working and leaving in Warsaw. If You like my work contact me and tell me how I can help in your project.</p>
             <a class="barlow-condensed txt1" href="mailto:olivetum@gmail.com"><strong>Mail</strong></a><br>
             <a class="barlow-condensed txt5" href="tel:+48531051434"><strong>Phone</strong></a>

           </div>
       </div>
     </div>

     <div class="box-tall nohover me"  :style="{background: me}" style="background-position: 0 35% !important;">
       <div>
         <div class="box-bg"></div>
         <!-- <p class="description">Dolor sit amet</p> -->
       </div>
     </div>
   </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        me: "url('./src/assets/img/me.png')"
      }
    }
  }
</script>

<style>
</style>
