<script setup></script>

<template>
    <div class="picture">
        <img src="../img/bg-primary.png" alt="random" class="picture">
        <div class="text">
            <slot></slot>
        </div>
    </div>
</template>

<style scoped>
    .picture {
        display: flex;
        position: fixed;
        justify-content: space-around;
        align-items: center;
        left: 25%;
        top: 13%;
        width: 370px;
        height: 500px;
        border-radius: 50px;
    }

    .picture::after {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(152.19deg, rgba(136, 235, 239, 0.4) -0.04%, rgba(83, 91, 230, 0.4) 100%);
        border-radius: 50px;
        backdrop-filter: blur(2px);
    }

    .text {
        color: white;
        z-index: 1;
    }
</style>