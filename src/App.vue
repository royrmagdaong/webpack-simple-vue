<template>
  <div>
    <app-header></app-header>
    <app-content v-bind:students='students'></app-content>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Footer from './components/Footer'
import Header from './components/Header'
import Content from './components/Content'


export default {
  components:{
    'app-footer':Footer,
    'app-header':Header,
    'app-content':Content
  },
  data () {
    return {
      students:[
        {name:'Roy Magdaong', Course: 'BSIT', Specialization:'Programming', show:false},
        {name:'Christly Tejano', Course: 'BSIT', Specialization:'Networking', show:false},
        {name:'Alvin Domingo', Course: 'BSIT', Specialization:'General IT', show:false},
        {name:'Jhon Daniel Catalan', Course: 'BSIT', Specialization:'Programming', show:false},
        {name:'Sanjie Esmero', Course: 'BSIT', Specialization:'Computer Hardware', show:false}
      ]
    }
  }
}
</script>

<style>
body{
  margin: 0%;
}
</style>
