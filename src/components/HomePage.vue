<template>
    <div>
        <HeaderComponent />
        <HomePageBaner />
        <HomePageProject />
        <HomePageCounter />
        <HomePageArticles />
        <FooterComponent />
    </div>
</template>

<script>
import FooterComponent from './CommonComponents/FooterComponent.vue';
import HeaderComponent from './CommonComponents/HeaderComponent.vue';
import HomePageArticles from './HomePage/HomePageArticles.vue';
import HomePageBaner from './HomePage/HomePageBaner.vue';
import HomePageCounter from './HomePage/HomePageCounter.vue';
import HomePageProject from './HomePage/HomePageProject.vue';

export default {
    name: "HomePage",
    data() {
        return {};
    },
    mounted() {
    },
    methods: {},
    components: { HeaderComponent, HomePageBaner, HomePageProject, HomePageCounter, HomePageArticles, FooterComponent }
};
</script>

<style lang="scss" scoped></style>