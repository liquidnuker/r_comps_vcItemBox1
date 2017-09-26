<template>
  <div>
  
  <!-- vcItemBox10101 -->
  <h2 class="item-id">vcItemBox102</h2>
  <div class="row">
    <div class="col-sm-3">
      <vcItemBox101 />
    </div>
    <div class="col-sm-9">
      39
    </div>
  </div>

  <!-- vcItemBox10102 -->
  <h2 class="item-id">vcItemBox102</h2>
  <div class="row">
    <div class="col-sm-3">
      <vcItemBox102 />
    </div>
    <div class="col-sm-9">
      39
    </div>
  </div>

  </div>
</template>
<script>
const vcItemBox101 = () => import ('./vcItemBox101.vue');
const vcItemBox102 = () => import ('./vcItemBox102.vue');
  export default {
    data () {
      return {    
      }
    },
    components: {
      vcItemBox101: vcItemBox101,
      vcItemBox102: vcItemBox102
    },
    mounted: function () {
      // console.log("Home.vue mounted");
    }
  }
</script>