<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 #[i Present perfect] / Presente perfecto
    .row.mb-5
      .col-lg-6.mb-4.mb-lg-0
        Traduccion.color-primario(:dialogo="traduccion1")
      .col-lg-6
        .row
          .col-12.p-4.p-lg-5.bg-color1
            .row
              .col-12.p-4.bg-color2
                p.mb-4 #[i We use Present Perfect for actions in the past which have a connection to the present, the time when these actions happened is not important].
                h4.text-center #[i Present Perfect]
                figure
                  img(src='@/assets/curso/tema1/img1.svg', style="width: 500px").m-auto
            .row.mb-4
              .col-12.p-4
                p #[i We use the Present Perfect for recently completed actions.]
                h4.text-center #[i Present Perfect]
                figure
                  img(src='@/assets/curso/tema1/img2.svg', style="width: 500px").m-auto
            .row
              .col-12.p-4.bg-color2
                p #[i We use Present Perfect for actions beginning in the past and still continuing.]
                h4.text-center #[i Present Perfect]
                figure
                  img(src='@/assets/curso/tema1/img3.svg', style="width: 500px").m-auto
    p.mb-5 A continuación, se presentan algunos ejemplos:
    .row.bg-color3.mb-5
      .col-12.p-5
        h4.text-center.mb-5 #[i When should I use the Present Perfect?]
        .row
          .col-auto.d-none.d-lg-block
            figure
              img(src='@/assets/curso/tema1/img4.svg')
          .col
            .tarjeta.tarjeta--blanca.p-4
              SlyderA(tipo="b")
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i When used to refer to unfinished actions]
                    p Cuando se usa para referir acciones no finalizadas. 
                    p #[i.txt-c2 In this case, it is observed that the action started in the past but continues even in the present]. #[span.txt-c3 En este caso, se observa que la acción inició en el pasado, pero continúa aún en el presente]. 
                    p #[i Listen to the audio]:
                    .row.mb-4
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Susy has worked here since 2019."
                          :audio="require('@/assets/curso/tema1/1_1.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="They have not paid any rent for several months."
                          :audio="require('@/assets/curso/tema1/1_2.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Caroline has practiced swimming in this pool since she was little."
                          :audio="require('@/assets/curso/tema1/1_3.wav')"
                        )
                    figure
                      img(src='@/assets/curso/tema1/img5.svg')
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i When talking about completed actions]
                    p #[i.txt-c2 When talking about completed actions, which have occurred in the past, but without saying when they happened]. #[span.txt-c3 Cuando se habla de acciones finalizadas, que han ocurrido en el pasado, pero sin decir cuando sucedieron]. 
                    p #[i Listen to the audio]:
                    .row.mb-4
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Frank has gone to Brazil."
                          :audio="require('@/assets/curso/tema1/1_4.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Lia has lost her Ipod."
                          :audio="require('@/assets/curso/tema1/1_5.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="They have climbed that mountain together."
                          :audio="require('@/assets/curso/tema1/1_6.wav')"
                        )
                    figure
                      img(src='@/assets/curso/tema1/img6.svg')
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i When the time for carrying out]
                    p #[i.txt-c2 When the time for carrying out the action has not ended]. #[span.txt-c3 Cuando el tiempo de realización de la acción no ha concluido]. 
                    p #[i Listen to the audio]:
                    .row.mb-4
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Carol and Sue have gone to the gym once a week."
                          :audio="require('@/assets/curso/tema1/1_7.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Mario has looked for a job this month."
                          :audio="require('@/assets/curso/tema1/1_8.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="They have been in line to pay for public services."
                          :audio="require('@/assets/curso/tema1/1_9.wav')"
                        )
                    figure
                      img(src='@/assets/curso/tema1/img7.svg')
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i When the action is constantly repeated]
                    p #[i.txt-c2 When the action is constantly repeated at an indeterminate time between the past and the present]. #[span.txt-c3 Cuando la acción se repite en forma constante en un tiempo indeterminado entre el pasado y el presente]. 
                    p #[i Listen to the audio]:
                    .row.mb-4
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Paul and Linda have gone to the movies several times."
                          :audio="require('@/assets/curso/tema1/1_10.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Julia has visited the theater at every premiere of a play."
                          :audio="require('@/assets/curso/tema1/1_11.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Sara has talked to her son about sexuality several times."
                          :audio="require('@/assets/curso/tema1/1_12.wav')"
                        )
                    figure
                      img(src='@/assets/curso/tema1/img8.svg')
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i When the action recently ended]
                    p #[i.txt-c2 When the action recently ended. In this case, it is accompanied by the adverb “just”]. #[span.txt-c3 Cuando la acción terminó recientemente. En este caso, se acompaña con el adverbio #[b #[i “just”]]]. 
                    p #[i Listen to the audio]:
                    .row.mb-4
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Joseph has fixed his car just now."
                          :audio="require('@/assets/curso/tema1/1_13.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="They have ended their relationship just this week."
                          :audio="require('@/assets/curso/tema1/1_14.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Mary has just finished her housework at home."
                          :audio="require('@/assets/curso/tema1/1_15.wav')"
                        )
                    figure
                      img(src='@/assets/curso/tema1/img9.svg')
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i When the moment isn´t relevant]
                    p #[i.txt-c2 When the moment in which the action was carried out is not relevant]. #[span.txt-c3 Cuando el momento en que se llevó a cabo la acción no es relevante]. 
                    p #[i Listen to the audio]:
                    .row.mb-4
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="I have lived near famous movie stars."
                          :audio="require('@/assets/curso/tema1/1_16.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Debbie has studied in Harvard for her Law degree."
                          :audio="require('@/assets/curso/tema1/1_17.wav')"
                        )
                      .col-lg
                        TarjetaAudio.color-primario.mb-3(
                          texto="Donald has won the lottery."
                          :audio="require('@/assets/curso/tema1/1_18.wav')"
                        )
                    figure
                      img(src='@/assets/curso/tema1/img10.svg')
    p.mb-5 El siguiente video amplía la información sobre el uso del #[i present perfect].
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/UA7OSCHDbMA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    p.mb-5 #[i.txt-c2 As can be seen in the previous examples, the present perfect tense is formed using the auxiliary verb "to have" conjugated in the corresponding grammatical person in the present tense, plus the past participle of the main verb of the sentence, according to the following structure:] / #[span.txt-c3 Como puede observarse en los ejemplos anteriores, el tiempo presente perfecto se forma utilizando el verbo auxiliar “to have” conjugado en la persona gramatical correspondiente en tiempo presente, más el participio pasado del verbo principal de la oración, de acuerdo con la siguiente estructura:]
    .row.bg-color4
      .col-12.p-5
        .titulo-sexto.color-acento-contenido.mb-5
          p.mb-0 #[b Tabla 1]. Estructura gramatical del #[i present perfect]
        .row.d-none.d-lg-block.mb-5
          .col-auto
            figure
              img(src='@/assets/curso/tema1/img11.svg')
        .row.d-block.d-lg-none.mb-5
          .col-12
            .row.justify-content-center
              .col-8.mb-3
                figure
                  img(src='@/assets/curso/tema1/img12.svg')
            .row.justify-content-center
              .col-2.mb-3
                figure
                  img(src='@/assets/curso/tema1/img16.svg')
            .row.justify-content-center
              .col-10.mb-3
                figure
                  img(src='@/assets/curso/tema1/img13.svg')
            .row.justify-content-center
              .col-2.mb-3
                figure
                  img(src='@/assets/curso/tema1/img16.svg')
            .row.justify-content-center
              .col-10.mb-3
                figure
                  img(src='@/assets/curso/tema1/img14.svg')
            .row.justify-content-center
              .col-2.mb-3
                figure
                  img(src='@/assets/curso/tema1/img16.svg')
            .row.justify-content-center
              .col-10
                figure
                  img(src='@/assets/curso/tema1/img15.svg')
        .row.align-items-center
          .col-lg-auto.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema1/img1.png')
          .col-auto
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>I <c1>have</c1> <c2>worked</c2> <c3>very hard</c3></em> / Yo he trabajado muy duro.</p>"
              :audio="require('@/assets/curso/tema1/2_1.wav')"
              no-barra
            )
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>Mary <c1>has</c1> <c2>listened</c2> <c3>to the radio</c3></em> / Mary ha escuchado la radio.</p>"
              :audio="require('@/assets/curso/tema1/2_2.wav')"
              no-barra
            )
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>George <c1>has</c1> <c2>bought</c2> <c3>a big house</c3></em> / George ha comprado una casa grande.</p>"
              :audio="require('@/assets/curso/tema1/2_3.wav')"
              no-barra
            )
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>Ida and Susy <c1>have</c1> <c2>traveled</c2> <c3>abroad</c3></em> / Ida y Susy han viajado al extranjero.</p>"
              :audio="require('@/assets/curso/tema1/2_4.wav')"
              no-barra
            )
    Separador
    #t_1_1
    .titulo-segundo.color-primario
      h2 1.1 #[i Verbs in past participle] / Verbos en participio pasado
    .row.mb-5
      .col-lg.mb-4.mb-lg-0
        Traduccion.color-primario(:dialogo="traduccion2")
      .col-lg-auto
        figure
          img(src='@/assets/curso/tema1/img2.png')
    .row.mb-5
      .col-lg
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img17.svg' alt='AvatarTop')
          .tarjeta.tarjeta--c1
            .p-4
              p.mb-0 #[b #[i Work + ed = worked]]
              p.mb-0 Trabajar → trabajado
      .col-lg
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img18.svg' alt='AvatarTop')
          .tarjeta.tarjeta--c1
            .p-4
              p.mb-0 #[b #[i Travel + ed = traveled]]
              p.mb-0 Viajar → viajado
      .col-lg
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img19.svg' alt='AvatarTop')
          .tarjeta.tarjeta--c1
            .p-4
              p.mb-0 #[b #[i Dance + ed = danced]]
              p.mb-0 Bailar → bailado
      .col-lg
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img20.svg' alt='AvatarTop')
          .tarjeta.tarjeta--c1
            .p-4
              p.mb-0 #[b #[i Listen + ed = listened]]
              p.mb-0 Escuchar → escuchado
    p.mb-5 #[i.txt-c2 It is important to keep in mind that these verbs have the same form as in the simple past. That is, it will be necessary to analyze the context to be clear about the verb form used. An example will make it much clearer:] / #[span.txt-c3 Es importante tener presente que estos verbos tienen la misma forma que en pasado simple, es decir, sería necesario analizar el contexto para tener claro cuál es la forma verbal utilizada. Con un ejemplo, se verá mucho más claro:]
    .row.mb-5
      .col-lg-auto.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema1/img3.png')
      .col-lg
        TabsB.color-acento-contenido.mb-5.bg-color5
          .py-4.py-md-5(titulo="Structure 1" :icono="require('@/assets/curso/tema1/img21.svg')")
            .row.p-4
              .col-12
                h4 #[i.txt-c2 Structure 1]
                p #[i When the verb ends in a consonant before "y", the letter "y" is changed to "i" and the ending "ed" is added.] / #[span.txt-c3 Cuando el verbo termina en consonante antes de “y”, se cambia la letra “y” por “i” y se agrega la terminación “-ed”.]
                p #[i For example:] / Por ejemplo:
                .row.justify-content-center
                  .col-10.col-lg-auto.mb-3.mb-lg-0
                    figure
                      img(src='@/assets/curso/tema1/img23.svg', style="width: 220px").m-auto
                  .col-10.col-lg-auto.mb-3.mb-lg-0
                    figure
                      img(src='@/assets/curso/tema1/img24.svg', style="width: 220px").m-auto
                  .col-10.col-lg-auto
                    figure
                      img(src='@/assets/curso/tema1/img25.svg', style="width: 240px").m-auto
          .py-4.py-md-5(titulo="Structure 2" :icono="require('@/assets/curso/tema1/img22.svg')")
            .row.p-4
              .col-12
                h4 #[i.txt-c2 Structure 2]
                p #[i When there are irregular verbs that have a different past participle.] / #[span.txt-c3 Cuando hay verbos irregulares que tienen un participio pasado diferente].
                p #[i For example:] / Por ejemplo:
                .row.justify-content-center
                  .col-10.col-lg-auto.mb-3.mb-lg-0
                    figure
                      img(src='@/assets/curso/tema1/img26.svg', style="width: 270px").m-auto
                  .col-10.col-lg-auto.mb-3.mb-lg-0
                    figure
                      img(src='@/assets/curso/tema1/img27.svg', style="width: 185px").m-auto
                  .col-10.col-lg-auto
                    figure
                      img(src='@/assets/curso/tema1/img28.svg', style="width: 175px").m-auto
    .row.bg-color6
      .col-12.p-5
        p.mb-5 #[i.txt-c4 Below is a list of some irregular verbs that are widely used in the English language, with their respective past participles. Also, an example is presented in each case]. #[span.text-white / A continuación, se presenta una lista con algunos verbos irregulares que son muy utilizados en el idioma inglés, con sus respectivos participios pasados. Asimismo, se presenta un ejemplo en cada caso.]
        .row.align-items-center
          .col-lg-8
            .tarjeta.tarjeta--blanca.p-4
              SlyderA(tipo="b")
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i Picture Dictionary Present Perfect Sentences]
                    .row
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Awake - Awoken]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Lucy has awoken to reality."
                          :audio="require('@/assets/curso/tema1/3_1.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Bit - Bitten]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Firulay has bitten my favorite toy."
                          :audio="require('@/assets/curso/tema1/3_5.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Beat - Beaten]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="The boy has beaten  his little friend."
                          :audio="require('@/assets/curso/tema1/3_2.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Buy - Bought]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Frank has bought a blue car."
                          :audio="require('@/assets/curso/tema1/3_6.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Begin - Begun]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Cindy has begun to study French."
                          :audio="require('@/assets/curso/tema1/3_3.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Fly - Flown]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="The eagle has flown to its nest."
                          :audio="require('@/assets/curso/tema1/3_7.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Build - Built]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="The engineer has built a beautiful building."
                          :audio="require('@/assets/curso/tema1/3_4.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Feel - Felt]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Patrick has felt a lot of pain for your departure."
                          :audio="require('@/assets/curso/tema1/3_8.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i Picture Dictionary Present Perfect Sentences]
                    .row
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Fall - Fallen]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Billy has fallen from the ladder!"
                          :audio="require('@/assets/curso/tema1/3_9.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Draw - Drawn]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Vincent has drawn several sketches."
                          :audio="require('@/assets/curso/tema1/3_13.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Eat - Eaten]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Mark has eaten a big piece of cake!"
                          :audio="require('@/assets/curso/tema1/3_10.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Choose - Chosen]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Sue has chosen the ring with a diamond."
                          :audio="require('@/assets/curso/tema1/3_14.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Drive - Driven]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Have you ever driven a bike?"
                          :audio="require('@/assets/curso/tema1/3_11.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Catch - Caught]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Robert has caught the ball several times."
                          :audio="require('@/assets/curso/tema1/3_15.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Drink - Drunk]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Mickie has drunk all the soda."
                          :audio="require('@/assets/curso/tema1/3_12.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Give - Given]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Lucas has given a birthday present to your baby."
                          :audio="require('@/assets/curso/tema1/3_16.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i Picture Dictionary Present Perfect Sentences]
                    .row
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Go - Gone]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="I have gone to the movies twice this week."
                          :audio="require('@/assets/curso/tema1/3_17.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Hide - Hidden]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Molly has hidden the car keys."
                          :audio="require('@/assets/curso/tema1/3_21.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Get - Got/Gotten]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="All students have got their diplomas."
                          :audio="require('@/assets/curso/tema1/3_18.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Hear - Heard]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Conny has not heard your side of the story."
                          :audio="require('@/assets/curso/tema1/3_22.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Keep - Kept]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Her grandmother has kept her love letters."
                          :audio="require('@/assets/curso/tema1/3_19.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Have - Had]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Mike has had a lot of work."
                          :audio="require('@/assets/curso/tema1/3_23.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Know - Known]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Mary has always known that you are married."
                          :audio="require('@/assets/curso/tema1/3_20.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Sing - Sung]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Samantha has sung at the party all night."
                          :audio="require('@/assets/curso/tema1/3_24.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i Picture Dictionary Present Perfect Sentences]
                    .row
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Sell - Sold]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="The travel agency has sold all the tickets to Miami."
                          :audio="require('@/assets/curso/tema1/3_25.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Read - Read]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Felix has read many novels."
                          :audio="require('@/assets/curso/tema1/3_29.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i See - Seen]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Paul has seen all the works of Picasso at the museum."
                          :audio="require('@/assets/curso/tema1/3_26.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Put - Put]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Candy has put the money in a safe."
                          :audio="require('@/assets/curso/tema1/3_30.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Say - Said]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Donald has said the truth all time."
                          :audio="require('@/assets/curso/tema1/3_27.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Pay - Paid]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="My parents have paid all my debts"
                          :audio="require('@/assets/curso/tema1/3_31.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Ring - Rung]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Nick has rung all day."
                          :audio="require('@/assets/curso/tema1/3_28.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Meet - Met]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="I have met my friends at the club."
                          :audio="require('@/assets/curso/tema1/3_32.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-5.txt-c1 #[i Picture Dictionary Present Perfect Sentences]
                    .row
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Make - Made]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Melina has made a very nice ornament."
                          :audio="require('@/assets/curso/tema1/3_33.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Lose - Lost]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Charles has lost his wallet."
                          :audio="require('@/assets/curso/tema1/3_35.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Leave - Left]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="That boy has left a package for you."
                          :audio="require('@/assets/curso/tema1/3_34.wav')"
                        )
                      .col-lg-6
                        p.text-center.mb-3 #[b #[i Lend - Lent]]
                        TarjetaAudio.color-primario.mb-3(
                          texto="Your cousin has lent you his suit for graduation."
                          :audio="require('@/assets/curso/tema1/3_36.wav')"
                        )
          .col-lg-auto.d-none.d-lg-block
            figure
              img(src='@/assets/curso/tema1/img4.png')
    Separador
    #t_1_2
    .titulo-segundo.color-primario
      h2 1.2 #[i Auxiliary Have - Has ] / Auxiliar #[i Have - Has]
    .row.mb-5
      .col-lg.mb-4.mb-lg-0
        Traduccion.color-primario(:dialogo="traduccion3").mb-4
        .row.justify-content-center
          .col-10.mb-4
            .row.justify-content-center.align-items-center.bg-color7
              .col-6.col-lg-auto.mb-4.mb-lg-0
                figure
                  img(src='@/assets/curso/tema1/img30.svg')
              .col-lg
                .row
                  .col-lg-6.mb-4.mb-lg-0
                    TarjetaAudio.color-primario(
                      texto="She is going to have a nap in the hammock."
                      :audio="require('@/assets/curso/tema1/4_1.wav')"
                    )
                  .col-lg-6
                    TarjetaAudio.color-primario(
                      texto="Sue and Marty are going to have a drink together."
                      :audio="require('@/assets/curso/tema1/4_2.wav')"
                    )
          .col-10
            .row.justify-content-center.align-items-center.bg-color7
              .col-6.col-lg-auto.mb-4.mb-lg-0
                figure
                  img(src='@/assets/curso/tema1/img31.svg')
              .col
                .row
                  .col-lg-6.mb-4.mb-lg-0
                    TarjetaAudio.color-primario(
                      texto="You have to study more."
                      :audio="require('@/assets/curso/tema1/4_3.wav')"
                    )
                  .col-lg-6
                    TarjetaAudio.color-primario(
                      texto="They have to explain what happened."
                      :audio="require('@/assets/curso/tema1/4_4.wav')"
                    )
      .col-lg-auto.d-none.d-lg-block
        figure
          img(src='@/assets/curso/tema1/img29.svg')
    .row.mb-5
      .col-lg-auto.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema1/img33.svg')
      .col-lg
        Traduccion.color-primario(:dialogo="traduccion4")
    .row.justify-content-center.mb-5
      .col-lg-10
        .tabla-a.color-acento-botones
          table
            tbody
              tr.bgt-1
                td
                  p.mb-0.text-center #[b #[i Subject]] 
                  p.mb-0.text-center Sujeto
                td(width="5%")
                  p.mb-0.text-center +
                td
                  p.mb-0.text-center #[b #[i Auxiliary verb]]
                  p.mb-0.text-center Verbo auxiliar #[i “to have”]
                td(width="5%")
                  p.mb-0.text-center +
                td
                  p.mb-0.text-center #[b #[i Past participle of main verb]]
                  p.mb-0.text-center Participio pasado
                  p.mb-0.text-center (#[i To work] - Trabajar)
                td(width="5%")
                  p.mb-0.text-center +
                td
                  p.mb-0.text-center #[b #[i Complement]]
                  p.mb-0.text-center Complemento
              tr
                td.bgt-2
                  p.mb-0.text-center #[i I (Yo)]
                  p.mb-0.text-center #[i You (Tú)]
                td(rowspan="3").bgt-2
                  p.mb-0.text-center +
                td.bgt-2
                  p.mb-0.text-center #[i have (he)]
                  p.mb-0.text-center #[i have (has)]
                td(rowspan="3").bgt-2
                  p.mb-0.text-center +
                td(rowspan="3").bgt-2
                  p.mb-0.text-center #[i worked]
                  p.mb-0.text-center #[i (trabajado)]
                td(rowspan="3").bgt-2
                  p.mb-0.text-center +
                td(rowspan="3").bgt-2
                  p.mb-0.text-center #[i very hard.]
                  p.mb-0.text-center #[i (muy duro).]
              tr
                td.bgt-2
                  p.mb-0.text-center #[i He, She, It]
                  p.mb-0.text-center #[i (Él, Ella, Ello)]
                td.bgt-2
                  p.mb-0.text-center #[i has (ha)]
              tr
                td.bgt-2
                  p.mb-0.text-center #[i We (Nosotros)]
                  p.mb-0.text-center #[i You (Ustedes)]
                  p.mb-0.text-center #[i They (Ellos/Ellas)]
                td.bgt-2
                  p.mb-0.text-center #[i have (hemos)]
                  p.mb-0.text-center #[i have (han/habéis)]
                  p.mb-0.text-center #[i have (han)]
    p.mb-5.text-center #[i.txt-c2 From this figure, the following examples are handled:] #[span.txt-c3 / A partir de esta figura, se manejan los siguientes ejemplos:]
    .row.justify-content-center
      .col-lg-10
        .row
          .col-lg.bg-color8.p-4.m-2
            figure.mb-3
              img(src='@/assets/curso/tema1/img34.svg')
            TarjetaAudio.color-primario.mb-3(
                texto="I have worked very hard."
                :audio="require('@/assets/curso/tema1/5_1.wav')"
              )
            p.ms-3.mb-0 Yo he trabajado muy duro.
          .col-lg.bg-color8.p-4.m-2
            figure.mb-3
              img(src='@/assets/curso/tema1/img35.svg')
            TarjetaAudio.color-primario.mb-3(
                texto="You have worked very hard."
                :audio="require('@/assets/curso/tema1/5_3.wav')"
              )
            p.ms-3.mb-0 Tú has trabajado muy duro.
          .col-lg.bg-color8.p-4.m-2
            figure.mb-3
              img(src='@/assets/curso/tema1/img36.svg')
            TarjetaAudio.color-primario.mb-3(
                texto="He has worked very hard."
                :audio="require('@/assets/curso/tema1/5_5.wav')"
              )
            p.ms-3.mb-0 Él ha trabajado muy duro.
        .row
          .col-lg.bg-color8.p-4.m-2
            figure.mb-3
              img(src='@/assets/curso/tema1/img37.svg')
            TarjetaAudio.color-primario.mb-3(
                texto="We have worked very hard."
                :audio="require('@/assets/curso/tema1/5_2.wav')"
              )
            p.ms-3.mb-0 Nosotros hemos trabajado duro.
          .col-lg.bg-color8.p-4.m-2
            figure.mb-3
              img(src='@/assets/curso/tema1/img38.svg')
            TarjetaAudio.color-primario.mb-3(
                texto="You have worked very hard."
                :audio="require('@/assets/curso/tema1/5_4.wav')"
              )
            p.ms-3.mb-0 Ustedes han trabajado duro.
          .col-lg.bg-color8.p-4.m-2
            figure.mb-3
              img(src='@/assets/curso/tema1/img39.svg')
            TarjetaAudio.color-primario.mb-3(
                texto="They have worked very hard."
                :audio="require('@/assets/curso/tema1/5_6.wav')"
              )
            p.ms-3.mb-0 Ellos han trabajado duro.
    Separador
    #t_1_3
    .titulo-segundo.color-primario
      h2 1.3 #[i Affirmative, negative and interrogative structures] / Estructuras afirmativas, negativas e interrogativas
    p.mb-5 #[i.txt-c2 In this compound verb tense (Present Perfect), affirmative, negative and interrogative structures are also handled, as can be seen in the following video:] #[span.txt-c3 / En este tiempo verbal compuesto (Presente Perfecto), también se manejan las estructuras afirmativas, negativas e interrogativas, como se puede observar en el siguiente video:]
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/sNMPApLiotQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    Separador
    #t_1_4
    .titulo-segundo.color-primario
      h2 1.4 #[i Structure of questions and answers] / Estructura de preguntas y respuestas
    .row.mb-5
      .col-lg-auto.d-none.d-lg-block
        figure
          img(src='@/assets/curso/tema1/img40.svg')
      .col-lg
        Traduccion.color-primario(:dialogo="traduccion5")
    p.mb-5.text-center #[b #[i For example:] / Por ejemplo:]
    .row.mb-5
      .col-lg-8.bg-color9.p-4.mb-4.mb-lg-0
        figure.mb-5
          img(src='@/assets/curso/tema1/img41.svg')
        .row
          .col-lg-6
            p.text-center.mb-0 #[b #[i Question]]
            p.text-center.mb-3 Pregunta
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>Has Lucy travelled to Europe?</em> / ¿Ha viajado Lucy a Europa?</p>"
              :audio="require('@/assets/curso/tema1/6_1.wav')"
            )
          .col-lg-6
            p.text-center.mb-0 #[b #[i Short answer - affirmative]]
            p.text-center.mb-3 Respuesta corta - afirmativa
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>Yes, she has.</em> / Sí, ella sí.</p>"
              :audio="require('@/assets/curso/tema1/6_4.wav')"
            )
          .col-lg-6
            p.text-center.mb-0 #[b #[i Affirmative answer]]
            p.text-center.mb-3 Respuesta afirmativa
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>Yes, she has travelled to Europe.</em> / Sí, ella ha viajado a Europa.</p>"
              :audio="require('@/assets/curso/tema1/6_2.wav')"
            )
          .col-lg-6
            p.text-center.mb-0 #[b #[i Short answer - negative]]
            p.text-center.mb-3 Respuesta corta - negativa
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>No, she has not.</em> / No, ella no.</p>"
              :audio="require('@/assets/curso/tema1/6_5.wav')"
            )
          .col-lg-6
            p.text-center.mb-0 #[b #[i Negative answer]]
            p.text-center.mb-3 Respuesta negativa
            TarjetaAudio.color-primario.mb-3(
              texto="<p><em>No, she has not travelled to Europe.</em> / No, ella no ha viajado a Europa.</p>"
              :audio="require('@/assets/curso/tema1/6_3.wav')"
            )
      .col-lg-4
        p.txt-c2 As can be seen, the pronoun “she” has been used instead of the name “Lucy” in the responses. Both options are valid, that is, it can be answered using the respective noun or pronoun, since both forms are correct.
        p.txt-c3 Como puede observarse, en la respuesta se ha empleado el pronombre “she” en lugar del nombre “Lucy”. Son válidas las dos opciones, es decir, puede responderse utilizando el nombre o el pronombre respectivo, pues ambas formas son correctas.
        figure
          img(src='@/assets/curso/tema1/img42.svg')
    p.mb-3.text-center #[i Some other examples] / Otros ejemplos:
    p.mb-5.text-center #[b #[i.txt-c5 Questions and Answers with Have and Has]]
    .row.mb-5
      .col-lg.bg-color10.p-4.m-2
        figure.mb-3
          img(src='@/assets/curso/tema1/img43.svg')
        .row
          .col-12.bg-color11.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema1/7_1.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Has George bought a speedy car?]]
            p.mb-0.text-center #[b #[i.txt-c2 Yes, George has bought a speedy car.]]
      .col-lg.bg-color10.p-4.m-2
        figure.mb-3
          img(src='@/assets/curso/tema1/img44.svg')
        .row
          .col-12.bg-color11.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema1/7_2.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Have you ever met an important writer?]]
            p.mb-0.text-center #[b #[i.txt-c2 No, I haven’t met an important writer yet.]]
      .col-lg.bg-color10.p-4.m-2
        figure.mb-3
          img(src='@/assets/curso/tema1/img45.svg')
        .row
          .col-12.bg-color11.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema1/7_3.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Has the baby eaten all his breakfast?]]
            p.mb-0.text-center #[b #[i.txt-c2 Yes, the baby has eaten all his breakfast.]]
    p.mb-5 #[i.txt-c2 When specific questions are asked using “Wh questions”, then it is necessary to give a complete answer with the required information.] #[span.txt-c3 / Cuando se trata de preguntas específicas utilizando “Wh questions”, entonces es necesario dar una respuesta completa con la información requerida.]
    p.mb-5 #[i For example:] / Por ejemplo:
    .row.bg-color12
      .col-12.p-5
        .row
          .col-lg-4.d-none.d-lg-block
            figure
              img(src='@/assets/curso/tema1/img5.png')
          .col-lg-8.bg-color13
            .fig-p1
              figure
                img(src='@/assets/curso/tema1/img47.svg', style="width:60px")
            p.text-center.mb-5 #[b #[i Wh Questions]]
            SlyderF(columnas="col-lg-6")
              .tarjeta.color-primario.p-5
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/tema1/img48.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color13
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema1/8_1.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-3 #[b #[i.txt-c5 #[span.txt-c2 Question:] Where have you been on vacation this summer?]]
                    p.text-center.mb-0 #[b #[i.txt-c5 #[span.txt-c2 Answer:] We have been in Jamaica this summer.]]
              .tarjeta.color-primario.p-5
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/tema1/img49.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color13
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema1/8_2.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-3 #[b #[i.txt-c5 #[span.txt-c2 Question:] How long have you worked in that company?]]
                    p.text-center.mb-0 #[b #[i.txt-c5 #[span.txt-c2 Answer:] I have worked in that company for five years.]]
              .tarjeta.color-primario.p-5
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/tema1/img50.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color13
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema1/8_3.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-3 #[b #[i.txt-c5 #[span.txt-c2 Question:] When has Denisse won the prize?]]
                    p.text-center.mb-0 #[b #[i.txt-c5 #[span.txt-c2 Answer:] Denisse has won the prize three times this year.]]
              .tarjeta.color-primario.p-5
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/tema1/img51.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color13
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema1/8_4.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-3 #[b #[i.txt-c5 #[span.txt-c2 Question:] Who has helped you solve the math problems?]]
                    p.text-center.mb-0 #[b #[i.txt-c5 #[span.txt-c2 Answer:] My brother has helped me solve the math problems.]]
              .tarjeta.color-primario.p-5
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='@/assets/curso/tema1/img52.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color13
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema1/8_5.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-3 #[b #[i.txt-c5 #[span.txt-c2 Question:] Whom have you sold the skateboard?]]
                    p.text-center.mb-0 #[b #[i.txt-c5 #[span.txt-c2 Answer:] I have sold the skateboard to my friend Benny.]]
            .fig-p2
              figure
                img(src='@/assets/curso/tema1/img46.svg', style="width:60px")
    Separador
    #t_1_5
    .titulo-segundo.color-primario
      h2 1.5 #[i Intonation in questions] / Entonación en preguntas
    .row.mb-5
      .col-lg-auto.d-none.d-lg-block
        figure
          img(src='@/assets/curso/tema1/img53.svg')
      .col-lg
        Traduccion.color-primario(:dialogo="traduccion6")
    .row.bg-color14.mb-5
      .col-12.p-4
        .row.align-items-center
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema1/img55.svg')
          .col-lg
            .tarjeta.tarjeta--blanca.p-4
              SlyderA(tipo="b")
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i The intonation with “ Yes/No questions”]]
                    Traduccion.mb-4.color-primario(:dialogo="traduccion7")
                    p.text-center.mb-5 #[i For example:] / Por ejemplo:
                    .row
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Have you ever traveled by ship?"
                          :audio="require('@/assets/curso/tema1/9_1.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Has Susan written a best-seller?"
                          :audio="require('@/assets/curso/tema1/9_4.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Have they walked many kilometers?"
                          :audio="require('@/assets/curso/tema1/9_2.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Has Felix broken your heart?"
                          :audio="require('@/assets/curso/tema1/9_5.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Have Mary and Paul lived together for much time?"
                          :audio="require('@/assets/curso/tema1/9_3.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Have you followed me on social networks?"
                          :audio="require('@/assets/curso/tema1/9_6.wav')"
                        )
                .row
                  .col-12.p-4
                    h4.text-center.mb-4 #[b #[i The intonation with “Wh- Questions”]]
                    Traduccion.mb-4.color-primario(:dialogo="traduccion8")
                    p.text-center.mb-5 #[i For example:] / Por ejemplo:
                    .row
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Where have you ever traveled by ship?"
                          :audio="require('@/assets/curso/tema1/9_7.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Who has been your favorite writer until now?"
                          :audio="require('@/assets/curso/tema1/9_10.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Who has been your partner in the office?"
                          :audio="require('@/assets/curso/tema1/9_8.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Which trip has been the funniest?"
                          :audio="require('@/assets/curso/tema1/9_11.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="What is your goal in life?"
                          :audio="require('@/assets/curso/tema1/9_9.wav')"
                        )
                      .col-lg-6
                        TarjetaAudio.color-primario.mb-3(
                          texto="Whom have you given the car keys?"
                          :audio="require('@/assets/curso/tema1/9_12.wav')"
                        )
    p.mb-5 A continuación, escuche el siguiente diálogo, en el cual se aplica lo estudiado en el tema:
    Dialogo.color-acento-contenido(:dialogo="dialogo")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) #[i A short story] / Un cuento corto.
      template(#descripcion-actividad) Arrastra y suelta cada una de las palabras en el orden correcto.

</template>

<script>
import DialogoChat from '../components/DialogoChat.vue'
import Traduccion from '../components/Traduccion.vue'
export default {
  name: 'Tema1',
  components: {
    Traduccion,
    DialogoChat,
  },
  data: () => ({
    traduccion1: {
      dialogo: [
        {
          textoIng:
            '<em>The present perfect tense is a compound verb tense and is used to talk about something that happened in the past and is relevant in the present, because it happened recently or because it is an action that has not yet finished. It is also used to indicate a repeated action in a non-specific period of time located between the past and the present, or when an action is mentioned for which the precise moment in which it happened is not important. It is quite useful when you want to tell an anecdote that has happened to you, or describe the trips made, as well as to express experiences or memories.</em>',
          textoEsp:
            'El tiempo presente perfecto es un tiempo verbal compuesto y se usa para hablar de algo que sucedió en el pasado y tiene relevancia en el presente, debido a que ocurrió hace poco tiempo o debido a que es una acción que aún no ha finalizado. También se emplea al señalar una acción repetida en un periodo temporal inespecífico situado entre el pasado y el presente, o cuando se menciona una acción para la cual no es importante el momento preciso en que aconteció. Resulta bastante útil cuando se quiere contar una anécdota que ha ocurrido, o describir los viajes realizados, así como para expresar experiencias o recuerdos. A continuación, se presentan algunos ejemplos:',
        },
      ],
    },
    traduccion2: {
      dialogo: [
        {
          textoIng:
            '<em>Participles in English are grammatical elements that can perform the function of a noun, an adjective or an adverb, however, they are formed from verbs. It should be noted that in the English language there are three types of participles: the present participle, the past participle and the perfect participle. But, in this case, to form the present perfect tense, the past participle is used.<br><br>Basically, the past participle of a verb is formed with the verb plus the ending "-ed". That is, when it is a regular verb, the particle "-ed" is simply added to the end. Some examples:</em>',
          textoEsp:
            'Los participios en inglés son elementos gramaticales que pueden realizar la función de sustantivo, adjetivo o adverbio, no obstante, se forman a partir de verbos. Cabe destacar que, en el idioma inglés, existen tres tipos de participios: el <i>participio presente</i>, el <i>participio pasado</i> y el <i>participio perfecto</i>, pero en este caso, para formar el tiempo presente perfecto, se utiliza el participio pasado.<br><br>Básicamente, el participio pasado de un verbo se forma con <i>el verbo</i> más la terminación <i>“-ed”</i>.  Es decir, cuando se trata de un verbo regular, sencillamente se le añade la partícula <i>“-ed”</i> al final. Algunos ejemplos son:',
        },
      ],
    },
    traduccion3: {
      dialogo: [
        {
          textoIng:
            '<em>The verb "to have" can function as a main verb or as an auxiliary verb. As a main verb, it can have several meanings, depending on the context in which it is used. Thus, in some cases it is translated as "take" or "throw". It is also a modal verb, to express obligations, when accompanied by the particle "to" (have to).</em>',
          textoEsp:
            'El verbo <i>“to have”</i> puede funcionar como verbo principal o como verbo auxiliar. Como verbo principal, puede tener varios significados, dependiendo del contexto en el cual se utilice. Así, en algunos casos se traduce como “tomar” o “echar”. También se emplea como verbo modal, para expresar obligaciones, cuando se acompaña de la partícula <i>“to” (have to)</i>.',
        },
      ],
    },
    traduccion4: {
      dialogo: [
        {
          textoIng:
            '<em>On this occasion, its meaning and use as an auxiliary verb will be explained, since it is used together with the main verb of the sentence to form a compound tense, as the present perfect. In this regard, it can be indicated that to form a sentence in the present perfect tense, the subject is placed first, then the conjugated auxiliary "to have" in the present tense, then the main verb of the sentence, and finally, the complement, as you can see in the following chart:</em>',
          textoEsp:
            'En esta ocasión, se va a explicar su significado y uso como verbo auxiliar, debido a que se utiliza conjuntamente con el verbo principal de la oración para formar un tiempo compuesto, como el presente perfecto. A este respecto, se puede indicar que, para formar una oración en tiempo presente perfecto, primero se coloca el <b>sujeto</b>, luego el <b>auxiliar <i>"to have"</i></b> conjugado en presente, luego el <b>verbo principal</b> de la oración, y finalmente, el <b>complemento</b>, como puede observarse en la siguiente tabla:',
        },
      ],
    },
    traduccion5: {
      dialogo: [
        {
          textoIng:
            '<em>When questions are asked using the present perfect tense, the answer is likewise given using this tense.<br><br>In general, you can answer yes or no, providing a complete answer. However, it can also be answered using a short answer, either yes or no.</em>',
          textoEsp:
            'Cuando se hacen preguntas utilizando el tiempo presente perfecto, de igual manera, la respuesta viene dada utilizando este tiempo verbal.<br><br>En general, se puede responder en forma afirmativa o negativa, proporcionando una respuesta completa. Sin embargo, también puede responderse utilizando una respuesta corta, ya sea en forma afirmativa o negativa.',
        },
      ],
    },
    traduccion6: {
      dialogo: [
        {
          textoIng:
            '<em>In English, there are two main categories of questions: <span>“yes/no questions”</span> and <span>“wh questions”</span>. Two types of intonations are used to pronounce or intonate these questions: ascending intonation and descending intonation.<br><br>In general terms, it can be noted that intonation is the cadence or musical tone of the voice and it plays a very important role in English. In the following resource, you can see some examples used to identify intonation in questions.</em>',
          textoEsp:
            'En inglés, se cuenta con dos grandes categorías de preguntas: <i>“yes/no questions”</i> y <i>“wh questions”</i>. Para pronunciar o entonar estas preguntas, se emplean dos tipos de entonación: ascendente y descendente.<br><br>En líneas generales, puede señalarse que la entonación es la cadencia o tono musical de la voz y desempeña un papel muy importante en inglés. En el siguiente recurso, puede observar algunos ejemplos utilizados para identificar la entonación en preguntas:',
        },
      ],
    },
    traduccion7: {
      dialogo: [
        {
          textoIng:
            '<em>With these types of questions, an increasing or rising intonation should be used. So, at the end of the question, the intonation should be raised slowly. Thus, it will be recognized that what was said is a question and it will sound more natural.</em>',
          textoEsp:
            'En este tipo de preguntas debe utilizarse una entonación creciente o ascendente. De esa manera, al final de la pregunta, la entonación debe elevarse lentamente. Así, se reconocerá que lo dicho es una pregunta y sonará más natural.',
        },
      ],
    },
    traduccion8: {
      dialogo: [
        {
          textoIng:
            '<em>Basically, with these questions you should use a decreasing or falling intonation, so that, at the end of the question, the intonation drops slowly.</em>',
          textoEsp:
            'Básicamente, con estas preguntas debe utilizar una entonación decreciente o descendente, de manera que, al final de la pregunta, la entonación baje lentamente.',
        },
      ],
    },
    dialogo: {
      personajes: [
        {
          nombre: 'James',
          img: require('@/assets/curso/tema1/img56.svg'),
        },
        {
          nombre: 'Clarisse',
          img: require('@/assets/curso/tema1/img57.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'James',
          textoIng: 'Clarisse, *** my car’s keys?',
          textoEsp: 'Clarisse, ¿has visto las llaves de mi carro?',
          audio: require('@/assets/curso/tema1/audio1.mp3'),
          palabra: 'have you seen',
        },
        {
          personaje: 'Clarisse',
          textoIng: 'No, James. I haven’t *** your car’s keys.',
          textoEsp: 'No, James. No he visto las llaves de tu carro.',
          audio: require('@/assets/curso/tema1/audio1.wav'),
          palabra: 'seen',
        },
        {
          personaje: 'James',
          textoIng: 'Oh, no! I have *** all over the house.',
          textoEsp: 'Oh, no! He buscado por toda la casa.',
          audio: require('@/assets/curso/tema1/audio2.mp3'),
          palabra: 'searched',
        },
        {
          personaje: 'Clarisse',
          textoIng: 'Where *** you looked for them?',
          textoEsp: '¿En donde las has buscado?',
          audio: require('@/assets/curso/tema1/audio2.wav'),
          palabra: 'have',
        },
        {
          personaje: 'James',
          textoIng:
            'I told you: I’ve searched for the car’s keys all over the house.',
          textoEsp:
            'Te lo dije: he buscado las llaves del carro por toda la casa.',
          audio: require('@/assets/curso/tema1/audio3.mp3'),
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
