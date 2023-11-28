<template>
    <div>
        <HeaderComponent />
        <BlogDetailsPageBaner />
        <BlogDetailsPageArticle />
        <FooterComponent />
    </div>
</template>

<script>
import BlogDetailsPageArticle from './BlogDetailsPage/BlogDetailsPageArticle.vue';
import BlogDetailsPageBaner from './BlogDetailsPage/BlogDetailsPageBaner.vue';
import FooterComponent from './CommonComponents/FooterComponent.vue';
import HeaderComponent from './CommonComponents/HeaderComponent.vue';

export default {
    name: "BlogDetailsPage",
    data() {
        return {};
    },
    mounted() {
    },
    methods: {},
    components: { HeaderComponent, BlogDetailsPageBaner, BlogDetailsPageArticle, FooterComponent }
};
</script>

<style lang="scss" scoped></style>