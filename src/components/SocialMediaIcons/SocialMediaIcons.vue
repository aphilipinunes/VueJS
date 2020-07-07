<template>
  <div class="icons" :class="[className]">
    <img src="../../assets/images/linkedin-icon.png">
     <img src="../../assets/images/pinterest-icon.png">
      <img src="../../assets/images/twitter-icon.png">
       <img src="../../assets/images/facebook-icon.png">
  </div>
</template>



<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class SocialMediaIcons extends Vue {
  @Prop() private className!: string;
}
</script>


<style lang="scss" scoped>
  @import "./SocialMediaIcons.scss";
</style>