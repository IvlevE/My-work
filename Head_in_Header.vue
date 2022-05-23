<template>
    <div class="head1">
        <header>Сереневый закат</header>
        <a>Рассписание</a>
        <a>Номера</a>
        <p>Аккаунт</p>
    </div>
</template>

<script>
    export default {
        name: "Head_in_Header"
    }
</script>

<style scoped>
.head1{
    background-color: #9655ff;
    display: static;
    overflow: auto;
}

a{
    float: left;
    color: rgb(255, 237, 237);
    text-align: center;
    padding: 19px 50px;
    text-decoration: none;
    font-size: 22px;
}

header{
    float: left;
    margin-left: 18%;
    color: rgb(255, 237, 237);
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 27px;
}

p{
    color: rgb(255, 237, 237);
    text-align:center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 27px;
    margin: 0;
}
</style>