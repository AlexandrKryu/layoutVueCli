<template>
    <section class="blog center">
        <h2 class="blog__title-left">Articles & News</h2>
        <ArticlesComponent :quantity="6"></ArticlesComponent>
        <div class="count__page">
            <div class="count__page-wrap">
                <a href="#" class="count__page-number">
                    <p class="count__page-number-text">01</p>
                </a>
                <a href="#" class="count__page-number">
                    <p class="count__page-number-text">02</p>
                </a>
                <a href="#" class="count__page-number">
                    <p class="count__page-number-text">03</p>
                </a>
                <a href="#">
                    <svg class="count__page-svg" xmlns="http://www.w3.org/2000/svg" width="53" height="52"
                        viewBox="0 0 53 52" fill="none">
                        <circle cx="26.5" cy="26" r="25.5" stroke="#CDA274" />
                        <path d="M23.5571 32L29.5 25.3143L23.5571 18.6286" stroke="#292F36" stroke-width="2"
                            stroke-linecap="round" stroke-linejoin="round" />
                    </svg>
                </a>
            </div>
        </div>
    </section>
</template>

<script>

import ArticlesComponent from '../CommonComponents/ArticlesComponent.vue';

export default {
    name: 'BlogPageBlogs',

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

<style lang="scss" scoped>
@import '../../scss/vars.scss';

.blog__title-left {
    text-align: left;
    margin-top: 150px;
    margin-bottom: 30px;
    color: #292f36;
    font-family: $familyTitle;
    font-size: 50px;
    font-style: normal;
    font-weight: $font-400;
    line-height: 125%;
    letter-spacing: 1px;
}

.count__page {
    margin-top: 51px;
    margin-bottom: 200px;
    display: flex;
    justify-content: center;

    &-wrap {
        display: flex;
        gap: 20px;
    }

    &-number {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: nowrap;
        border: 1px #cda274 solid;
        width: 52px;
        height: 52px;
        border-radius: 52px;

        &-text {
            color: #292f36;
            font-family: $familyText;
            font-size: 16px;
            font-style: normal;
            font-weight: $font-500;
            line-height: 150%;
            text-transform: capitalize;
        }

        &:hover {
            background: #f4f0ec;
            border: none;
            width: 54px;
            height: 54px;
        }
    }

    &-svg:hover {
        fill: #f4f0ec;

        & circle {
            stroke: none;
        }
    }
}</style>