<script setup>
import IconArrow1 from "./icons/IconArrow1.vue";
</script>


<template>
  <div 
  class="v-btn"
  
  >
    <span>{{ buttonText }}</span>
  </div>
</template>

<script>
export default {
  props: {
    buttonText: {
      type: String,
      default: () => "",
    },
    
  }
  

};
</script>

<style lang="sass">
.v-btn
  border-radius: 20px
  padding: 14px 46px
  color: #fff
  background: #000
  cursor: pointer
  font-size: 18px
  text-transform: uppercase
  
</style>