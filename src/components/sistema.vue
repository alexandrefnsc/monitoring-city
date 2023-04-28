<template>
  <section class="bg-neutral-100 py-10">
    <div class="lg:w-10/12 px-5 lg:px-0 mx-auto grid lg:grid-cols-2 gap-5 items-center">
      <div class="order-first lg:order-last p-10">
        <img src="images/celular-01.png" alt="">
      </div>
      <div>
        <h1 class="text-xl font-bold mb-5">Esse sistema permite planejar as atividades, conforme os recursos disponíveis: mão de obra, materiais, equipamentos ou contratação de empresa terceirizada.</h1>
        <div class="lg:w-8/12">
          <btn_cta/>
        </div>
      </div>
    </div>
  </section>
</template>
<script lang="ts">
  import btn_cta from './btn-cta.vue'
  export default{
    name: 'Sistema',
    components:{
      btn_cta,
    }
  }
</script>