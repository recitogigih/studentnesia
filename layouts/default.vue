<template>
  <div>
    <TheHeader/>
    <Nuxt />
  </div>
</template>

<script>
  import TheHeader from '@/components/navbarComp'
 
  export default {
    components: {
      TheHeader,
    },
  }
</script>
