// template 不参与编译 使用组件时需要使用一个根节点容器div
<template>
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
import School from "./School";
import Student from "./Student";

export default {
  name: "App",
  // App的作用：汇总所有的组件
  components: {
    Student,
    School,
  },
};
</script>
