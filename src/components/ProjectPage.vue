<template>
    <div>
        <HeaderComponent></HeaderComponent> />
        <ProjectPageBaner></ProjectPageBaner> />
        <ProjectPageContent></ProjectPageContent> />
        <FooterComponent></FooterComponent> />
    </div>
</template>

<script>
import FooterComponent from './CommonComponents/FooterComponent.vue';
import HeaderComponent from './CommonComponents/HeaderComponent.vue';
import ProjectPageBaner from './ProjectPage/ProjectPageBaner.vue'
import ProjectPageContent from './ProjectPage/ProjectPageContent.vue'

export default {
    name: 'ProjectPage',
    data() {
        return {};
    },
    mounted() {
    },
    methods: {},
    components: { HeaderComponent, ProjectPageBaner, ProjectPageContent, FooterComponent }
};
</script>

<style lang="scss" scoped></style>