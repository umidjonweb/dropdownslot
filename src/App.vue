
<template>

  <div>
 
    <BDropdown>
        <template v-slot:title> Umidjon </template>
         <template v-slot:mirjalol> Mirjalol aka </template>
         <template v-slot:vue> Vue </template>
    </BDropdown>
  </div>
</template>

<script>
import BButton from './components/BButton.vue'
import BDropdown from './components/BDropdown.vue'
export default{
   components:{
      BButton,
      BDropdown
   }
}
</script>

<style>

</style>
