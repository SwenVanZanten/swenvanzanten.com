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
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
                ac imperdiet odio. Sed eget elit eleifend, faucibus nisi
                vulputate, accumsan urna. Vivamus porttitor porttitor ipsum, id
                finibus urna. Fusce feugiat accumsan vehicula. Vestibulum sit
                amet orci mi. Pellentesque posuere nulla posuere tellus
                tincidunt placerat.
              </p>
            </article>
          </div>
          <div class="column">
            <b-menu>
              <b-menu-list label="More specific">
                <b-menu-item label="Developer" />
                <b-menu-item label="Music" />
                <b-menu-item label="Snowboarding" />
                <b-menu-item label="Airsoft" />
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
  background-image: url('/portret1.png');
  background-size: cover;
}
</style>
