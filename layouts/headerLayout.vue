<template>
  <b-navbar type="is-warning" spaced shadow>
    <template slot="brand">
      <b-navbar-item :to="{ path: '/' }" tag="nuxt-link">
        <img src="~/assets/swenvanzanten.png" alt="Swen van Zanten" />
      </b-navbar-item>
    </template>
    <template slot="start">
      <template v-for="page in pages">
        <b-navbar-item
          v-if="page.enabled"
          :to="page.path"
          :active="$route.path === page.path"
          tag="nuxt-link"
        >
          {{ page.name }}
        </b-navbar-item>
      </template>
    </template>

    <template slot="end">
      <b-navbar-item tag="div">
        <div class="buttons">
          <a class="button is-light" href="https://github.com/swenvanzanten">
            <b-icon icon="github" />
          </a>
          <a class="button is-light" href="https://twitter.com/swenvanzanten">
            <b-icon icon="twitter" />
          </a>
        </div>
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {
  name: 'HeaderLayout',

  props: {
    pages: {
      type: Array,
      required: true
    }
  }
}
</script>

<style>
@media screen and (min-width: 1024px) {
  .navbar.is-spaced {
    min-height: 5.25rem;
  }
}
</style>
