<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: 'TrainingsPage',
  data(){
    return{
      items: [
        {
          icon: 'bir-necha-kuchlar.png',
          title: "Bir necha kushlar ta'sirida harakat",
          to: '/traing'
        },
        {
          icon: 'butun-olam.png',
          title: "Butun olam tortishish qonuni",
          to: '/eight'
        },
        {
          icon: 'ogirlik-kuchi.png',
          title: "Jism og'irligi. Yuklama va vazinsizlik",
          to: '/eight'
        },
        {
          icon: 'butun-olam.png',
          title: "Kinematikaning asosiy tushunchalari",
          to: '/eight'
        },
        {
          icon: 'nyuton-qonun.png',
          title: "Nyuton qonunlari",
          to: '/eight'
        },
        {
          icon: 'nyutonning-3.png',
          title: "Nyutonning 3-qonuni",
          to: '/eight'
        },
        {
          icon: 'ogirlik-kuchi.png',
          title: "Og'irlik kuchi ta'sirida harakat, gorizontal otilgan jism",
          to: '/eight'
        },
        {
          icon: 'tezlik-haqida.png',
          title: "Tezlik haqida tushuncha",
          to: '/eight'
        },

      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
