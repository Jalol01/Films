<template>
  <Box class="app-info">
    <p class="fs-3 text-upparcase">Barcha kinolar soni: {{allMoviesCount}}</p>
    <p class="fs-4 text-upparcase">Ko`rilgan kinolar soni: {{favouriteMoviesCount}}</p>
  </Box>
</template>

<script>
export default {
    props:{
      allMoviesCount:{
        type: Number,
        required: true
      },
      favouriteMoviesCount:{
        type: Number,
        required: true,
      }
    }
}
</script>

<style scoped>


</style>