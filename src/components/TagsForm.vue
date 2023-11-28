<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-5 text-center">
          <h3 class="fw-bold">Tags HTML para Forms</h3>
          <p class="fs-4">Conociendo que tags HTML son usados para crear formularios</p>
        </div>
        <div class="col-md-7 text-center">
          <img :src="imgTags1" alt="tags html" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import imgTags1 from '../assets/tags1.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      imgTags1: imgTags1
    };
  }
}
</script>
