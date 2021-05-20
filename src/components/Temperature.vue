<template>
  <div>
    {{ temperature }} °F
  </div>
</template>
<script>
export default {
  name: "Temperature",
  data: function () {
    return {
      temperature: -1
    }
  },
  mounted: function () {
    fetch('https://www4.des.state.nh.us/rti_data/WEIN3_TABLE.HTML')
      .then(res => res.text())
      .then(body => console.log(body));
  }
}
</script>
