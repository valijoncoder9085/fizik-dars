<template>
  <div>
    <video v-if="1" width="400" controls>
      <source src="" type="video/avi" >
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
