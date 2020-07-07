<template>
  <div class="post-one">
    <div class="bg-blue">
      
    </div>
    <div class="content">
  <div class="title-media">
    <div class="title-post">
      Business <span>Events</span>
    </div>
    <img src="../../assets/images/image-1-post-1.jpg">
  </div>

  <div class="social-media">
 <img src="../../assets/images/image-2-post-1.jpg">
 <p>
   Lorem Ipsum available, but the 
suffered alteration some
 </p>

 
  <SocialMediaIcons class='small-icons'></SocialMediaIcons>

  </div>

  <div class="mobile-p">
     <p>
   Lorem Ipsum available, but the 
suffered alteration some
 </p>

 
  <SocialMediaIcons class='small-icons'></SocialMediaIcons>

  </div>
  </div>
  </div>
</template>

<script lang="ts">
import SocialMediaIcons from '@/components/SocialMediaIcons/SocialMediaIcons.vue';

export default {
  name:'PostOne',
  components:{SocialMediaIcons}
}

</script>


<style lang="scss" scoped>
  @import "./Post1.scss";
</style>