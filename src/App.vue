<template>
  <div id="app">
    <header>
      <h1>Football Guide</h1>
      <p>Learn how to play every role on the football field</p>
    </header>
    <main class="roles-grid">
      <RoleBox v-for="role in roles" :key="role.name" :role="role" />
    </main>
    <footer>
      <p>&copy; 2025 Football Guide. All images and descriptions are for educational purposes.</p>
    </footer>
  </div>
</template>

<script setup>
import { ref } from 'vue';
import RoleBox from './components/RoleBox.vue';
import roles from './data/roles.js';
</script>

<style>
#app {
  font-family: 'Segoe UI', Arial, sans-serif;
  background: #f7f9fa;
  color: #222;
  min-height: 100vh;
}
</style>
