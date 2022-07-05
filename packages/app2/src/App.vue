<!--
 * @Author: SukiYuSijing 15767301655@163.com
 * @Date: 2022-07-06 00:30:38
 * @LastEditors: SukiYuSijing 15767301655@163.com
 * @LastEditTime: 2022-07-06 00:34:37
 * @FilePath: \20200706\packages\app2\src\App.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <App1 />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import App1 from "app1";

export default {
  name: "App",
  components: {
    HelloWorld,
    App1,
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
