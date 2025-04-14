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
import MainComp from './components/blocks/MainComp.vue'
import ServicesBlock from './components/blocks/ServicesBlock.vue'
import PartnershipsBlock from './components/blocks/PartnershipsBlock.vue'
import PositionsBlock from './components/blocks/PositionsBlock.vue'
import PurposeBlock from './components/blocks/PurposeBlock.vue'
import DevelopmentBlock from './components/blocks/DevelopmentBlock.vue'
import FooterBlock from './components/blocks/FooterBlock.vue'

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
