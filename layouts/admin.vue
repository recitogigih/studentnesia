<template>

  <div>
    <div class="columns">
      <div class="column is-2" style="height:102vh">
        <Sidebar />
      </div>
      <div class="column is-10 mt-5">
        <div class="container is-fluid">
        <Nuxt />
        </div>
      </div>
    </div>
  </div>

</template>

<script>
  import Sidebar from '@/components/admin/sidebar.vue'

  export default {
    components: {
      Sidebar
    },
    data() {
      return {

      }
    },

  }

</script>
