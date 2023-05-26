<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 11
      h1 Plan de capacitación y concienciación

    p(data-aos="fade-up") La estrategia de formación a las personas interesadas, empleadas o que administran la información en las organizaciones hoy en día cobra gran importancia, dado que, aun a pesar de la gran capacidad de adquisición tecnológica, herramientas e implementación de controles, se necesitan fortalecer y formar en las siguientes habilidades:

    .row.mt-5
      .col-lg-6.mb-4.mb-xl-0.col-xl
        .h-100.p-4.cont_tarjeta_11_1(style="position:relative;background-color:#D5CEF8;border-radius:10px;")
          figure
            img(src="@/assets/curso/tema11/3.png" data-aos="zoom-in-up")
          p.mt-4(data-aos="fade-up") Formar conciencia en el manejo seguro de la información.
      .col-lg-6.mb-4.mb-xl-0.col-xl
        .h-100.p-4.cont_tarjeta_11_1(style="position:relative;background-color:#D5CEF8;border-radius:10px;")
          figure
            img(src="@/assets/curso/tema11/4.png" data-aos="zoom-in-up")
          p.mt-4(data-aos="fade-up") Enfrentar amenazas de ingeniería social donde se aprovechan de estas debilidades de las personas que administran la información para socavarla, y, haciendo uso de engaños o campañas falsas, buscan acceder a los activos de la organización con fines delictivos.
      .col-lg-6.mb-4.mb-xl-0.col-xl
        .h-100.p-4.cont_tarjeta_11_1(style="position:relative;background-color:#D5CEF8;border-radius:10px;")
          figure
            img(src="@/assets/curso/tema11/5.png" data-aos="zoom-in-up")
          p.mt-4(data-aos="fade-up") Fortalecer las habilidades para la gestión de entornos de trabajo seguros, donde sus empleados consigan organizar, en primer lugar. espacios limpios y que no dejen a disposición de terceros información sensible.
      .col-lg-6.mb-4.mb-xl-0.col-xl
        .h-100.p-4.cont_tarjeta_11_1(style="position:relative;background-color:#D5CEF8;border-radius:10px;")
          figure
            img(src="@/assets/curso/tema11/6.png" data-aos="zoom-in-up")
          p.mt-4(data-aos="fade-up") Fortalecer las capacidades para gestionar la información haciendo uso de herramientas y buenas prácticas que eviten que terceros puedan interceptarla.

    p.mt-5(data-aos="fade-up") #[strong A continuación, vamos a establecer algunas recomendaciones para el establecimiento de planes de capacitación que se sugieren sean adoptados por las organizaciones:]

    Separador.mt-5

    .titulo-segundo
      h2#t_11_1 11.1 Ruta de actualización

    .row.cont_11_1(style="position:relative;")
      .col-lg-10.col-md-8.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") Partiendo de la premisa que las organizaciones deben invertir en formar a su personal y establecer la forma en que estos deben gestionar y salvaguardar la información, estas deben de establecer los planes de formación y actualización que precisa su personal, estar al tanto de las últimas estrategias que utilizan los ciberdelincuentes para acceder a la información, así como reconocer algunos comportamientos anómalos que, si bien no conocen del tema por no ser de su competencia, deberán conocer una ruta para reportar a las áreas responsables de cada organización; para esto, se recomienda que las organizaciones consideren algunas de las siguientes rutas de información:
      .col-lg-2.col-md-4(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema11/7.svg" data-aos="fade-left" style="max-width:100px;")

    .col-xl-10.m-auto.mt-5
      h3(data-aos="fade-up") Conceptos de seguridad
      AcordionA.mt-4(tipo="b" clase-tarjeta="tarjeta tarjeta--gris")
        .row(titulo="Técnicas más comunes utilizadas por los ciberdelincuentes")
          .col-md-4.mb-4.mb-md-0
            figure
              img(src="@/assets/curso/tema11/9.png")
          .col-md-8
            ul.fa-ul
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Ingeniería social.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | #[em Phishing].
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | #[em Spam].
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | #[em Pharming].
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Accesos físicos.

        .row(titulo="Ataques más comunes de la actualidad")
          .col-md-4.mb-4.mb-md-0
            figure
              img(src="@/assets/curso/tema11/10.png")
          .col-md-8
            ul.fa-ul
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Cifrado #[em (Ransomware)].
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | #[em Malware].
        .row(titulo="Normatividad vigente")
          .col-md-4.mb-4.mb-md-0
            figure
              img(src="@/assets/curso/tema11/11.png")
          .col-md-8
            ul.fa-ul
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | SGSI.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Normatividad gubernamental (instituciones públicas).
        .row(titulo="Uso de herramientas seguras para la gestión de la información en la organización")
          .col-md-4.mb-4.mb-md-0
            figure
              img(src="@/assets/curso/tema11/12.png")
          .col-md-8
            ul.fa-ul
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Navegadores seguros.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Herramientas criptográficas.
        .row(titulo="Buenas prácticas de seguridad")
          .col-md-4.mb-4.mb-md-0
            figure
              img(src="@/assets/curso/tema11/13.png")
          .col-md-8
            ul.fa-ul
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Campañas para mantener un escritorio y entorno limpios.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Reconocimiento de mensajes seguros.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Uso de contraseñas seguras.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Uso de protocolos seguros.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Actualizaciones.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Uso de canales seguros (vpn, proxy, ssh).
        .row(titulo="Ataques de ingeniería social")
          .col-md-4.mb-4.mb-md-0
            figure
              img(src="@/assets/curso/tema11/14.png")
          .col-md-8
            ul.fa-ul
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Reconocimiento.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Actuación frente a un ataque.
        .row(titulo="Incidentes que afecten la seguridad de la información")
          .col-md-4.mb-4.mb-md-0
            figure
              img(src="@/assets/curso/tema11/15.png")
          .col-md-8
            ul.fa-ul
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Ruta para el reporte de incidentes.
              li.mb-1.d-block(data-aos="fade-up")
                i.fa-li.fa.fa-angle-right(style="color:#583AE2;")
                | Acciones a realizar durante y después del incidente.

    p.mt-5(data-aos="fade-up") Los temas expuestos anteriormente son algunos de los que se recomienda sean abordados por el personal, lo cual permitirá reconocer y determinar el actuar frente a un incidente.

    Separador.mt-5

    .titulo-segundo
      h2#t_11_2 11.2 Estrategia de transferencia del conocimiento

    p(data-aos="fade-up") Las estrategias para la transferencia del conocimiento hacia el personal deben ser dinámicas y que no solo se queden en un momento de charla; se recomienda que se considere que los planes de capacitación cuenten con algunas de las siguientes estrategias que permitan reforzar la seguridad de la información:

    .row.mt-5
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_11_2.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema11/16.svg" data-aos="zoom-in-up" style="max-width:80px;")
          p.mt-4(data-aos="fade-up") #[strong Capacitaciones #[em in situ] periódicas] #[br] Estas permitirán convocar a que las personas asistan a jornadas de capacitación sobre temas que permitan mejorar la seguridad de la información.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_11_2.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema11/16.svg" data-aos="zoom-in-up" style="max-width:80px;")
          p.mt-4(data-aos="fade-up") #[strong Canales de autoformación] #[br] Establecer medios para que los empleados consulten y realicen ejercicios para mejorar sus capacidades de seguridad para la gestión de la información.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_11_2.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema11/16.svg" data-aos="zoom-in-up" style="max-width:80px;")
          p.mt-4(data-aos="fade-up") #[strong Ejercicios de demostración] #[br] Conformar ejercicios para que los empleados se enfrenten a situaciones, como, por ejemplo, de ingeniería social, lo cual les permitirá reconocer patrones de comportamiento, así como identificar la ruta de actuación frente a una situación en particular, como se puede apreciar en la figura.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_11_2.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema11/16.svg" data-aos="zoom-in-up" style="max-width:80px;")
          p.mt-4(data-aos="fade-up") #[strong Campañas de socialización] #[br] Las campañas de socialización que se puedan desplegar a través de fondos de escritorios, volantes, correos, mensajería instantánea, donde se den #[em tips] y recomendaciones para la gestión de la seguridad.

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 20.
      span Planes de formación y capacitación sobre gestión de la ciberseguridad en las organizaciones
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema11/17.svg" data-aos="zoom-in-up")
      img.d-block.d-lg-none(src="@/assets/curso/tema11/17.svg" data-aos="zoom-in-up")
      figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Tomado de https://www.alert-software.com/hs-fs/hubfscyber%20security%20campaign.png

    p.mt-5(data-aos="fade-up") #[strong Estas acciones se pueden articular de acuerdo con las características de cada una de las organizaciones y de los activos que administre, permitiendo fortalecer en sus empleados esas capacidades de identificar, enfrentar y evitar que se consoliden incidentes que afecten la seguridad de la información.]




</template>

<script>
export default {
  name: 'Tema11',
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
.cont_tarjeta_11_1 *,.cont_tarjeta_11_1
  position: relative
  z-index: 1
.cont_tarjeta_11_1:before
  content: ''
  position: absolute
  width: 150px
  height: 150px
  left: 0
  top: 0
  background: url(../assets/curso/tema11/1.png)
  background-repeat: no-repeat
  z-index: 0
.cont_tarjeta_11_1:after
  content: ''
  position: absolute
  width: 110px
  height: 110px
  right: 0
  bottom: 0
  background: url(../assets/curso/tema11/2.png)
  background-repeat: no-repeat
  z-index: 0
.cont_tarjeta_11_1:hover
  background-color: #2FF980 !important
.cont_11_1 *
  position: relative
.cont_11_1:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #D5CEF8
.cont_tarjeta_11_2:hover
  background-color: #6AC9D6 !important
.tarjeta.tarjeta--gris.acordion__activo
  background-color: #DAF1F5
</style>
