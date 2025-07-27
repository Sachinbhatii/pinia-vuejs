<script setup>
import { useCounterStore } from "../stores/counter";
import { storeToRefs } from "pinia";
let store = useCounterStore();
const { count, doubleCount } = storeToRefs(store);
</script>
<template>
  <hr />
  <h1>B Component</h1>
  <h2>Count: {{ count }}</h2>
  <h2>Double Count: {{ doubleCount }}</h2>
</template>
<style></style>
