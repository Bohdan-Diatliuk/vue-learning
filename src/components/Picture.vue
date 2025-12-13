<script setup></script>

<template>
    <div class="picture">
        <img src="../img/bg-primary.png" alt="random" class="image">
        <video
        class="media video"
        src="../img/bg-video-2.mp4"
        muted
        loop
        playsinline
        autoplay
        ></video>
        <div class="text">
            <slot></slot>
        </div>
    </div>
</template>

<style scoped>
    .picture {
        position: fixed;
        left: 25%;
        top: 13%;
        width: 370px;
        height: 500px;
        border-radius: 50px;

        display: flex;
        justify-content: center;
        align-items: center;

        overflow: hidden;
    }

    .media {
        position: absolute;
        inset: 0;
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 50px;

        transition: opacity 0.4s ease;
    }

    .image {
        opacity: 1;
    }

    .video {
        opacity: 0;
    }

    .picture:hover .image {
        opacity: 0;
    }

    .picture:hover .video {
        opacity: 1;
    }

    .picture::after {
        content: '';
        position: absolute;
        inset: 0;
        background: linear-gradient(152.19deg,
        rgba(136, 235, 239, 0.7) -0.04%,
        rgba(83, 91, 230, 0.6) 100%
        );
  
        border-radius: 50px;
        backdrop-filter: blur(2px);
        z-index: 0;
    }

    .text {
        position: relative;
        z-index: 1;
        color: white;
    }
</style>