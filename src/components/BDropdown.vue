<template>
   <div>
      <div class="dropdown">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton2" data-bs-toggle="dropdown" aria-expanded="false">
   <slot name="title" />
  </button>
  <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="dropdownMenuButton2">
    <li><a class="dropdown-item active" href="#">
       <slot name="mirjalol"/>
       </a></li>
    <li><a class="dropdown-item" href="#"><slot name="vue"/></a></li>
    <li><a class="dropdown-item" href="#">Something else here</a></li>
    <li><hr class="dropdown-divider"></li>
    <li><a class="dropdown-item" href="#">Separated link</a></li>
  </ul>
  
   </div>
   </div>
</template>

<script>
export default {
   name: 'Dropdown',
   props: {
    open: {
      type: Boolean,
      default: false,
    },
  },

   data() {
      return {
         
      };
   },

   mounted() {
      
   },

   methods: {
      
   },
};
</script>

<style lang="scss" scoped>

</style>