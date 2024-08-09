<template>
  <div class="container-fluid p-4">
    <Header />
    <div class="row my-2">
      <div class="col-lg-9 grid-margin stretch-card">
        <TradingChartCard />
        <Footer />
      </div>
      <SideBar />
    </div>
  </div>
</template>

<script>
import Header from './components/layouts/Header.vue'
import TradingChartCard from './components/layouts/TradingChartCard.vue'
import Footer from './components/layouts/Footer.vue'
import SideBar from './components/layouts/SideBar.vue'

export default {
  name: "app",
  components: {
    TradingChartCard,
    Header, 
    Footer,
    SideBar
  },
};
</script>
