<template>
  <div id="head">
    <Header></Header>
  </div>
</template>

<script>
import Header from "../components/header";
  export default {
    name: "home",
    components: {
      Header,
    },
  };
</script>

<style lang="scss" scoped>
#head{
  background-color: rgba(25, 67, 134, 0.664);
  width: 100%;
  height: 200px;
  color: white;
}
</style>