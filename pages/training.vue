<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: 'TrainingPage',
  data(){
    return{
      items: [
        {
          icon: 'ishlanma.png',
          title: "Ma'ruza uchun dars ishlanma",
          to: '/trainings'
        },
        {
          icon: 'labar.png',
          title: "Labaratoriya",
          to: '/eight'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
