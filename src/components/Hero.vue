<template>
    <div id="hero">
        <img src="/og-image-announcing-vite3.png" alt="">
    </div>
</template>

<script>
    export default {
        name: 'Hero',
        data(){
            return {

            }
        }
    }
</script>

<style scoped>
    #hero{
        /* position: sticky; */
        left: 0;
        width: 100%;
        height: 500px;
        /* height: 100vh; */
        background-color: aqua;
        /* object-fit: cover; */
    }
    img {
        display: block;
        width: 100%;
        height: 500px;
        object-fit: cover;
    }
    
</style>