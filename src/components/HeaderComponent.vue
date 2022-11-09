<template>
    <header>
        <h1>Ciao Mondo!!!</h1>
        <div class="background-image"></div>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComponent',
        data() {
            return {

            }
        }
        
    }
</script>

<style scoped>
    h1 {
        
        
        width: 100%;
        z-index: 10;
        margin: 0;
        padding: 20px;
        
    }
    header{position: fixed;
        top:0;
        left:0;
        width: 100%;
        z-index: 100;

}
header .background-image {
position: absolute;
top: 0;

width: 100%;
height: 100%;
z-index: -1;
/* -webkit-filter: blur(5px);
-moz-filter: blur(5px);
-o-filter: blur(5px);
-ms-filter: blur(5px); */
 /* filter: blur(20px); */
 background-color: rgba(0, 150, 150, 0.3);
 backdrop-filter: blur(30px);

}
</style>