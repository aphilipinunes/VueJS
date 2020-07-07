<template>
  <div class="post-three">

<div class="content-img">

<div class="border-top-bottom">

</div>

<div class="border-right">

</div>


<div class="border-right-left">

</div>

<div class="border-left-bottom">


</div>


<div class="border-right-bottom">


</div>

<div class="border-left">

</div>

  <div class="triangle"></div>
    <div class="triangle-2"></div>
      <div class="triangle-3"></div>
        <div class="triangle-4"></div>
</div>

    <div class="content">
      <div class="content__title">
     <div class="title">
        Business <span>EVENTS</span>
      </div>

      </div>
      <div class="content__social-media">
        <p>Lorem Ipsum available, but the 
suffered alterationsome </p>

    <SocialMediaIcons class='small-icons'></SocialMediaIcons>


      </div>

    </div>

  </div>
</template>

<script lang="ts">

import SocialMediaIcons from '@/components/SocialMediaIcons/SocialMediaIcons.vue';

export default{
    name:'PostThree',
  components:{SocialMediaIcons}
}
</script>


<style lang="scss" scoped>
  @import "./Post3.scss";
</style>