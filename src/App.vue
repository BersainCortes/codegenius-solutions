<template>
  <div class="container-fluid">
    <NavBar></NavBar>
    <SectionHome></SectionHome>
    <SectionServicios></SectionServicios>
    <SectionTecnologias></SectionTecnologias>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import SectionHome from './components/SectionHome.vue'
import SectionServicios from './components/SectionServicios.vue'
import SectionTecnologias from './components/SectionTecnologias.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    SectionHome,
    SectionServicios,
    SectionTecnologias
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
    padding: 0px;
    width: 100%;
}
</style>
