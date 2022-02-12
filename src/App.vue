<template>
<the-header title="RememberMe"></the-header>
  <the-resources></the-resources>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
// import LearningResource from './components/learning-resources/LearningResource.vue';
// import StoredResourses from './components/learning-resources/StoredResources.vue';
import TheResources from './components/learning-resources/TheResources.vue';

export default {
  components: {
    // LearningResource,
    // StoredResourses,
    TheHeader,
    TheResources
  },
  methods: {
    //   deleteResource(id){
    //       this.storedResourses = this.storedResourses.filter(res => res.id != id);
    //   }

  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>