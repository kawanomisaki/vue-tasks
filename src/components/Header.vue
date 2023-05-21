<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: "App",
  props: {
    title: {
      type: String,
    }
  }
}
</script>

<style scoped>
/* scoped measn this style applies to only this component */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
