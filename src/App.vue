<template>
  <div>
    <div>
      <NavBar />
    </div>

    <div class="container d-flex col-xs-12">
      <div class="row gy-2">
        <div>
          <BannerGrid />
        </div>
        <div>
          <Modal />
        </div>
        <div class="row gy-2 justify-content-center mb-3">
          <div class="col">
            <Card />
          </div>
          <div class="col">
            <Card />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import BannerGrid from "./components/BannerGrid.vue";
import Modal from "./components/Modal.vue";
import Card from "./components/Card.vue";
import NavBar from "./components/NavBar.vue";
</script>

<style lang="scss">
@import "../public/scss/_reset.scss";

h1 {
  color: green;

  &:hover {
    color: greenyellow;
  }
}
</style>
