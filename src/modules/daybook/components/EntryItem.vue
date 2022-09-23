<template>
  <div 
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name:'entry', params: { id: 10 }})"
  >
      <!-- Titulo -->
      <div class="entry-title d-flex">
          <span class="text-success fs-5 fw-bold">21</span>
          <span class="mx-1 fs-5">Sep</span>
          <span class="mx-2 fw-light">2022, Mie</span>
      </div>
      <div class="entry-description">
        Sit voluptate proident fugiat consequat occaecat eu irure sunt ex laboris veniam officia incididunt est. Sint enim do velit dolore. Cillum elit Lorem minim ut ad aliquip cillum cillum. Labore magna cupidatat et est duis id. Cupidatat nostrud adipisicing in mollit fugiat nostrud reprehenderit fugiat amet irure pariatur eiusmod do. Do voluptate quis Lorem tempor magna pariatur ullamco laborum labore quis aute amet.
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    };
    .entry-description{
        font-size: 12px;
    }
}
</style>