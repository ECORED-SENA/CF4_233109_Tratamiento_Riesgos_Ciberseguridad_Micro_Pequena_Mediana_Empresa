<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Gestión de acceso

    .row
      .col-lg-4.mb-4.mb-lg-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema1/1.png" data-aos="fade-right")
      .col-lg-8(style="place-self:center")
        p(data-aos="fade-up") La gestión de acceso cobra un gran valor, ya que permite establecer los controles y condiciones bajo los cuales un usuario puede hacer uso de los activos de información de la empresa.
        p.mt-4(data-aos="fade-up") De acuerdo con el Instituto Nacional de Ciberseguridad de España, el objetivo de este control es #[strong “Establecer quién, cómo y cuándo puede acceder a los activos de información de la empresa y registrar convenientemente dichos accesos” (INCIBE, 2017)]. Esto conlleva establecer controles que permitan una adecuada gestión de los permisos de los usuarios u otros sistemas de información para interactuar con los activos de la organización.
        p.mt-4(data-aos="fade-up") A continuación, es posible ver los pasos técnicos que se deben valorar para gestionar una adecuada autorización y acceso a los recursos requeridos, y estos son:

    .row.mt-5.col-xl-10.m-auto
      .col-lg.mb-4.mb-lg-0
        .p-4.h-100.cont_tarjeta1(style="background-color:#583AE2;border-radius:15px;")
          img.img_fondo(src="@/assets/curso/tema1/2.png")
          figure
            img(src="@/assets/curso/tema1/3.png" data-aos="zoom-in-up")
          h4.text-white.mt-4(data-aos="fade-up") Identificación
          p.mt-4.text-white(data-aos="fade-up") Permite identificar particularmente un usuario o un sistema con un identificador único y diferenciarlo de otros.
      .col-lg.mb-4.mb-lg-0
        .p-4.h-100.cont_tarjeta1(style="background-color:#583AE2;border-radius:15px;")
          img.img_fondo(src="@/assets/curso/tema1/2.png")
          figure
            img(src="@/assets/curso/tema1/4.png" data-aos="zoom-in-up")
          h4.text-white.mt-4(data-aos="fade-up") Autenticación
          p.mt-4.text-white(data-aos="fade-up") Permite validar que el usuario o sistema que intenta acceder a un recurso es quien dice ser, mediante la validación de un mecanismo como, por ejemplo: contraseña, pin, token o cualquier otro mecanismo asociado.
      .col-lg.mb-4.mb-lg-0
        .p-4.h-100.cont_tarjeta1(style="background-color:#583AE2;border-radius:15px;")
          img.img_fondo(src="@/assets/curso/tema1/2.png")
          figure
            img(src="@/assets/curso/tema1/5.png" data-aos="zoom-in-up")
          h4.text-white.mt-4(data-aos="fade-up") Autorización
          p.mt-4.text-white(data-aos="fade-up") Consiste en el permiso específico sobre el recurso al cual desea acceder, por ejemplo, un rol en una tabla de una base de datos.

    p.mt-5(data-aos="fade-up") A continuación, en la siguiente figura, es posible apreciar un esquema que ilustra los pasos de un control para la gestión de accesos:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 1.
      span Pasos de un control de gestión de acceso
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema1/6.svg" data-aos="zoom-in-up" alt="La imagen presenta los pasos de un control de gestión de acceso, el cual comienza con el usuario, la identificación, autenticación y autorización. Si en esta última se bloquea, presenta alerta y reporte, y si se autoriza, va a los recursos.")
      img.d-block.d-lg-none(src="@/assets/curso/tema1/7.svg" data-aos="zoom-in-up" alt="La imagen presenta los pasos de un control de gestión de acceso, el cual comienza con el usuario, la identificación, autenticación y autorización. Si en esta última se bloquea, presenta alerta y reporte, y si se autoriza, va a los recursos.")
      figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Adaptado de ICHI.PRO - Introducción a la gestión de identidades y accesos

    p.mt-5(data-aos="fade-up") Como factor fundamental de este control, se debe considerar contar con mecanismos de auditoría que registren y/o alerten sobre accesos no permitidos o fallidos, con el fin de determinar accesos no autorizados.

    Separador.mt-5

    .titulo-segundo
      h2#t_1_1 1.1 Tipos

    .row.cont_1_1(style="position:relative;")
      .col-lg-10.col-md-12.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") El control para la gestión de accesos se puede abordar desde diferentes frentes, tanto de gestión como técnicos. A continuación, se van a identificar algunos de los más comunes:
      .col-lg-2.col-md-4(style="place-self:center").d-none.d-lg-block
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema1/8.svg" data-aos="fade-left" style="max-width:100px;")

    p.mt-4(data-aos="fade-up") #[strong De acuerdo con la complejidad del control, estos pueden ser:]

    .row.mt-5.col-xl-10.m-auto

      .col-lg.mb-4.mb-lg-0
        .p-4.h-100.cont_tarjeta2(style="background-color:#583AE2;border-radius:15px;")
          img.img_fondo(src="@/assets/curso/tema1/12.png")
          figure.d-flex.justify-content-center
            img(src="@/assets/curso/tema1/10.svg" data-aos="zoom-in-up" style="max-width:140px;")
          h4.text-white.mt-4.text-center(data-aos="fade-up") Básicos
          p.mt-4.text-white(data-aos="fade-up") Su implementación no requiere de mayor esfuerzo ni ajustes en los sistemas de información y pueden abordarse con capacitaciones y controles básicos.

      .col-lg.mb-4.mb-lg-0
        .p-4.h-100.cont_tarjeta2(style="background-color:#583AE2;border-radius:15px;")
          img.img_fondo(src="@/assets/curso/tema1/12.png")
          figure.d-flex.justify-content-center
            img(src="@/assets/curso/tema1/11.svg" data-aos="zoom-in-up" style="max-width:140px;")
          h4.text-white.mt-4.text-center(data-aos="fade-up") Avanzados
          p.mt-4.text-white(data-aos="fade-up") Estos controles requieren de herramientas avanzadas y establecimiento de políticas y controles, como, por ejemplo, la implementación de servicios de directorio activo y la implementación de políticas de grupo.

    p.mt-5(data-aos="fade-up") Dentro de los tipos de accesos a los sistemas de información, es necesario considerar los siguientes controles:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 2.
      span Tipos de accesos a los sistemas de información - Controles

    figure.mt-5
      img(src="@/assets/curso/tema1/13.svg" data-aos="zoom-in-up" alt="La imagen presenta los tipos de accesos a los sistemas de información, los cuales contienen controles y se clasifican en control para la gestión de usuario y control accesos, el cual a su vez se clasifican en control de accesos a dispositivos, control de acceso a los sistemas de información y activos y control de acceso a recursos de red.")

    Separador.mt-5

    .titulo-segundo
      h2#t_1_2 1.2 Características

    p(data-aos="fade-up") La implementación de los controles para gestión del acceso debe contemplar ciertas condiciones que eleven la complejidad y dificulten el acceso no autorizado a los activos de información de la organización, como, por ejemplo:

    SlyderF.mt-5(columnas="col-lg-6 col-xl-4")
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/14.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Privilegio mínimo
            p.mt-4(style="color:#12263F !important;") Cualquier autorización de acceso debe darse de acuerdo con las necesidades de cada rol y necesidad, por ejemplo, no hacer uso de credenciales de DBA en un usuario de conexión a través de una página web.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/15.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Usuarios por defecto
            p.mt-4(style="color:#12263F !important;") Reducir el uso de usuarios que vienen por defecto en los sistemas operativos o aplicaciones, ya que estos son utilizados en ataques de fuerza bruta.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/16.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Actualización de credenciales
            p.mt-4(style="color:#12263F !important;") Establecer los controles que requieran la actualización de contraseñas periódicamente.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/17.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Uso de credenciales complejas
            p.mt-4(style="color:#12263F !important;") Promover, a través de controles, el uso de contraseñas seguras.
      .tarjeta-avatar
        img(src='@/assets/curso/tema1/18.svg' style="max-width:120px")
        .tarjeta.color-primario.cont_slydef1
          .text-white.p-4.text-center
            h4.text-center(style="color:#12263F !important;") Almacenamiento de credenciales seguro
            p.mt-4(style="color:#12263F !important;") Toda la información relacionada con información de usuarios, debe almacenarse de manera segura, haciendo uso de algoritmos de cifrado unidireccional y bajo, bajo algún mecanismo de cifrado de base de datos.



</template>

<script>
export default {
  name: 'Tema1',
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
.cont_tarjeta1
  position: relative
  overflow: hidden
.cont_tarjeta1 *
  position: relative
.cont_tarjeta1 .img_fondo
  position: absolute
  content: ''
  top: 0
  z-index: 0
  left: -11px
.cont_1_1 *
  position: relative
.cont_1_1:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #B5E4EB
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
</style>
