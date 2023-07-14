<template>
  <v-app dark>
    <v-app-bar
      app
      elevation="0"
      class="px-2"
      style="background-color: inherit; text-align: center; font-family: 'Playfair Display', serif;font-size: 32px;"
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
      title: 'Fizika'
    }
  },
}
</script>
<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
.toolbar-text{
  font-family: "Calibri Light";
}

</style>
