<template>
   <main class="container-fluid">
    <Navbar></Navbar>
    <Footer></Footer>

    <router-view/>
  </main>

</template>
<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import spinner from './components/spinner.vue';
export default{
  components:{
    Navbar,
    Footer,
    spinner
  }
}

</script>

<style src="@/assets/css/style.css">

</style>
