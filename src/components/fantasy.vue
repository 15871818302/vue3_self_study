<template>
  <div></div>
</template>

<script>
export default {
  name: "HelloVue3Fantasy",

  props: {
    user: {
      type: String,
    },
  },

  // setup 是一个接收props和context的函数
  // setup 中不能使用this，setup中的this指向的是undefined
  setup(props) {
    console.log(props);
    console.log(this);
    return {};
  },

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped></style>
