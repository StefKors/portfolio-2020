<template>
  <article>
    <Markdown class="introduction" :file="require('./explainer.md')" />
  </article>
</template>

<script>
export default {
  name: "artist-websites"
}
</script>

<style lang="scss" scoped>


.header {
  margin-top: 20vh;
  font-family: "Unna", sans-serif;
  font-weight: 700;
  font-style: normal;
  line-height: 1.2em;
  font-size: 2.5rem;
  text-transform: none;
  text-decoration: none;
  letter-spacing: 0px;
}

</style>