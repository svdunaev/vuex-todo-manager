<template>
  <div>
    <TodosList />
  </div>
</template>

<script lang="ts">
import TodosList from "./components/TodosList.vue";

export default {
  name: "app",
  components: {
    TodosList,
  },
};
</script>
<style scoped></style>
