<template>
  <MainComp/>
  <ServicesBlock/>
  <PartnershipsBlock/>
  <PositionsBlock/>
  <PurposeBlock/>
</template>

<script>
import MainComp from './components/MainComp.vue'
import ServicesBlock from './components/ServicesBlock.vue'
import PartnershipsBlock from './components/PartnershipsBlock.vue'
import PositionsBlock from './components/PositionsBlock.vue'
import PurposeBlock from './components/PurposeBlock.vue'

export default {
  name: 'App',
  components: {
    MainComp,
    ServicesBlock,
    PartnershipsBlock,
    PositionsBlock,
    PurposeBlock
  }
}
</script>

<style>
html, body {
  overflow-x: hidden;
  margin: 0;
  padding: 0;
}
</style>
