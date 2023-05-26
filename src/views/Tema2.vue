<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 #[em Firewall]

    .row.cont_2_1(style="position:relative;")
      .col-lg-10.col-md-8.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") Los #[em Firewalls], también conocidos como cortafuegos, cumplen la función de proteger los activos de información de la organización mediante la gestión del tráfico entrante y saliente entre redes, permitiendo bloquear o garantizar el acceso a partir de la aplicación de políticas, tal como se muestra en la siguiente figura. Teniendo presente el tráfico, por defecto, debe partir de la siguiente lógica:
      .col-lg-2.col-md-4(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema2/1.svg" data-aos="fade-left" style="max-width:100px;")

    .row.mt-5.col-xl-8.m-auto
      .col-lg.mb-4.mb-lg-0
        .p-4.h-100(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema2/2.svg" data-aos="zoom-in-up" style="max-width:100px")
          p.mt-3(data-aos="fade-up") #[strong Tráfico entrante:] bloquea todo el tráfico entrante y autoriza lo necesario.
      .col-lg.mb-4.mb-lg-0
        .p-4.h-100(style="background-color:#2FF980;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema2/3.svg" data-aos="zoom-in-up" style="max-width:100px")
          p.mt-3(data-aos="fade-up") #[strong Tráfico saliente:] permite todo el tráfico saliente y restringe los destinos no deseados o peligrosos.

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 2.
      span Gestión de tráfico entrante por #[em Firewall]
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema2/4.svg" data-aos="zoom-in-up")
      img.d-block.d-lg-none(src="@/assets/curso/tema2/5.svg" data-aos="zoom-in-up")

    p.mt-5(data-aos="fade-up") #[strong Los #[em firewalls] cuentan con políticas para la gestión de tráfico por defecto, pero cada administrador de red puede crear o modificarlas de acuerdo con sus necesidades.]

    p.mt-4(data-aos="fade-up") Para la operación de un #[em firewall], es necesario tener presentes ciertos conceptos y definiciones que son muy comunes y que su conocimiento permite realizar una adecuada gestión, de la siguiente manera:

    .tarjeta.tarjeta--azul.p-5.mt-5.cont_slyderab1
      SlyderA(tipo="b")
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 #[em Host]
            p Se refiere a cualquier dispositivo que se encuentra conectado a la red y que cuenta con una dirección IP y/o nombre asignado.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/7.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 NAT (#[em Network Address Translator])
            p Traductor de Direcciones de Red, que permite establecer la comunicación desde Internet hacia un dispositivo en el interior de la red.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/8.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Paquete
            p Un paquete se considera como los bloques que componen la información que viaja a través de la red.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/9.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Política
            p Las políticas son condiciones bajo las cuales es posible autorizar o denegar el tráfico entre un origen y un destino en la red.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/10.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Puerto
            p Un puerto se considera una entrada lógica hacia un servicio específico, por ejemplo, puerto 80 http, 443 https, 21 ftp, etc. Es posible encontrar un listado completo de los puertos TCP en el siguiente <a href="https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml" target="_blank">https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml</a>.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/11.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Rango de IP
            p Se conoce como rango de IP a un grupo de direcciones IP agrupadas para una función o política específica, por ejemplo: 192.168.1.10-192.168.1.20.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/12.png')
        .row
          .col-lg-7.mb-4.mb-lg-0
            h4 Servicio
            p Un servicio es ofrecido por aplicaciones o sistemas para compartir información entre dos o más sistemas, a partir de la aplicación de protocolos, por ejemplo: el servicio web HTTP.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/13.png')

    Separador.mt-5

    .titulo-segundo
      h2#t_2_1 2.1 Funcionalidades

    p(data-aos="fade-up") Entre las funciones que desempeña un #[em firewall], se encuentran:

    .row.mt-4
      .row.m-0.col-lg-4.mb-4.mb-lg-0.cont_tarjeta_2_1
        .col-auto.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_img(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:10px;")
          figure
            img(src="@/assets/curso/tema2/14.svg" data-aos="fade-right" style="width:60px;filter: brightness(4);")
        .col.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_texto(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:10px;")
          p.mb-0(data-aos="fade-up") Proteger los activos de información de la organización.
      .row.m-0.col-lg-4.mb-4.mb-lg-0.cont_tarjeta_2_1
        .col-auto.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_img(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:10px;")
          figure
            img(src="@/assets/curso/tema2/15.svg" data-aos="fade-right" style="width:60px;filter: brightness(4);")
        .col.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_texto(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:10px;")
          p.mb-0(data-aos="fade-up") Evitar accesos no permitidos por usuarios no autorizados hacia nuestra red.
      .row.m-0.col-lg-4.cont_tarjeta_2_1
        .col-auto.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_img(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:10px;")
          figure
            img(src="@/assets/curso/tema2/16.svg" data-aos="fade-right" style="width:60px;filter: brightness(4);")
        .col.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_texto(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:10px;")
          p.mb-0(data-aos="fade-up") Controlar la cantidad de usuarios conectados a un servicio.
      .row.m-0.col-lg-4.cont_tarjeta_2_1.mt-4
        .col-auto.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_img(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:10px;")
          figure
            img(src="@/assets/curso/tema2/17.svg" data-aos="fade-right" style="width:60px;filter: brightness(4);")
        .col.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_texto(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:10px;")
          p.mb-0(data-aos="fade-up") Restringir el tráfico saliente hacia los destinos autorizados.
      .row.m-0.col-lg-4.cont_tarjeta_2_1.mt-4
        .col-auto.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_img(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:10px;")
          figure
            img(src="@/assets/curso/tema2/18.svg" data-aos="fade-right" style="width:60px;filter: brightness(4);")
        .col.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_texto(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:10px;")
          p.mb-0(data-aos="fade-up") Evitar ataques de presentación hacia la red interna, por ejemplo, deteniendo ataques de denegación de servicios o de suplantación IP Address Spoofing, entre otros.
      .row.m-0.col-lg-4.cont_tarjeta_2_1.mt-4
        .col-auto.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_img(style="background-color:#583AE2;border-top-left-radius:10px;border-bottom-left-radius:10px;")
          figure
            img(src="@/assets/curso/tema2/19.svg" data-aos="fade-right" style="width:60px;filter: brightness(4);")
        .col.p-3.pt-4.pb-4.d-flex.align-items-center.cont_sub_tarjeta_texto(style="background-color:#D5CEF8;border-top-right-radius:10px;border-bottom-right-radius:10px;")
          p.mb-0(data-aos="fade-up") Brindar los informes necesarios para auditoría.

    Separador.mt-5

    .titulo-segundo
      h2#t_2_2 2.2 Tipos

    p(data-aos="fade-up") Existe actualmente gran variedad de soluciones #[em Firewall], entre las cuales es importante identificar las relacionadas en el siguiente video:

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/V-8J5rlLBb4" title="Tipos de soluciones Firewall" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)





</template>

<script>
export default {
  name: 'Tema2',
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
.cont_2_1 *
  position: relative
.cont_2_1:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #B5E4EB
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
.cont_tarjeta_2_1:hover .d-flex figure img
  filter: none !important
.cont_tarjeta_2_1:hover .cont_sub_tarjeta_img
  background-color: #2FF980 !important
.cont_tarjeta_2_1:hover .cont_sub_tarjeta_texto
  background-color: #DAF1F5 !important
</style>
