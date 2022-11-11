<script>
import icons from '../assets/data/social.js'

export default{
    name: 'SiteFooter',
    data(){
        return{
            icons: icons
        }
    }
}

</script>


<template>
    <footer id="site_footer">
        <div class="footer_top">
            <div class="container">
                <div class="col">
                    <h3>Dc comics</h3>
                    <ul>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Movies</a>
                        </li>
                        <li>
                            <a href="#">TV</a>
                        </li>
                        <li>
                            <a href="#">Games</a>
                        </li>
                        <li>
                            <a href="#">Videos</a>
                        </li>
                        <li>
                            <a href="#">News</a>
                        </li>
                    </ul>
                    <div class="shop">
                        <h3>Shop</h3>
                        <ul>
                            <li>
                                <a href="#">Shop DC</a>
                            </li>
                            <li>
                                <a href="#">Shop DC Collectibles</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col">
                    <h3>dc</h3>
                    <ul>
                        <li>
                            <a href="#">Terms of use</a>
                        </li>
                        <li>
                            <a href="#">Privacy Policy(New)</a>
                        </li>
                        <li>
                            <a href="#">Ad Choices</a>
                        </li>
                        <li>
                            <a href="#">Advertising</a>
                        </li>
                        <li>
                            <a href="#">Jobs</a>
                        </li>
                        <li>
                            <a href="#">Subscriptions</a>
                        </li>
                        <li>
                            <a href="#">Talent Workshops</a>
                        </li>
                        <li>
                            <a href="#">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="#">Ratings</a>
                        </li>
                        <li>
                            <a href="#">Shop Help</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <h3>Sites</h3>
                    <ul>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="#">DC Kids</a>
                        </li>
                        <li>
                            <a href="#">DC Universe</a>
                        </li>
                        <li>
                            <a href="#">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <!-- footer_top -->
        <div class="footer_bottom">
            <div class="container">
                <div class="col">
                    <div class="btn">
                        <a>SIGN-UP now!</a>
                    </div>
                </div>
                <div class="social">
                    <div class="follow">Follow us</div>
                    <img :src="icon.path" alt="" v-for="icon in icons">
                </div>                                
            </div>
        </div>
        <!-- /. footer_top -->
    </footer>
</template>

<style>

</style>