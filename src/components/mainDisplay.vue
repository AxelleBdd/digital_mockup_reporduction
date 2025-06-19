<template>
  <div class="main-display" >
    <ContentGroup />
    <SideBar />
  </div>
</template>

<script>
    import ContentGroup from './ContentGroup.vue';
    import SideBar from './SideBar.vue';
    export default {
        components: {
            ContentGroup,
            SideBar
        }
    };
</script>

<style>
.main-display{
    display: flex;
    gap: 3rem;
    justify-content: center;
    align-items: center;
}
</style>
