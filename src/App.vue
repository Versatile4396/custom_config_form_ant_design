<template>
  <div class="main-form">
    <div class="form-wrapper">
      <Form></Form>
    </div>
  </div>
</template>
<script setup lang="ts">
import Form from "./components/configForm/index.vue";
</script>
<style scoped lang="scss">
.main-form {
  padding-top: 20px;
  display: flex;
  justify-content: center;
  .form-wrapper {
    width: 40vw;
    min-height: 100px;
    background: radial-gradient(
      100% 157.26% at 0% 0%,
      rgba(217, 242, 255, 0.5) 0%,
      rgba(242, 240, 252, 0.5) 27.87%,
      rgba(191, 216, 255, 0.5) 100%
    );
    border-radius: 16px;
  }
}
</style>
