<script setup>

</script>

<template>
    <button class="button">
        <slot></slot>
    </button>
</template>

<style scoped>
    .button {
        border: none;
        border-radius: 10px;
        background: var(--gradiend);
        font-size: 20px;
        padding: 15px;
    }
</style>