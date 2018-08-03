<template>
    <div>
      <h1 v-text="titulo"></h1>
      <img :src="foto.url" :alt="foto.alt"/>
    </div>
</template>

<script>
export default {
  data(){
    return {
      titulo: 'AluraPic',
      foto: {
        url: 'http://tudosobrecachorros.com.br/wp-content/uploads/cachorro-independente.jpg',
        alt: 'Cachorro'
      }
    }
  }
}
</script>

<style>

</style>
