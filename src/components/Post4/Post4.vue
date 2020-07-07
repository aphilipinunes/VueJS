<template>
  <div class="post-four">

<div class="content">
  <div class="bg-yellow-rounded">
     <div class="bg-image">

    </div>
  </div>

  <div class="info">

         <div class="rounded-element-blue"></div>

    <div class="square-element-blue-lighten"></div>

    <div class="rounded-element-blue-lighten">

    </div>

            <div class="info__title">
     <div class="title">
        Business <span>EVENTS</span>
      </div>

      </div>
      <div class="info__social-media">
        <p>Lorem Ipsum available, but the 
suffered alterationsome form
humour </p>

    <SocialMediaIcons class='small-icons'></SocialMediaIcons>


      </div>
  </div>
 
</div>

  </div>
</template>

<script lang="ts">
import SocialMediaIcons from '@/components/SocialMediaIcons/SocialMediaIcons.vue';

export default{
    name:'PostFour',
  components:{SocialMediaIcons}
}
</script>


<style lang="scss" scoped>
  @import "./Post4.scss";
</style>