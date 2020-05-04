<template>
  <q-page class="q-ma-xl">
    <div class="q-mb-xl">
      <q-img src="../assets/hero-image.jpg" height="850px" class="hero-image">
        <div class="text-black hero-image-text">
          <div class="image-caption">Loren's Cafe</div>
          <div class="image-subheading q-mb-lg">Breakfast, brunch and some more breakfast</div>
          <div>
            <q-btn size="xl" color="primary">See our menu</q-btn>
          </div>
        </div>
      </q-img>
    </div>
    <div>
      <div class="text-h3 text-center q-my-xl text-weight-bold">This is Us</div>
      <div class="text-center">
        <p
          class="q-mb-xs"
        >Lorem ipsum is simply dummy text of the printing and typesetting industry.Lorem Ipsum has been</p>
        <p
          class="q-mb-xs"
        >the industry's standard dummy text ever since the 1500s,when an unknown printer</p>
        <p class="q-mb-xs">took a galley of type and scrambled it to make a type specimen book</p>
      </div>
    </div>
    <img-slider></img-slider>
    <menu-gallery></menu-gallery>
  </q-page>
</template>

<script>
import ImgSlider from "../components/HotelImageSlider";
import MenuGallery from '../components/MenuGallery'

export default {
  name: "PageIndex",
  components: {
    ImgSlider, MenuGallery
  },
  data() {
    return {};
  }
};
</script>
<style lang="scss">
.hero-image {
  opacity: 0.8;
}
.hero-image-text {
  background-color: transparent !important;
  position: relative !important;
  text-align: center;
  top: 25%;
  font-weight: 700;
  .image-caption {
    font-size: 100px;
  }
  .image-subheading {
    font-size: 30px;
  }
}
</style>
