<script>

export default{
    name: 'BannerItem',

    data(){
        return{
            cards:[
                {
                    img: '/img/buy-comics-digital-comics.png',
                    title: 'Digital comics'
                },
                {
                    img: '/img/buy-comics-merchandise.png',
                    title: 'dc merchandise'
                },
                {
                    img: '/img/buy-comics-subscriptions.png',
                    title: 'Subscriptions'
                },
                {
                    img:'/img/buy-comics-shop-locator.png',
                    title:'comic shop locator'
                },
                {
                    img:'/img/buy-dc-power-visa.svg',
                    title:'dc power visa'
                }
            ]
        }
    }
}

</script>

<template>
<div class="features">
    <div class="container">
        <div class="card" v-for="card in cards">
            <div>
                <img :src="`${card.img}`" alt="">
            </div>
            <span>            
                {{card.title}}
            </span>
        </div>          
    </div>
</div>
</template>

