<template>
  <div class="home">
    <Header></Header>
      <div class="container mt-5">
        <div class="row">
          <div class="col-lg-8">
            <div class="home-main">
              <h1>Get Smarter about your <br> career</h1>
              <p>Get the <strong>5-minute newsletter</strong> keeping about smart career</p>
              <form action="#">
                <div class="input-group flex-nowrap">
                  <span class="input-group-text span" id="addon-wrapping"><i class="fa-regular fa-envelope"></i></span>
                  <input type="email" class="form-control input" placeholder="Your E-mail Address">
                  <button class="btn join" type="button" id="button-addon2">Join Free</button>
                </div>
              </form>
              <p class="mt-4 lh-lg">We're committed to your privacy. DashCareer uses the information you provide to contact you about our relevant content and services. You may unsubscribe from these communications at any time. For more information, check out our Privacy Policy.</p>
            </div>
          </div>
        </div>
      </div>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    Footer
  }
}
</script>

<style>

</style>
