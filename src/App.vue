<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Al-Nafi" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import index from"./components/index";
export default {
  name: "App",
  components: {
    HelloWorld,
    index,
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
body {
  background-color: rgb(172, 127, 200);
}
</style> 
<!-- <template>
  <div>
    <h1>Hellow From Karachi</h1>
    <TodoList />
  </div>
</template>

<script>
import TodoList from "/src/components/TodoList.vue";
export default {
  name: "App",
  components: {
    TodoList,
  },
};
</script>

<style>
body {
  background-color: rgb(0, 0, 0);
  color: aliceblue;
}
</style> 
<template>
  <div>
    <h1>H</h1>
    <TodoList />
  </div>
</template>

<script>
import TodoList from "./components/TodoList.vue";
export default {
  name: "App",
  components: {
    TodoList,
  },
};
</script>

<style>
body {
  background-color: rgb(20, 130, 24);
  color: aliceblue;
  text-decoration-color: rgb(37, 41, 41);
}
</style> 
