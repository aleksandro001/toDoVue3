<script setup>
import Task from "@/components/Task.vue";
const Completed = 'Completed task'
const Editing = 'Editing task'
const Active = 'Active task'
</script>

<template>
  <ul class="todo-list">

    <Task name-task='Completed task'/>
    <Task name-task='Editing task'/>
    <Task name-task='Active task'/>
  </ul>

</template>

<style scoped>

</style>