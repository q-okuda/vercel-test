<script setup>
defineProps({
  testTxt: {
    type: String,
  }
});
</script>

<template>
  <p class="part-testTxt">{{ testTxt }}</p>
</template>