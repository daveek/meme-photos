<template>
  <div class="avenir">
    <Header />
    <Memes msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Memes from '@/components/Memes.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    Memes,
    Header
  }
}
</script>
