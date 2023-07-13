<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: "LessonsPage",
  data() {
    return {
      items: [
        {
          icon: 'fizika-7.jpg',
          title: "Fizika 7-sinf",
          to: '/lessons'
        },
        {
          icon: 'fizikaDastur.jpg',
          title: "7-sinf FIZIKA dastur",
          to: '/lessons'
        },
        {
          icon: 'fizik-kecha.png',
          title: "Fizika kech",
          to: '/lessons'
        },
        {
          icon: 'ishqalanish.png',
          title: "Turmushda va texnikada ishqalanish",
          to: '/lessons'
        },
        {
          icon: 'suroq.png',
          title: "Fizika masalalar",
          to: '/lessons'
        },
        {
          icon: 'zaryad.png',
          title: "Zaryadlangan sharning elektr maydoni",
          to: '/lessons'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
