<template>
  <div>
    <SearchForm @picturesReceived></SearchForm>
    <PictureResults></PictureResults>
  </div>
</template>

<script>
import SearchForm from "./components/SearchForm.vue";
import PictureResults from "./components/PictureResults.vue";
export default {
  components: {
    SearchForm,
    PictureResults
  }
};
</script>

<style>
body {
  background-color: seagreen;
  font-family: Georgia;
}
</style>
