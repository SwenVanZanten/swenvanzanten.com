<template>
  <div>
    <header-layout :pages="pages" />

    <section class="main-content">
      <nuxt />
    </section>

    <footer-layout />
  </div>
</template>

<script>
import FooterLayout from '@/layouts/footerLayout'
import HeaderLayout from '~/layouts/headerLayout'

export default {
  components: { FooterLayout, HeaderLayout },

  data() {
    return {
      pages: [
        {
          name: 'Me',
          path: '/',
          enabled: true
        },
        {
          name: 'Developer',
          path: '/developer',
          enabled: true
        },
        {
          name: 'Music',
          path: '/music',
          enabled: true
        },
        {
          name: 'Snowboarding',
          path: '/snowboarding',
          enabled: true
        },
        {
          name: 'Airsoft',
          path: '/airsoft',
          enabled: false
        }
      ]
    }
  }
}
</script>

<style>
html,
body,
#__nuxt,
#__layout,
#__nuxt > #__layout > div {
  height: 100%;
}

#__nuxt > #__layout > div {
  display: flex;
  flex-direction: column;
}

.main-content {
  flex: 1;
}
</style>
