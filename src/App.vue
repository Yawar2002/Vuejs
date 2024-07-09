<!-- <template>
<img alt="Vue logo" src="./assets/logo.png" /> --
<HelloWorld msg="Welcome to Al-Nafi" />

<myHome />
<twobinding />
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
    <!-- <HelloWorld msg="Welcome to Al-Nafi" /> -->
    <h1>Wellcome to Alnafi</h1>
    <!-- <myHome />
  <TwoBinding />  -->
    <!-- <CheckBox /> -->
    <!-- <ul>
        <li v-for="item in ReUse" :key="item.name">
            {{ item.name }}
             <br>
            {{ item.email }}
            <button v-on:click="getData(name)">Alert Name</button>
        </li>
    </ul> -->
    <!-- <ReUse /> -->
    <!-- <ChildPre name="Yassir" :email="email" :getData="getData"/> -->
     <ClassBin />
</template>

<script>
     import ClassBin from "./components/ClassBin.vue";

    //import ChildPre from "./components/ChildPre.vue";
    // import CheckBox from "./components/CheckBox.vue";
    // import HelloWorld from "./components/HelloWorld.vue";
    // import myHome from "./components/myHome.vue";
    // import TwoBinding from "./components/TwoBinding.vue"; 

    export default {
        // names: "App",
        // // components: {
        //   HelloWorld,
        //    myHome,
        //   TwoBinding
        // }
        //   Namess: "CheckBox",
        // components: {
        //       CheckBox
        // }
        //   
        // components: {
        //     ReUse
        // },
        // data() {
        //     return {
        //         ReUse: [{
        //                 name: 'Ali',
        //                 email: 'ali@gmail.com'
        //             },
        //             {
        //                 name: 'Ali',
        //                 email: 'ali@gmail.com'
        //             },
        //             {
        //                 name: 'Ali',
        //                 email: 'ali@gmail.com'
        //             }
        //         ]
        //     }
        // }
        omponents: {
              ClassBin
        }
    };
</script>

<style scope>
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
