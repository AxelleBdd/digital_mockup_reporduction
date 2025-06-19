<template>
  <div class="content-card" >
    <div class="content">Content</div>
    <button type="like">
      <img src="../assets/like.svg" alt="favori" srcset="">
    </button>
  </div>
</template>

<script setup>
</script>

<style scoped>
.content-card {
  margin: auto;
  display: flex;
  position: relative;
  border-radius: 0.5rem;
  background: #ddd;
  height: 17rem;
  width: 17rem;
  justify-content: center;
  align-items: center;
}

img {
  height: 10px;
  width: 10px;
  object-fit: contain
}

button {
  position: absolute;
  top: 0.5rem;
  right: 0.5rem;
  background: #ccc;
  border: none;
  border-radius: 50%;
  cursor: pointer;

  font-size: 1.2rem;
  width: 20px;
  height: 20px;
  padding: 0;

  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
