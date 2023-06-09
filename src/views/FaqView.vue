<template>
    <Header></Header>
    <div class="contact mt-5">
      <div class="container">
        <h1>This is faq page</h1>
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
  