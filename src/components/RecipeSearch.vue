<template>
  <v-form action="searchForRecipes()" method="get">
    <v-container>
      <v-row d-inline-flex justify-center align-items="center">
        <v-col offset="3" cols="4">
          <v-text-field id="searchText" name="searchText" label="Find Recipes" solo />
        </v-col>
        <v-col cols="2">
          <v-btn type="submit">Search</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-form>
</template>

<script>
export default {
  name: 'RecipeSearch'
}
</script>

<style>
</style>
