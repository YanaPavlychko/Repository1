<template>
  <div class="card">
    <h2>Ім’я: {{ name }}</h2>
    <p>Номер: {{ phone }}</p>
    <p>Пошта: {{ email }}</p>
  </div>
</template>

<script>
export default {
  name:"BusinessCard",
  props:['name', 'phone', 'email']
}
</script>

<style scoped>
.card {
  border: 1px solid #aaa;
  padding: 10px;
  border-radius: 8px;
  max-width: 250px;
  font-family: sans-serif;
  background-color: #f4f4f4;
}
</style>
