<template>
  <div class="home">
    <h1>Homepage</h1>
    
    <v-btn class="pink white--text">Click me</v-btn>
    <v-btn depressed color="pink">Click me</v-btn>
    <v-btn flat color="pink">Click me</v-btn>

    <v-btn depressed class="pink white--text">
      <v-icon left>email</v-icon>
      <span>EMAIL ME</span>
    </v-btn>
    <v-btn small depressed class="pink white--text">
      <v-icon small left>email</v-icon>
      <span>EMAIL ME</span>
    </v-btn>
    <v-btn large depressed class="pink white--text">
      <span>EMAIL ME</span>
      <v-icon large right>email</v-icon>
    </v-btn>
    <v-btn fab small dark depressed color="purple">
      <v-icon>favorite</v-icon>
    </v-btn>
  </div>
</template>
