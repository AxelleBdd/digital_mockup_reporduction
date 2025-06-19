<template>
    <div class="header">
        <div class="logo">Logo</div>
        <div class="navbar">Navbar</div>
    </div>
</template>

<script>
export default {};
</script>

<style scoped>
.header {
    width: 100%;
    display: flex;
    align-items: center;
    padding: 1rem;
    gap: 1rem;
    border-radius: 0.5rem;
}

.logo {
    width: 80px;
    height: 80px;
    background: #ccc;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: bold;
}

.navbar {
    flex: 1;
    height: 80px;
    background: #ccc;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: bold;
}
</style>
