<script>
export default {
    name:'Comic',

    props:{
        img: String,
        title: String
    }
}
</script>

<template>

<div class="card col-2">
    <div class="card-img">
        <img :src="img" alt="">
    </div>
    <div class="card-title">
        {{title}}
    </div>
</div>

</template>