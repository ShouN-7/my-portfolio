<template>
    <div class="container">
        <img class="rounded-circle img-fluid img-thumbnail col-sm-3" v-for="(val, index) in skills" :src="imagePath(val)" :key="index" />
    </div>
</template>
<script>
export default {
  data: function () {
    return {
      skills: ['java', 'php', 'android', 'cs', 'html_css', 'js', 'docker', 'gas']
    }
  },
  methods: {
    imagePath (slug) {
      return require('@/assets/' + slug + '_icon.png')
    }
  }
}

</script>
