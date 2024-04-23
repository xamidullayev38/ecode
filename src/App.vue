<template>
  <div class="container">
    <Navbar />
    <Header />
    <Social />
    <Future />
    <Connect />
    <Optimize />
    <Info />
    <Enode />
    <Case />
    <Final />
    <Footer />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Header from '@/components/Header.vue'
import Social from '@/components/Social.vue'
import Future from '@/components/Future.vue'
import Connect from '@/components/Connect.vue'
import Optimize from '@/components/Optimize.vue'
import Info from '@/components/Info.vue'
import Enode from '@/components/Enode.vue'
import Case from '@/components/Case.vue'
import Final from '@/components/Final.vue'
import Footer from '@/components/Footer.vue'

export default {
    components: {
        Navbar,
        Header,
        Social,
        Future,
        Connect,
        Optimize,
        Info,
        Enode,
        Case,
        Final,
        Footer,
    }
}
</script>

<style>

</style>