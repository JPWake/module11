<template>
  <div class="about">
    <h1>About This Site</h1>
    <p>
      The API Ninjas Facts API is provides tons of random interesting facts
      about science, literature, philosophy and other cool topics.
    </p>
    <p>
      Get endless interesting facts at the tap of a button! Interested in the
      details on how it was made? Check it out at
      <a href="https://api-ninjas.com/api/facts">
        https://api-ninjas.com/api/facts</a
      >
    </p>
    <p>
      This little website is made in Vue v3 to demonstrate materials learned in
      Module 11.
    </p>
  </div>
  <GoBack />
</template>

<script>
import GoBack from "@/components/GoBack.vue";

export default {
  components: { GoBack },
};
</script>
