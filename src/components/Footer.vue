<template>
  <footer>
    <p>{{copyright}}</p>
  </footer>
</template>

<script>
export default {
  data () {
    return {
      copyright: 'Copyright Roy Magdaong 2019'
    }
  }
}
</script>

<style scoped>
footer{
  background: #222;
  padding: 10px;
}
p{
  color: lightblue;
  text-align: center;
}
</style>
