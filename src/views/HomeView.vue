<template>
  <div class="home">
    <HelloWorld />
    <Feed />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/Header.vue";
import Feed from "@/components/FeedComponent.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    Feed,
  },
};
</script>
