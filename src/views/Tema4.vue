<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 UTM/XTM

    .row.cont_4_1(style="position:relative;")
      .col-lg-10.col-md-8.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") Integra soluciones (como #[em firewall], ids, ips) en un solo dispositivo conocido como UTM (#[em Unified Threat Management]) o Gestión Unificada de Amenazas y los XTM (Extensible UTM) o UTM Extendido, los cuales cubren las necesidades básicas y más comunes requeridas por las organizaciones en una única solución. A continuación, puede reconocer en qué se diferencia cada uno de ellos:
      .col-lg-2.col-md-4(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema4/1.svg" data-aos="fade-left" style="max-width:100px;")

    .row.mt-5.col-xl-10.m-auto
      .col-lg-6.mb-5.mb-lg-0
        .p-4.pt-5.h-100.cont_scale_1
          figure
            img(src="@/assets/curso/tema4/4.png" data-aos="zoom-in-up")
          h4.mt-4.text-center(data-aos="fade-up") UTM (#[em Unified Threat Management])
          p.mt-4(data-aos="fade-up") UTM, o Gestión Unificada de Amenazas, es una solución novedosa y que integra las soluciones que requieren las organizaciones hoy en día; de acuerdo con Fortinet, “consolida múltiples funciones de seguridad y redes con un #[em appliance] unificado que protege a las empresas y simplifica la infraestructura” (FORTINET, 2021), permitiendo encontrar en una sola solución herramientas como: #[em firewall], IDS/IPS, antivirus, #[em antimalware], filtrado #[em antispam], filtrado web, acceso remoto seguro como VPN y una amplia variedad de reportes que simplifican la administración de este tipo de arquitecturas.
      .col-lg-6.mb-5.mb-lg-0
        .p-4.pt-5.h-100.cont_scale_2
          figure
            img(src="@/assets/curso/tema4/5.png" data-aos="zoom-in-up")
          h4.mt-4.text-center(data-aos="fade-up") XTM (#[em Extensible UTM])
          p.mt-4(data-aos="fade-up") XTM o UTM Extendido, como su nombre lo indica, permite ampliar las capacidades del UTM, agregando en una única solución herramientas de #[em logging], protección de la reputación, correlación de eventos, herramientas para control de acceso a la red, capacidad de gestión de vulnerabilidades, así como capacidad de gestión del ancho de banda de red y control de tráfico; extendiendo así las capacidades de administrar de una mejor manera la seguridad perimetral.

    p.mt-5(data-aos="fade-up") Este tipo de soluciones ha ganado campo de aplicación por sus capacidades de ajustarse a casi cualquier tipo de organización, facilitando su implementación y administración.

    Separador.mt-5

    .titulo-segundo
      h2#t_4_1 4.1 Tipos

    p(data-aos="fade-up") Las diferencias entre este tipo de dispositivos no son tan significativas a simple vista, se requiere de un análisis de las operaciones de análisis que puede realizar para identificar cuál es la más indicada para cada organización:

    .row.mt-5.col-xl-10.m-auto
      .col-lg.mb-4.mb-lg-0
        .p-4.h-100.cont_tarjeta2(style="background-color:#583AE2;border-radius:15px;")
          img.img_fondo(src="@/assets/curso/tema1/12.png")
          figure.d-flex.justify-content-center
            img(src="@/assets/curso/tema4/6.svg" data-aos="zoom-in-up" style="max-width:180px;")
          h4.text-white.mt-4.text-center(data-aos="fade-up") UTM/XTM
          p.mt-4.text-white(data-aos="fade-up") Este tipo de soluciones, como se mencionó anteriormente, además de sus funciones de #[em firewall], cuenta con herramientas como sistemas de prevención de intrusiones, antivirus, filtros de URL, red privada virtual (VPN), balanceo de enlaces, informes de seguridad, entre otros; este tipo de soluciones se puede encontrar tanto en presentación de #[em hardware] como #[em software]; este modelo es muy recomendado para pequeñas organizaciones.
      .col-lg.mb-4.mb-lg-0
        .p-4.h-100.cont_tarjeta3(style="background-color:#45BBCC;border-radius:15px;")
          img.img_fondo(src="@/assets/curso/tema1/9.png")
          figure.d-flex.justify-content-center
            img(src="@/assets/curso/tema4/7.svg" data-aos="zoom-in-up" style="max-width:180px;")
          h4.mt-4.text-center(data-aos="fade-up") NGFW
          p.mt-4(data-aos="fade-up") Este tipo de #[em firewall] de nueva generación incorpora herramientas para el análisis de amenazas recientes, así como #[em malware] que frecuentemente aparece en nuevas versiones y modalidades de ataques; este tipo de soluciones se recomienda en grandes organizaciones o aquellas que presentan gran cantidad de solicitudes y acceso a través de red.

    .mt-5.p-4(style="background-color:#B5E4EB;border-radius:15px;")
      p.mb-0(data-aos="fade-up") #[strong Una de las principales diferencias entre estas soluciones es que el NGFW puede realizar una inspección avanzada de paquetes y permite establecer políticas para gestionar el acceso seguro a los recursos.]

    Separador.mt-5

    .titulo-segundo
      h2#t_4_2 4.2 Características

    .row.cont_4_2(style="position:relative;")
      .col-lg-2.col-md-4.mb-4.mb-md-0(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema4/8.svg" data-aos="fade-left" style="max-width:100px;")
      .col-lg-10.col-md-8
        p.mb-0(data-aos="fade-up") Este tipo de dispositivos UTM/XTM cuenta con las capacidades para realizar la gestión de la seguridad, mediante la administración tráfico, análisis de #[em malware], control de aplicaciones, gestión de vlan, como lo demuestra la siguiente figura:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 6.
      span Características y funcionalidades de los UTM/XTM
    figure.mt-4
      img(src="@/assets/curso/tema4/9.svg" data-aos="zoom-in-up")
      figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Adaptado de http://fibraoptica.blog.tartanga.eus/files/2018/01/Equipos-UTM-2-2.jpg







</template>

<script>
export default {
  name: 'Tema4',
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
.cont_4_1 *
  position: relative
.cont_4_1:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #D5CEF8
.cont_scale_1
  background: url(../assets/curso/tema4/2.png)
  background-repeat: no-repeat
  background-size: cover
  border-radius: 20px
  transition: all .3s ease-out
.cont_scale_2
  background: url(../assets/curso/tema4/3.png)
  background-repeat: no-repeat
  background-size: cover
  border-radius: 20px
  transition: all .3s ease-out
.cont_scale_1:hover,.cont_scale_2:hover
  transform: translateY(-30px)
.cont_tarjeta2
  position: relative
  overflow: hidden
.cont_tarjeta2 *
  position: relative
.cont_tarjeta2 .img_fondo
  position: absolute
  content: ''
  top: 0
  z-index: 0
  left: 0
  max-width: 250px
.cont_tarjeta3
  position: relative
  overflow: hidden
.cont_tarjeta3 *
  position: relative
.cont_tarjeta3 .img_fondo
  position: absolute
  content: ''
  z-index: 0
  right: 0
  bottom: 0
  max-width: 280px
.cont_4_2 *
  position: relative
.cont_4_2:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  left: 0
  top: -10%
  background-color: #D5CEF8
</style>
