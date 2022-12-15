<script setup>
import VBtn from './components/v-btn.vue'
</script>

<template>
  <VBtn 
  buttonText="Отправить письмо" 
  />
</template>


<script>
export default {
  name: "App",
  components: {
    VBtn,
  }
}
</script>