<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- 添加“scoped”属性以将 CSS 仅限于此组件 -->
<style scoped>
h1 {
  color: red;
}
</style>
