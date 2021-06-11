<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/signin">Log in</router-link>
    <router-link to="/dashboard">Home</router-link>
  </div>
  <router-view/>
</template>


<script>
import Nav from '@/components/Nav'
export default {
  components : {
    Nav
  }
}
</script>



<style>



</style>
