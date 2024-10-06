<script setup lang="ts">
import { CommonButton } from "@charles/ui";

const handleClick = () => {
  console.log("Bouton cliqué !");
};
</script>
<template>
  <main>
    <CommonButton @click="handleClick"> Cliquez-moi ! </CommonButton>
  </main>
</template>
