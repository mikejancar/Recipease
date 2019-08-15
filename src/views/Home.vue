<template>
  <v-content>
    <h1>Welcome to Recipease</h1>
    <RecipeSearch />
  </v-content>
</template>

<script>
import RecipeSearch from '@/components/RecipeSearch.vue';

export default {
  name: 'Home',
  components: {
    RecipeSearch
  }
}
</script>

