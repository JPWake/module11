<template>
  <div id="app">
    <h1>Oops!</h1>
    <p>Sorry, This page doesn't exist!</p>
    <div id="button">
      <div id="vertical-center">
        <GoBack />
      </div>
    </div>
  </div>
</template>

<style scoped>
button {
  padding: 12px 32px;
  font-size: 16px;
  border-radius: 8px;
}
</style>

<script>
import GoBack from "@/components/GoBack.vue";

export default {
  components: { GoBack },
};
</script>
