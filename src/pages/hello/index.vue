<template>
  <div class="hello">
    <headers></headers>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'hello',
  components: {
    Headers: () => import('../../components/Headers.vue')
  },
  data () {
    return {
      msg: 'Enkel ui Hello 3333'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  color: rgb(10, 81, 15);
}
.hello img {
  max-width: 500px;
}
.btn {
  padding: 4px 10px;
  background-color: transparent;
  border: 1px solid rgb(10, 81, 15);
  color: rgb(10, 81, 15);
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}
</style>
