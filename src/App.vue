<template>
  <v-app>
    <v-main>
      <TableResult/>
    </v-main>
  </v-app>
</template>

<script>
import TableResult from './components/TableResult';

export default {
  name: 'App',
  components: {
    TableResult,
  }
};
</script>
