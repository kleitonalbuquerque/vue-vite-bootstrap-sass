<template id="banner-grid">
  <div class="grid text-center banner-grid col-lg-12">
    <div class="p-0 border bg-light col-lg-6 col-xs-12">
      <img
        src="https://media.istockphoto.com/photos/futuristic-technology-concept-autonomous-semi-truck-with-cargo-at-picture-id1351045479?s=612x612"
        class="img-fluid"
        alt="truck"
      />
    </div>
    <div class="p-3 border bg-light col-lg-6 col-xs-12">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id
      est laborum.
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import "../../public/scss/reset";
.banner-grid {
  display: flex;
  flex-direction: row;
  background-color: $green-color;
}

@media (max-width: $breakpoint-sm) {
  .banner-grid {
    display: none;
    display: flex;
    flex-direction: column;
  }
}
</style>
