<template>
  <div>
    <section class="hero is-medium is-bold portret-1">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Me,
          </h1>
          <h2 class="subtitle">
            Myself and I
          </h2>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="columns">
          <div class="column">
            <article class="content">
              <p>
                Hi my name is <strong>Swen van Zanten</strong> and you've
                reached the placeholder response for
                <strong>GET</strong> requests on
                <strong>https://swenvanzanten.com</strong> over port
                <strong>80</strong>.
              </p>
              <p>
                Sorry, soon more info...
              </p>
            </article>
          </div>
          <div class="column">
            <b-menu>
              <b-menu-list label="More specific">
                <b-menu-item
                  label="Developer"
                  to="/developer"
                  tag="nuxt-link"
                />
                <b-menu-item label="Music" to="/music" tag="nuxt-link" />
                <b-menu-item
                  label="Snowboarding"
                  to="/snowboarding"
                  tag="nuxt-link"
                />
                <!--<b-menu-item label="Airsoft" to="/airsoft" tag="nuxt-link" />-->
              </b-menu-list>
            </b-menu>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'MePage'
}
</script>

<style scoped>
.portret-1 {
  background-image: url('/portret1.jpg');
  background-size: cover;
}
</style>
