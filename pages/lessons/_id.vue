<template>
  <div>
    <iframe v-if="id == 1" class="pdf" src="/pdf/dummy_fizika.pdf"/>
    <iframe v-else-if="id == 2" class="pdf" src="/pdf/FIZIKA-dastur.pdf"/>
    <iframe v-else-if="id == 3" class="pdf" src="/pdf/Fizik%20kecha.pdf"/>
    <iframe v-else-if="id == 4" class="pdf" src="/pdf/ishqalanish.pdf"/>
    <iframe v-else-if="id == 5" class="pdf" src="/pdf/masala.pdf"/>
    <iframe v-else="id == 6" class="pdf" src="/pdf/zaryadlangan.pdf"/>
  </div>
</template>

<script>
export default {
  name: "LessonsPage_id",
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
