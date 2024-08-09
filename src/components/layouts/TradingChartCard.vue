<template>
  <div class="card mb-2">
    <div class="card-body p-0">
      <trading-vue
        :data="chart"
        :width="this.width"
        :height="this.height"
      >
      </trading-vue>
    </div>
  </div>
</template>

<script>
import TradingVue from "../../TradingVue.vue";
import Data from "../../../data/data.json";
import DataCube from "../../helpers/datacube.js";

export default {
    name: 'app',
    components: {
        TradingVue
    },
    methods: {
        onResize() {
          const cardBody = document.querySelector('.card-body');
          if (cardBody) {
              this.width = cardBody.clientWidth;
              this.height = cardBody.innerHeight; 
          }
        }
    },
    mounted() {
        this.onResize();
        window.addEventListener('resize', this.onResize)
        window.dc = this.chart
    },
    beforeDestroy() {
        window.removeEventListener('resize', this.onResize)
    },
    data() {
        return {
            chart: new DataCube(Data),
            width: window.innerWidth,
            height: window.innerHeight,
            colors: {
                colorBack: '#fff',
                colorGrid: '#eee',
                colorText: '#333',
            }
        };
    }
};
</script>

<style>
html,
body {
    background-color: #000;
    margin: 0;
    padding: 0;
    overflow: hidden;
}
</style>