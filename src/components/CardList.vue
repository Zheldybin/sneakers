<script setup>
import Card from './Card.vue'
const onClickAdd = () => {
  alert('Добавить!')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      :price="19900"
      title="Мужские Кроссовки Nike Blazer Mid Suede"
      image-url="/sneakers/sneakers-1.jpg"
      :onClickAdd="onClickAdd"
    />
  </div>
</template>
