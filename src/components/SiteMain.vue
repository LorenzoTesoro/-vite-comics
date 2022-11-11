<script>
import BannerItem from './BannerItem.vue';
import AppHero from './AppHero.vue';
import ComicItem from './ComicItem.vue'
import comics from '../assets/data/comics.js'

export default{
    name: 'SiteMain',
    components: {
        BannerItem,
        AppHero,
        ComicItem,
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
                <ComicItem v-for="comic in comics"
                :img="comic.thumb"
                :title="comic.series"/>
            </div>
            <!-- /. main content  -->
        </div>
        <BannerItem/>
        <!-- main features -->
    </main>
</template>

<style>
</style>