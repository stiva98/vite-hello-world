<script>

export default {

  props: {
    title: String,
  }

}

</script>

<template>
  <h1>{{ title }}</h1>
</template>

<style scoped>
h1 {
  color: brown;
  text-align: center;
  margin: 0;
}
</style>
