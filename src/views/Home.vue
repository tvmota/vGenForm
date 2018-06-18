
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import GenHeader from '@/components/header/GenHeader'
import GenFooter from '@/components/footer/GenFooter'

export default {
  name: 'home',
  components: {
    HelloWorld,
    GenHeader,
    GenFooter
  }
}
</script>
<template>
  <div class="grid-main">
    <header role="header">
      <gen-header></gen-header>
    </header>
    <main>
      <router-view></router-view>
    </main>
    <footer>
      <gen-footer></gen-footer>
    </footer>
  </div>
</template>
