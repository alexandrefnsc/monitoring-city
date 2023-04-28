<template>
  <section>
    <Hero />
    <Sobre />
    <ComoFunciona />
    <Sistema />
    <Servicos />
    <Lista />
    <Footer />
  </section>
</template>
<script>
  import Hero from './components/hero.vue'
  import Sobre from './components/sobre.vue'
  import ComoFunciona from './components/como-funciona.vue'
  import Sistema from './components/sistema.vue'
  import Servicos from './components/servicos.vue'
  import Lista from './components/lista.vue'
  import Footer from './components/footer.vue'

  export default{
    name: 'App',
    components:{
      Hero,
      Sobre,
      ComoFunciona,
      Sistema,
      Servicos,
      Lista,
      Footer,
    }
  }
</script>