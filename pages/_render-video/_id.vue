<template>
  <div>
    <v-card class="d-flex align-center justify-center">
      <v-card-text>
        <video v-if="id == 1" width="100%" height="500" controls autoplay>
          <source src="/video/1.mp4" type="video/mp4">
        </video>
        <video v-else-if="id == 2" width="100%" height="500" controls autoplay>
          <source src="/video/2.mp4" type="video/mp4">
        </video>
        <video v-else-if="id == 3" width="100%" height="500" controls autoplay>
          <source src="/video/3.mp4" type="video/mp4">
        </video>
        <video v-else-if="id == 4" width="100%" height="500" controls autoplay>
          <source src="/video/4.mp4" type="video/mp4">
        </video>
        <video v-else-if="id == 5" width="100%" height="500" controls autoplay>
          <source src="/video/5.mp4" type="video/mp4">
        </video>
        <video v-else-if="id == 6" width="100%" height="500" controls autoplay>
          <source src="/video/6.mp4" type="video/mp4">
        </video>
        <video v-else-if="id == 7" width="100%" height="500" controls autoplay>
          <source src="/video/7.mp4" type="video/mp4">
        </video>
      </v-card-text>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "VideoIdPage_id",
  data() {
    return {
      id: '',
    }
  },
  async mounted() {
    this.id = this.$route.params.id
  }
}
</script>

<style lang="scss" scoped>
</style>
