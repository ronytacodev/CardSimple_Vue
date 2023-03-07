<template>
    <div class="card-person">
        <img class="card-person__img" src="@/assets/goku.jpg">

        <p class="card-person__name">Goku con Sass</p>

        <span class="card-person__anime">Dragon Ball Z</span>

        <div class="card-person__controls">
            <button class="card-person__controls__btn celeste">Invitar</button>
            <button class="card-person__controls__btn">Pasar</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CardPersonSass'
}
</script>

<style lang="scss" scoped>
.card-person {
    border: 1px solid;
    margin: 2em auto;
    width: 236px;
    padding: 2em;
    border-radius: 10px;
    border-color: #7f8c8d;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    &__img {
        width: 100px;
        height: 100px;
        border-radius: 50%;
    }

    &__name {
        font-size: 18px;
        font-weight: bold;
        margin-bottom: 0px;
    }

    &__anime {
        font-size: 12px;
        color: #7f8c8d;
        margin-bottom: 1em;
    }

    &__controls {
        width: 100%;
        display: flex;
        justify-content: space-around;

        &__btn {
            padding: 5px 20px 5px 20px;
            background-color: #27ae60;
            border: none;
            color: white;
            border-radius: 1em;
            font-size: 1em;

            &.celeste {
                background-color: #2980b9;
            }
        }
    }
}
</style>