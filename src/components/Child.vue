<template>
  <div>child</div>
</template>


<script>
const tag = "Child";
export default {
  name: "Child",
  methods: {},

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
  activated() {
    console.log(tag, "activated");
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
