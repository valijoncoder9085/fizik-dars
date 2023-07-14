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
          to: '/video-id/1'
        },
        {
          icon: 'video-2.png',
          title: "Dinamika qonunlari",
          to: '/video-id/2'
        },
        {
          icon: 'video-3.png',
          title: "Elastiklik kuchi prujinaning bikirligini aniqlash",
          to: '/video-id/3'
        },
        {
          icon: 'video-4.png',
          title: "Impulsning saqlanish qonuni Reaktiv harakat",
          to: '/video-id/4'
        },
        {
          icon: 'video-5.png',
          title: "Jismlarning erkin tushishi",
          to: '/video-id/5'
        },
        {
          icon: 'video-6.png',
          title: "Mexanik to'lqinlar va tovush to'lqinlari",
          to: '/video-id/6'
        },
        {
          icon: 'video-7.png',
          title: "Suyuqlik va gazlarning xossalaridan foydalanish",
          to: '/video-id/7'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
