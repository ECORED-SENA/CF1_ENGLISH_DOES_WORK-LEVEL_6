<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.mb-5
      .col.mb-4.mb-lg-0
        Traduccion.color-primario(:dialogo="traduccion1")
      .col-auto
        figure
          img(src='@/assets/curso/intro/img1.png')
    p.mb-5 Se invita a explorar el video que se presenta a continuación:
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
</template>

<script>
import DialogoChat from '../components/DialogoChat.vue'
import Traduccion from '../components/Traduccion.vue'
export default {
  name: 'Introduccion',
  components: {
    Traduccion,
    DialogoChat,
  },
  data: () => ({
    traduccion1: {
      dialogo: [
        {
          textoIng:
            '<em>In general terms, it can be pointed out that the content of this training component is very useful, since it deals with the function of the present perfect tense of verbs, its form and pronunciation, using concrete and simple examples that will allow the practice of these grammatical structure, which also make it easier to express lived experiences and use expressions of time.</em>',
          textoEsp:
            'En líneas generales, puede señalarse que el contenido de este componente formativo resulta de gran utilidad, porque aborda la función del tiempo presente perfecto de los verbos, su forma y pronunciación, utilizando ejemplos concretos y sencillos que van a permitir la práctica de esta estructura gramatical, que además facilita expresar las experiencias vividas y usar expresiones de tiempo.',
        },
      ],
    },
  }),
}
</script>

<style lang="sass"></style>
