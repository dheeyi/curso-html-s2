<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-5 text-center">
          <h4 class="fw-bold">Nivel 3: Formulario completo</h4>
          <p class="fs-4">Generar el siguiente formulario - Lab3 Final</p>
        </div>
        <div class="col-md-7 text-center">
          <img :src="imgCreateForm" alt="Descripción de la imagen" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import imgCreateForm from '../assets/img_lab.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      imgCreateForm: imgCreateForm,
    };
  }
}
</script>
