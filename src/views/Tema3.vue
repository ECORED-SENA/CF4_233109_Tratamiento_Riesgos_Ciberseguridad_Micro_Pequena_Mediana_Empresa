<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 IDS/IPS, Sistemas de detección y prevención de intrusos

    p(data-aos="fade-up") A continuación, se encuentra otro tipo de soluciones que complementan la seguridad perimetral de nuestra organización a partir del análisis del tráfico que pasa por la red, identificando accesos no autorizados hacia algún recurso del perímetro.

    Separador.mt-5

    .titulo-segundo
      h2#_3_1 3.1 Definiciones

    p(data-aos="fade-up") Observe las siguientes definiciones de los diferentes conceptos y sus características:

    .row.mt-5.cont_3_1.p-5
      .col-lg-3.col-md-4.mb-md-0.mb-4(style="place-self:center;")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema3/2.svg" data-aos="fade-right" style="max-width:150px;")
      .col-lg-9.col-md-8(style="place-self:center;")
        p(data-aos="fade-up") #[strong IDS e IPS]
        ul.lista-ul.mt-4
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Se consolidan como herramientas para la detección y la prevención de intrusiones en redes de datos.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Operan analizando el tráfico que circula desde redes externas y comparándolo con patrones basados en firmas.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Permiten identificar comportamientos sospechosos.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Establecen el comportamiento de los dispositivos frente al tráfico.

    p.mt-5(data-aos="fade-up") #[strong Las siguientes son las características de cada uno de ellos y la forma como se integran a las infraestructuras de red:]

    .row.mt-5.p-5(style="background-color:#D5CEF8;")
      .col-lg-7.col-md-6.mb-md-0.mb-4(style="place-self:center;")
        p(data-aos="fade-up") #[strong IDS (#[em Intrusion Detection System])]
        ul.lista-ul.mt-4
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Soluciones para el monitoreo de la seguridad perimetral.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Son sistemas que monitorizan el tráfico entrante y lo cotejan con una base de datos actualizada de firmas de ataque conocidas.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Se encargan de generar los mensajes de advertencia para que el administrador de la red tome las acciones correspondientes.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            | Para realizar su función de monitoreo, deben permanecer enlazados a la red interna y, desde su posición, analizar el tráfico confrontando comportamientos con bases de datos de diferentes fuentes, para así poder emitir alertas.
      .col-lg-5.col-md-6(style="place-self:center;")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema3/3.svg" data-aos="fade-right")

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 4.
      span Esquema de implementación de un IDS
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema3/4.svg" data-aos="zoom-in-up" alt="La imagen presenta un esquema de implementación de un IDS, comenzando del computador del usuario, pasando por el router, el firewall, el switch, donde va a los activos de información, o pasa al IDS para generar una alerta.")
      img.d-block.d-lg-none(src="@/assets/curso/tema3/5.svg" data-aos="zoom-in-up" alt="La imagen presenta un esquema de implementación de un IDS, comenzando del computador del usuario, pasando por el router, el firewall, el switch, donde va a los activos de información, o pasa al IDS para generar una alerta.")

    p.mt-5(data-aos="fade-up") #[strong De acuerdo con su funcionalidad, es posible encontrar dos tipos de IDS:]

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 5.
      span Diferencias entre #[em NIDS y HIDS]
    .row.mt-4
      .col-lg-6.mb-4.mb-lg-0
        figure
          img.d-none.d-lg-block(src="@/assets/curso/tema3/6.svg" data-aos="zoom-in-up" alt="La imagen presenta las diferencias entre un NIDS y un HIDS.")
          img.d-block.d-lg-none(src="@/assets/curso/tema3/7.svg" data-aos="zoom-in-up" alt="La imagen presenta las diferencias entre un NIDS y un HIDS.")
          figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Adaptado de Comparitech.com
      .col-lg-6
        .p-4.h-100.d-flex.align-items-center(style="background-color:#D5CEF8;")
          ul.fa-ul
            li.mb-3(data-aos="fade-up")
              i.fas.fa-check-circle.fa-li(style="color:#40327B;")
              | #[strong HIDS #[em Host-based Intrusion Detection System:]] sistema de detección de intrusiones basado en #[em host], analiza el comportamiento de un dispositivo a partir de los eventos registrados.
            li.mb-3(data-aos="fade-up")
              i.fas.fa-check-circle.fa-li(style="color:#40327B;")
              | #[strong Los HIDS:] analizan las anomalías registradas en los eventos de cualquier dispositivo de la red.
            li.mb-3(data-aos="fade-up")
              i.fas.fa-check-circle.fa-li(style="color:#40327B;")
              | #[strong NIDS #[em Network-based Intrusion Detection System:]] sistema de detección de intrusiones basado en red, se encarga del análisis del tráfico que pasa por la red.
            li(data-aos="fade-up")
              i.fas.fa-check-circle.fa-li(style="color:#40327B;")
              | #[strong Los NIDS:] analizan las sumas de comprobación de paquetes, comparándolos con firmas en bases de datos.

    p.mt-5(data-aos="fade-up") #[strong Además, los IDS, de acuerdo con los métodos de detección, se pueden clasificar como:]

    .row.mt-5
      .col-lg-6.mb-lg-0.mb-4
        .row.m-0.p-4.h-100(style="background-color:#D5CEF8;border-radius:15px;")
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema3/8.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong IDS basado en firmas:] este tipo de IDS está presente en NIDS y HIDS.
      .col-lg-6.mb-lg-0.mb-4
        .row.m-0.p-4.h-100(style="background-color:#2FF980;border-radius:15px;")
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema3/9.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong IDS basado en anomalías:] este tipo de IDS busca patrones de acuerdo con las actividades identificadas en el tráfico de paquetes. Para el caso de los HIDS, este analiza los eventos como los inicios de sesión no exitosos y reiterativos; para el caso de los NIDS, realiza comparaciones a partir de un comportamiento base.


    .row.mt-5.col-xl-10.m-auto.cont_3_2(style="position:relative;")
      .col-xl-2.col-lg-3.mb-lg-0.mb-4(style="place-self:end")
        figure
          img(src="@/assets/curso/tema3/10.svg" data-aos="fade-right" style="max-width:90px")
      .col-xl-6.col-lg-5.mb-lg-0.mb-4(style="place-self:center")
        .py-3
          p(data-aos="fade-up") #[strong Entre los IDS más conocidos, están]
          ul.lista-ul
            li.mb-1(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              span Zeek: #[a(href="https://zeek.org/", target="_blank") #[u https://zeek.org/]]
            li.mb-1(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              span OSSEC: #[a(href="https://www.ossec.net/", target="_blank") #[u https://www.ossec.net/]]
            li.mb-1(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              span Snort: #[a(href="https://www.snort.org/", target="_blank") #[u https://www.snort.org/]]
            li.mb-1(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              span Suricata: #[a(href="https://suricata.io/", target="_blank") #[u https://suricata.io/]]
            li.mb-1(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              span Security Onion: #[a(href="https://securityonionsolutions.com/", target="_blank") #[u https://securityonionsolutions.com/]]

      .col-xl-4.col-lg-4
        figure.col-8.m-auto.col-md-12
          img(src="@/assets/curso/tema3/11.svg" data-aos="fade-left" style="position:relative;bottom:-16px;")

    .row.justify-content-center.mt-5.p-4(style="background-color:#D5CEF8;")
      .col-lg-4.col-md-6.col-8.mb-md-0.mb-4(style="place-self:center;")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema3/12.svg" data-aos="fade-right")
      .col-lg-8.col-md-6(style="place-self:center;")
        p(data-aos="fade-up") #[strong IPS #[em (Intrusion Prevention System)]]
        ul.lista-ul.mt-4
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            span Son soluciones que permiten asegurar de manera preventiva los recursos de la red de ataques e intrusiones.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            span Realizan un análisis en tiempo real de las conexiones, con el fin de cotejar con patrones o comportamientos conocidos.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            span Tienen el control para denegar paquetes, así como cerrar conexiones que consideren sospechosas.
          li(data-aos="fade-up")
            i.fas.fa-check-circle(style="color:#40327B;")
            span Operan desde la red interna, por lo general, después del #[em firewall] de seguridad perimetral.

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 6.
      span Esquema de implementación de un IPS
    figure
      img.d-none.d-lg-block(src="@/assets/curso/tema3/13.svg" data-aos="zoom-in-up" alt="La imagen presenta un esquema de implementación de un IPS, comenzando desde el computador del usuario hasta los activos de información.")
      img.d-block.d-lg-none(src="@/assets/curso/tema3/14.svg" data-aos="zoom-in-up" alt="La imagen presenta un esquema de implementación de un IPS, comenzando desde el computador del usuario hasta los activos de información.")


    p.mt-5(data-aos="fade-up") En la actualidad, existen muchas soluciones de tipo UTM que incorporan estos 2 tipos de soluciones dentro de sus herramientas, permitiendo extender la cobertura y control del tráfico que circula en la red.

    Separador.mt-5

    .titulo-segundo
      h2#t_3_2 3.2 Características

    p(data-aos="fade-up") Dentro de las características más relevantes de estos 2 sistemas, están:

    .row.mt-5.col-xl-10.m-auto
      .col-lg-6.mb-4.mb-lg-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.d-flex.flex-wrap(:style="{'background-image': `url(${require('@/assets/curso/tema3/15.png')})`}")
              figure.d-flex.justify-content-center.align-items-end
                img(src="@/assets/curso/tema3/16.svg" style="max-width:200px;")
              .m-auto.text-center(style="width:fit-content;")
                .pt-2.pb-2.bg-white.ps-4.pe-4(style="border-radius:50px;")
                  p.mb-0 #[strong #[em(style="color:initial;") IDS #[em (Intrusion Detection System)]]]
            .tarjeta-flip__contenido.p-4.p-xl-5.d-flex.justify-content-center.flex-column(:style="{'background-image': `url(${require('@/assets/curso/tema3/18.png')})`}")
              h4.text-center IDS (#[em Intrusion Detection System])
              ul.lista-ul.mt-4
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  span Realiza análisis del tráfico a partir de verificación y comparación de patrones contra bases de datos con firmas conocidas de ataques maliciosos.
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  span Realiza monitoreo permanente del tráfico que pasa por la red.
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  span Cuenta con la capacidad de monitorear el comportamiento de los sistemas de información para identificar la intención de algún ataque.
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  span Permite identificar cambios en las configuraciones de los dispositivos o servicios.
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  span Capacidad de emitir alertas en gran variedad de sistemas.
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  span Requiere de actualización permanente de bases de datos con firmas actualizadas.
      .col-lg-6.mb-4.mb-lg-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.d-flex.flex-wrap(:style="{'background-image': `url(${require('@/assets/curso/tema3/15.png')})`}")
              figure.d-flex.justify-content-center.align-items-end
                img(src="@/assets/curso/tema3/17.svg" style="max-width:200px;")
              .m-auto.text-center(style="width:fit-content;")
                .pt-2.pb-2.bg-white.ps-4.pe-4(style="border-radius:50px;")
                  p.mb-0 #[strong #[em(style="color:initial;") IPS #[em (Intrusion Prevention System)]]]
            .tarjeta-flip__contenido.p-4.p-xl-5.d-flex.justify-content-center.flex-column(:style="{'background-image': `url(${require('@/assets/curso/tema3/18.png')})`}")
              h4.text-center IPS #[em (Intrusion Prevention System)]
              ul.lista-ul.mt-4
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  | Complementa a los IDS, identificando y bloqueando conexiones con tráfico sospechoso.
                li(data-aos="fade-up")
                  i.fas.fa-check-circle(style="color:#40327B;")
                  | Permite descartar paquetes sospechosos.
                li(data-aos="fade-up").align-items-end
                  i.fas.fa-check-circle(style="color:#40327B;")
                  | Permite bloquear direcciones sospechosas.





</template>

<script>
export default {
  name: 'Tema3',
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
.cont_3_1
  background: url(../assets/curso/tema3/1.png)
  background-repeat: no-repeat
  background-size: cover
.cont_3_2 *
  position: relative
.cont_3_2:before
  content: ''
  position: absolute
  width: 85%
  height: 100%
  top: 0
  background-color: #B5E4EB
  border-top-left-radius: 150px
  border-bottom-left-radius: 150px
.tarjeta-flip.color-primario .tarjeta-flip__contenido
  background-size: cover !important
  background-repeat: no-repeat
</style>
