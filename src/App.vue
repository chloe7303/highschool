<template lang="pug">
#app
  Top
  #content
    #left
      Menu
      Update
    #right
      Mar
      Main
  Footer
</template>

<script>
import Top from './components/Top.vue'
import Menu from './components/Menu.vue'
import Update from './components/Update'
import Mar from './components/Mar'
import Main from './components/Main'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Top,
    Menu,
    Update,
    Mar,
    Main,
    Footer
  }
}
</script>
