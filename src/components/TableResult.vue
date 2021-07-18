<template>
  <v-container>
    <v-row class="text-center">
      <Footer/>
    </v-row>
  </v-container>
</template>

<script>
  import Footer from './Footer.vue';

  export default {
    name: 'TableResult',
    components: {
      Footer,
    },

    data: () => ({
    }),
  }
</script>
