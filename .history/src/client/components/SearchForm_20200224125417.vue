<template>
  <div>
    <h1>Conf Search</h1>
    <form>
      <label for="user">Username</label>
      <input type="text" id="user" />
      <label for="hashtag">Event Hashtag</label>
      <input type="text" id="hashtag" />
      <button type="submit" @click.prevent="getThosePics">
        Get those pics
      </button>
      <button>Clear</button>
    </form>
  </div>
</template>

<script>
import Search from "../services/Search";

export default {
  methods: {
    getThosePics() {
      Search.getSearch();
      console.log("getThosePics");
    }
  }
};
</script>
