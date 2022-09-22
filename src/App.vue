<template>
  <div class="app">
    <myTest></myTest>
  </div>
</template>
<script>
import myTest from "./components/v-if和v-for不推荐一起使用";
export default {
  components: {
    myTest,
  },
  data() {
    return {};
  },
};
</script>
<style scoped>
.app {
  width: 900px;
}
</style>
