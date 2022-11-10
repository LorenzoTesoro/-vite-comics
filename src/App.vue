<script>
import SiteHeader from './components/SiteHeader.vue';
import SiteMain from './components/SiteMain.vue';
import MainFeatures from './components/MainFeatures.vue';
import SiteFooter from './components/SiteFooter.vue';


export default {
    name: "App",
    components: { 
        SiteHeader,
        SiteMain,
        SiteFooter,
        MainFeatures
    }
}

</script>

<template>
    <SiteHeader/>
    <!-- site_header -->
    <SiteMain/>
    <!-- site_main -->
    <SiteFooter/>
    <!-- site_footer -->
</template>

<style lang="scss"></style>