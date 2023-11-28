<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-5 text-center">
          <h3 class="fw-bold">Tag INPUT tipos de entrada</h3>
          <p class="fs-4">Que tipos de entrada existen</p>
        </div>
        <div class="col-md-7 text-center">
          <img :src="imgTags1" alt="tags html" class="img-fluid">
          <a href="https://www.facebook.com/" target="_blank" class="h4">
            <strong>Click aqui:</strong> Caso ejemplo facebook
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import imgTags2 from '../assets/tags2.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      imgTags1: imgTags2
    };
  }
}
</script>
