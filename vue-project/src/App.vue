<template>
	<transition name="el-fade-in-linear">
    <router-view />
  </transition>
</template>

<script>

export default {
  data() {
    return {
      loaded: true
    }
  }
}
</script>

<style>
  body,html {padding:0;margin:0;overflow: hidden;}
</style>