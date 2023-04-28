<template>
  <section class="bg-neutral-100 py-10">
    <div class="lg:w-10/12 mx-auto px-5 lg:px-0">
      <h1 class="text-xl font-bold mb-5 text-center">A MONITORING CITY vai te ajudar nos seguintes serviços:</h1>
      <div class="grid lg:grid-cols-2 gap-5 my-5">
        <div class="text-center">
          <img src="images/servicos/tapa-buracos.png" alt="" class="rounded-2xl shadow-lg mb-5">
          <h2 class="text-xl font-bold uppercase">tapa-buraco</h2>
        </div>
        <div class="text-center">
          <img src="images/servicos/recolhimento-galhas.png" alt="" class="rounded-2xl shadow-lg mb-5">
          <h2 class="text-xl font-bold uppercase">recolhimento de galhas</h2>
        </div>
        <div class="text-center">
          <img src="images/servicos/pintura-meio-fio.png" alt="" class="rounded-2xl shadow-lg mb-5">
          <h2 class="text-xl font-bold uppercase">pintura de meio-fio</h2>
        </div>
        <div class="text-center">
          <img src="images/servicos/reforma-calcadas.png" alt="" class="rounded-2xl shadow-lg mb-5">
          <h2 class="text-xl font-bold uppercase">reforma de calçadas</h2>
        </div>
      </div>
      <p class="text-center">E muitos outros serviços para o seu condomínio</p>
      <div class="lg:w-8/12 mt-8 mx-auto">
        <btn_cta/>
      </div> 
    </div>
  </section>
</template>
<script lang="ts">
  import btn_cta from './btn-cta.vue'
export default {
  name:'Servicos',
  components:{
      btn_cta,
    }
}
</script>