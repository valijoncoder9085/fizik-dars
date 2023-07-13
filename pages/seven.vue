<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: 'SevenPage',
  data(){
    return{
      items: [
        {
          icon: 'hujjat.png',
          title: "Meyoriy hujjat",
          to: '/dts'
        },
        {
          icon: 'metodik.jpg',
          title: "O'quv metoddik taminot",
          to: '/metodic'
        },
        {
          icon: 'mash.jpg',
          title: "Mashg'ulot",
          to: '/training'
        },
        {
          icon: 'vid.jpg',
          title: "Video",
          to: '/video'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
