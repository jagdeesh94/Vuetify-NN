<template>
  <div class="home">
    <h1>Home Page</h1>
    <v-btn color="pink white--text">Click Me</v-btn>
    <!--To remove the shadow from the button, use depressed prop-->
    <v-btn depressed color="yellow purple--text">Press</v-btn>
    <!--To show the bg of button as transparent, use text prop-->
    <v-btn text color="yellow pink--text">Click Me</v-btn>
    <!--To show the bg of button as rounded, use rounded prop-->
    <v-btn rounded color="pink yellow--text">Click Me</v-btn>

    <!--refer this for buttons https://vuetifyjs.com/en/components/buttons/#buttons-->

    <!--https://cdn.materialdesignicons.com/1.1.34/-->
    <v-btn rounded color="yellow purple--text">
      <v-icon>mdi-mail</v-icon>
    </v-btn>
    <!--https://fontawesome.com/icons/accessible-icon?style=brands-->
    <v-btn rounded color="yellow purple--text">
      <v-icon>fa-address-book</v-icon>
    </v-btn>
    <!--check https://v15.vuetifyjs.com/en/f<ramework/typography-->

    <v-btn depressed class="pink white--text">
      <v-icon>mdi-mail</v-icon>
      <span>Email Me</span>
    </v-btn>

    <v-btn depressed small class="pink white--text">
      <v-icon left small>mdi-mail</v-icon>
      <span>Email Me</span>
    </v-btn>

    <v-btn depressed large color="pink white--text">
      <span>Email Me</span>
      <v-icon right large>mdi-mail</v-icon>
    </v-btn>

    <v-btn depressed small dark color="pink white--text">
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn fab depressed small dark color="pink white--text">
      <v-icon>mdi-heart</v-icon>
    </v-btn>
  </div>
</template>

<script>
export default {};
</script>
