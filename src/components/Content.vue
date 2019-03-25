<template>
  <ul>
    <li v-for="student in students" 
      @click="student.show=!student.show" 
      :key="student.index"
    >
      <h2>{{student.name}}</h2>
      <caption>{{student.Course}}</caption>
      <h3 v-show="student.show">{{student.Specialization}}</h3>
    </li>
  </ul>
</template>

<script>
export default {
  props:{
    students:{
      type: Array
    }
  },
  data () {
    return {
      
    }
  }
}
</script>

<style scoped>
</style>
