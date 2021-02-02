<template>
    <div class="galeria">
        <div class="titulo">
            <h2>Galeria</h2>
        </div>
        <div class="imagenes">
            <div class="img">
                <picture>
                    <!-- <img src="../assets/logos/instagram_logo.png" alt="logo_instagram"> -->
                </picture>
            </div>
            <div class="img">
                <img src="" alt="">
            </div>
            <div class="img">
                <img src="" alt="">
            </div>
            <div class="img">
                <img src="" alt="">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'galeria'
    }
</script>

<style scoped>
.galeria {
    display: flex;
    width: 100vw;
    height: 30vh;
    background: rebeccapurple;
    border: 2px solid black;
    flex-wrap: wrap;

}
.titulo {
    justify-content: center;
    width: 100%;
    height: 21%;
    border: 2px solid red;
    display: flex;

}
.imagenes {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border: 2px solid red;
    width: 100%;
    height: 70%;
    flex-wrap: wrap;
    padding: 0.3vw;

}
.img {
    width: 21%;
    height: 90%;
    border: 2px solid black;
    padding: 3%;

}

</style>