<template>
  <div id="app">
    <Header/>
    <main>
      <route-view/>
      <LoginModal/>
      <RegistrationModal/>
      <CheckoutModal/>
    </main>
    <Footer/>
  </div>
</template>

<script>
import LoginModal from "@/components/modal/Login";
import Header from "@/components/header/Header";
import Footer from "@/components/footer/Footer";
import RegistrationModal from "@/components/modal/Registration";
import CheckoutModal from "@/components/modal/Checkout";

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    LoginModal,
    RegistrationModal,
    CheckoutModal
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
