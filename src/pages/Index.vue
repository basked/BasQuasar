<template>
  <q-page class="flex">
    <!--<img alt="Quasar logo" src="~assets/quasar-logo-full.svg">-->
   <!--<test></test>-->
    <data-grid ></data-grid>
  </q-page>
</template>

<style>
</style>

<script>
import 'devextreme/dist/css/dx.common.css'
import 'devextreme/dist/css/dx.material.blue.light.css'
import DataGrid from '../components/DataGrid'

export default {
  name: 'PageIndex',
  components: {
    DataGrid
  }
}
</script>
