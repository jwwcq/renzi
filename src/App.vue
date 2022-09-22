<template>
  <div class="app">
    <myParent></myParent>
  </div>
</template>
<script>
import myParent from "./components/lifecycle/parent.vue";
export default {
  components: {
    myParent,
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
