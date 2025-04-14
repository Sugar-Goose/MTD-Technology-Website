<template>
  <MainComp/>
  <ServicesBlock/>
  <PositionsBlock/>
  <DevelopmentBlock/>
  <PurposeBlock/>
  <PartnershipsBlock/>
  <FooterBlock/>
</template>

<script>
import MainComp from './components/MainComp.vue'
import ServicesBlock from './components/ServicesBlock.vue'
import PartnershipsBlock from './components/PartnershipsBlock.vue'
import PositionsBlock from './components/PositionsBlock.vue'
import PurposeBlock from './components/PurposeBlock.vue'
import DevelopmentBlock from './components/DevelopmentBlock.vue'
import FooterBlock from './components/FooterBlock.vue'

export default {
  name: 'App',
  components: {
    MainComp,
    ServicesBlock,
    PartnershipsBlock,
    PositionsBlock,
    PurposeBlock,
    DevelopmentBlock,
    FooterBlock
  }
}
</script>

<style>
html, body {
  overflow-x: hidden;
  margin: 0;
  padding: 0;
}

body {
  background-color: #000;
}
</style>
