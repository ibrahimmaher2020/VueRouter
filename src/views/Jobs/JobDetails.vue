<template>
  <h1>Job Details Page</h1>
  <div>
    <p>Job ID is :  {{ id }}</p>    
    <p>Job Name{{ title }}</p>
    <p>Details {{  }}</p>

  </div>
    
</template>

<script>
export default {
    props:['id','title'],
    // data(){
    //     return{
    //         id:this.$route.params.id
    //     }
    // }

}
</script>

<style>

</style>