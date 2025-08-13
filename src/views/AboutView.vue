<script setup lang="ts">
const mapName = "roslyn-peninsula";
</script>
<template>
  <main id="main-about">
    <section>
      <h1>About page</h1>
      <img v-bind:src="`/maps/${mapName}/${mapName}-top.png`" />
    </section>
  </main>
</template>
