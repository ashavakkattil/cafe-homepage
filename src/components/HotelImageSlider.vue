<template>
  <div class="q-my-xl">
    <q-carousel
      v-model="slide"
      transition-prev="slide-right"
      transition-next="slide-left"
      swipeable
      animated
      control-color="white"
      padding
      arrows
      height="500px"
      prev-icon="mdi-arrow-left"
      next-icon="mdi-arrow-right"
    >
      <q-carousel-slide :name="1" class="column no-wrap">
        <div class="row fit justify-center q-gutter-xl q-col-gutter no-wrap">
          <q-img class="rounded-borders full-height" src="../assets/slider-1.jpg" width="470px" />
          <q-img
            class="rounded-borders col-3 full-height"
            src="../assets/slider-2.png"
            width="470px"
          />
          <q-img
            class="rounded-borders col-3 full-height"
            src="../assets/slider-3.jpg"
            width="470px"
          />
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="2" class="column no-wrap">
        <div class="row fit justify-center q-gutter-xl q-col-gutter no-wrap">
          <q-img class="rounded-borders full-height" src="../assets/slider-1.jpg" width="470px" />
          <q-img
            class="rounded-borders col-3 full-height"
            src="../assets/slider-2.png"
            width="470px"
          />
          <q-img
            class="rounded-borders col-3 full-height"
            src="../assets/slider-3.jpg"
            width="470px"
          />
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="3" class="column no-wrap">
        <div class="row fit justify-center q-gutter-xl q-col-gutter no-wrap">
          <q-img class="rounded-borders full-height" src="../assets/slider-1.jpg" width="470px" />
          <q-img
            class="rounded-borders col-3 full-height"
            src="../assets/slider-2.png"
            width="470px"
          />
          <q-img
            class="rounded-borders col-3 full-height"
            src="../assets/slider-3.jpg"
            width="470px"
          />
        </div>
      </q-carousel-slide>
    </q-carousel>
  </div>
</template>
<script>
export default {
  data() {
    return {
      slide: 1
    };
  }
};
</script>
<style lang="scss">
.q-carousel__control {
  background: #009c9d;
  height: 40px;
  width: 100px;
  opacity: 0.7;
  top: 50%;
}
.q-carousel__slide {
  padding-right: 0px !important;
}
.q-carousel__prev-arrow--horizontal {
  left: 5%;
}
.q-carousel__next-arrow--horizontal {
  right: 4.5%;
}
</style>
