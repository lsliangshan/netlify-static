<template>
  <div class="headers">HEADER >>> {{msg}}</div>
</template>
<style scoped>
.headers {
  width: 300px;
  height: 40px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  font-size: 24px;
}
</style>
<script>
export default {
  name: 'headers',
  data () {
    return {
      msg: 'message from headers.vue'
    }
  }
}
</script>

