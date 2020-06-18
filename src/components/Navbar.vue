<template>
  <nav>
    <v-app-bar flat app>
      <v-app-bar-nav-icon class="grey--text" @click="drawer=!drawer"></v-app-bar-nav-icon>
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-light">Todo</span>
        <span>Ninja</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text color="grey">
        <span>Sign Out</span>
        <v-icon right>mdi-exit-to-app</v-icon>
      </v-btn>
    </v-app-bar>
    <!-- app is needed here , so that nav-drawer will come on top of the toolbar also.If not given , 
    then toolbar will be on top of nav drawer and a part of nav drawer will be overlapped by toolbar-->
    <v-navigation-drawer app class="primary" v-model="drawer">
      <p>test</p>
    </v-navigation-drawer>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      drawer: false
    };
  }
};
</script>