<template>
  <section class="bg-neutral-100 py-10">
    <div class="lg:w-10/12 mx-auto px-5 lg:px-0">
      <div class="grid lg:grid-cols-2 gap-2 items-center">
        <div>
          <img src="images/logo.png" alt="" class="w-3/12 lg:w-2/12 mb-5">
          <h1 class="text-2xl lg:text-4xl font-bold mb-3">Conheça o sistema que vai melhorar <span class="text-red-600">o planejamento e gestão do condomínio</span></h1>
          <p>Apresento a plataforma Monitoring City que auxilia no mapeamento de serviços e demandas</p>
          <div class="lg:w-8/12 mt-8">
            <btn_cta/>
          </div> 
        </div>
        <div>
          <img src="images/hero-person.png" alt="">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  import btn_cta from './btn-cta.vue'
  export default{
    name: 'Hero',
    components:{
      btn_cta,
    }
  }
</script>