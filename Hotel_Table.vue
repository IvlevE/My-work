<template>
    <div>
        <table :Headers="tableHeads" :content="tableContent"></table>
    </div>
</template>

<script>

    export default {
        data(){
            return{
                tableHeads:[
                    'Дата и номер',Date.now()-3,Date.now()-2,Date.now()-1,Date.now(),Date.now()+1,Date.now()+2,Date.now()+3
                ],
                tableContent:[
                    ['Номер 1','True','False','False','True','False','True','True'],
                    ['Номер 2','False','False','False','True','False','False','True']
                ]
            }
        }
    }
</script>

<style scoped>

</style>