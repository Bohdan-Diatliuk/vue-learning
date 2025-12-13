<script setup>

</script>

<template>
    <button class="button">
        <slot></slot>
    </button>
</template>

<style scoped>
    .button {
        position: relative;
        left: 10%;
        top: 10%;
        width: 80%;
        border: none;
        border-radius: 10px;
        font-size: 20px;
        padding: 15px;
        background: linear-gradient(90.8deg, rgba(144, 217, 224, 0.9) 0.2%, rgba(84, 96, 230, 0.9) 100%);
    }

    .button:hover {
    }
</style>