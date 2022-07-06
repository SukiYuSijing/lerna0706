<!--
 * @Author: SukiYuSijing 15767301655@163.com
 * @Date: 2022-07-07 00:30:22
 * @LastEditors: SukiYuSijing 15767301655@163.com
 * @LastEditTime: 2022-07-07 01:33:03
 * @FilePath: \lerna0706\lerna-demo2\packages\project-a\src\App.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import { jInput } from "ysj-jinput";
import say from "ysj-ninput";
jInput("project-a");
say("project-a");
export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
