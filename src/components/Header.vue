<template>
  <header>
    <h1>{{title}}</h1>
  </header>
</template>

<script>
export default {
  data () {
    return {
      title:'Sample header component'
    }
  }
}
</script>

<style scoped>
header{
  background: lightblue;
  padding: 12px;
}
h1{
  color:#222;
  text-align: center;
}
</style>
