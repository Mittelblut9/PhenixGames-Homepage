<template>
    <homepageNav />
    <mainbody />
    <!-- <currentstate /> -->
    <roleplaybody />
    <!-- <gangwarsbody /> -->
    <aboutbody />
    <footerbody />
</template>

<script>
import homepageNav from '../../components/homepage/nav.vue';
import mainbody from '../../components/homepage/main-body.vue';
import roleplaybody from '../../components/homepage/roleplay-body.vue';
import gangwarsbody from '../../components/homepage/gangwars-body.vue';
import aboutbody from '../../components/homepage/about-body.vue';
import footerbody from '../../components/homepage/footer-body.vue';
import currentstate from '../../components/homepage/current_state.vue';

export default {
    components: {
        homepageNav,
        mainbody,
        currentstate,
        roleplaybody,
        gangwarsbody,
        aboutbody,
        footerbody,
    },
};
</script>

<style scoped>
@import url('../../assets/css/homepage/main.css');
</style>
