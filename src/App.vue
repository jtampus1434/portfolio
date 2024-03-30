<template>
  <HeaderFile></HeaderFile>
  <BodyContent></BodyContent>
  <FooterGaw></FooterGaw>
</template>

<script>
import HeaderFile from './components/HeaderFile.vue'
import BodyContent from './components/BodyContent.vue'
import FooterGaw from './components/FooterGaw.vue'

export default {
  name: 'App',
  components: {
    HeaderFile,
    BodyContent,
    FooterGaw
  }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
