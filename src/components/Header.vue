<template>
    <div class="header">
        <nav class="navbar navbar-expand-lg">
            <div class="container">
                <router-link class="navbar-brand" to="/"><img src="../assets/img/logo.png" alt="logo"></router-link>
                <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
                <div class="offcanvas-header">
                    <router-link class="navbar-brand" to="/"><img src="../assets/img/logo.png" alt="logo"></router-link>
                    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <div class="offcanvas-body">
                    <ul class="navbar-nav justify-content-end flex-grow-1 mt-2">
                        <li class="nav-item" v-for="navLink in navLinks" :key="navLink.id">
                            <router-link class="nav-link" :to="navLink.navURL">{{navLink.linkText}}</router-link>
                        </li>
                        <button class="btn border-none" type="submit">Join Now</button>
                    </ul>
                </div>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "Header",
    data(){
        return{
            navLinks: [
                {id: 1, linkText: 'Home', navURL:'/'},
                {id: 2, linkText: 'Privacy Policy', navURL:'/privacy'},
                {id: 3, linkText: 'Terms Condition', navURL:'/terms'},
                {id: 4, linkText: 'About Us', navURL:'/about'},
                {id: 5, linkText: 'Contact Us', navURL:'/contact'},
                {id: 6, linkText: 'Advertise', navURL:'/advertise'},
            ],
        }
    }
}
</script>

<style scoped>


</style>