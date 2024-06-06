<template>
  <div class="app">
    <ComInput v-model="content"></ComInput>
  </div>
</template>

<script>
import ComInput from "./components/ComInput.vue";
export default {
  components: {
    ComInput,
  },
  data() {
    return {
      content: "",
    };
  },
};
</script>

<style>
</style>