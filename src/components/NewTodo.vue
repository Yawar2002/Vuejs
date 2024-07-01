<template>
  <form @submit.prevent="addTodo()" action class="col-12 cil-lf-6">
    <input
      v-model="NewTodo"
      placeholder="Enter todo"
      type="text"
      class="form-control"
    />
  </form>
</template>
<script>
export default {
  data() {
    return {
      NewTodo: "",
    };
  },
  methods: {
    addTodo() {
      if (this.NewTodo.length > 1) {
        this.$emit("on-addtodo", this.NewTodo);
      }
      this.NewTodo = "";
    },
  },
};
</script>
<style scoped></style>
