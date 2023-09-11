<script setup>
import {ref} from "vue";
import NewTaskForm from "@/components/NewTaskForm.vue";
import TaskList from "@/components/TaskList.vue";
import Footer from "@/components/Footer.vue";
import { formatDistanceToNow } from 'date-fns'

const timeDistance = formatDistanceToNow(new Date(), {addSuffix: true})
console.log(timeDistance)
</script>

<template>
  <section class="todoapp">
    <header class="header">
      <h1>todos</h1>
      <NewTaskForm/>
    </header>
    <section class="main">

        <TaskList/>

      <Footer/>
    </section>
  </section>
</template>

<style scoped>

</style>
