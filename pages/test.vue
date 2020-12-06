<template>
  <h1 class="red">Hello {{ name }}!</h1>
</template>

<script>
export default {
  //  The “data” option should be a function that returns a per-instance value in component definitions.
  data() {
    return {
      language: ['English', 'Japaese'],
      name: 'Hello Vue!',
    }
  },
}
</script>

<style>
.red {
  color: red;
}
</style>
