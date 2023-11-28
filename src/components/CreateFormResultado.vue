<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-4 text-center">
          <h4 class="fw-bold">Manejo Formularios</h4>
          <p class="fs-4">Nivel 1:  RESULTADO</p>
        </div>
        <div class="col-md-8 text-center">
          <img :src="imgCreateFormResult" alt="Descripción de la imagen" class="img-fluid">
          <img :src="imgCreateForm" alt="Descripción de la imagen" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import imgCreateForm from '../assets/img_registro.png';
import imgCreateFormResult from '../assets/img_registro_result.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      imgCreateForm: imgCreateForm,
      imgCreateFormResult: imgCreateFormResult
    };
  }
}
</script>
