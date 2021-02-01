<template>
  <v-app>
    <v-app-bar
      app
      color="dark"
      dark
    >

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <Dashboard/>
    </v-main>
  </v-app>
</template>

<script>
import Dashboard from './components/Dashboard';

export default {
  name: 'App',

  components: {
    Dashboard,
  },

  data: () => ({
    //
  }),
};
</script>
