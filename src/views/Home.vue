<template>
<div>
  <promo/>
  <div width="60px" style="background-color:black">
    <br>
    
    <h1 class="text-center display-1 white--text font-weight-black">All-New Interior</h1>
  <br>
  </div>
  <interior/>
  <specifications></specifications>
  <div width="60px" style="background-color:black">
    <br>  
  <br>
  <br>
  </div>
  
  <core-features/>
  <order-now/>
</div>
</template>

<script>
import CoreFeatures from '../components/CoreFeatures.vue'
import Interior from '../components/Interior.vue'
import OrderNow from '../components/OrderNow.vue'
import Promo from '../components/Promo.vue'
import Specifications from '../components/Specifications.vue'
export default {
  components: { Promo, Specifications, Interior, CoreFeatures, OrderNow },

}
</script>

<style>

</style>