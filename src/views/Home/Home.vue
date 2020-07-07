<template>
  <div class="home">

      <TitleHome msg="Social Media Post" description="Business Events"></TitleHome>

<div class="container">

      <Post5></Post5>

   <Post1></Post1>


   
  <Post2></Post2>

      <Post3></Post3>




      <Post4></Post4>



    
   

</div>

  </div>
</template>

<script>

import TitleHome from '@/components/TitleHome/TitleHome.vue';
import Post5 from '@/components/Post5/Post5.vue';
import Post4 from '@/components/Post4/Post4.vue';
import Post3 from '@/components/Post3/Post3.vue';
import Post2 from '@/components/Post2/Post2.vue';
import Post1 from '@/components/Post1/Post1.vue';

export default {
  name: 'Home',
  components: {
    TitleHome,
    Post5,
    Post4,
    Post3,
    Post2,
    Post1
  }
}
</script>


<style lang="scss" scoped>
  @import "./Home.scss";
</style>
