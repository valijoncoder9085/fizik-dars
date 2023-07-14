<template>
  <div>
    <iframe v-if="id == 1" class="pdf" src="/traing/1.pdf"/>
    <iframe v-else-if="id == 2" class="pdf" src="/traing/2.pdf"/>
    <iframe v-else-if="id == 3" class="pdf" src="/traing/3.pdf"/>
    <iframe v-else-if="id == 4" class="pdf" src="/traing/4.pdf"/>
    <iframe v-else-if="id == 5" class="pdf" src="/traing/5.pdf"/>
    <iframe v-else-if="id == 6" class="pdf" src="/traing/6.pdf"/>
    <iframe v-else-if="id == 7" class="pdf" src="/traing/7.pdf"/>
    <iframe v-else-if="id == 8" class="pdf" src="/traing/8.pdf"/>
    <iframe v-else="id == 9" class="pdf" src="/traing/9.pdf"/>
  </div>
</template>
<script>
export default {
  name: "TrainingsPage_id",
  data() {
    return {
      id: ''
    }
  },
  mounted() {
    this.id = this.$route.params.id
  }
}
</script>

<style lang="scss" scoped>
.pdf{
  width: 100%;
  height: 100vh;
}
</style>
