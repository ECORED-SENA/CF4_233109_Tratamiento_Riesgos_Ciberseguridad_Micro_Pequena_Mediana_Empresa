<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 9
      h1 Sistemas de correlacionamiento de #[em logs] y monitoreo

    .row
      .col-lg-4.mb-4.mb-lg-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema9/1.png" data-aos="fade-left")
      .col-lg-8(style="place-self:center")
        p(data-aos="fade-up") Los sistemas para el relacionamiento de #[em logs] y monitoreo de la actividad que pasa sobre nuestra red y dispositivos permiten visión actualizada del nivel de seguridad de los controles implementados.
        p.mt-4(data-aos="fade-up") Estos sistemas, como su nombre lo sugiere, permiten recoger e integrar las salidas de registros, también denominados #[em logs], en una base de datos centralizada, permitiendo agrupar e identificar los comportamientos relacionados con el tráfico, tanto entrante como saliente, de nuestra red y, en especial, de los servidores, generando vistas gráficas de los aspectos más relevantes, como, por ejemplo, eventos de seguridad, dispositivos fuera de línea, ataques de denegación de servicio, entre otros, los cuales, a su vez, permiten notificar, a través de diferentes medios, a un destinatario en particular.
        p.mt-4(data-aos="fade-up") #[strong A continuación, podrá conocer algunos aspectos importantes de estos sistemas:]

    Separador.mt-5

    .titulo-segundo
      h2#t_9_1 9.1 Conceptos

    p(data-aos="fade-up") Mantener una vista del estado de la seguridad de una red requiere de herramientas que permitan representar de manera fácil la información consolidada, esta información de monitoreo proviene de los activos de información y de los controles implementados, los cuales son los encargados de reportar las acciones realizadas. A continuación, se detalla cada uno de ellos:

    .tarjeta.tarjeta--azul.p-5.mt-5.cont_slyderab1
      SlyderA(tipo="b")
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Correlacionados de eventos / SIEM
            p Estas soluciones especializadas brindan la capacidad de crear centros de monitoreo a partir de las fuentes de información recolectadas, como, por ejemplo: registro de un servidor web, registros de auditoría de un servicio LDAP, etc.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema9/2.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Sensor
            p Mecanismos encargados de monitorear el comportamiento de un servicio o de un dispositivo, permitiendo recolectar la información sobre algún comportamiento irregular, por ejemplo, un sensor para monitoreo de servicio web.
            p.mt-4 Estos sensores pueden ser IDS, IPS, sistemas de monitoreo, como, por ejemplo: Snort, Suricata, etc.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema9/3.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 #[em Dashboard]
            p También llamado tablero de control, es una herramienta visual que representa, mediante gráficas, el estado actual de la red, o puede presentar las alertas a las que es necesario prestar atención. En la siguiente figura, es posible ver un ejemplo de un #[em dashboard] de un SIEM resaltando activamente las novedades a las que se debe prestar atención.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema9/4.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Registro #[em Log]
            p Es un historial de registros de eventos, ordenados en orden cronológico, que almacenan la información de diferentes eventos, como, por ejemplo: sistema operativo, servicio, o registro de autenticación desde una aplicación.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema9/5.png')

    Separador.mt-5

    .titulo-segundo
      h2#t_9_2 9.2 Tipos

    p(data-aos="fade-up") Actualmente, existe una amplia gama de proveedores para soluciones SIEM y de correlación de eventos, entre los cuales es posible resaltar, de acuerdo con licenciamientos, modo de implementación, entre otros; por ejemplo:

    .row.mt-5.col-xl-10.m-auto.cont_9_1.p-4
      figure
        img(src="@/assets/curso/tema9/6.svg" data-aos="fade-right" style="max-width:60px;")
      p.mt-4.col-lg-8(data-aos="fade-up") Si se analizan las Soluciones SIEM, por tipo de licencia, se encontrará una amplia gama de productos dividida en dos categorías: las comerciales, que cuentan con servicios de actualización de reglas, soporte técnico, mecanismos de integración con más soluciones; y, por otra parte, las soluciones Open Source, que son proyectos, por lo general en desarrollo, y que por su naturaleza no ofrecen soporte técnico ni asesoría en la implementación, esto se debe adquirir por aparte.
      .row.mt-4
        .col-lg-7.mb-4.mb-lg-0
          p(data-aos="fade-up") También es posible identificar las soluciones SIEM de acuerdo con su modo de implementación y operación. Se tienen los SIEM Internos, que son aquellos que son implementados en la infraestructura tecnológica de la misma organización; los SIEM basados en la nube, que brindan mayor funcionalidad al permitirles acceder remotamente y sin hacer uso de los recursos de procesamientos dentro de la organización; y también se encuentran los SIEM Gestionados, los cuales se ofrecen como servicios y son administrados por terceros, bajo una modalidad de contrato.
        .col-lg-5
          figure
            img(src='@/assets/curso/tema9/7.png' data-aos="fade-left")

    p.mt-5(data-aos="fade-up") #[strong En la siguiente figura, es posible observar un listado de los productos más representativos disponibles en el mercado:]

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 17.
      span Soluciones SIEM disponibles en el mercado
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema9/9.svg" data-aos="zoom-in-up")
      img.d-block.d-lg-none(src="@/assets/curso/tema9/10.svg" data-aos="zoom-in-up")
      figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.]  Basado en Marty (2013).

    Separador.mt-5

    .titulo-segundo
      h2#t_9_3 9.3 Características

    p(data-aos="fade-up") De acuerdo con INCIBE, un SIEM es “una solución híbrida centralizada que engloba la gestión de información de seguridad (#[em Security Information Management]) y la gestión de eventos (#[em Security Event Manager])” (INCIBE, 2020).

    .mt-5.p-4.p-lg-5(style="background-color:#D5CEF8;")
      p(data-aos="fade-up") Entre las funcionalidades más relevante de un SIEM, se pueden resaltar las siguientes:
      ul.fa-ul.mt-4
        li.mb-2.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Cumplimiento:] permite reconocer el nivel de cumplimiento frente a estándares y marcos de seguridad, por ejemplo: ISO 27001, NIST, CIS Controls, entre otras.
        li.mb-2.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Analítica:] análisis de información proveniente de servicios o de generadores de datos, por ejemplo: ficheros log de servidores, bases de datos, etc.
        li.mb-2.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Protección de dispositivos móviles:] vigilancia permanente de dispositivos móviles, dada la vulnerabilidad presentada por robo y su capacidad de perder información.
        li.mb-2.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Protección ante amenazas:] búsqueda, reporte y bloqueo de nuevas amenazas.
        li.mb-2.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Administración:] gestión centralizada de los dispositivos protegidos.
        li.mb-2.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Protección de datos:] establecer las políticas para el comportamiento ante ciertas acciones.
        li.mb-2.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Protección de dispositivos:] capacidad de gestionar dispositivos que presenten algún comportamiento extraño.
        li.d-block(data-aos="fade-up")
          i.fa-li.fa.fa-check-circle(style="color:#40327B;")
          | #[strong Protección de red:] capacidad de analizar el tráfico que fluye en la red y tomar acciones de acuerdo con patrones y políticas implementadas.

    p.mt-5(data-aos="fade-up") Como se puede observar en la siguiente figura, estas características deben incorporarse como mínimo en un SIEM en una organización para mantener un panorama completo de la seguridad:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 18.
      span Funcionalidades de un SIEM
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema9/11.svg" data-aos="zoom-in-up")
      img.d-block.d-lg-none(src="@/assets/curso/tema9/12.svg" data-aos="zoom-in-up")

    p.mt-5(data-aos="fade-up") Asimismo, es importante resaltar el esquema lógico de un SIEM, que se puede apreciar en la siguiente figura, donde se presenta un esquema de cómo, a partir de la ingesta o alimentación de fuentes de diferentes sistemas de información, consigue realizar un procesamiento y correlación de patrones para generar una vista amigable, como se había visto en el #[em dashboard]:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 19.
      span Esquema lógico de un SIEM
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema9/13.svg" data-aos="zoom-in-up")
      img.d-block.d-lg-none(src="@/assets/curso/tema9/14.svg" data-aos="zoom-in-up")




</template>

<script>
export default {
  name: 'Tema9',
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
.cont_slyderab1
  background: url(../assets/curso/tema2/6.png)
  background-repeat: no-repeat
  background-size: cover
.slyder-a__bullets__item
  background-color: #A097CC
.slyder-a__bullets__item--active
  background-color: #40327B !important
  border: 0 !important
@media screen and (max-width: 720px)
  .slyder-a__bullets__item
    margin: 0 4px !important
.cont_9_1 *, .cont_9_1
  position: relative
.cont_9_1:before
  position: absolute
  content: ''
  width: 85%
  height: 80%
  top: 10%
  left: -1%
  background: url(../assets/curso/tema9/8.png)
  background-size: 100% 100%
@media screen and (max-width: 1300px)
  .cont_9_1:before
    width: 100%
    height: 100%
    left: 0
    top: 0
</style>
