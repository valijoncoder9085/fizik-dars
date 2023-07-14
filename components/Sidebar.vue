<template>
  <v-app dark>
    <v-app-bar
      app
      elevation="0"
      class="px-2"
      style="background-color: inherit"
    >
      <v-spacer/>
      <v-toolbar-title>
      </v-toolbar-title>
      {{ title }}

      <v-spacer/>
    </v-app-bar>
    <v-main :style="{backgroundImage: `url(${background})`}" style="background-repeat: no-repeat; background-attachment: fixed; background-position: center; background-size: cover">
      <v-container>
        <Nuxt/>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import background from '../static/img_background.jpg'
export default {
  name: 'SidebarPages',
  data() {
    return {
      background,
      fixed: false,
      img: require('../static/img_background.jpg'),
      title: 'Fizika fanini rivojlantirishga qaratilgan elektron platforma prototipi'
    }
  },
}
</script>
<style lang="scss" scoped>
.toolbar-text{
  font-family: "Calibri Light";
}
</style>
