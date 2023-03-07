<template>
    <div class="card-person">
        <img class="card-person__img" src="@/assets/goku.jpg">

        <p class="card-person__name">Goku solo con CSS</p>

        <span class="card-person__anime">Dragon Ball Z</span>

        <div class="card-person__controls">
            <button class="card-person__controls__btn color-celeste">Invitar</button>
            <button class="card-person__controls__btn">Pasar</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CardPerson'
}
</script>

<style lang="css" scoped>
.card-person {
    border: 1px solid;
    width: 236px;
    padding: 2em;
    margin: 2em auto;
    text-align: center;
    border-radius: 10px;
    border-color: #7f8c8d;
}

.card-person__img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

.card-person__name {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 0px;
}

.card-person__anime {
    display: block;
    font-size: 12px;
    color: #7f8c8d;
    margin-bottom: 1em;
}

.card-person__controls {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.card-person__controls__btn {
    padding: 5px 20px 5px 20px;
    background-color: #27ae60;
    border: none;
    color: white;
    border-radius: 1em;
    font-size: 1em;
}

.color-celeste {
    background-color: #2980b9;
}
</style>