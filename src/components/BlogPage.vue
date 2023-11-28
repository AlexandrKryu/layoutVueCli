<template>
    <div>
        <HeaderComponent />
        <BlogPageBaner />
        <BlogPageBlogs />
        <FooterComponent />
    </div>
</template>

<script>
import BlogPageBaner from './BlogPage/BlogPageBaner.vue';
import BlogPageBlogs from './BlogPage/BlogPageBlogs.vue';
import FooterComponent from './CommonComponents/FooterComponent.vue';
import HeaderComponent from './CommonComponents/HeaderComponent.vue';

export default {
    name: "BlogPage",
    data() {
        return {};
    },
    mounted() {
    },
    methods: {},
    components: { HeaderComponent, BlogPageBaner, BlogPageBlogs, FooterComponent }
};
</script>

<style lang="scss" scoped></style>