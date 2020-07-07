<template>
  <div class="post-five">

<div class="content">

<div class="social-media">
<div class="social-media__title">
  2020
</div>
<p class="social-media__description">
  Lorem Ipsum available
but the  suffered alterat
ionsome form humour
or randomised words 
</p>

  <SocialMediaIcons></SocialMediaIcons>

</div>

<div class="title-media">
  <div class="title-post">
    Business <span>Events</span>
  </div>
<img src="../../assets/images/social-media-post5.jpg">

</div>



</div>



  </div>
</template>

<script lang="ts">
import SocialMediaIcons from '@/components/SocialMediaIcons/SocialMediaIcons.vue';

export default {
  name:'PostFive',
  components:{SocialMediaIcons}
}

 
</script>


<style lang="scss" scoped>
  @import "./Post5.scss";
</style>