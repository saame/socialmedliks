<template>
  <b-carousel>
    <b-carousel-item v-for="(carousel, i) in carousels" :key="i">
      <section :class="`hero is-medium is-${carousel.color}`">
        <div class="hero-body has-text-centered">
          <h1 class="title">{{ carousel.text }}</h1>
        </div>
      </section>
    </b-carousel-item>
  </b-carousel>
</template>

<script>
export default {
  data() {
    return {
      carousels: [
        { text: "plan", color: "primary" },
        { text: "before", color: "info" },
        { text: "to start", color: "success" },
      ],
    };
  },
};
</script>
