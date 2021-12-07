<template>
  <div class="hello">
    <NioButton @click="learnMore">Learn more about Tacklebox</NioButton>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  methods: {
    learnMore() {
      console.log("learn more");
    },
  },
};
</script>

<style scoped>

</style>
