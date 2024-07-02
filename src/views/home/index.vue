<template>
  <div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";
// todo 使用以下代码导入组件就报错
// import { HelloWorld } from "@/components/HelloWorld.vue";

export default {
  name: "HomeA",
  components: {
    HelloWorld,
  },
};
</script>

<style>
</style>