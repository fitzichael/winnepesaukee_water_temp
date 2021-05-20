<template>
  <div>
    <div id="tempHeader">The current temperature at Lake Winnipesaukee is</div>
    <Temperature id="temp"/>
  </div>
</template>

<script>
import Temperature from "./Temperature.vue";
export default {
  name: "Main",
  components: {
    Temperature
  }
}
</script>
<style scoped>
#tempHeader {
  font-size: 40px;
  color: black;
  left: 0;
  line-height: 200px;
  margin-top: -100px;
  position: absolute;
  text-align: center;
  top: 35%;
  width: 100%;
}
#temp {
  font-size: 40px;
  color: black;
  left: 0;
  line-height: 200px;
  margin-top: -100px;
  position: absolute;
  text-align: center;
  top: 45%;
  width: 100%;
}
</style>
