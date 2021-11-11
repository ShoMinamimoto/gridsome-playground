<template>
  <Layout>
    <p>Dice go here.</p>
    <p class="dice text-5xl">1 2 3 4 5 6</p>
    <p class="dice text-5xl">6_ON_D12 ACE_HEARTS</p>
  </Layout>
</template>

<script>
export default {
  name: "DicePlayground"
}
</script>

<style scoped>
  .dice{
    font-family: Dicier-Round, sans-serif;
    font-weight: 700;
    font-feature-settings: "ss03", "cv31";
  }
</style>