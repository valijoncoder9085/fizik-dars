<template>
  <v-app dark>
    <v-app-bar
      fixed
      app
    >
      <v-spacer/>
      <v-toolbar-title>{{ title }}</v-toolbar-title>
      <v-spacer/>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt/>
      </v-container>
    </v-main>
    <v-footer
      :absolute="!fixed"
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'SidebarPages',
  data() {
    return {
      fixed: false,
      title: 'Fizika'
    }
  }
}
</script>
