<template>
  <div>
    <section class="hero is-medium is-bold music-1">
      <div class="hero-body">
        <div class="container">
          <h1 class="title has-text-light">
            Music
          </h1>
          <h2 class="subtitle has-text-light">
            Emotional creation at its best
          </h2>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="columns">
          <div class="column">
            My previously released music can be found on the following services:
          </div>
          <div class="column">
            <b-message type="is-success">
              <a href="https://open.spotify.com/artist/5R9Upj7DCtU8VBTPKnAx2i">
                Spotify
              </a>
            </b-message>
            <b-message type="is-danger">
              <a
                href="https://music.apple.com/us/artist/swen-van-zanten/1227256117"
              >
                Apple Music
              </a>
            </b-message>
            <b-message>
              <a
                href="https://play.google.com/store/music/album/Swen_Van_Zanten_Earth?id=Beyfobjz5qmoe242ov3lvxf6yoy"
              >
                Google Play/YouTube
              </a>
            </b-message>
            <b-message type="is-warning">
              <a
                href="https://www.amazon.com/gp/product/B075HPDKQT/?tag=distrokid06-20"
              >
                Amazon Music
              </a>
            </b-message>
            <b-message type="is-primary">
              <a href="https://www.deezer.com/nl/artist/12314014">
                Deezer
              </a>
            </b-message>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'MusicPage'
}
</script>

<style scoped>
.music-1 {
  background-image: url('/music1.jpg');
  background-size: cover;
  background-position-y: 30%;
}
</style>
