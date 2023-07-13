<template>
  <div>
    <Card :items="items"/>
  </div>
</template>

<script>
export default {
  name: 'VideoPage',
  data(){
    return{
      items: [
        {
          icon: 'video.png',
          title: "Video",
          to: '/video-id'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
