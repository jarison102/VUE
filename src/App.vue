

<script setup>
const Name="Vue Dinamico";

var Nombre = "Jarison";
if(Nombre === "Jarison"){
   alert("Hola Soy Jarison")
}else{
   alert ("No es Jarison")
}

</script>


<template>
  <h1>H1 {{ Name }}</h1>
</template>

<style>
h1{
  color:red
}
</style>