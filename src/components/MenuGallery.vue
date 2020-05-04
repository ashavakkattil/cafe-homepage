<template>
  <div>
    <div class="q-py-xl">
      <div class="row">
        <div class="bg-accent left-container" style>
          <q-img src="../assets/pancake-1.jpg" class="food-image"></q-img>
        </div>
        <div style="height: 400px ; width: 55%" class="bg-secondary">
          <div class="menu-text-container breakfast-panel">
            <div class="text-h2 q-my-lg">Sit-n-Indulge</div>
            <div class="text-h4 q-mb-sm">Great breakfast, hearty brunch and Summer cocktails</div>
            <div class="text-h4">If it's not chocolate, it's not breakfast.</div>
            <q-btn class="q-my-lg" color="primary" size="xl">Our menu</q-btn>
          </div>
        </div>
      </div>
    </div>
    <div class="q-py-xl">
      <div class="row">
        <div style="height: 400px ; width: 55%;" class="bg-accent left-container">
          <div class="menu-text-container text-right coffee-panel">
            <div class="text-h2 q-my-lg">Grab-n-Go</div>
            <div class="text-h4 q-mb-sm">Great breakfast, hearty brunch and Summer cocktails</div>
            <div class="text-h4">If it's not chocolate, it's not breakfast.</div>
            <q-btn class="q-my-lg" color="primary" size="xl">Our menu</q-btn>
          </div>
        </div>
        <div style="width: 40%;" class="bg-accent">
          <q-img src="../assets/coffee.jpg" class="food-image"></q-img>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss">
.left-container {
  top: 100px;
  left: 100px;
  position: relative;
  width: 40%;
  z-index: 1;
}
.food-image {
  height: 550px;
}
.menu-text-container {
  padding-top: 50px;
}
.breakfast-panel{
    padding-left: 200px
}
.coffee-panel{
    padding-right: 50px
}
</style>
