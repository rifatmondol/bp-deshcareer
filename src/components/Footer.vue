<template>
    <div class="footer mt-5">
        <div class="container">
            <div class="social text-center mt-2">
                <span><a href="#"><i class="fa-brands fa-facebook"></i></a></span>
                <span><a href="#"><i class="fa-brands fa-youtube"></i></a></span>
                <span><a href="#"><i class="fa-brands fa-linkedin-in"></i></a></span>
            </div>
            <div class="footer-main">
                <div class="row mt-3 mt-lg-1">
                    <div class="col-sm-12 col-lg-4">
                        <div class="footer-item p-2">
                            <router-link to="/"><img src="../assets/img/logo.png" alt="logo"></router-link>
                            <p class="mt-2">Desh Career is Career based newsletter in Bengali language. This newsletter has published weekly. This is published in every Saturday at 12.00 PM. </p>
                        </div>
                    </div>
                    <div class="col-sm-6 col-lg-4">
                        <div class="footer-item p-2 text-center">
                            <h4>Privacy And Terms</h4>
                            <ul class="navbar-nav">
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/privacy">Privacy Policy</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/terms">Terms Condition</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/faq">FAQ</router-link>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-sm-6 col-lg-4">
                        <div class="footer-item p-2 text-lg-end">
                            <h4>Support</h4>
                            <ul class="navbar-nav">
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/">Affiliate Link</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/contact">Contact Us</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/advertise">Advertise with us</router-link>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <hr class="hr-line">
        <div class="container">
            <div class="footer-bottom">
                <div class="row">
                    <div class="col-md-6">
                        <div class="footer-item text-md-start">
                            <p>&copy; 2023 Newsletter E-mail Service: All Copy right reserved</p>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="footer-item text-md-end">
                            <router-link class="nav-link" to="/">Terms</router-link>
                            <router-link class="nav-link" to="/">Cookie Policy</router-link>
                            <router-link class="nav-link" to="/">Terms</router-link>
                            <router-link class="nav-link" to="/">Privacy</router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    name:'Footer',
}
</script>

<style>

</style>