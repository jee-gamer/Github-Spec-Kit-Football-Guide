<template>
  <section class="role-box">
    <h2>{{ role.name }}</h2>
    <img :src="role.image" :alt="role.name" class="role-img" @error="onImgError" />
    <div class="role-desc">
      <div v-for="(section, idx) in role.description" :key="idx">
        <h3>{{ section.sectionTitle }}</h3>
        <p>{{ section.sectionBody }}</p>
      </div>
    </div>
  </section>
</template>

<script setup>
const props = defineProps({
  role: Object
});
function onImgError(event) {
  event.target.src = require('../assets/placeholder.png');
}
</script>

<style scoped>
.role-box {
  background: #fff;
  border-radius: 1rem;
  box-shadow: 0 2px 12px rgba(30, 58, 92, 0.08);
  padding: 1.5rem 1rem 1.5rem 1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  transition: box-shadow 0.2s;
}
.role-box:hover {
  box-shadow: 0 4px 24px rgba(30, 58, 92, 0.16);
}
.role-img {
  width: 120px;
  height: 120px;
  object-fit: cover;
  border-radius: 50%;
  margin: 1rem 0;
  border: 3px solid #e0e7ef;
  background: #e0e7ef;
}
.role-box h2 {
  margin: 0;
  font-size: 1.4rem;
  color: #1e3a5c;
  letter-spacing: 0.5px;
}
.role-desc {
  width: 100%;
  margin-top: 1rem;
}
.role-desc h3 {
  margin: 0.7rem 0 0.2rem 0;
  font-size: 1.1rem;
  color: #2d5a8c;
}
.role-desc p {
  margin: 0 0 0.7rem 0;
  font-size: 1rem;
  color: #333;
}
</style>
