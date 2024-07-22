<template>
    <h1>Child to Parent</h1>
    <button v-on:Click="getUser(UserName)">Click On</button>
    
    <br>

    <br>
    <br>
    <input type="text" ref="input">
    <button v-on:click="getData">Click Me</button>
</template>
<script>
export default {
// name: childparent,
    data(){
        return {
            UserName: "alnafi"
        }
    },
    props:{
        getUser: Function,
    },
    methods: {
        getData(){
            // 
            this.$refs.input.focus();
            let val=this.$refs.input.value;
            console.warn(val);
            this.$refs.input.style.color="red"
        }
    }
}
</script>
<style>

</style>