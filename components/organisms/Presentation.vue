<template>
    <div class="presentation">
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sed cupiditate id ad quibusdam vitae quia culpa dolore voluptatem labore, ea aspernatur vero harum. Voluptatum, qui dolorem repudiandae nam iure repellat officiis! A similique maiores unde debitis enim quaerat cum ullam, nemo asperiores, assumenda repellat officia, velit sit consequatur harum repellendus.</p>
        <img src="@/assets/img/presentation.svg" alt="">
    </div>
</template>

<script lang="ts">
    import Vue from 'vue'

    export default Vue.extend({
        
    })
</script>

<style lang="scss" scoped>
  .presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}  
</style>