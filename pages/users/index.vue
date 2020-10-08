<template>
<div>
  <h1>User view</h1>
  <input type="text" v-model="userId">
    <button @click="load">Load user</button>
    </div>
  </template>

<script>
export default {
  data(){
  return {
     userId: ""
  }
  },
  methods:{
     load(){
       this.$router.push('/users/'+this.userId);
     }
  }
}
</script>

