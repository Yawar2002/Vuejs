<!-- <template>
  <h1>
    <li class="d-flex align-items-center list-group-item">
      <button
        v-if="isEditing"
        :class="{ completed }"
        @click="$emit('on-toggle')"
        class="btn boder-0 text-left flex-glow-1"
      >
        {{ todoString }}
      </button>
      <form v-else @submit.prevent="endEditing" class="flex-glow-1">
        <input
          @blur="startEditing()"
          v-model="newTodoString"
          type="text"
          class="form-control"
        />
        <button @click="startEditing()" class="btn outline-primary">
          Edit
        </button>
        <button @click="$emit('0n-delete')" class="btn outline-danger">
          Delete
        </button>
      </form>
    </li>
  </h1>
</template>
<script>
export default {
  props: {
    todoString: String,
    complete: Boolean,
  },
  data() {
    return {
      isEditing: false,
      newTodoString: "",
    };
  },
  methods: {
    startEditing() {
      if (!this.isEditing) {
        this.newTodoString = this.todoString;
        this.endEditing = true;
      } else {
        this.endEditing();
      }
    },
    endEditing() {
      this.isEditing = false;
      this.$emit("on-edit", this.newTodoString);
    },
  },
};
</script>
<style scope>
.complete {
  text-decoration: line-center;
  text-decoration-color: aliceblue;
}
</style>

<template>
  <li class="list-group-item">
    {{ todo.todoString }}
  </li>
</template>

<script>
export default {
  props: {
    todo: {
      type: Object,
      required: true,
    },
  },
};
</script>

<style></style> --> 
