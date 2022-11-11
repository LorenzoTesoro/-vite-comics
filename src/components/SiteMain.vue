<script>
import Banner from './Banner.vue';
import AppHero from './AppHero.vue';
import Comic from './Comic.vue'
import comics from '../assets/data/comics.js'

export default{
    name: 'SiteMain',
    components: {
        Banner,
        AppHero,
        Comic,
    },
    data (){
        return {
          comics : comics
        }   
    }
}

</script>

<template>
    <main id="site_main">
        <div class="content">
            <AppHero/>
            <!-- Jumbotron -->
            <div class="container">
                <Comic v-for="comic in comics"
                :img="comic.thumb"
                :title="comic.series"/>
            </div>
            <!-- /. main content  -->
        </div>
        <Banner/>
        <!-- main features -->
    </main>
</template>

<style>
</style>