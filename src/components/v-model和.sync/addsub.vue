<template>
  <div>
    <button>-</button>
    {{ value111 }}
    <button @click="add">+</button>
  </div>
</template>

<script>
export default {
  name: "VuePractiseAddsub",
  props: {
    value111: {
      type: Number,
      default: 0,
    },
  },
  model: {
    prop: "value111",
    event: "change111",
  },
  data() {
    return {};
  },

  mounted() {},

  methods: {
    add() {
      this.$emit("change111", this.value111 + 1);
    },
  },
};
</script>

<style lang="scss" scoped></style>
