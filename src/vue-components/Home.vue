<template>
  <div>
  
  <!-- vcItemBox101 -->
  <h2 class="item-id">vcItemBox101</h2>
  <div class="row">
    <div class="col-sm-3">
      <vcItemBox1 />
    </div>
    <div class="col-sm-9">
      39
    </div>
  </div>

  </div>
</template>
<script>
const vcItemBox1 = () => import ('./vcItemBox1.vue');
  export default {
    data () {
      return {    
      }
    },
    components: {
      vcItemBox1: vcItemBox1
    },
    mounted: function () {
      // console.log("Home.vue mounted");
    }
  }
</script>