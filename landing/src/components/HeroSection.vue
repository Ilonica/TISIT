<script setup lang="ts">
import MyIcon from '@/assets/styles/icon.svg';
</script>

<template>
    <div class="hero">
        <header class="header">
            <div class="logo">
                <div class="logo-img"></div>
                <p class="text-logo">TISIT</p>
            </div>
            <button class="btn-site btn-site-text">
                Посмотреть на сайте 
                <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 22 22" fill="none">
                    <g clip-path="url(#clip0_1792_1305)">
                        <path d="M16.393 6.4516C16.3814 5.87377 15.9027 5.41402 15.3249 5.42567L7.92861 5.57479C7.35078 5.58644 6.89103 6.0651 6.90268 6.64294C6.91433 7.22077 7.39299 7.68051 7.97083 7.66886L12.8454 7.56828L5.89717 14.8024C5.49631 15.2198 5.50964 15.8808 5.927 16.2817C6.34435 16.6825 7.00539 16.6692 7.40625 16.2519L14.3522 9.02007L14.4527 13.89C14.4644 14.4678 14.943 14.9276 15.5209 14.9159C16.0987 14.9043 16.5584 14.4256 16.5468 13.8478L16.3977 6.45151L16.393 6.4516Z" fill="#5664FF"/>
                    </g>
                    <defs>
                        <clipPath id="clip0_1792_1305">
                            <rect width="12.5545" height="16.7393" fill="white" transform="translate(12.2705 0.615356) rotate(43.845)"/>
                        </clipPath>
                    </defs>
                </svg>
            </button>
        </header>
        <div class="main">
            <div class="promo">
                <p class="text-promo">Ваш персональный<br>AI тренер</p>
                <div class="download">
                    <button class="btn-download btn-download-text">Скачать на iPhone</button>
                    <button class="btn-download btn-download-text">Скачать на Android</button>
                </div>   
            </div>
            <div class="gradient">
                <img class="gradient-img" src="@/assets/image/mockup_hero.png">
            </div> 
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import '@/assets/styles/hero_section.scss';
</style>