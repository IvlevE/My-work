<template>
  <Head_in_Header></Head_in_Header>
  <Vhod_V_Accaunt></Vhod_V_Accaunt>
  <Dobavlenie_Homerov></Dobavlenie_Homerov>
  <Tablisa_Homerov></Tablisa_Homerov>

</template>

<script>
import Head_in_Header from "@/components/Head_in_Header";
import Vhod_V_Accaunt from "@/components/Vhod_V_Accaunt";
import Dobavlenie_Homerov from "@/components/Dobavlenie_Homerov";
import Tablisa_Homerov from "@/components/Tablisa_Homerov";

export default {
  name: 'App',
  components: {
    Tablisa_Homerov,
    Dobavlenie_Homerov,
    Vhod_V_Accaunt,
    Head_in_Header,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
