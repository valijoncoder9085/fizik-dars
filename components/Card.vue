<template>
  <div>
    <v-row class="mt-4">
      <v-col cols="12" md="6" lg="4" sm="3" v-for="(item, idx) in items" :key="'id_'+idx">
        <nuxt-link :to="item.to">
          <div class="card rounded-lg d-flex align-center">
            <div class="card_img mr-3">
              <v-img style="height: 100px" :src="`/${item.icon}`"></v-img>
            </div>
            <span style="color: white" class="text-h5">
            {{item.title}}
          </span>
          </div>
        </nuxt-link>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "CardPage",
  props:{
    items: {
      type: Array,
      required: true
    }
  },
  data() {
    return {
    }
  }
}
</script>

<style lang="scss" scoped>
.card {
  background-color: #757575;
  min-width: 205px;
}

.card_img{
  max-width: 120px !important;
  min-height: 120px;
  padding: 10px;
}
.card:hover {
  cursor: pointer;
  box-shadow: rgba(0, 0, 0, 0.19) 0 10px 20px, rgba(0, 0, 0, 0.23) 0 6px 6px;
}
</style>
