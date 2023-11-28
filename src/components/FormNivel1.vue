<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-12 text-center">
          <div class="text-center">
            <h4 class="fw-bold">Creando INPUTS</h4>
            <p class="fs-4">Usemos el tipo TEXT y el PASSWORD</p>
          </div>
          <img :src="formNivel1" alt="tags html" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import formNivel1 from '../assets/formNivel1.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      formNivel1: formNivel1
    };
  }
}
</script>
