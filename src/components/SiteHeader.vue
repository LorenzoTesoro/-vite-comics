<script>
export default {
    name:'SiteHeader'
}

</script>

<template>

    <header id="site_header" class="debug">
        <div class="container">
            <div class="logo"></div>
            <nav class="navbar">
                <ul>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                    <li>Lorem.</li>
                </ul>
            </nav>
        </div>
    </header>

</template>

<style scoped>
header{
    height:300px;
    background-color: red;
}
.container{
    height:300px;
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
}
.debug .logo{
    width:30%;
    height:300px;
    background-color: blue;
}

.debug .navbar{
    background-color: green;
}
.debug .navbar ul{
    display: flex;
    justify-content: space-between;
    list-style: none;
}

</style>