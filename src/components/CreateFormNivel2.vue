<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-5 text-center">
          <h4 class="fw-bold">Nivel 2: Añadiendo Elementos Adicionales y Validaciones</h4>
          <p class="fs-4">Creando un 2do formulario - Lab2</p>
        </div>
        <div class="col-md-7 text-center">
          <img :src="imgCreateForm2" alt="Descripción de la imagen" class="img-fluid">
          <img :src="imgCreateForm" alt="Descripción de la imagen" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import imgCreateForm from '../assets/img_form_nivel2.png';
import imgCreateForm2 from '../assets/img_form_nivel2_result.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      imgCreateForm: imgCreateForm,
      imgCreateForm2: imgCreateForm2
    };
  }
}
</script>
