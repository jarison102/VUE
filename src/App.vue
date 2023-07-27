

<script setup>
const Name="Vue Dinamico";

var Nombre = "Jarison";
if(Nombre === "Jarison"){
   alert("Hola Soy Jarison");
}else{
   alert ("No es Jarison");
}

const Names = ["Jarison","STIVED","HU","YI","YASUO","VUE","JAVASCRIPT"];
</script>


<template>
  <h1>H1 {{ Name }}</h1>
  <ul>
    <li v-for="(Nombres ,index) in Names ">{{ index }} - {{ Names }}</li>
  </ul>
</template>

<style>
h1{
  color:red
}
</style>