<script>
    export default{

    }
</script>

<template>
    <div class="jumbo-box d-flex flex-column align-items-center">
        <p class="display-5 text-light p-5"> My first Jumbotron with Vite + Vue</p>
        <img class="status-img" src="../assets/nyan.png" alt="">
    </div>
</template>

<style scoped>
    .jumbo-box{
        background-image: url(../assets/bg-banner-hero.jpg);
        background-size: cover;
        height: 600px;
    }

    .status-img{
        height: 200px;
    }
</style>