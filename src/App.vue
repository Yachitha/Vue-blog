<template>
  <div>
    <blog-header></blog-header>
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  export default{
    components:{
      'blog-header':Header
    },
    data(){
      return {
        title: 'This is my first project!'
      }
    },
    methods:{
      greeting: function(){
        return 'this is the body';
      }
    }
  }
</script>

