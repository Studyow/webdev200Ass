<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="12" lg="12">

      <!-- 1 Header-->
      <div>
        <!-- <Header /> -->
      </div>

      <!-- 2 Hero Section -->
      <div>
        <HeroSec />
      </div>

      <!-- 3 Product Categories or Featured Collections -->
      <div>
        <FeaCollection />
      </div>

      <!-- 4 Product Listings -->
      <div>
        <ProdList />
      </div>

      <!-- 5 Special Offers or Promotions -->
      <div>
        <Promotions />
      </div>

      <!-- 6 Testimonials or Customer Reviews -->
      <div>
        <CustReview />
      </div>

      <!-- 7 Featured Brands or Partners -->
      <div>
        <FeaBrands />
      </div>

      <!-- 8 Footer -->
      <div>
        <Footer />
      </div>

    </v-col>
  </v-row>
</template>

<script>
import Header from '../components/Landing/Header.vue'
import HeroSec from '../components/Landing/HeroSec.vue'
import FeaCollection from '../components/Landing/FeaCollection.vue'
import ProdList from '../components/Landing/ProdList.vue'
import Promotions from '../components/Landing/Promotions.vue'
import CustReview from '../components/Landing/CustReview.vue'
import FeaBrands from '../components/Landing/FeaBrands.vue'
import Footer from '../components/Landing/Footer.vue'

export default {
  components: { 
    Header, 
    HeroSec,
    FeaCollection,
    ProdList,
    Promotions,
    CustReview,
    FeaBrands,
    Footer
  },
  name: 'IndexPage',
}
</script>

