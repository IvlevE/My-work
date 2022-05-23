<template>
    <div class="box1">
        <form @submit.prevent="login">
        <H5 class="dopbox"><button class="Exit">X</button></H5>
        <H1 class="t1">Вход в аккаунт</H1>
        <H3 class="t2">Логин <input required v-bind:value="login" @input="login = $event.target.value" type="text"
                                          placeholder="Login"> </H3>
        <H3 class="t2">Пороль <input required v-bind:value="password" @input="password = $event.target.value" type="password"
                                           placeholder="Password"> </H3>
            <v-button class="OK" @click="checkLogin" type="submit">Войти</v-button>
        </form>
    </div>
</template>

<script>
    export default {
        name: "Vhod_V_Accaunt",
        data(){
            return{
                login:'',
                password:''
        }
    },
    methods: {
        checkLogin() {
            if ((this.login == "admin") && (this.password == "admin")) {
                this.style.class.display = 'none';
            } else {
                alert("Неверный логин/пароль!")
            }
        }
    }
}
</script>

<style scoped>
.box1{
    display: -ms-flexbox;
    margin-left: 30%;
    margin-top: 5%;
    width: 40%;
    border-color: #6f00ff;
    background-color: #8e31ff;
    color:rgb(255, 237, 237);
    border-width: 2px;
    text-align: center;
}

.dopbox{
    height: 20px;
}

.t1{
    font-size: 23px;
    height: 60px;
}

.t2{
    font-size: 18px;
    height: 50px;
}

.OK{
    background-color:#ae6efd;
    color:aliceblue;
    border-color: #8725ff;
}

.Exit{
    background-color:#8e31ff;
    color:aliceblue;
    border-color:#8725ff;
    float: right;
    width:5%;
}
</style>