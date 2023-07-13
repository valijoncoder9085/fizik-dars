<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: "MetodicPage",
  data(){
    return{
      items: [
        {
          icon: 'darslar.jpg',
          title: "Darslar",
          to: '/lessons'
        },
        {
          icon: 'qullanma.png',
          title: "O'quv qo'llanma",
          to: '/metodic'
        },
        {
          icon: 'uslubiy.png',
          title: "Uslubiy ko'rsatmalar",
          to: '/nine'
        },
        {
          icon: 'tarqatma.png',
          title: "Tarqatma",
          to: '/ten'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
