<template>
  <div>Child Component</div>
</template>

<script>
export default {
  name: "child",
  beforeCreate() {
    console.log("Child beforeCreate()");
  },
  created() {
    console.log("Child created()");
  },
  beforeMount() {
    console.log("Child beforeMount()");
  },
  mounted() {
    console.log("Child mounted()");
  },
  beforeUpdate() {
    console.log("Child beforeUpdate()");
  },
  updated() {
    console.log("Child updated()");
  },
  beforeUnmount() {
    console.log("Child beforeUnmount()");
  },
  unmounted(){
    console.log("Child Unmounted()");
  }
};
</script>

<style scoped>
</style>