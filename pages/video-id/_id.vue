<template>
  <div class="d-flex align-center justify-center">
    <video v-if="id == 1" width="50%" controls>
      <source src="/video/1.mp4" type="video/mp4" >
    </video>
    <video v-else-if="id == 2" width="50%" controls>
      <source src="/video/2.mp4" type="video/mp4" >
    </video>
    <video v-else-if="id == 3" width="50%" controls>
      <source src="/video/3.mp4" type="video/mp4" >
    </video>
    <video v-else-if="id == 4" width="50%" controls>
      <source src="/video/4.mp4" type="video/mp4" >
    </video>
    <video v-else-if="id == 5" width="50%" controls>
      <source src="/video/5.mp4" type="video/mp4" >
    </video>
    <video v-else-if="id == 6" width="50%" controls>
      <source src="/video/6.mp4" type="video/mp4" >
    </video>
    <video v-else-if="id == 7" width="50%" controls>
      <source src="/video/7.mp4" type="video/mp4" >
    </video>
  </div>
</template>

<script>
export default {
  name: "VideoIdPage_id",
  data(){
    return{
      id: '',
    }
  },
  mounted() {
    this.id = this.$route.params.id
  }
}
</script>

<style lang="scss" scoped>

</style>
