<template>
  <section class="bg-neutral-100 py-10">
    <div class="lg:w-10/12 px-5 lg:px-0 mx-auto grid lg:grid-cols-2 gap-5 items-center">
      <div class="p-10">
        <img src="images/woman-01.png" alt="">
      </div>
      <div>
        <h1 class="text-3xl font-bold mb-3">Como utilizar o <span class="text-red-600">MONITORING CITY?</span></h1>
        <div class="space-y-3 my-5">
          <p>A equipe fará o registro das informações no aplicativo, inserindo coordenadas do local e foto.</p>
          <p>Simultaneamente é criado um banco de dados em categorias de serviços, facilitando a definição das ações pelo gestor, alcançando metas e resultados para o condomínio.</p>
        </div>
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
    name: 'ComoFunciona',
    components:{
      btn_cta,
    }
  }
</script>