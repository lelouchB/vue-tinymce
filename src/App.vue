/* eslint-disable vue/no-unused-components */
<template>
  <h1>Vue TinyMCE Example</h1>
  <editor
    api-key= "8wphbjzfrlwugpe3ibkx678fsntv1nhp05ze8jokrqspn4l9io"
    :init="{
      height: 500,
      menubar: false,
      plugins: ['image '],
    }"
  />
</template>

<script>
import Editor from "@tinymce/tinymce-vue";

export default {
  name: "App",
  components: {
    editor: Editor,
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
  margin-top: 60px;
}
</style>
