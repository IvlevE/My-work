<template>
    <table class="Norm">
        <thead class="table1">
            <tr>
                <th class="Up" v-for="item in headers" :key="item">{{item}}</th>
            </tr>
        </thead>
        <tbody class="Nomber">
            <tr class="True1" v-for="row in content" :key="row">
                <td v-for="item in row" :key="item">{{item}}</td>
            </tr>
        </tbody>
    </table>
</template>

<script>
    export default {
        name: "Tablisa_Homerov",
        props: ['headers','content']
    }
</script>

<style scoped>
    .Up{
        background-color: #9655ff;
    }

    .Norm{
        width:100%;
        height: 100%;
    }

    .True1{
        background-color: #b67bff;
        color: #b67bff;
    }

    .table1{
        display: -ms-flexbox;
        margin-left: 23%;
        margin-top: 5%;
        border-color: #6f00ff;
        background-color: #8e31ff;
        color:rgb(255, 237, 237);
        border-width: 2px;
    }

    .Nomber{
        background-color: #ae6efd;
        color: rgb(255, 237, 237);
        width: 100%;
    }
</style>