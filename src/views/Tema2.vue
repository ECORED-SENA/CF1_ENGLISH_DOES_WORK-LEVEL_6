<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 #[i Time expressions] / Expresiones de tiempo
    .row.mb-5(data-aos="fade-right")
      .col-lg-auto.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema2/img1.svg')
      .col-lg
        Traduccion.color-primario(:dialogo="traduccion1")
    p.mb-5.text-center A continuación, puede ver las expresiones de tiempo utilizando algunos ejemplos:
    .row.bg-color15.mb-5(data-aos="fade-left")
      .col-12.p-4
        .row.align-items-center
          .col-lg-3.d-none.d-lg-block
            figure
              img(src='@/assets/curso/tema2/img2.svg')
          .col-lg-9
            .tarjeta.tarjeta--blanca.p-4
              SlyderA(tipo="b")
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i Already]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion2")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img4.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>Claire and Susan have already finished  their work in the office.</em> / Claire y Susan han terminado ya su trabajo en la oficina.</p>"
                          :audio="require('@/assets/curso/tema2/10_1.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i Ever]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion3")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img5.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>Have you ever gone to that town?</em> / ¿Has ido alguna vez a ese pueblo?</p>"
                          :audio="require('@/assets/curso/tema2/10_2.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i For]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion4")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img6.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>Robert has lived in New York for many years.</em> / Robert ha vivido en New York por muchos años.</p>"
                          :audio="require('@/assets/curso/tema2/10_3.wav')"
                       )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i How long]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion5")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img7.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>How long has Cheryl swum in the pool?</em> / ¿Cuánto tiempo ha nadado Cheryl en la piscina?</p>"
                          :audio="require('@/assets/curso/tema2/10_4.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i Just]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion6")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img8.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>I have just finished cooking the turkey for dinner.</em> / Apenas he terminado de cocinar el pavo para la cena.</p>"
                          :audio="require('@/assets/curso/tema2/10_5.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i Recently]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion7")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img9.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>Mr. Montero has recently bought a yacht.</em> / El señor Montero ha comprado recientemente un yate.</p>"
                          :audio="require('@/assets/curso/tema2/10_6.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i Since]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion8")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img10.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>Mr. Gómez has worked at that institute since 1998.</em> / El Sr. Gómez ha trabajado en ese instituto desde 1998.</p>"
                          :audio="require('@/assets/curso/tema2/10_7.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i So far / Up to now]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion9")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img11.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>That band has performed in this theater so far.</em> / Esa banda se ha presentado en este teatro hasta ahora.</p>"
                          :audio="require('@/assets/curso/tema2/10_8.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i Still]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion10")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img12.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>Monique still hasn’t washed the dishes.</em> / Monique todavía no ha lavado los platos.</p>"
                          :audio="require('@/assets/curso/tema2/10_9.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i Yet]]
                    Traduccion.color-primario.mb-4(:dialogo="traduccion11")
                    .row.align-items-center
                      .col-lg-auto
                        figure.mb-lg-3
                          img(src='@/assets/curso/tema2/img13.svg')
                      .col-lg
                        p.mb-3 #[i For example:] / Por ejemplo:
                        TarjetaAudio.color-primario(
                          texto="<p><em>They haven’t eaten their lunch yet.</em> / Ellos no han comido su almuerzo todavía.</p>"
                          :audio="require('@/assets/curso/tema2/10_10.wav')"
                        )
    p.mb-5 A continuación, escuche el siguiente diálogo, en el cual se aplica lo estudiado en el tema:
    Dialogo.color-acento-contenido(:dialogo="dialogo")(data-aos="fade-right")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) #[i A short story] / Un cuento corto.
      template(#descripcion-actividad) Arrastra y suelta cada una de las palabras en el orden correcto.

</template>

<script>
import DialogoChat from '../components/DialogoChat.vue'
import Traduccion from '../components/Traduccion.vue'
export default {
  name: 'Tema2',
  components: {
    Traduccion,
    DialogoChat,
  },
  data: () => ({
    traduccion1: {
      dialogo: [
        {
          textoIng:
            '<em>There are certain expressions that are used with the present perfect as their main use is to describe past events that are still important in the present. Among these expressions, the following can be named: <span>“already”</span>, <span>“ever”</span>, <span>“for”</span>, <span>“how long”</span>, <span>“just”</span>, <span>“recently”</span>, <span>“since”</span>, <span>“still”</span>, <span>“yet”</span>, and so on.</em>',
          textoEsp:
            'Existen ciertas expresiones que se utilizan con el presente perfecto debido a que su principal uso es para describir los acontecimientos pasados que tienen todavía importancia en el presente. Entre estas expresiones, se pueden nombrar las siguientes: <i>“already”</i>, <i>“ever”</i>, <i>“for”</i>, <i>“how long”</i>, <i>“just”</i>, <i>“recently”</i>,  <i>“since”</i>, <i>“still”</i>,  <i>“yet”</i>, entre otras.',
        },
      ],
    },
    traduccion2: {
      dialogo: [
        {
          textoIng:
            '<em>It is used to indicate that the simple present perfect describes an action that began in the past and has continued up to the present moment. It is used in affirmative sentences and in questions in order to give emphasis. It means: <span>“still”</span> or <span>“already”</span>. It is usually placed between the auxiliary verb <span>“to have”</span> and the past participle of the main verb. It can also be placed at the end of the sentence.</em>',
          textoEsp:
            'Se utiliza para indicar que el presente perfecto simple describe una acción que comenzó en el pasado y ha continuado hasta el momento presente. Se usa en oraciones afirmativas y en preguntas para dar énfasis. Significa: <i>“still”</i> o <i>“already”</i>. Se suele colocar entre el verbo auxiliar <i>“to have”</i> y el participio pasado del verbo principal. También se puede colocar al final de la oración.',
        },
      ],
    },
    traduccion3: {
      dialogo: [
        {
          textoIng:
            '<em>This time expression is usually used in interrogative sentences asking about the person’s experiences, and is placed between the subject and the main verb of the sentence. It translates as: “Sometime”. And to answer you can use “never”, or “never ever” to deny, which means ever, never.</em>',
          textoEsp:
            'Esta expresión de tiempo generalmente se usa en oraciones interrogativas que preguntan sobre las experiencias de la persona y se coloca entre el sujeto y el verbo principal de la oración. Se traduce como: <i>“Sometime”</i>. Y para responder puedes usar <i>“never”</i>, o <i>“never ever”</i> para negar, lo que significa nunca, nunca.',
        },
      ],
    },
    traduccion4: {
      dialogo: [
        {
          textoIng:
            '<em>This time expression indicates the duration or extent of the action. It can be translated as “during”. In general, the action started at a specific time in the past and continues in the present.</em>',
          textoEsp:
            'Esta expresión de tiempo indica la duración o extensión de la acción. Se puede traducir como <i>“during”</i>. En general, la acción comenzó en un momento específico del pasado y continúa en el presente.',
        },
      ],
    },
    traduccion5: {
      dialogo: [
        {
          textoIng:
            '<em>It expresses a question about the time that elapses between one period of time and another. It is only used in interrogative sentences and is usually placed at the beginning. It means: How long? / How long ago?</em>',
          textoEsp:
            'Expresa una pregunta sobre el tiempo que transcurre entre un periodo de tiempo y otro. Solo se usa en oraciones interrogativas y generalmente se coloca al principio. Significa: ¿Cuánto tiempo? / ¿Hace cuánto?',
        },
      ],
    },
    traduccion6: {
      dialogo: [
        {
          textoIng:
            '<em>It is used to indicate immediacy, generally in affirmative sentences. It can be translated as “finish” and is placed between the auxiliary verb and the main verb of the sentence.</em>',
          textoEsp:
            'Se utiliza para indicar inmediatez, generalmente en oraciones afirmativas. Se puede traducir como “terminar” y se coloca entre el verbo auxiliar y el verbo principal de la oración.',
        },
      ],
    },
    traduccion7: {
      dialogo: [
        {
          textoIng:
            '<em>This expression is used with the present perfect to indicate that the activity described has been carried out very recently, that is, it has just happened. It is always placed between the auxiliary verb “to have” and the main verb of the sentence, and its translation is, in general, “not long ago”.</em>',
          textoEsp:
            'Esta expresión se utiliza con el presente perfecto para indicar que la actividad descrita se ha realizado muy recientemente, es decir, acaba de ocurrir. Siempre se coloca entre el verbo auxiliar <i>“to have”</i> y el verbo principal de la oración, y su traducción es, en general, “no hace mucho”.',
        },
      ],
    },
    traduccion8: {
      dialogo: [
        {
          textoIng:
            '<em>This temporary expression can be used interchangeably in any sentence of the present perfect. It indicates the moment in which the action began and also the period of time between that specific moment in the past and the present moment. It can be translated by “from” and does not need to be located in a specific place in the sentence.</em>',
          textoEsp:
            'Esta expresión temporal se puede usar indistintamente en cualquier oración del presente perfecto. Indica el momento en que comenzó la acción y también el período de tiempo entre ese momento específico en el pasado y el momento presente. Se puede traducir por “de” y no es necesario ubicarlo en un lugar específico de la oración.',
        },
      ],
    },
    traduccion9: {
      dialogo: [
        {
          textoIng:
            '<em>It can be established that they are used to indicate that an activity has been carried out up to the present moment. It means: “For now” or “Until now”. They are always placed at the end of the sentence.</em>',
          textoEsp:
            'Se puede establecer que se utilizan para indicar que se ha realizado una actividad hasta el momento presente. Significa: “Por ahora” o “Hasta ahora”. Siempre se colocan al final de la oración.',
        },
      ],
    },
    traduccion10: {
      dialogo: [
        {
          textoIng:
            '<em>This expression is used to indicate that an activity has been going on up to the present moment and apparently has not finished, to talk about things that are still true and to ask if they still are. It basically means “still”. It is located at the beginning of the sentence, after the subject and before the auxiliary verb and the main verb of the sentence.</em>',
          textoEsp:
            'Esta expresión se utiliza para indicar que se ha estado realizando una actividad hasta el momento presente y aparentemente no ha terminado, para hablar de cosas que aún son ciertas y para preguntar si aún lo son. Básicamente significa "todavía". Se ubica al principio de la oración, después del sujeto y antes del verbo auxiliar y del verbo principal de la oración.',
        },
      ],
    },
    traduccion11: {
      dialogo: [
        {
          textoIng:
            '<em>Basically, it is used on interrogative or negative sentences. It is used to ask if an action has been carried out or not. Its position is at the end of the sentence. If it accompanies a question, it is usually translated as “already” and if it accompanies a negation, it is usually translated as “yet”.</em>',
          textoEsp:
            'Básicamente, se usa en oraciones interrogativas o negativas. Se utiliza para preguntar si se ha realizado o no una acción. Su posición es al final de la oración. Si acompaña a una pregunta, se suele traducir como “ya” y si acompaña a una negación, se suele traducir como “todavía”.',
        },
      ],
    },
    dialogo: {
      personajes: [
        {
          nombre: 'Barbie',
          img: require('@/assets/curso/tema2/img14.svg'),
        },
        {
          nombre: 'Paul',
          img: require('@/assets/curso/tema2/img15.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Barbie',
          textoIng: 'Have you *** bought cookies at Kris’s Cookies?',
          textoEsp: 'Alguna vez has probado galletas en Kris’s Cookies',
          audio: require('@/assets/curso/tema2/audio1.wav'),
          palabra: 'ever',
        },
        {
          personaje: 'Paul',
          textoIng: 'Never! Why have you asked me about that?',
          textoEsp: 'Nunca! ¿Por qué me has preguntado eso?',
          audio: require('@/assets/curso/tema2/audio1.mp3'),
          palabra: '',
        },
        {
          personaje: 'Barbie',
          textoIng:
            'Because my friends have said that those cookies are delicious!',
          textoEsp:
            'Porque mis amigos has dicho que esas galletas son deliciosas!',
          audio: require('@/assets/curso/tema2/audio2.wav'),
          palabra: '',
        },
        {
          personaje: 'Paul',
          textoIng: 'But you *** have done a pastry course...',
          textoEsp: 'Pero, ya tu has hecho un curso de repostería...',
          audio: require('@/assets/curso/tema2/audio2.mp3'),
          palabra: 'already',
        },
        {
          personaje: 'Barbie',
          textoIng: 'Yes, but I haven’t learned how to make cookies *** !',
          textoEsp: 'Si, pero no he aprendido cómo haceer galletas aún!',
          audio: require('@/assets/curso/tema2/audio3.wav'),
          palabra: 'yet',
        },
        {
          personaje: 'Paul',
          textoIng: 'Well, maybe they haven’t taught that lesson yet ...',
          textoEsp: 'Bueno, quizás aún no te han dado esa lección...',
          audio: require('@/assets/curso/tema2/audio3.mp3'),
          palabra: '',
        },
      ],
    },
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
