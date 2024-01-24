<script setup lang="ts">
import Node from "@/assets/icons/node.png";
import Flutter from "@/assets/icons/flutter.png";
import Rust from "@/assets/icons/rust.png";
</script>

<template>
  <div>
    <h1 class="text-6xl mb-2">Adrian Bueno</h1>
    <div class="flex items-center">
      Desenvolvedor Full-Stack |
      <img class="h-10 mx-2" :src="Node" />
      Nodejs |
      <img class="h-10 mx-1" :src="Flutter" />
      Flutter |
      <img class="h-10 mx-2" :src="Rust" />
      Rust
    </div>
  </div>
</template>

<style scoped></style>
