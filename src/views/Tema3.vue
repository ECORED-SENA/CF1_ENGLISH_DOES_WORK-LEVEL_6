<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 #[i We have traveled a lot this year!] / ¡Hemos viajado mucho este año!
    .row(data-aos="fade-right")
      .col-lg-5.mb-4.mb-lg-0
        Traduccion.color-primario(:dialogo="traduccion1")
      .col-lg-7
        SlyderF(columnas="col-lg-6")
          .tarjeta.color-secundario.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img1.svg' alt='AvatarTop')
            .row
              .col-12.bg-color16
                p.text-center.mb-0 #[b #[i.txt-c5 Travel with a group of friends]]
                p.text-center.mb-0 Viaje con un grupo de amigos
          .tarjeta.color-secundario.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img2.svg' alt='AvatarTop')
            .row
              .col-12.bg-color16
                .row.h-100.align-items-center
                  .col-12
                    p.text-center.mb-0 #[b #[i.txt-c5 Travel alone]]
                    p.text-center.mb-0 Viajar solo
          .tarjeta.color-secundario.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img3.svg' alt='AvatarTop')
            .row
              .col-12.bg-color16
                .row.h-100.align-items-center
                  .col-12
                    p.text-center.mb-0 #[b #[i.txt-c5 Family trip]]
                    p.text-center.mb-0 Viaje familiar
          .tarjeta.color-secundario.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img4.svg' alt='AvatarTop')
            .row
              .col-12.bg-color16
                .row.h-100.align-items-center
                  .col-12
                    p.text-center.mb-0 #[b #[i.txt-c5 Travel by water]]
                    p.text-center.mb-0 Viaje por agua
          .tarjeta.color-secundario.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img5.svg' alt='AvatarTop')
            .row
              .col-12.bg-color16
                .row.h-100.align-items-center
                  .col-12
                    p.text-center.mb-0 #[b #[i.txt-c5 Business trip]]
                    p.text-center.mb-0 Viaje de negocios
          .tarjeta.color-secundario.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img6.svg' alt='AvatarTop')
            .row
              .col-12.bg-color16
                .row.h-100.align-items-center
                  .col-12
                    p.text-center.mb-0 #[b #[i.txt-c5 Adventure trip]]
                    p.text-center.mb-0 Viaje de aventura
          .tarjeta.color-secundario.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/tema3/img7.svg' alt='AvatarTop')
            .row
              .col-12.bg-color16
                .row.h-100.align-items-center
                  .col-12
                    p.text-center.mb-0 #[b #[i.txt-c5 Space travel]]
                    p.text-center.mb-0 Viaje espacial
    Separador
    #t_3_1
    .titulo-segundo.color-primario
      h2 3.1 #[i Verbs related to transportation] / Verbos relacionados con el transporte
    .row.mb-5(data-aos="fade-left")
      .col-lg-5.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema3/img1.png')
      .col-lg-7
        p #[i.txt-c2 In general, there are many verbs that can be related to transportation, to indicate a series of actions such as getting on or off a vehicle, or to indicate how to travel, or also when driving a vehicle, stopping or parking it, among other verbs that can be used, in this case, in the present perfect tense.]
        p #[span.txt-c3 En general, existen muchos verbos que pueden relacionarse con el transporte, para indicar una serie de acciones como subir o bajar de un vehículo, o para señalar la forma de viajar, o también al conducir un vehículo, detenerlo o estacionarlo, entre otros verbos que pueden utilizarse, en este caso, en el tiempo presente perfecto.]
    .row.bg-color17(data-aos="fade-up")
      .col-12.p-5
        p.text-center.mb-5 #[b #[i For example:] / Por ejemplo:]
        SlyderF(columnas="col-lg-4")
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Drive]]
                p.text-center #[span.txt-c3 Manejar]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_1.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Harry has driven his father’s car.]]
                    p.text-center.mb-0 Harry ha manejado el carro de su padre.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Drop off]]
                p.text-center #[span.txt-c3 Dejar (un pasajero)]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_2.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 The taxi driver has dropped Billy off in front of the university.]]
                    p.text-center.mb-0 El taxista ha dejado a Billy frente a la Universidad.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Fasten seatbelt]]
                p.text-center #[span.txt-c3 Abrocharse el cinturón]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_3.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Before landing, the stewardess fastens her seatbelt.]]
                    p.text-center.mb-0 Antes de aterrizar, la azafata abrocha su cinturón.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Fly]]
                p.text-center #[span.txt-c3 Volar]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_4.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Jimmy has flown to Japan.]]
                    p.text-center.mb-0 Jimmy ha volado a Japón.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Get in]]
                p.text-center #[span.txt-c3 Entrar]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_5.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Clarisse has got in the car slowly.]]
                    p.text-center.mb-0 Clarisse ha entrado al carro lentamente.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Get lost]]
                p.text-center #[span.txt-c3 Perderse]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_7.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 The child has gotten lost in the mall.]]
                    p.text-center.mb-0 El niño se ha perdido en el centro comercial.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Get off]]
                p.text-center #[span.txt-c3 Bajarse]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_8.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 They have gotten off the subway at 10 a.m.]]
                    p.text-center.mb-0 Ellos se han bajado del metro a las 10 a.m.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Get on]]
                p.text-center #[span.txt-c3 Subirse]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_9.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 The girls have gotten on the bus quickly.]]
                    p.text-center.mb-0 Las chicas se han subido al autobús rápidamente.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Get out]]
                p.text-center #[span.txt-c3 Salir]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_10.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 The gentleman has gotten out of the car to open the door for his girlfriend.]]
                    p.text-center.mb-0 El caballero ha salido del carro para abrirle la puerta a su novia.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Go by bus]]
                p.text-center #[span.txt-c3 Ir en bus]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_11.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Nora has gone by bus to the stadium.]]
                    p.text-center.mb-0 Nora se ha ido en autobús al estadio.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Go by car]]
                p.text-center #[span.txt-c3 Ir en carro]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_12.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Henry has gone by car to the office today.]]
                    p.text-center.mb-0 Henry ha ido en carro a la oficina hoy.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Lose (passport)]]
                p.text-center #[span.txt-c3 Perder (pasaporte)]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_13.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Barbie has lost her passport at the hotel.]]
                    p.text-center.mb-0 Barbie ha perdido su pasaporte en el hotel.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Miss the plane]]
                p.text-center #[span.txt-c3 Perder el avión]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_14.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Bob has missed the plane for being late at the airport.]]
                    p.text-center.mb-0 Bob ha perdido el avión por llegar tarde al aeropuerto.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Pick up]]
                p.text-center #[span.txt-c3 Recoger (un pasajero)]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_15.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 The Uber has picked up Samantha in front of her house.]]
                    p.text-center.mb-0 El Uber ha recogido a Samantha en frente de su casa.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Ride (a horse/bike)]]
                p.text-center #[span.txt-c3 Montar (un caballo/bici)]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_16.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Vivian has ridden that horse with great skill.]]
                    p.text-center.mb-0 Vivian ha montado ese caballo con gran destreza.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Run over]]
                p.text-center #[span.txt-c3 Atropellar]
                .row
                  .col-12.borde.p-2.p-lg-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_17.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Today I have almost ran over a drunk who crossed the street carelessly.]]
                    p.text-center.mb-0 Hoy casi he atropellado un borracho que cruzó la calle despreocupadamente.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Set sail]]
                p.text-center #[span.txt-c3 Zarpar]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_18.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 The yacht has set sail early in the morning.]]
                    p.text-center.mb-0 El yate ha zarpado temprano en la mañana.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Slow down]]
                p.text-center #[span.txt-c3 Desacelerar]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_19.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Bob has slowed down the car on that curve in the road.]]
                    p.text-center.mb-0 Bob ha desacelerado el auto en esa curva de la carretera.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Speed up]]
                p.text-center #[span.txt-c3 Acelerar]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_20.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Carol has sped up the car to be able to arrive on time.]]
                    p.text-center.mb-0 Carol ha acelerado el carro para poder llegar a tiempo.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Take (the bus)]]
                p.text-center #[span.txt-c3 Tomar (el bus)]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_21.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 Mary has taken the bus to go to school.]]
                    p.text-center.mb-0 Mary ha tomado el bus para ir a la escuela.
          .tarjeta.color-acento-contenido.px-5.py-5
            .row
              .col-12.bg-color18
                p.text-center.mb-0 #[b #[i Walk]]
                p.text-center #[span.txt-c3 Caminar]
                .row
                  .col-12.borde.p-4
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/11_22.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center #[b #[i.txt-c5 They have walked to go to school.]]
                    p.text-center.mb-0 Ellas han caminado para ir a la escuela.
    Separador
    #t_3_2
    .titulo-segundo.color-primario
      h2 3.2 #[i Means of transportation] / Medios de transporte
    p.mb-5 #[i.txt-c2 Nowadays, there is a great variety of means of transport, not only for people, but also to carry and bring all kinds of heavy load. Therefore, means of land, water or air transport can be used. The respective vocabulary is presented below.] / #[span.txt-c3 En la actualidad, se cuenta con gran variedad de medios de transporte, no solo para las personas, sino también para llevar y traer todo tipo de carga pesada. Por ello, pueden utilizarse medios de transporte terrestre, acuáticos o aéreos. Conozca el vocabulario respectivo.]
    .row.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-auto.d-none.d-lg-block
        figure
          img(src='@/assets/curso/tema3/img8.svg').m-auto
      .col-lg-10
        p.text-center.mb-5 #[b #[i Air transport] / Transporte aéreo]
        SlyderF(columnas="col-lg-6 col-xl-3")
          .tarjeta
            .row.justify-content-center.bg-color19
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_1.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Airplane]]
                p.mb-0.text-center Avión
          .tarjeta
            .row.justify-content-center.bg-color21
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_2.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Cargo plane]]
                p.mb-0.text-center Avión de carga
          .tarjeta
            .row.justify-content-center.bg-color22
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_3.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Helicopter]]
                p.mb-0.text-center Helicóptero
          .tarjeta
            .row.justify-content-center.bg-color23
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_4.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Hot air balloon]]
                p.mb-0.text-center Globo aerostático
          .tarjeta
            .row.justify-content-center.bg-color24
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_5.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Rocket]]
                p.mb-0.text-center Cohete
          .tarjeta
            .row.justify-content-center.bg-color25
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_6.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Space shuttle]]
                p.mb-0.text-center Transbordador espacial
          .tarjeta
            .row.justify-content-center.bg-color26
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_7.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Spaceship]]
                p.mb-0.text-center Nave espacial
          .tarjeta
            .row.justify-content-center.bg-color27
              .col-10.bg-color20.p-4
                Audio.color-primario.m-auto.mb-3(
                  :audio="require('@/assets/curso/tema3/12_8.wav')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.text-center #[b #[i.txt-c5 Zeppelin]]
                p.mb-0.text-center Dirigible
    .row.bg-color12.mb-5(data-aos="fade-left")
      .col-12.p-5
        .row.align-items-center
          .col-lg-10
            p.text-center.mb-5 #[b #[i Water transportation] / Transporte acuático]
            SlyderF(columnas="col-lg-3")
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img10.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_12.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Pirate ship]]
                    p.text-center.mb-0 Barco pirata
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img11.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_11.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Cargo ship]]
                    p.text-center.mb-0 Buque de carga
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img12.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_10.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Cruise ship]]
                    p.text-center.mb-0 Crucero
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img13.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_9.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Sailboat]]
                    p.text-center.mb-0 Velero
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img14.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_21.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Fishing boat]]
                    p.text-center.mb-0 Barco pesquero
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img15.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_20.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Submarine]]
                    p.text-center.mb-0 Submarino
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img16.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_19.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Vessel]]
                    p.text-center.mb-0 Buque
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img17.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_18.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Ship]]
                    p.text-center.mb-0 Embarcación
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img18.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_17.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Kayak]]
                    p.text-center.mb-0 Kayak
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img19.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_16.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Canoe]]
                    p.text-center.mb-0 Canoa
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img20.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_15.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Ferry]]
                    p.text-center.mb-0 Ferry
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img21.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_14.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Boat]]
                    p.text-center.mb-0 Lancha
              .tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-3
                  .col-8.col-lg-12
                    img(src='@/assets/curso/tema3/img22.svg' alt='AvatarTop')
                .row
                  .col-12.bg-color28
                    Audio.color-primario.m-auto.mb-3(
                      :audio="require('@/assets/curso/tema3/12_13.wav')"
                      @audio-hover="mostrarIndicadorAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorAudio")
                    p.text-center.mb-0 #[b #[i.txt-c5 Jet ski]]
                    p.text-center.mb-0 Moto de agua
          .col-lg-auto.d-none.d-lg-block
            figure
              img(src='@/assets/curso/tema3/img8.svg').m-auto
    p.text-center.mb-5 #[b #[i Ground transportation] / Transporte terrestre]
    SlyderF.mb-5(columnas="col-lg-6 col-xl-3")(data-aos="fade-down")
      .tarjeta
        .row.justify-content-center.bg-color29
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_26.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Double-decker bus]]
            p.mb-0.text-center Autobús de dos pisos
      .tarjeta
        .row.justify-content-center.bg-color30
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_25.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Car]]
            p.mb-0.text-center Carro
      .tarjeta
        .row.justify-content-center.bg-color31
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_24.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Bus]]
            p.mb-0.text-center Autobús
      .tarjeta
        .row.justify-content-center.bg-color32
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_23.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Bicycle]]
            p.mb-0.text-center Bicicleta
      .tarjeta
        .row.justify-content-center.bg-color33
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_22.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Ambulance]]
            p.mb-0.text-center Ambulancia
      .tarjeta
        .row.justify-content-center.bg-color34
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_38.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Van]]
            p.mb-0.text-center Camioneta
      .tarjeta
        .row.justify-content-center.bg-color35
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_37.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Truck]]
            p.mb-0.text-center Camión
      .tarjeta
        .row.justify-content-center.bg-color36
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_36.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Train]]
            p.mb-0.text-center Tren
      .tarjeta
        .row.justify-content-center.bg-color37
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_35.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Tank]]
            p.mb-0.text-center Tanque
      .tarjeta
        .row.justify-content-center.bg-color38
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_34.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Subway]]
            p.mb-0.text-center Metro
      .tarjeta
        .row.justify-content-center.bg-color39
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_33.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Snowmobile]]
            p.mb-0.text-center Motonieve
      .tarjeta
        .row.justify-content-center.bg-color40
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_32.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Skateboard]]
            p.mb-0.text-center Patineta
      .tarjeta
        .row.justify-content-center.bg-color41
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_31.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Scooter]]
            p.mb-0.text-center Motoneta
      .tarjeta
        .row.justify-content-center.bg-color42
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_30.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 School bus]]
            p.mb-0.text-center Bus escolar
      .tarjeta
        .row.justify-content-center.bg-color43
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_29.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Motorcycle]]
            p.mb-0.text-center Motocicleta
      .tarjeta
        .row.justify-content-center.bg-color44
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_28.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Limousine]]
            p.mb-0.text-center Limusina
      .tarjeta
        .row.justify-content-center.bg-color45
          .col-10.bg-color20.p-4
            Audio.color-primario.m-auto.mb-3(
              :audio="require('@/assets/curso/tema3/12_27.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
            p.mb-0.text-center #[b #[i.txt-c5 Garbage truck]]
            p.mb-0.text-center Camión de basura
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
  name: 'Tema3',
  components: {
    Traduccion,
    DialogoChat,
  },
  data: () => ({
    traduccion1: {
      dialogo: [
        {
          textoIng:
            '<em>Traveling is an exciting experience. There are business trips, pleasure trips, adventure trips, tourist trips, even backpackers... and they all allow us to live experiences that are unforgettable, which we can then tell our friends, family or co-workers... and even publish them on social networks.<br><br>Always, at the end of a walk or a trip, we have new anecdotes and stories to tell others.<br><br>In this regard, St. Augustine has said <b>"The world is a book, and those who do not travel read only one page"</b>... that is why it is convenient for the mind, body and spirit to travel whenever possible. For this reason, different types of trip are indicated:</em>',
          textoEsp:
            'Viajar es una experiencia emocionante. Hay viajes de negocios, de placer, de aventura, turísticos, hasta mochileros… y todos nos permiten vivir experiencias que resultan inolvidables, que podemos contar luego a nuestros amigos, familiares o compañeros de trabajo… y hasta publicarlas en las redes sociales.<br><br>Siempre, al terminar un paseo o un viaje, tenemos nuevas anécdotas e historias para contar a los demás.<br><br>A este respecto, San Agustín ha dicho <i>“El mundo es un libro, y aquellos que no viajan leen solo una página”</i>... por ello, conviene a la mente, al cuerpo y al espíritu viajar cada vez que se pueda. A continuación, se señalan diversos tipos de viaje:',
        },
      ],
    },
    dialogo: {
      personajes: [
        {
          nombre: 'Susy',
          img: require('@/assets/curso/tema3/img23.svg'),
        },
        {
          nombre: 'Laurie',
          img: require('@/assets/curso/tema3/img24.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Susy',
          textoIng: 'Laurie! When have you *** from Europe?',
          textoEsp: '¡Laurie! ¿Cuándo has llegado de Europa?',
          audio: require('@/assets/curso/tema3/audio1.wav'),
          palabra: 'arrived',
        },
        {
          personaje: 'Laurie',
          textoIng: '*** last week, dear friend!',
          textoEsp: '¡Desde la semana pasada, querida amiga!',
          audio: require('@/assets/curso/tema3/audio2.wav'),
          palabra: 'Since',
        },
        {
          personaje: 'Susy',
          textoIng: 'So, how many *** have you visited on your vacation trip?',
          textoEsp:
            'Entonces, ¿Cuántos países has visitado en tu viaje de vacaciones?',
          audio: require('@/assets/curso/tema3/audio3.wav'),
          palabra: 'countries',
        },
        {
          personaje: 'Laurie',
          textoIng: 'Not enough! I have only ***, France, and Italy.',
          textoEsp:
            '¡No suficientes! Solo he visitado España, Francia e Italia.',
          audio: require('@/assets/curso/tema3/audio4.wav'),
          palabra: 'visited Spain',
        },
        {
          personaje: 'Susy',
          textoIng: 'Surely you have not *** your vacation enough.',
          textoEsp:
            'Seguramente no has planeado suficientemente tus vacaciones.',
          audio: require('@/assets/curso/tema3/audio5.wav'),
          palabra: 'planed',
        },
        {
          personaje: 'Laurie',
          textoIng: 'Maybe, but I have *** them to the fullest!',
          textoEsp: '¡Quizás, pero las he disfrutado al máximo!',
          audio: require('@/assets/curso/tema3/audio6.wav'),
          palabra: 'enjoyed',
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
