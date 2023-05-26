<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Dispositivos móviles

    .row.cont_7_1(style="position:relative;")
      .col-lg-10.col-md-8.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") Dentro de la norma ISO 27001 - Anexo A, se cuenta con controles que establecen los lineamientos para el uso de dispositivos móviles, lo anterior teniendo en cuenta las consideraciones de seguridad para su uso.
        p.mt-4(data-aos="fade-up") #[strong Para contextualizar sobre la seguridad de dispositivos móviles, es importante tener presentes los siguientes términos:]
      .col-lg-2.col-md-4(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema7/1.svg" data-aos="fade-left" style="max-width:100px;")

    .row.mt-5
      .col-lg-6.col-xl.mb-xl-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/tema7/4.svg' style="max-width:120px")
          .tarjeta.color-primario.cont_tarjeta_7_1
            .text-white.p-4.text-center
              h4.text-center(style="color:#12263F !important;" data-aos="fade-up") Terminal
              p.mt-4(style="color:#12263F !important;" data-aos="fade-up") Se conoce a cualquier dispositivo móvil que permite registrar y consultar información.
      .col-lg-6.col-xl.mb-xl-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/tema7/5.svg' style="max-width:120px")
          .tarjeta.color-primario.cont_tarjeta_7_2
            .text-white.p-4.text-center
              h4.text-center(style="color:#12263F !important;" data-aos="fade-up") #[em(style="color:#12263F !important;") Smartphone]
              p.mt-4(style="color:#12263F !important;" data-aos="fade-up") Teléfono inteligente que cuenta con funciones avanzadas para utilizar aplicaciones y gestionar información; estos dispositivos están compuestos por sistema operativo, aplicaciones e información.
      .col-lg-6.col-xl.mb-xl-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/tema7/6.svg' style="max-width:120px")
          .tarjeta.color-primario.cont_tarjeta_7_1
            .text-white.p-4.text-center
              h4.text-center(style="color:#12263F !important;" data-aos="fade-up") #[em(style="color:#12263F !important;") Byod #[br] (Bring Your Own Device)]
              p.mt-4(style="color:#12263F !important;" data-aos="fade-up") Es una tendencia por la cual optan algunas organizaciones, permitiendo que sus trabajadores utilicen sus dispositivos personales para el desarrollo de actividades laborales.
      .col-lg-6.col-xl.mb-xl-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/tema7/7.svg' style="max-width:120px")
          .tarjeta.color-primario.cont_tarjeta_7_2
            .text-white.p-4.text-center
              h4.text-center(style="color:#12263F !important;" data-aos="fade-up") Política de seguridad
              p.mt-4(style="color:#12263F !important;" data-aos="fade-up") Son controles lógicos que se aplican a dispositivos con el objetivo de controlar acciones o capacidades de un dispositivo móvil.

    Separador.mt-5

    .titulo-segundo
      h2#t_7_1 7.1 Tipos

    p(data-aos="fade-up") Los tipos de dispositivos móviles son utilizados para la comunicación y transmisión de información, entre los que se pueden identificar: teléfonos inteligentes, dispositivos smart entre los que se encuentran los relojes, dispositivos expansión de sonido, video o accesorios para interacción, como gafas 3D, que hacen parte de los dispositivos móviles y que cada uno, por el hecho de mantener una comunicación hacia la red y compartir datos sensibles, deben ser controlados y asegurados.
    p.mt-4(data-aos="fade-up") #[strong Entre algunas de las amenazas actuales a las que están expuestos este tipo de dispositivos móviles, se encuentran las siguientes:]

    .tarjeta.tarjeta--azul.p-5.mt-5.cont_slyderab1
      SlyderA(tipo="b")
        .row
          .col-lg-6.mb-4.mb-lg-0
            h4 Aplicaciones maliciosas
            p Mediante las cuales se puede instalar apps maliciosas que pueden presentar algún tipo de filtración de datos o daño, tanto en los dispositivos como en la información.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema7/8.png')
        .row
          .col-lg-6.mb-4.mb-lg-0
            h4 Vulnerabilidades en los dispositivos
            p Algunas marcas y/o modelos no cuentan con los componentes necesarios para un sistema seguro, lo que se considera una debilidad, y esta puede ser aprovechada por terceros para robar información.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema7/9.png')
        .row
          .col-lg-6.mb-4.mb-lg-0
            h4 #[em Phishing]
            p Esta es una de las vulnerabilidades más comunes, con la cual buscan captar usuarios incautos para robar información, cuentas o acceder a información de sistemas bancarios o de redes sociales, para luego pedir algún rescate.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema7/10.png')
        .row
          .col-lg-6.mb-4.mb-lg-0
            h4 Ataques #[em Man-in-the-Middle]
            p Teniendo presente la cantidad de información que circula en las redes hoy, este tipo de ataque permite intervenir el tráfico para capturar la información que por ella transita.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema7/11.png')
        .row
          .col-lg-6.mb-4.mb-lg-0
            h4 Ataques basados en la red
            p Problemas de #[em malware] en dispositivos, que puede tomar el control y realizar acciones no requeridas, por ejemplo: envío masivo de mensajes a los contactos o publicación autónoma en las redes sociales.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema7/12.png')
        .row
          .col-lg-6.mb-4.mb-lg-0
            h4 Por pérdida o robo
            p Información, contenido y si esta se encontraba cifrada o no.
          .col-lg-6
            figure
              img(src='@/assets/curso/tema7/13.png')

    Separador.mt-5

    .titulo-segundo
      h2#t_7_2 7.2 Características

    p(data-aos="fade-up") Los dispositivos de comunicación actuales cuentan con mecanismos para la personalización y establecimiento de controles de seguridad directos de fábrica, como son bloqueos remotos, reporte de ubicación en tiempo real e, incluso, el enlace exclusivo con dispositivos específicos, con lo cual se pueden organizar estrategias para su aseguramiento.

    .tarjeta.color-primario.p-4.mt-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/tema7/14.svg" data-aos="fade-right")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.mb-1.text-white(data-aos="fade-up") Guía para configurar dispositivos móviles
              p.mb-0.text-white(data-aos="fade-up") De acuerdo con el Control 6.2.1 de la Norma ISO 27001 Anexo A, se deben establecer políticas que establezcan las medidas para la seguridad de la información gestionada a través de dispositivos móviles y adoptar los controles necesarios para su administración, por ejemplo, aplicar controles como los sugeridos por la Oficina de Seguridad del Internauta OSI, en su publicación titulada “Guía para configurar dispositivos móviles”, en la cual brinda algunas recomendaciones básicas para contar con un nivel básico de seguridad en los dispositivos. Ingresando al siguiente enlace, podrá conocer todo al respecto:
            .col-sm-auto
              a.boton.color-acento-botones(href="https://www.osi.es/es/guia-para-configurar-dispositivos-moviles" target="_blank" data-aos="fade-left")
                span Ir a enlace

    Separador.mt-5

    .titulo-segundo
      h2#t_7_3 7.3 #[em Telework and Bring Your Own Device (BYOD) Security (NIST-SP800-114)]

    .tarjeta.color-primario.p-4.mt-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/tema7/14.svg" data-aos="fade-right")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.mb-1.text-white(data-aos="fade-up") Guía NIST-SP800-114
              p.mb-0.text-white(data-aos="fade-up") El Instituto NIST ofrece la guía NIST-SP800-114 para el aseguramiento de actividades realizadas bajo la modalidad de teletrabajo y la adopción de la filosofía BYOD para el desarrollo de sus actividades contractuales. Clic en el enlace para observarla.
            .col-sm-auto
              a.boton.color-acento-botones(href="https://csrc.nist.gov/publications/detail/sp/800-114/rev-1/final" target="_blank" data-aos="fade-left")
                span Ir a enlace

    .row.mb-5.m-0.mt-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Aspectos importantes de la guía

    .row.cont_7_2(style="position:relative;")
      .col-lg-10.col-md-8.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") La guía se encuentra estructurada por secciones que abordan los conceptos y las recomendaciones para la implantación de controles, de las cuales se resaltan seguidamente:
      .col-lg-2.col-md-4(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema7/15.svg" data-aos="fade-left" style="max-width:100px;")

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 13.
      span Guía para NIST-SP800-114)
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema7/16.svg" data-aos="zoom-in-up")
      img.d-block.d-lg-none(src="@/assets/curso/tema7/17.svg" data-aos="zoom-in-up")


    p.mt-5(data-aos="fade-up") #[strong Si la organización tiene implementada la modalidad de teletrabajo, se recomienda tener presente esta guía.]

    .row.mb-5.m-0.mt-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Seguridad en el teletrabajo

    .row
      .col-lg-8.mb-4.mb-lg-0(style="place-self:center")
        p(data-aos="fade-up") Las organizaciones actualmente vienen habilitando las capacidades para poder desarrollar sus actividades sin que necesariamente sus empleados se encuentren en la sede física y, aprovechando la reglamentación y cumplimiento tanto legal como laboral, estas deben garantizar que los empleados cuenten con los recursos necesarios para el desarrollo de sus actividades; entre estos, se encuentran las condiciones de seguridad, por ello, se sugiere considerar las siguientes recomendaciones adicionales para el desarrollo de actividades bajo la modalidad de teletrabajo:
      .col-lg-4(style="place-self:center")
        figure
          img(src="@/assets/curso/tema7/18.png" data-aos="fade-left")

    .row.mt-5.cont_7_3.p-4.pt-5.pb-5
      .col-lg-4.mb-4.mb-lg-0.col-xl-3(style="place-self:center")
        figure.d-flex.justify-content-center.col-md-6.col-6.m-auto
          img(src="@/assets/curso/tema7/20.svg" data-aos="fade-right")
      .col-lg-8.col-xl-9(style="place-self:center")
        ul.fa-ul
          li.mb-2(data-aos="fade-up")
            i.fa-li.fas.fa-check-circle(style="color:#40327B;")
            | Uso de equipos adecuados.
          li.mb-2(data-aos="fade-up")
            i.fa-li.fas.fa-check-circle(style="color:#40327B;")
            | Garantizar el acceso a la información, de acuerdo con las condiciones y controles de seguridad anteriormente nombrados.
          li.mb-2(data-aos="fade-up")
            i.fa-li.fas.fa-check-circle(style="color:#40327B;")
            | Contar con mecanismos de conexión segura, evitando hacer uso de canales abiertos y públicos.
          li.mb-2(data-aos="fade-up")
            i.fa-li.fas.fa-check-circle(style="color:#40327B;")
            | Proveer de herramientas contra #[em malware] actualizadas.
          li.mb-2(data-aos="fade-up")
            i.fa-li.fas.fa-check-circle(style="color:#40327B;")
            | Mantener un monitoreo permanente del tráfico de la red donde se encuentran los activos de información.
          li.mb-2(data-aos="fade-up")
            i.fa-li.fas.fa-check-circle(style="color:#40327B;")
            | Contar con políticas de seguridad implementadas e informadas a todo el personal.






</template>

<script>
export default {
  name: 'Tema7',
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
.cont_7_1 *
  position: relative
.cont_7_1:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #DAF1F5
.cont_tarjeta_7_1
  background-image: url(../assets/curso/tema7/2.png)
  background-size: 100% 100%
  background-color: white !important
.cont_tarjeta_7_2
  background-image: url(../assets/curso/tema7/3.png)
  background-size: 100% 100%
  background-color: white !important
.cont_slyderab1
  background: url(../assets/curso/tema7/21.png)
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
.cont_7_2 *
  position: relative
.cont_7_2:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #D5CEF8
.cont_7_3
  background-image: url(../assets/curso/tema7/19.png)
  background-size: 100% 100%
</style>
