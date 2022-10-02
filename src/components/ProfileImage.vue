<template>
    <img v-bind:src="image" class="profile" :alt="imageAlt" />
  </template>

<script setup>
    defineProps({
      image: {
        type: String,
        default:
          "https://cdns-images.dzcdn.net/images/artist/a423dd42b7394eeacc882be8ac633eee/500x500.jpg",
      },
      imageAlt: {
        type: String,
        default: "Snoop Dogg looking good!",
      },
    });
</script>

<style>

</style>