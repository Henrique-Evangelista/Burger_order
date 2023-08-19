<template>
  <div>
    <Banner/>
    <div class="main-container">
      <h1>Monte seu burguer</h1>
      <Formulario/>
    </div>
  </div>
</template>

<script>
import Formulario from '@/components/Formulario.vue';
import Banner from '@/components/Banner.vue';
export default{
  name:"Home",
  components: {
    Banner,
    Formulario,
  }
}
</script>
