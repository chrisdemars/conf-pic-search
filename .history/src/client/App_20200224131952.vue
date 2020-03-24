<template>
  <div>
    <SearchForm @picturesReceived="gotThosePics"></SearchForm>
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
  },
  methods: {
    gotThosePics() {
      console.log("gotThosePics");
};
</script>

<style>
body {
  background-color: seagreen;
  font-family: Georgia;
}
</style>
