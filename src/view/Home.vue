<script setup>
    import CardView from "../components/CardView.vue";
    import ButtonView from "../components/ButtonView.vue";
</script>

<template>
    <div class="main">
        <CardView />
        <CardView />
        <CardView />
        
    </div>
</template>

<style scoped>
    .main{
        background-color: pink;
        display: flex;
        flex-grow: 1;
    }

    

</style>