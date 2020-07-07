<template>
  <div class="title">

    <h1>{{ msg }}</h1>
       <div class="text-description">{{ description }}</div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class TitleHome extends Vue {
  @Prop() private msg!: string;
   @Prop() private description!: string;
}
</script>


<style lang="scss" scoped>
  @import "./TitleHome.scss";
</style>