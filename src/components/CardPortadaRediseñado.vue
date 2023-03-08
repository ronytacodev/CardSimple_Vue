<template>
    <div class="card-portada">
        <img class="card-portada__img" src="@/assets/bg_night.jpg">

        <div class="card-portada__content">

            <v-card-image-name />

            <div class="card-portada__content__report">
                <div class="card-portada__content__report__items">
                    <p class="card-portada__content__report__items__number">20</p>
                    <p class="card-portada__content__report__items__text">Artículos</p>
                </div>
                <div class="card-portada__content__report__items">
                    <p class="card-portada__content__report__items__number">5</p>
                    <p class="card-portada__content__report__items__text">Proyectos</p>
                </div>
                <div class="card-portada__content__report__items">
                    <p class="card-portada__content__report__items__number">2</p>
                    <p class="card-portada__content__report__items__text">Años Experiencia</p>
                </div>
            </div>

            <div class="card-portada__content__controls">
                <v-button-primary />
                <button class="card-portada__content__controls__btn">Ver más</button>
            </div>
        </div>
    </div>
</template>

<script>

import VCardImageName from '@/components/template/VCardImageName'
import VButtonPrimary from '@/components/template/VButtonPrimary'

export default {
    name: 'CardPortadaRediseñado',
    components: {
        VCardImageName,
        VButtonPrimary
    }
}
</script>

<style lang="scss" scoped>
.card-portada {
    border: 1px solid;
    width: 100%;
    height: 400px;
    position: relative;
    display: flex;
    justify-content: center;

    &__img {
        width: 100%;
        height: 100%;
    }

    &__content {
        position: absolute;
        top: 0px;
        left: 0px;
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        &__report {
            border-top: 3px solid white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;

            &__items {
                // border: 1px solid white; this line serves to model
                width: 100px;
                // height: 100px;
                color: white;

                &__number {
                    font-weight: bold;
                }

                &__text {
                    font-size: 12px;
                }
            }
        }

        &__controls {
            &__btn {
                background: #27ae60;
                padding: 5px 2em 5px;
                color: white;
                margin: 5px;
                border: none;
                border-radius: 1em;
            }
        }
    }

}
</style>