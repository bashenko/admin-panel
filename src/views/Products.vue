<template>
  <div>
    <CRow>
      <CCol sm="12">
        <CInput placeholder="Search">
        <template #append-content><CIcon name="cil-magnifying-glass"/></template>
      </CInput>
      </CCol>
    </CRow>
    <CRow>
      <standardCard></standardCard>
      <standardCard></standardCard>
      <standardCard></standardCard>
      <standardCard></standardCard>
      <standardCard></standardCard>
      <standardCard></standardCard>
    </CRow>
  </div>
</template>

<script>
import standardCard from '../components/standardCard'

export default {
  name: 'Products',
  components: {
    standardCard
  }
}
</script>

<style>

</style>