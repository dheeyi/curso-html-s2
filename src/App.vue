<template>
  <div id="app">
    <div class="reveal">
      <div class="slides">
        <conceptos></conceptos>
        <tags-form></tags-form>
        <tags-form2></tags-form2>
        <tags-form-ejemplo></tags-form-ejemplo>
        <form-nivel1></form-nivel1>
        <form-nivel2></form-nivel2>
        <form-nivel3-div></form-nivel3-div>
        <create-form></create-form>
        <create-form-resultado></create-form-resultado>
        <create-form-nivel2></create-form-nivel2>
        <create-form-nivel3-avanzado></create-form-nivel3-avanzado>
        <section>Gracias, terminamos nuestro contenido de hoy!!!</section>
      </div>
    </div>
  </div>
</template>

<script>
import Reveal from "reveal.js";
import Markdown from "reveal.js/plugin/markdown/markdown.js";
import Highlight from "reveal.js/plugin/highlight/highlight.js";
import "reveal.js/dist/reveal.css";
import "reveal.js/dist/theme/serif.css";
import "reveal.js/plugin/highlight/monokai.css";

import Conceptos from "@/components/ConceptosForm.vue";
import TagsForm from "@/components/TagsForm.vue";
import TagsForm2 from "@/components/TagsForm2.vue";
import TagsFormEjemplo from "@/components/TagsFormEjemplo.vue";
import FormNivel1 from "@/components/FormNivel1.vue";
import FormNivel2 from "@/components/FormNivel2.vue";
import FormNivel3Div from "@/components/FormNivel3Div.vue";
import CreateForm from "@/components/CreateForm.vue";
import CreateFormResultado from "@/components/CreateFormResultado.vue";
import CreateFormNivel2 from "@/components/CreateFormNivel2.vue";
import CreateFormNivel3Avanzado from "@/components/CreateFormNivel3Avanzado.vue";

export default {
  name: "App",
  components: {
    Conceptos,
    TagsForm,
    TagsForm2,
    TagsFormEjemplo,
    FormNivel1,
    FormNivel2,
    FormNivel3Div,
    CreateForm,
    CreateFormResultado,
    CreateFormNivel2,
    CreateFormNivel3Avanzado,
  },
  mounted() {
    Reveal.initialize({
      plugins: [Markdown, Highlight],
      markdown: {
        breaks: true,
        gfm: true,
      },
    });
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 97vh;
}
</style>
