<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6 text-center">
          <h4 class="fw-bold">Nivel 1: Introducción a Formularios HTML Básicos</h4>
          <p class="fs-4">Creando nuestro primer formulario - Lab1</p>
        </div>
        <div class="col-md-6 text-center">
          <img :src="imgCreateForm" alt="Descripción de la imagen" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import imgCreateForm from '../assets/img.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      imgCreateForm: imgCreateForm
    };
  }
}
</script>
