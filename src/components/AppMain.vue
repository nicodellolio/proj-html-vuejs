<script>
import AppJumbotron from './AppJumbotron.vue';
import FeaturedOnlineCourses from './FeaturedOnlineCourses.vue';
import Companionship from './Companionship.vue';
import TopLearners from './TopLearners.vue';
import PreFooterSection from './PreFooterSection.vue';

export default {
    name: 'AppMain',
    components: {
        AppJumbotron,
        FeaturedOnlineCourses,
        Companionship,
        TopLearners,
        PreFooterSection
    },

    data() {
        return {
        }
    }
}
</script>

<template>
    <div class="main">

        <AppJumbotron />

        <FeaturedOnlineCourses />

        <Companionship />

        <TopLearners />

        <PreFooterSection />

    </div>
</template>

<style lang="css">
</style>
