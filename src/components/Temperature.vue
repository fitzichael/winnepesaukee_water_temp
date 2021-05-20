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
  }
}
</script>
