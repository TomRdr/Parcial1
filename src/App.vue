<template>
  <v-app id="fundo">
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<style>
#fundo {
  background-image: url("http://www.hdfondos.eu/pictures/2012/1008/1/orig_575193.jpg");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>