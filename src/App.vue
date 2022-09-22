<template>
  <div class="app"></div>
</template>
<script>
export default {
  data() {
    return {
      formData: {
        phone: "",
        password: "",
      },
      rules: [{}],
    };
  },
};
</script>
<style scoped>
.app {
  width: 900px;
}
</style>
