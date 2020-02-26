<template>
  <div id="app">
    <main class="container">
      <the-header></the-header>
      <section class="row">
        <div class="col-sm-6">
          <the-card></the-card>
        </div>
        <div class="col-sm-6">
          <the-card></the-card>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
import TheHeader from "./components/TheHeader";
import TheCard from "./components/TheCard";

export default {
  name: "App",
  components: {
    TheHeader,
    TheCard
  }
};
</script>

<style>
@import "https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css";
</style>

