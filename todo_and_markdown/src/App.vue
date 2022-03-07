<script setup>
import MarkdownEditor from './components/MarkdownEditor.vue';
import TodoList from './components/TodoList.vue';

</script>

<template>
  
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <p> TEST HEADING </p>
    
  </header>

  <main>
    <TodoList />
    <MarkdownEditor />
  </main>
</template>
