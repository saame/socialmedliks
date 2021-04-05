<template>
  <div class="home">
    <carousel />
    <Links msg="Welcome You to" />
  </div>
</template>

<script>
// @ is an alias to /src
import Links from "@/components/Links.vue";
import carousel from "@/components/carousel.vue";

export default {
  name: "Home",
  components: {
    carousel,
    Links,
  },
};
</script>
