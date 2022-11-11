<script>
export default {
    name:'SiteHeader',
    data(){
        return{
            menu:[
                {
                    text:'Characters'
                },
                {
                    text:'Comics'
                },
                {
                    text:'Movies'
                },
                {
                    text:'Tv'
                },
                {
                    text:'Games'
                },
                {
                    text:'collectibles'
                },
                {
                    text:'videos'
                },
                {
                    text:'fans'
                },
                {
                    text:'news'
                },
                {
                    text:'shop'
                },
                

            ]
        }
    }
}

</script>

<template>

    <header id="site_header">
        <div class="container">
            <div class="col">
                <div class="logo">
                    <img src="/img/dc-logo.png" alt="">
                </div>
            </div>
            <!-- ./ logo -->
            <div class="col">
                <nav class="navbar">
                    <ul>
                        <li v-for="item in menu">
                            <a href="#">{{item.text}}</a>
                        </li>
                    </ul>
                </nav>
                <!-- /. navbar -->
            </div>
        </div>
    </header>

</template>

