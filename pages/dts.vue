<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: "DTSpage",
  data() {
    return {
      items: [
        {
          icon: 'dts.png',
          title: "DTS",
          to: '/dtsFiz'
        },
        {
          icon: 'qaror.png',
          title: "Qaror",
          to: '/decision'
        },
        {
          icon: 'farmon.jpg',
          title: "Farmon",
          to: '/decree'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
