<template>
<div>
  <!-- begin vcitemBox101 -->
  <div class="vcitemBox101">
    <div class="vcitemBox101_img-holder">
      <img src="img.jpg" alt="img alt" title="Image Title">
    </div>
    <h3 class="vcitemBox101_heading">ItemBox title</h3>
    <hr>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua.</p>
    <div class="vcitemBox101_btn-holder">
      <button class="btn btn1-01" data-message="button1" tabindex="0">button1</button>
      <button class="btn btn1-01" data-message="button2" tabindex="0">button2</button>
    </div>
  </div>
  <!-- end vcitemBox101 -->
</div>
</template>
<script>
export default {
  data () {
    return {   

    }
  },
  watch: {
  // : function () {
  // }
  },
  props: [
    "prName1"
  ],
  components: {
  },
  mounted: function () {
    // console.log(".vue mounted");
  },
  methods: {        
  }
}
</script>