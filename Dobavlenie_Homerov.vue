<template>
    <div class="box2">
        <h1>
            <button class="but">Номер 1</button>
            <button class="but">Номер 2</button>
            <button class="but">Добавить</button>
            <button class="Exit">X</button>
        </h1>
        <h1>
            <h2 class="t3">Название <input type="text" size="20"></h2>
            <h2 class="t5">
                Статус: <select name="select" size="1" multiple>
                <option selected value="s1">Свободен</option>
                <option value="s2">Занят</option>
            </select>
            </h2>
            <h2 class="t3">Стоймость <input type="text" size="19"></h2>
            <h2 class="t4">Вместимость <input type="text" size="20"></h2>
            <h2 class="t3">Дата заезда <input type="text" size="19"></h2>
            <h2 class="t4">Дата выезда <input type="text" size="20"></h2>
        </h1>
    </div>
</template>

<script>
    export default {
        name: "Dobavlenie_Homerov"
    }
</script>

<style scoped>
.box2{
    display: none;
    margin-left: 30%;
    margin-top: 5%;
    width: 40%;
    height: 280px;
    border-color: #6f00ff;
    background-color: #8e31ff;
    color:rgb(255, 237, 237);
    border-width: 2px;
}

.Exit{
    background-color:#8e31ff;
    color:aliceblue;
    border-color:#8725ff;
    float: right;
    width:5%;
}

.but{
    background-color:#8e31ff;
    color:aliceblue;
    border-color:#8725ff;
    width:31%;
}

.t3{
    float: left;
    height: 20px;
    font-size: 18px;
    margin-left: 5%;
    margin-top: 5%;
}

.t4{
    float: right;
    height: 20px;
    font-size: 18px;
    margin-right: 5%;
    margin-top: 5%;
}

.t5{
    float: right;
    height: 20px;
    font-size: 18px;
    margin-right: 28%;
    margin-top: 5%;
}
</style>