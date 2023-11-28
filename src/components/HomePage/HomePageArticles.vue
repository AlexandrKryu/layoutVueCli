<template>
    <section class="blog center">
        <h2 class="blog__title">Articles & News</h2>
        <p class="blog__text">It is a long established fact that a reader will be distracted by the of readable content of
            a page when lookings at its layouts the points of using.</p>
        <ArticlesComponent :quantity="3"></ArticlesComponent>
    </section>
</template>

<script>
import ArticlesComponent from '../CommonComponents/ArticlesComponent.vue'

export default {
    name: 'HomePageArticles',

    components: {
        ArticlesComponent
    },

    data() {
        return {

        };
    },

    mounted() {

    },

    methods: {

    },
};
</script>

<style lang="scss" scoped></style>