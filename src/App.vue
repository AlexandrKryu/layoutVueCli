<template>
  <div id="app">
    <HomePage />

    <BlogPage />

    <BlogDetailsPage />

    <ProjectPage />
  </div>
</template>

<script>
import BlogDetailsPage from './components/BlogDetailsPage.vue';
import BlogPage from './components/BlogPage.vue';
import HomePage from './components/HomePage.vue';
import ProjectPage from './components/ProjectPage.vue';




export default {
  name: 'App',
  components: {
    HomePage,
    BlogPage,
    BlogDetailsPage,
    ProjectPage,
  }
}
</script>

<style lang="scss">
@import "./scss/vars.scss";

* {
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

.center {
  padding-left: calc(50% - $widthSite / 2);
  padding-right: calc(50% - $widthSite / 2);
}
</style>
