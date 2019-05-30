<template>
  <div>
    <h1>{{ titulo }}</h1>
    <img :src="foto.url" :alt="foto.titulo" />
  </div>
</template>

<script>
export default {
  data () {
    return {
      titulo: 'Alurapic',
      foto: {
        url: 'https://www.portaldodog.com.br/cachorros/wp-content/uploads/2017/01/3-doen%C3%A7as-que-todo-tutor-de-Dachshund-deve-prestar-mais-aten%C3%A7%C3%A3o-pdd1-500x357.jpg',
        titulo: 'cachorro'
      }
    }
  }
}
</script>

<style>
</style>