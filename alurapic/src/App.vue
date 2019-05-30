<template>
  <div>
    <h1>{{ titulo }}</h1>
    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo" />
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      titulo: 'Alurapic',
      fotos: [
        {
          url: 'https://www.portaldodog.com.br/cachorros/wp-content/uploads/2017/01/3-doen%C3%A7as-que-todo-tutor-de-Dachshund-deve-prestar-mais-aten%C3%A7%C3%A3o-pdd1-500x357.jpg',
          titulo: 'cachorro 1'
        },
        {
          url: 'https://abrilsuperinteressante.files.wordpress.com/2018/05/filhotes-de-cachorro-alcanc3a7am-o-c3a1pice-de-fofura-com-8-semanas1.png',
          titulo: 'cachorro 2'
        }
      ]
    }
  }
}
</script>

<style>
</style>