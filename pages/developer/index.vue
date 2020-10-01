<template>
  <div class="has-text-light">
    <section class="hero is-medium is-bold developer-1">
      <div class="hero-body">
        <div class="container">
          <h1 class="title has-text-light">
            Developer
          </h1>
          <h2 class="subtitle has-text-light">
            Both my hobby and profession
          </h2>
        </div>
      </div>
    </section>
    <section class="section has-background-dark">
      <div class="container">
        Developer
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'DeveloperPage'
}
</script>

<style scoped>
.developer-1 {
  background-image: url('/developer1.png');
  background-size: cover;
  background-position-y: 50%;
}
</style>
