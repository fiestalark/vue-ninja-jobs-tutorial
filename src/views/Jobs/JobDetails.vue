<template>
  <h1>Job Details Page</h1>
  <!-- The .id is whatever the parameter is called for that route on the index.js router -->
  <p>The job id is {{ id }}</p>
</template>

<script>
export default {
    data() {
        return {
            id: this.$route.params.id
        }
    }
}
</script>

<style>

</style>