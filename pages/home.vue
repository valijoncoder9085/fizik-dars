<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: "HomePage",
  data(){
    return{
      items: [
        {
          icon: '7.png',
          title: "7-sinf",
          to: '/seven'
        },
        {
          icon: '8.jpg',
          title: "8-sinf",
          to: '/home'
        },
        {
          icon: '9.png',
          title: "9-sinf",
          to: '/home'
        },
        {
          icon: '10.png',
          title: "10-sinf",
          to: '/home'
        },
        {
          icon: '11.png',
          title: "11-sinf",
          to: '/home'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
