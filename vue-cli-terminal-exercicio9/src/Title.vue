<template>
  <h1>{{ titulo }}</h1>
  <h1>{{ subtitulo }}</h1>
</template>

<script>
export default {
  name: "Title",
  props:{
      titulo:{
          type: String,
          required: true,
      },
      subtitulo:{
          type:String,
          required:false,
          default:"subtitulo"
      },
  },
  components: {},
  data() {
    return {};
  },
};
</script>
