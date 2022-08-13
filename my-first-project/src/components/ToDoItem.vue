<template>
   <h1>Message: {{ message }} </h1>
</template>
<script>
export default {
  name: 'ToDoItem',
  data() {
    return {
      message: 'This is the component in a variable',
    };
  },
};
</script>
