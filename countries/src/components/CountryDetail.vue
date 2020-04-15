<template lang="html">
<div v-if="selectedCountry">
  <h3>{{selectedCountry.name}}</h3>
  <p>alpha3Code: {{selectedCountry.alpha3Code}}</p>
</div>
</template>

<script>
export default {
  name: 'selectedCountry-detail',
  props: ['selectedCountry']
}
</script>

<style lang="css" scoped>
</style>
