<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: 'VideoIdPage',
  data(){
    return{
      items: [
        {
          icon: 'video-1.png',
          title: "Aylanma harakat",
          to: '/dts'
        },
        {
          icon: 'video-2.png',
          title: "Dinamika qonunlari",
          to: '/eight'
        },
        {
          icon: 'video-3.png',
          title: "Elastiklik kuchi prujinaning bikirligini aniqlash",
          to: '/training'
        },
        {
          icon: 'video-4.png',
          title: "Impulsning saqlanish qonuni Reaktiv harakat",
          to: '/video'
        },
        {
          icon: 'video-5.png',
          title: "Jismlarning erkin tushishi",
          to: '/video'
        },
        {
          icon: 'video-6.png',
          title: "Mexanik to'lqinlar va tovush to'lqinlari",
          to: '/video'
        },
        {
          icon: 'video-7.png',
          title: "Suyuqlik va gazlarning xossalaridan foydalanish",
          to: '/video'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
