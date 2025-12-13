<script setup></script>

<template>
    <div class="forecast">
        <div class="block">
            <span>Вологість</span>
            <span>af</span>
        </div>
        <div class="block">
            <span>Опади</span>
            <span>124</span>
        </div>
        <div class="block">
            <span>Вітер</span>
            <span>12</span>
        </div>
    </div>
</template>

<style scoped>
    .forecast {
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        font-size: 27px;
        margin: 30px;
        text-transform: uppercase;
    }

    .block {
        display: flex;
        justify-content: space-between;
        width: 90%;
    }

</style>