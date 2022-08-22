<template>
  <div>
    parent

    <Child />
  </div>
</template>


<script>
import Child from "./Child";
const tag = "Parent";
export default {
  name: "Parent",
  methods: {},
  components: {
    Child,
  },
  beforeCreate() {
    console.log(tag, "beforeCreate");
  },
  created() {
    console.log(tag, "created");
  },
  mounted() {
    console.log(tag, "mounted");
  },
  beforeUpdate() {
    console.log(tag, "beforeUpdate");
  },
  updated() {
    console.log(tag, "updated");
  },
  activaed() {
    console.log(tag, "activaed");
  },
  deactivated() {
    console.log(tag, "deactivated");
  },

  beforeDestroy() {
    console.log(tag, "beforeDestroy");
  },
  destroyed() {
    console.log(tag, "destroyed");
  },
};
</script>


