<script>
import MainFeatures from './MainFeatures.vue';

export default{
    name: 'SiteMain',
    components: {
        MainFeatures
    }
}

</script>

<template>
    <main id="site_main">
        <div class="content">
            <div class="container">
                Content goes here
            </div>
            <!-- /. main content  -->
        </div>
        <MainFeatures/>
        <!-- main features -->
    </main>
</template>

<style>
</style>