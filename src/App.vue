<template>
  <div class="container-fluid">
    <NavBar></NavBar>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>

<style src="./assets/bootstrap/css/bootstrap.min.css"></style>

<style>
:root{
    --Color-1: #f7f7f7;
    --Color-2: #2cc295;
    --Color-2: #03624c;
    --Color-3: #00df82;
    --Color-4: #042222;
    --Color-5: #021a1a;
}

.container-fluid{
    background-color: var(--Color-1);
}
</style>
