<template>
   <h1>Message: {{ message }} </h1>
   <button @click="helloWorld()">Get a surprise greeting in console</button>
</template>
<script>
export default {
  name: 'ToDoItem',
  data() {
    return {
      message: 'This is the component in a variable',
    };
  },
  methods: {
    helloWorld() {
      console.log('Hello world');
    },
  },
};
</script>
