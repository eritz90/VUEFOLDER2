<template>
    <header>
      <h1>{{ title }}</h1>
      <h1>This is a Newsfeed :)</h1>
      <Button text ="Add Task" color = "green"/>
      <Button text ="Edit Task" color = "blue"/>
      <Button text ="Delete Task" color = "red"/>
    </header>
  </template>

<script lang = "ts">
import Button from '@/components/Button.vue';

export default {
  name: 'Header',
  props: {
    title: String,
  },
  components: {
    Button,
  },
};
</script>

  <style scoped>
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
  }
  </style>
