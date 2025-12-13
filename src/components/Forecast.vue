<script setup></script>

<template>
    <div class="forecast">
        <div class="block">
            <span class="block-primary">Вологість</span>
            <span>%</span>
        </div>
        <div class="block">
            <span class="block-primary">Опади</span>
            <span>%</span>
        </div>
        <div class="block">
            <span class="block-primary">Вітер</span>
            <span>м/с</span>
        </div>
    </div>
</template>

<style scoped>
    .forecast {
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 30px;
        font-size: 23px;
    }
    
    .block {
        display: flex;
        justify-content: space-between;
        width: 90%;
        padding: 3px;
    }
    
    .block-primary {
        text-transform: uppercase;
        font-weight: bold;
    }

</style>