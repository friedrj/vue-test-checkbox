<script setup lang="ts">
import CheckboxTest from "./components/CheckboxTest.vue";
import { ref } from "vue";

const val = ref(true);
</script>

<template>
  <div>
    <span>{{ val }}</span>
    <CheckboxTest v-model="val" label="test label" />
  </div>
</template>
