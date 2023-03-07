<template>
    <div class="card-portada">
        <img class="card-portada__img" src="@/assets/bg_night.jpg">

        <div class="card-portada__content">
            <img class="card-portada__content__img" src="@/assets/goku.jpg">

            <p class="card-portada__content__name">Goku</p>

            <div class="card-portada__content__reporte">
                <div class="card-portada__content__reporte__items">
                    <p class="card-portada__content__reporte__items__number">20</p>
                    <p class="card-portada__content__reporte__items__text">Artículos</p>
                </div>
                <div class="card-portada__content__reporte__items">
                    <p class="card-portada__content__reporte__items__number">5</p>
                    <p class="card-portada__content__reporte__items__text">Proyectos</p>
                </div>
                <div class="card-portada__content__reporte__items">
                    <p class="card-portada__content__reporte__items__number">2</p>
                    <p class="card-portada__content__reporte__items__text">Años Experiencia</p>
                </div>
            </div>

            <div class="card-portada__content__controls">
                <button class="card-portada__content__controls__btn">Conectar</button>
                <button class="card-portada__content__controls__btn">Ver más</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CardPortada'
}
</script>

<style lang="scss" scoped></style>