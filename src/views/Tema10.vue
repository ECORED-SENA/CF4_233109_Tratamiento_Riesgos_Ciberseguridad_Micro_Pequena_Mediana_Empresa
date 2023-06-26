<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 10
      h1 Parcheado y/o actualización

    .row
      .col-lg-8.col-md-12.mb-4.mb-lg-0(style="place-self:center;")
        p(data-aos="fade-up") La gestión de las actualizaciones y parcheo de los sistemas de información o de los dispositivos de la organización se convierte en un factor fundamental para garantizar la seguridad de la información, ya que, a partir de esta gestión, es posible reducir amenazas por desactualización de sistemas y evitar que terceros puedan aprovecharla.
        p.mt-4(data-aos="fade-up") Desde los estándares de seguridad abordados, se presenta como una premisa que se deben mantener los sistemas de información, aplicaciones e incluso dispositivos de red actualizados en su última versión, lo que garantiza que cuenten con los últimos ajustes y solución a #[em bugs] que puedan ser aprovechados para abrir brechas a la seguridad de la información.
        p.mt-4(data-aos="fade-up") #[strong A continuación, se van a revisar algunos detalles importantes relacionados con este ejercicio y así poder comprender su utilidad y necesidad de aplicarlos en la infraestructura tecnológica:]
      .col-lg-4(style="place-self:center").d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema10/1.png" data-aos="fade-left")

    Separador.mt-5

    .titulo-segundo
      h2#t_10_1 10.1 Tipos

    p(data-aos="fade-up") Los parches para las aplicaciones se pueden clasificar de acuerdo con cómo están estructurados y cómo se distribuyen, es así como es posible clasificarlos de acuerdo con el código:

    .row.cont_10_1.mt-5.p-4.pt-5.pb-5
      .col-lg-3.mb-4.mb-lg-0(style="place-self:center")
        figure.text-center
          img(src="@/assets/curso/tema10/3.svg" data-aos="fade-right" style="max-width:120px;display:inline;")
      .col-lg-9(style="place-self:center")
        ul.fa-ul
          li.mb-3.d-block(data-aos="fade-up")
            i.fa-li.fa.fa-check-circle(style="color:#40327B;")
            | #[strong Parches de archivos binarios:] cuando se realiza el reemplazo de un archivo ejecutable, compilado y que no puede ser alterado por el usuario final.
          li.mb-3.d-block(data-aos="fade-up")
            i.fa-li.fa.fa-check-circle(style="color:#40327B;")
            | #[strong Parches de código fuente:] son las actualizaciones de fragmentos de aplicaciones o rutinas que se implementan en un sistema y este los puede interpretar a partir de un intérprete de comandos, o este tiene la potestad de compilar directamente sobre el sistema, muy comúnmente cuando se realiza parcheo de aplicaciones web.

    p.mt-5(data-aos="fade-up") #[strong Ahora bien, los parches también se pueden clasificar de acuerdo con el propósito para el cual fueron generados, es así como es posible clasificarlos de la siguiente manera:]

    .row.justify-content-center.p-4.p-md-5.mt-5(style="background-color:#D5CEF8;")
      .col-lg-8.mb-4.mb-lg-0(style="place-self:center")
        ul.fa-ul
          li.mb-3.d-block(data-aos="fade-up")
            i.fa-li.fa.fa-check-circle(style="color:#40327B;")
            span #[strong Parche de reparación:] parche que corrige fallas o #[em bugs] en los sistemas.
          li.mb-3.d-block(data-aos="fade-up")
            i.fa-li.fa.fa-check-circle(style="color:#40327B;")
            span #[strong Parche de seguridad:] parches que solucionan agujeros de seguridad o brechas en la seguridad del mismo, sin modificar la funcionalidad del sistema.
          li.mb-3.d-block(data-aos="fade-up")
            i.fa-li.fa.fa-check-circle(style="color:#40327B;")
            span #[strong Parche de actualización:] este tipo de parches actualiza algunas rutinas, métodos, o agrega funcionalidades al sistema.
          li.mb-3.d-block(data-aos="fade-up")
            i.fa-li.fa.fa-check-circle(style="color:#40327B;")
            span #[strong Parche de traducción:] este tipo de parches permite cambiar el lenguaje de un sistema.
          li.mb-3.d-block(data-aos="fade-up")
            i.fa-li.fa.fa-check-circle(style="color:#40327B;")
            span #[strong Parche de piratería ilegal:] este parche, denominado también #[em crack], permite liberar funcionalidades o alterar rutinas del sistema de manera ilegal.
          li.mb-3.d-block(data-aos="fade-up")
            span #[strong No se recomienda la aplicación de este tipo de parches en organizaciones. ]
      .col-lg-4.col-7
        figure
          img(src="@/assets/curso/tema10/4.svg" data-aos="fade-left")

    Separador.mt-5

    .titulo-segundo
      h2#t_10_2 10.2 Características

    .row.cont_10_2(style="position:relative;")
      .col-lg-10.col-md-12.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") A continuación, se van a reconocer algunas características y recomendaciones para una adecuada gestión de parches y actualizaciones en sistemas de información y de arquitecturas tecnológicas en las organizaciones.
      .col-lg-2.col-md-4(style="place-self:center").d-none.d-xl-block
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema10/5.svg" data-aos="fade-left" style="max-width:100px;")

    SlyderF.mt-5(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-primario.cont_slydef1.p-4
        figure.text-center
          img(src='@/assets/curso/tema10/6.svg' style="max-width:100px;display:inline;")
        .text-white.text-center
          p.mt-4(style="color:#12263F !important;") Buscar información de actualizaciones y descargarlas de sitios oficiales.
      .tarjeta.color-primario.cont_slydef1.p-4
        figure.text-center
          img(src='@/assets/curso/tema10/7.svg' style="max-width:100px;display:inline;")
        .text-white.text-center
          p.mt-4(style="color:#12263F !important;") Validar las actualizaciones, tanto de manera previa como posterior, para verificación de funcionalidad de los sistemas.
      .tarjeta.color-primario.cont_slydef1.p-4
        figure.text-center
          img(src='@/assets/curso/tema10/8.svg' style="max-width:100px;display:inline;")
        .text-white.text-center
          p.mt-4(style="color:#12263F !important;") Preferiblemente, realizar la instalación en ambiente de pruebas, y posteriormente, en producción.
      .tarjeta.color-primario.cont_slydef1.p-4
        figure.text-center
          img(src='@/assets/curso/tema10/9.svg' style="max-width:100px;display:inline;")
        .text-white.text-center
          p.mt-4(style="color:#12263F !important;") Siempre mantener las actualizaciones de los sistemas al día, a excepción de las documentadas por requerimientos técnicos o compatibilidades.
      .tarjeta.color-primario.cont_slydef1.p-4
        figure.text-center
          img(src='@/assets/curso/tema10/10.svg' style="max-width:100px;display:inline;")
        .text-white.text-center
          p.mt-4(style="color:#12263F !important;") Mantener los sistemas operativos, sistemas de información y aplicaciones de uso diario actualizados.
      .tarjeta.color-primario.cont_slydef1.p-4
        figure.text-center
          img(src='@/assets/curso/tema10/11.svg' style="max-width:100px;display:inline;")
        .text-white.text-center
          p.mt-4(style="color:#12263F !important;") Implemente soluciones para la automatización de actualizaciones generales, como, por ejemplo, WSUS para sistemas Microsoft.
      .tarjeta.color-primario.cont_slydef1.p-4
        figure.text-center
          img(src='@/assets/curso/tema10/12.svg' style="max-width:100px;display:inline;")
        .text-white.text-center
          p.mt-4(style="color:#12263F !important;") Establezca horarios de actualizaciones automáticas que no afecten el desarrollo de las actividades laborales.




</template>

<script>
export default {
  name: 'Tema10',
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
.cont_10_1
  background: url(../assets/curso/tema10/2.png)
  background-size: cover
.cont_10_2 *
  position: relative
.cont_10_2:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #DAF1F5
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
