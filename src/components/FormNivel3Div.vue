<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-12 text-center">
          <div class="text-center">
            <h4 class="fw-bold">Creando INPUTS</h4>
            <p class="fs-4">Conociendo el tag DIV</p>
          </div>
          <div>
            <p class="badge bg-primary text-wrap">
              Que estrategia utilizariamos para generar un salto de linea?
            </p>
          </div>
          <img :src="formNivel2" alt="tags html" class="img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import formNivel2 from '../assets/typesColumn.png';

export default {
  name: 'CreateForm',
  data() {
    return {
      formNivel2: formNivel2
    };
  }
}
</script>
