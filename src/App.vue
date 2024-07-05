 <!-- <template>
<img alt="Vue logo" src="./assets/logo.png" /> --
<HelloWorld msg="Welcome to Al-Nafi" /> 
<myHome/>
<twobinding/>
</template>

<script>
    import twoBinding from "./twoBinding.vue";
     import HelloWorld from "./components/HelloWorld.vue";
     import myHome from "./components/myHome.vue";
    export default {
        name: "App",
              components: {
            HelloWorld,
            myHome,
            twoBinding
        },
       
        };
</script> --> 
<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <HelloWorld msg="Welcome to Al-Nafi" />
  <myHome />
  <TwoBinding /> <!-- Use the correct name as per import -->
</template>

<script>
// Importing components
import HelloWorld from "./components/HelloWorld.vue";
import myHome from "./components/myHome.vue";
import TwoBinding from "./components/TwoBinding.vue"; 

export default {
  name: "App",
  components: {
    HelloWorld,
     myHome,
    TwoBinding
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #050505;
  margin-top: 60px;
  margin-left: 60px;
}

body {
  background-color: hsl(0, 0%, 86%);
}
</style>


<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: left;
        color: #050505;
        margin-top: 60px;
        margin-left: 60px;
      
    }

    body {
        background-color: hsl(0, 0%, 86%);
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
</style>  --> 
