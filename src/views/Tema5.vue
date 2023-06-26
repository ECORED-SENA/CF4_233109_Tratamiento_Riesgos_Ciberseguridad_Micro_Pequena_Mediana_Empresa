<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 #[em Antimalware]

    .row.cont_5_1(style="position:relative;")
      .col-lg-10.col-md-12.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") El #[em malware], de acuerdo con #[em MalwareBytes], “es un término amplio que describe cualquier programa o código malicioso que es dañino para los sistemas” (#[em MalwareBytes], 2021), es capaz de invadir nuestros sistemas de información de manera intrusiva para causar daños, generando pérdidas de información en caso de no estar preparados.
        p.mt-4(data-aos="fade-up") Existen varios tipos de #[em malware] y tienen su impacto diferente dependiendo de su funcionamiento; en el siguiente video, es posible identificar aquellos tipos de #[em malware] más conocidos y que han generado estragos en los últimos años:
      .col-lg-2.col-md-4(style="place-self:center").d-none.d-lg-block
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema5/1.svg" data-aos="fade-left" style="max-width:100px;")


    figure.mt-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/x56FT_OVARQ" title="Ataques de seguridad en la red" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Ataques de seguridad en la red

    p.mt-5(data-aos="fade-up") El #[em malware], una vez logra afectar un dispositivo, puede presentar los siguientes síntomas, que llevan a identificar que se encuentra afectado por este tipo de programas:

    .row.mt-5.m-auto
      .col-xl.col-lg-4.mb-4.mb-lg-0
        .cont_tarjeta_5_1.p-4.pt-5.h-100
          figure
            img(src="@/assets/curso/tema5/4.svg" data-aos="zoom-in-up" style="max-width:100px")
          p.mt-4(data-aos="fade-up") Lentitud del dispositivo.
      .col-xl.col-lg-4.mb-4.mb-lg-0
        .cont_tarjeta_5_2.p-4.pt-5.h-100
          figure
            img(src="@/assets/curso/tema5/5.svg" data-aos="zoom-in-up" style="max-width:100px")
          p.mt-4(data-aos="fade-up") Falta de espacio en el disco sin causa alguna.
      .col-xl.col-lg-4.mb-4.mb-lg-0
        .cont_tarjeta_5_1.p-4.pt-5.h-100
          figure
            img(src="@/assets/curso/tema5/6.svg" data-aos="zoom-in-up" style="max-width:100px")
          p.mt-4(data-aos="fade-up") Ejecución de programas automáticos o mensajes emergentes.
      .col-xl.col-lg-4.mb-4.mb-lg-0
        .cont_tarjeta_5_2.p-4.pt-5.h-100
          figure
            img(src="@/assets/curso/tema5/7.svg" data-aos="zoom-in-up" style="max-width:100px")
          p.mt-4(data-aos="fade-up") Consumo de recursos excesivo (CPU, Memoria RAM, tráfico de red, entre otros) sin razón alguna.
      .col-xl.col-lg-4.mb-4.mb-lg-0
        .cont_tarjeta_5_1.p-4.pt-5.h-100
          figure
            img(src="@/assets/curso/tema5/8.svg" data-aos="zoom-in-up" style="max-width:100px")
          p.mt-4(data-aos="fade-up") Entre otros comportamientos relacionados.

    p.mt-5(data-aos="fade-up") Como mecanismos de protección y para no verse afectado por este tipo de programas, se recomienda el uso de tecnologías #[em antimalware], las cuales vienen hoy en día integradas a las soluciones de antivirus como Norton 360, Avast, Mcafee, Kaspersky, o también podemos encontrar soluciones independientes, como #[em Malwarebytes].

    Separador.mt-5

    .titulo-segundo
      h2#t_5_1 5.1 Tipos

    p(data-aos="fade-up") En la actualidad, se encuentran tecnologías #[em antimalware] que permiten mantener la seguridad de los dispositivos de la organización, como son:

    .row.mt-5.col-xl-10.m-auto
      .col-lg.mb-4.mb-lg-0
        .cont_tarjeta_5_3.h-100.p-4.pt-5
          figure
            img(src="@/assets/curso/tema5/10.png" data-aos="zoom-in-up")
          h4.mt-4.text-white.text-center(data-aos="fade-up") #[em Software antimalware] autónomo
          p.mt-4.text-white(data-aos="fade-up") Este tipo de programa #[em antimalware], por lo general, está enfocado en ciertos tipos de #[em malware] y se distribuye de manera independiente, sin requerir de otros componentes para su funcionamiento; este tipo de soluciones es muy común para recuperación de sistemas que ya han sido afectados.
      .col-lg.mb-4.mb-lg-0
        .cont_tarjeta_5_3.h-100.p-4.pt-5
          figure
            img(src="@/assets/curso/tema5/11.png" data-aos="zoom-in-up")
          h4.mt-4.text-white.text-center(data-aos="fade-up") Paquetes de #[em software] de seguridad
          p.mt-4.text-white(data-aos="fade-up") Este tipo de solución, por lo general, viene integrado a otras herramientas, como antivirus, soluciones corporativas o centralizadas, que permiten gestionar la seguridad de los dispositivos de una organización en todo momento.
      .col-lg.mb-4.mb-lg-0
        .cont_tarjeta_5_3.h-100.p-4.pt-5
          figure
            img(src="@/assets/curso/tema5/12.png" data-aos="zoom-in-up")
          h4.mt-4.text-white.text-center(data-aos="fade-up") #[em Software antimalware] en la nube
          p.mt-4.text-white(data-aos="fade-up") Este tipo de solución se integra a servicios que se encuentran en la nube y es común encontrarlo en servicios de correo electrónico o de alojamiento de archivos; generalmente, cuenta con 2 componentes, el cliente que se instala en los dispositivos administrados y el otro componente es el servicio web, el cual se encarga de validar la información reportada por el cliente.

    br
    .row.mt-5.col-xl-10.m-auto.cont_5_2(style="position:relative;")
      .col-xl-2.col-lg-3.mb-lg-0.mb-4(style="place-self:end")
        figure
          img(src="@/assets/curso/tema3/10.svg" data-aos="fade-right" style="max-width:90px")
      .col-xl-6.col-lg-5.mb-lg-0.mb-4(style="place-self:center")
        p.mb-0(data-aos="fade-up") El portal #[em Safety Detectives] comparte su post titulado “Las 7 mejores aplicaciones y protecciones #[em antimalware] (2022): Mejores herramientas”, entre las cuales sobresalen Norton 360, Bitdefender McAfee, TotalAV, Avira, así como la solución de MalwareBytes como herramienta autónoma sobresaliente para la gestión de #[em malware] para sistemas operativos Windows.
      .col-xl-4.col-lg-4.col-md-9.col-7.m-auto
        figure
          img(src="@/assets/curso/tema5/13.svg" data-aos="fade-left" style="position:relative;bottom:-16px;")

    Separador.mt-5

    .titulo-segundo
      h2#t_5_2 5.2 Características

    p(data-aos="fade-up") Las soluciones #[em antimalware] deben de incorporar como características importantes lo siguiente:

    SlyderF.mt-5(columnas="col-lg-6 col-xl-4")
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/14.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Protección frente a #[em(style="color:#12263F !important;") malware]
            p.mt-4(style="color:#12263F !important;") Debe presentar soporte para asegurar y recuperar recursos afectados por #[em(style="color:#12263F !important;") malware] de manera permanente y actualizada.
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/15.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Facilidad de uso
            p.mt-4(style="color:#12263F !important;") Debe proveer una interfaz de fácil uso, que permita al usuario realizar sus actividades de limpieza y recuperación sin necesidad de contar con una persona especializada.
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/16.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Velocidad de verificación
            p.mt-4(style="color:#12263F !important;") Debe ser rápido en el proceso de revisión, análisis y detección de #[em(style="color:#12263F !important;") malware].
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/17.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Actualización permanente
            p.mt-4(style="color:#12263F !important;") Debe proveer actualizaciones tanto de la aplicación como de las bases de datos, de manera permanente y oportuna.
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/18.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Consumo de recursos
            p.mt-4(style="color:#12263F !important;")  Debe presentar un consumo adecuado de los dispositivos controlados, de tal manera que no afecte el desarrollo de las actividades de los usuarios.
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/19.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Herramientas adicionales para la gestión de #[em(style="color:#12263F !important;") malware]
            p.mt-4(style="color:#12263F !important;") Debe proveer a los usuarios con las herramientas necesarias para el aseguramiento de sus dispositivos e información.
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/20.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Compatibilidad con diferentes sistemas
            p.mt-4(style="color:#12263F !important;")  Debe soportar cualquier sistema operativo y ser compatible con la mayoría de aplicaciones informáticas, con el objetivo de reconocer una aplicación afectada de una original.
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/21.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Soporte
            p.mt-4(style="color:#12263F !important;") Debe proveer soporte técnico especializado a los usuarios que cuentan con suscripciones activas.

    Separador.mt-5

    .titulo-segundo
      h2#t_5_3 5.3 Detección y respuesta para #[em endpoints] (EDR)

    .row.cont_5_1(style="position:relative;")
      .col-lg-10.col-md-8.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") Otro tipo de soluciones que permite mejorar la seguridad de los dispositivos de nuestra red son los EDR, los cuales permiten monitorear permanentemente los cambios presentados en los dispositivos.
        p.mt-4(data-aos="fade-up") A continuación, podrá reconocer los conceptos básicos relacionados con los EDR, por medio del siguiente video:
      .col-lg-2.col-md-4(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema5/22.svg" data-aos="fade-left" style="max-width:100px;")

    p.mt-5(data-aos="fade-up") #[strong Detección y respuesta para #[em Endpoints]]

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/XuDaYwxGMU0" title="Detección y Respuesta para Endpoints (EDR)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Detección y Respuesta para Endpoints (EDR)

    .mt-5.row.mb-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Características

    p(data-aos="fade-up") Dentro de las características requeridas por una solución para la detección y respuesta de #[em endpoints], es importante tener presente que debe abordar los niveles de seguridad para este tipo de dispositivos, como son:

    .row.mt-5
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_5_4
          .row.m-0
            .col-auto.p-3.d-flex.align-items-center(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:0px;")
              figure
                img(src="@/assets/curso/tema5/24.svg" data-aos="fade-right" style="width:60px;")
            .col.p-3.d-flex.align-items-center(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:0px;")
              p.mb-0(data-aos="fade-up") #[strong Análisis de riesgos y endurecimiento]
          .p-4
            p(data-aos="fade-up") Capacidad de realizar un inventario y su correspondiente análisis de riesgos, generar un esquema de actualizaciones, sugiriendo aplicación de cifrado a la información, estableciendo controles de seguridad tanto a las aplicaciones como al dispositivo en general.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_5_4
          .row.m-0
            .col-auto.p-3.d-flex.align-items-center(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:0px;")
              figure
                img(src="@/assets/curso/tema5/25.svg" data-aos="fade-right" style="width:60px;")
            .col.p-3.d-flex.align-items-center(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:0px;")
              p.mb-0(data-aos="fade-up") #[strong Prevención]
          .p-4
            p(data-aos="fade-up") Proveer de soluciones de seguridad activa que protejan contra cualquier amenaza que pueda afectar los activos de información administrados, a partir del monitoreo permanente y aprendizaje de los comportamientos identificados, facilitando la defensa ante cualquier comportamiento anómalo presentado desde el #[em endpoint].
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_5_4
          .row.m-0
            .col-auto.p-3.d-flex.align-items-center(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:0px;")
              figure
                img(src="@/assets/curso/tema5/26.svg" data-aos="fade-right" style="width:60px;")
            .col.p-3.d-flex.align-items-center(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:0px;")
              p.mb-0(data-aos="fade-up") #[strong Detección y respuesta]
          .p-4
            p(data-aos="fade-up") Brindar un monitoreo permanente que permita identificar de manera oportuna amenazas que puedan afectar el dispositivo, aislamiento del mismo, y realizar las acciones necesarias para la limpieza y registro de las acciones adelantadas.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_5_4
          .row.m-0
            .col-auto.p-3.d-flex.align-items-center(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:0px;")
              figure
                img(src="@/assets/curso/tema5/27.svg" data-aos="fade-right" style="width:60px;")
            .col.p-3.d-flex.align-items-center(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:0px;")
              p.mb-0(data-aos="fade-up") #[strong Informes e integración]
          .p-4
            p(data-aos="fade-up") Debe brindar las capacidades de integrarse con soluciones y sistemas de monitoreo para una visualización general de los endpoints de la organización.

    p.mt-5(data-aos="fade-up") #[strong En la siguiente figura, se puede observar la arquitectura de seguridad sugerida para una solución de #[em endpoint]:]

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 7.
      span Arquitectura adaptativa por niveles de seguridad para soluciones EDR
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema5/29.svg" data-aos="zoom-in-up" alt="La imagen presenta la arquitectura adaptativa por niveles de seguridad para soluciones EDR, el cual está compuesto por el análisis de riesgos y endurecimiento, la prevención, la detección y respuesta y los informes de integración.")
      img.d-block.d-lg-none(src="@/assets/curso/tema5/29.svg" data-aos="zoom-in-up" alt="La imagen presenta la arquitectura adaptativa por niveles de seguridad para soluciones EDR, el cual está compuesto por el análisis de riesgos y endurecimiento, la prevención, la detección y respuesta y los informes de integración.")
      figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Basado en Bitdefender (s. f.).





</template>

<script>
export default {
  name: 'Tema5',
  components: {},
  data: () => ({
    indicadorTarjetaSlide: true,
    indicadorTarjetaFlip: true,
    indicadorTarjetas: true,
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
<style lang="sass">
.cont_5_1 *
  position: relative
.cont_5_1:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #D5CEF8
.cont_tarjeta_5_1
  background: url(../assets/curso/tema5/2.png)
  background-repeat: no-repeat
  background-size: cover
  border-radius: 10px
.cont_tarjeta_5_2
  background: url(../assets/curso/tema5/3.png)
  background-repeat: no-repeat
  background-size: cover
  border-radius: 10px
.cont_tarjeta_5_3
  background: url(../assets/curso/tema5/9.png)
  background-repeat: no-repeat
  background-size: cover
  border-radius: 15px
.cont_5_2 *
  position: relative
.cont_5_2:before
  content: ''
  position: absolute
  width: 85%
  height: 100%
  top: 0
  background-color: #B5E4EB
  border-top-left-radius: 150px
  border-bottom-left-radius: 150px
.slyder-f
  .horizontal-scroll
    display: flex !important
    align-items: stretch !important
    height: 100%
    .slyder-f__slyde
      display: flex
      align-items: stretch
      justify-content: space-around
.cont_slydef1
  background-image: url(../assets/curso/tema1/19.png)
  background-size: 100% 100%
  background-color: white !important
.slyder-f__btn i
  font-size: 1.6rem;
  background-color: #636363;
  border-radius: 100%;
  padding: 0.5rem 0.8rem;
  color: white
.cont_tarjeta_5_4
  background: url(../assets/curso/tema5/28.png)
  background-repeat: no-repeat
  background-size: cover
  background-position: center
@media screen and (max-width: 1000px)
  .cont_5_2:before
    width: 100%
    border-radius: 0px
</style>
