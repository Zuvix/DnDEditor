<script setup>
import { ref, computed } from "vue";
const questions = ref([
  {
    question: "Select a race for your character",
  },
]);
</script>

<template>
  <h1>DND Editor</h1>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Montserrat", sans-serif;
  background-color: #271c36;
  color: #fff;
}
</style>
