<template>
  <section>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-3 text-center">
          <h4 class="fw-bold">Tipos de entrada (Ejemplos)</h4>
          <p class="fs-4">Veamos algunos ejemplo, codeando!!!</p>
        </div>
        <div class="col-md-9 text-center w-75">
          <pre><code>
<!-- Campo de entrada con etiqueta -->
&lt;input type="text" id="nombre" name="nombre" required&gt;

<!-- Campo de entrada con etiqueta -->
&lt;input type="email" id="email" name="email" required&gt;

    </code></pre>
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
