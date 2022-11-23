<script setup></script>

<template>
  <div>
    <img class="logo" src="logo.svg" alt="logo" />
    <h1 class="title">Trivia-Tastic</h1>
    <img class="logo" src="logo.svg" alt="logo" />
  </div>
  <div>
    <div v-for="n in 24" :key="n" class="category">Category - {{ n }}</div>
  </div>
</template>
