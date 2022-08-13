<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <ToDoItem></ToDoItem>
  </div>
</template>

<script>
// @ is an alias to /src

import ToDoItem from '@/components/ToDoItem.vue';

export default {
  name: 'ToDoItem',
  components: {
    ToDoItem,
  },
};
</script>
