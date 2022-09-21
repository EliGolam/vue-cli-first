<template>
    <div class="hero-bg">
        <div class="img-container">
            <img src="../assets/img/01.jpg" alt="">
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HeroBG',
    }
</script>

<style scoped lang="scss">
    .img-container {
        position: absolute;
            top: 0;
            z-index: -1;

        object-fit: cover;
    }
</style>