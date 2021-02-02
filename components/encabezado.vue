<template>
    <div class="encabezado">
        <header>
            <!-- NOTE - Inicio del header, iconos y titulo -->
            <div class="header_uno">
                <div class="Titulo">
                    <h1>
                        <Nuxt-link to="/">
                            Screen Graft
                        </Nuxt-link>
                    </h1>
                </div>
                <div class="iconos">
                    Iconos redes sociales
                </div>
            </div>
            <!-- NOTE - Segunda fila logo y enlaces -->
        <div class="fila_dos">
            <div class="logo">
                <picture>
                    <!-- <img src="../assets/logos/screen_graft_logo.png" alt=""> -->
                </picture>
            </div>
        <div class="enlaces">
            <nav>
                <button>
                    <Nuxt-link to="/">Inicio</Nuxt-link>
                </button>
                <button>
                    <Nuxt-link to="sobremi">Sobre Mí</Nuxt-link>
                </button>
                <button>
                    <Nuxt-link to="portafolio">Portafolio</Nuxt-link>
                </button>
                <button>
                    <Nuxt-link to="mis_servicios">Servicios</Nuxt-link>
                </button>
            </nav>
        </div>
        </div>
        </header>
    </div>
</template>

<script>
    export default {
        name: 'encabezado'
    }
</script>

<style scoped>
.encabezado {
    display: flex;
    width: 100vw;
    height: 12vh;
    background: red;
}
.header_uno {
    display: flex;
    width: 100vw;
    height: 3vh;
    position: absolute;
    /* z-index: 10; */
    top: 0%;
    border: 2px solid white;
}
.Titulo {
    width: auto;
    position: relative;
    /* z-index: 20; */
    left: 40%;


}
.iconos {
    position: absolute;
    /* z-index: 30%; */
    right: 3vw;
    top: 3px;

}
.fila_dos {
    display: block;
    width: 100vw;
    border: 2px solid black;
    height: 12vh;
}
.logo {
    display: inline-flex;
    border: 2px solid black;
    position: relative;
    left: 3px;
    display: inline-flex;
    height: 12vh;
    width: 20%;
}
.enlaces {
    display: inline-flex;
    border: 2px solid black;
    position: absolute;
    width: 80%;
    height: 12vh;
    align-items: flex-end;
    justify-content: flex-end;

}
h1 {
    width: 50vw;
}

</style>