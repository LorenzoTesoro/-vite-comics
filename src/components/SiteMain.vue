<script>
export default{
    name: 'SiteMain'
}
</script>

<template>
    <main id="site_main" class="debug">
        <div class="content">
            <div class="container">
                Lorem, ipsum.
            </div>
        </div>
        <div class="features">
            <div class="container">
                Lorem, ipsum dolor.
            </div>
        </div>
    </main>
</template>

<style scoped>
main {
    height: 600px;
    background-color: lightblue;
}
.debug .content, .debug .features{
    height:50%;
}
.debug .content{
    background-color: lightgrey;
}
.debug .features{
    background-color: blueviolet;
}
</style>