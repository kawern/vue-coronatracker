
<template>
  <Header />
  <div class="p-6">
    <router-view />
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  components: {
    Header,
    }
  }
</script>