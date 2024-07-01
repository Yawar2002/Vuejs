<template>
  <div class="container">
    <div class="row">
      <div class="col-12">
        <p class="display-3">Add Crash course</p>
      </div>
      <div class="row">
        <div class="col-12 col-lg-6">
          <NewTodo @on-addtodo="addTodo" ($events) />
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-12 col-lg-6">
        <ul class="list-group">
          <ToDo
            v-for="(todo, index) in todos"
            :key="index"
            :todoString="todo.todoString"
            :completed="todoCompleted"
            @on-delete="deleteTodo(todo)"
            @on-toggle="ToggleTodo(todo)"
            @on-edit="editTodo(todo, $event)"
          />

          <!-- <li v-for="(todo, index) in todos" :key="index">
            {{ todo.todoString }}
          </li> -->
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
import ToDo from "./ToDo";
import NewTodo from "./NewTodo";
export default {
  components: {
    ToDo,
    NewTodo,
  },
  data() {
    return {
      todos: [
        { todoString: "Make angular course", completed: false },
        { todoString: "Make a fun", completed: true },
        { todoString: "Make course", completed: false },
        { todoString: "Make youtube", completed: true },
      ],
    };
  },
  methods: {
    addTodo(newTodo) {
      this.todos.push({
        todoString: newTodo,
        completed: false,
      });
    },
    ToggleTodo(todo) {
      todo.completed = !todo.completed;
    },
    editTodo(todo, newTodoString) {
      todo.todoString = newTodoString;
    },
    deleteTodo(deletetodo) {
      this.todoString = this.todoString.filters(
        (todo) => todo.todoString !== deletetodo
      );
    },
  },
};
</script>
<style></style>
