<template>
  <div>
    <TheHeader/>
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
  import TheHeader from '@/components/navbarComp'
  import Footer from '@/components/footerComp'
 
  export default {
    components: {
      TheHeader,
      Footer,
    },
  }
</script>
