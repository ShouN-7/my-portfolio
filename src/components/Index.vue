<template>
  <div>
    <router-link v-for="(content, index) in contents" :key="index" class="circle" :to="content">{{ content }}</router-link>
  </div>
</template>
<script>
export default{
  name: 'Index',
  data: function () {
    return {
      contents: ['Skills', 'Interest', 'Personal']
    }
  }
}
</script>
<style>
</style>
