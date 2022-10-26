<template>
  <div>
    <b-container class="bv-example-row">
      <Header />
      <Breadcrumb />

      <b-row>
        <b-col cols="12">
          <img src="~/assets/banner-acc.png" style="width: 100%;" />
        </b-col>
      </b-row>

      <b-row>
        <b-col lg="3" md="4" sm="12">col-4</b-col>
        <b-col lg="9" md="8" sm="12">
          <h3>Akun Anda</h3>
          <Tab />
        </b-col>
      </b-row>

      <hr>

      <b-row>
        <b-col lg="6" md="6" sm="12">
          <LastTransaction />
        </b-col>
        <b-col lg="6" md="6" sm="12">
          <NewsUpdate />
        </b-col>
      </b-row>
    </b-container>
    <br>
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
