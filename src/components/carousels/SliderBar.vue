<template>
  <div class="carousels">
    <v-carousel v-model="dataModel">
    <v-carousel-item
      v-for="(color, i) in colors"
      :key="color"
    >
      <v-sheet
        :color="color"
        height="100%"
        tile
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
          <div class="text-h2">
            Slide {{ i + 1 }}
          </div>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
  </div>
</template>
<script>
export default {
  name: 'SliderBar',
  data() {
    return {
        colors: ['red', 'blue', 'yellew', 'black', 'pink'],
        dataModel: ''
    }
  }
}
</script>
<style lang="scss">

</style>