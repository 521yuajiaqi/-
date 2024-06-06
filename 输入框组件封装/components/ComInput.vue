<template>
  <div class="com-input">
    <span>输入框:</span>
    <input placeholder="请输入内容" @change="handleInput" :value="value" />
  </div>
</template>

<script>
export default {
  props: {
    value: String,
  },
  methods: {
    handleInput(e) {
      this.$emit("input", e.target.value);
    },
  },
};
</script>

<style>
</style>