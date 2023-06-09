<template>
    <Header></Header>
    <div class="contact mt-5">
      <div class="container">
        <div class="row">
          <div class="col-xl-7">
            <h1>Contact Us</h1>
            <p>If you want to contact us: you can send an email to <a href="mailto:contact.deshcareer@gmail.com">contact.deshcareer@gmail.com</a><br>If you want to meet with us, you can come to our office based on an appointment. <br>Our Office address: <br>House: 13/3, <br> Road: 2, <br>Shyamoly, Dhaka-1207 <br>+8801880811047</p>
          </div>
        </div>
      </div>
    </div>
    <Footer></Footer>
  </template>
  
  <script>
  // @ is an alias to /src
  import Header from '@/components/Header.vue'
  import Footer from '@/components/Footer.vue'

  export default{
    name:'About',
    components:{
      Header,
      Footer
    }
  }
  </script>

<style scoped>

</style>
  