<template>
  <Header />
  <div class="container">
    <Balance />
  </div>
</template>

<script lang="ts">
import Header from './components/Header.vue'
import Balance from './components/Balance.vue'

export default {
  components: {
    Header,
    Balance,
  },
}
</script>
