<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" height="100px">
    <div>DIT355 Client</div>
    <h1>City Traffic Helper</h1>
    <p>temporary name</p>
    <h5>Hey guys don't forget to come up with a cool name for our project!</h5>
    <clock :blink="true"></clock>
    <h4>The clock above is a placeholder-like component just for padding this homepage :)</h4>
  </div>
</template>

<script>
// @ is an alias to /src
import Clock from '@/components/Clock.vue'
export default {
  name: 'home',
  components: {
    Clock
  }
}
</script>
