<template>
    <div class="contentGroup">
        <Content v-for="n in 5" :key="n"/>
    </div>
</template>

<script>
    import Content from './Content.vue';
    export default {
        components: {
            Content
  }
};
</script>

<style>
.contentGroup {
    width: 70%;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    gap: 3rem;
}
</style>