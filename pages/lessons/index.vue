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
          to: '/lessons/1'
        },
        {
          icon: 'fizikaDastur.jpg',
          title: "7-sinf FIZIKA dastur",
          to: '/lessons/2'
        },
        {
          icon: 'fizik-kecha.png',
          title: "Fizika kech",
          to: '/lessons/3'
        },
        {
          icon: 'ishqalanish.png',
          title: "Turmushda va texnikada ishqalanish",
          to: '/lessons/4'
        },
        {
          icon: 'suroq.png',
          title: "Fizika masalalar",
          to: '/lessons/5'
        },
        {
          icon: 'zaryad.png',
          title: "Zaryadlangan sharning elektr maydoni",
          to: '/lessons/6'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
