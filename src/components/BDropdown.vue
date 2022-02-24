<template>
  <div>
    <div class="dropdown">
      <button
        class="btn btn-secondary dropdown-toggle"
        type="button"
        id="dropdownMenuButton2"
        data-bs-toggle="dropdown"
        aria-expanded="false"
      >
        slotlar bilan ishlash
      </button>
      <ul
        class="dropdown-menu dropdown-menu-dark"
        aria-labelledby="dropdownMenuButton2"
      >
        <Blist class="dropdown-item active" >dropdown1</Blist>
        <Blist>dropdown2</Blist>
        <Blist>dropdow31</Blist>
        <Blist>dropdown1</Blist>  
          <Blist>dropdown2</Blist>
        <Blist>dropdow31</Blist>
        <Blist>dropdown1</Blist>
     
      
      </ul>
    </div>
  </div>
</template>

<script>
import Blist from "./Blist.vue";
export default {
  components: {
    Blist,
  },
  name: "Dropdown",
  props: {
    group: {
      type: String,
      default: false,
    },
    index: {
      type: Number,
      default: false,
    },
  },

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped>
</style>