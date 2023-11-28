<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-12 text-center">
          <div class="text-center">
            <h4 class="fw-bold">Creando INPUTS</h4>
            <p class="fs-4">Usemos mas types posibles</p>
          </div>
          <img :src="formNivel2" alt="tags html" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import formNivel2 from '../assets/type2.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      formNivel2: formNivel2
    };
  }
}
</script>
