<template>
  <form class="search-bar" >
    <input type="text" placeholder="Search..." />
    <button type="submit">
      <img src="../assets/search.svg" alt="" srcset="">
    </button>
  </form>
</template>

<style scoped>
.search-bar {
  margin: 1rem auto;
  display: flex;
  border-radius: 1rem;
  overflow: hidden;
  background: #ccc;
  max-width: 80%;
  justify-content: center;
}

input {
  flex: 1;
  padding: 1rem;
  border: none;
  outline: none;
  background: #ccc;
  font-weight: bold;
}

button {
  background: #ddd;
  border: none;
  padding: 0 1rem;
  cursor: pointer;
  font-size: 1.2rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
img{
  object-fit: contain;
  height: 20px;
  width: 20px;
}
</style>
