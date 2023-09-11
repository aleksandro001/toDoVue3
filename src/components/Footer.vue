<script setup>
import TasksFilter from "@/components/TasksFilter.vue";
</script>

<template>
  <footer class="footer">
    <span class="todo-count">1 items left</span>
    <TasksFilter/>
    <button class="clear-completed">Clear completed</button>
  </footer>
</template>

<style scoped>

</style>