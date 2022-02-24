
<template>

  <div>
 
    <BDropdown>dropdown1</BDropdown>
    

  
  </div>
</template>

<script>
import BButton from './components/BButton.vue'
import BDropdown from './components/BDropdown.vue'
export default{
   components:{
      BButton,
      BDropdown
   },
    data() {
    return {
      showModal: true,
    };
  },
}
</script>

<style>

</style>
