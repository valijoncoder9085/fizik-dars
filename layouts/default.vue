<template>
  <div>
    <Sidebar/>
  </div>
</template>
<script>
export default {
  name: 'DefaultLayout',
  data () {
    return{

    }
  }
}
</script>
<style lang="scss">
.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s ease;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
}
</style>
