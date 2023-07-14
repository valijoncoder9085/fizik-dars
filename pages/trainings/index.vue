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
          to: '/trainings/1'
        },
        {
          icon: 'butun-olam.png',
          title: "Butun olam tortishish qonuni",
          to: '/trainings/2'
        },
        {
          icon: 'ogirlik-kuchi.png',
          title: "Jism og'irligi. Yuklama va vazinsizlik",
          to: '/trainings/3'
        },
        {
          icon: '',
          title: "Kinematikaning asosiy tushunchalari",
          to: '/trainings/4'
        },
        {
          icon: 'nyuton-qonun.png',
          title: "Nyuton qonunlari",
          to: '/trainings/5'
        },
        {
          icon: 'nyutonning-3.png',
          title: "Nyutonning 3-qonuni",
          to: '/trainings/6'
        },
        {
          icon: 'ogirlik-kuchi.png',
          title: "Og'irlik kuchi ta'sirida harakat, gorizontal otilgan jism",
          to: '/trainings/7'
        },
        {
          icon: 'tezlik-haqida.png',
          title: "Tezlik haqida tushuncha",
          to: '/trainings/8'
        },

      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
