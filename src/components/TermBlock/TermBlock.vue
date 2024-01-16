<template>
    <div class="term">
      <div class="term__texts" v-if="isVisible">
        <div class="term__text">This website uses cookies to enhance the user experience. Read our <a href="/">privacy policy</a> for more info.</div>
        <button class="term__btn" @click="hideObject">Accept Cookies</button>
      </div>
    </div> 
  </template>
  
  <script>
  export default {
    data() {
      return {
        isVisible: true,
      };
    },
    methods: {
      hideObject() {
        this.isVisible = false;
      },
    },
  };
  </script>  

<style lang="scss" scoped>
@import '@/components/TermBlock/TermBlock.scss';
</style>