<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Cifrado

    p(data-aos="fade-up") Los controles de cifrado de información se han convertido en un elemento de gran importancia para la gestión de la seguridad de la información, ya que permiten proteger la privacidad de la misma al evitar que esta sea interpretada por personas no autorizadas.

    .row.mt-5.col-xl-10.m-auto.cont_6_1
      .col-lg-5.mb-4.mb-lg-0.p-0
        figure
          img(src="@/assets/curso/tema6/1.png" data-aos="fade-right" style="max-width:350px;")
      .col-lg-5.mb-4.mb-lg-0.ps-0(style="place-self:center")
        .py-4.px-4.px-lg-0
          p.mt-2(data-aos="fade-up") De acuerdo con WeLiveSecurity:
          p(data-aos="fade-up") #[strong El cifrado es “el proceso mediante el cual se codifica algo de modo que no resulte fácil de entender para quienes no tienen acceso autorizado”] (WeLiveSecurity, 2021). También es necesario conocer sobre los procesos de criptografía.
      .col-lg-1(style="place-self:end;")
        figure
          img(src="@/assets/curso/tema6/2.svg" data-aos="fade-left" style="max-width:70px;")

    p.mt-5(data-aos="fade-up") #[strong Estos procesos tienen como objetivos:]

    .row.mt-5
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_6_1.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema6/3.svg" data-aos="zoom-in-up" style="max-width:70px;")
          p.mt-4(data-aos="fade-up") Garantizar la privacidad y confidencialidad de tal manera que únicamente el destinatario interesado pueda leerla.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_6_1.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema6/3.svg" data-aos="zoom-in-up" style="max-width:70px;")
          p.mt-4(data-aos="fade-up") Integridad, evitando que esta sea modificada sin autorización.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_6_1.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema6/3.svg" data-aos="zoom-in-up" style="max-width:70px;")
          p.mt-4(data-aos="fade-up") Autenticación, garantizando que solo se pueda interpretar por los interesados.
      .col-xl.col-lg-6.mb-xl-0.mb-4
        .h-100.cont_tarjeta_6_1.p-4(style="background-color:#D5CEF8;border-radius:15px;")
          figure
            img(src="@/assets/curso/tema6/3.svg" data-aos="zoom-in-up" style="max-width:70px;")
          p.mt-4(data-aos="fade-up") No repudio, para evitar que se niegue el acceso a alguno de los interesados.

    .tarjeta.color-primario.p-4.mt-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/tema6/4.svg" data-aos="fade-right")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.mb-1.text-white(data-aos="fade-up") Cifrado de datos
              p.mb-0.text-white(data-aos="fade-up") Puede conocer más sobre el proceso de cifrado en el siguiente video titulado Cifrado de datos: qué es y cómo puede ayudarte a proteger tu información en Internet.
            .col-sm-auto
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=wcJBmoz6Vlk" target="_blank" data-aos="fade-left")
                span Ver video
                i.fas.fa-play

    Separador.mt-5

    .titulo-segundo
      h2#t_6_1 6.1 Tipos

    p(data-aos="fade-up") Se pueden identificar dos tipos de cifrado, como son:

    .bg-purple.mb-5
      .pt-4.pb-4.px-4.px-xl-0
        .row.justify-content-center.align-items-start
          .col-xl-7.col-12
            ul.lista-ul.mt-4
              li.mb-4(data-aos="fade-up")
                i.fas.fa-check-circle(style="color:#40327B;")
                span #[strong Cifrado simétrico:] este tipo de cifrado hace uso de una sola llave tanto para cifrar un mensaje como para recuperarlo.
              li(data-aos="fade-up")
                i.fas.fa-check-circle(style="color:#40327B;")
                div
                  p.mb-0 #[strong Cifrado asimétrico:] este tipo de cifrado hace uso de dos llaves:
                  .ps-4.pt-2
                    ol.lista-ul
                      li.mb-0
                        span #[strong 1. Llave pública:] la cual se puede compartir.
                      li.mb-0
                      span #[strong 2. Llave privada:] está únicamente debe ser conocida por el destinatario o interesado.
          .col-xxl-3.col-xl-4.d-none.d-xl-block
            figure.position-relative
              img(src="@/assets/curso/tema6/5.svg" data-aos="fade-left").img_t_6_1


    p.mt-5(data-aos="fade-up") #[strong En la siguiente figura, puede observar el proceso para cifrar mensajes a partir de estos dos tipos de cifrado.]

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 8.
      span Tipos de cifrado
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema6/6.svg" data-aos="zoom-in-up" alt="La imagen presenta el proceso para cifrar mensajes, a partir de los diferentes tipos de cifrado: simétrico y asimétrico.")
      img.d-block.d-lg-none(src="@/assets/curso/tema6/7.svg" data-aos="zoom-in-up" alt="La imagen presenta el proceso para cifrar mensajes, a partir de los diferentes tipos de cifrado: simétrico y asimétrico.")
      figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Adaptado de OSI (2019).

    Separador.mt-5

    .titulo-segundo
      h2#t_6_2 6.2 Comunicaciones cifradas

    .row.cont_6_3(style="position:relative;")
      .col-lg-10.col-md-12.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") Los controles de cifrado deben ser integrados en cualquier estrategia de seguridad como mecanismos vitales para salvaguardar la información confidencial y garantizar los pilares de la seguridad de la información.
        p.mt-4(data-aos="fade-up") #[strong A continuación, se van a identificar algunas aplicaciones específicas en servicios de red:]
      .col-lg-2.col-md-4(style="place-self:center").d-none.d-lg-block
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema6/8.svg" data-aos="fade-left" style="max-width:100px;")

    TabsB.color-acento-contenido.mt-5
      .py-4.py-md-5(titulo="HTTPS" :icono="require('@/assets/curso/tema6/22.svg')")
        .row.p-4
          h4 HTTPS
          p El protocolo de servicio web HTTP viaja de manera plana a través de los medios de comunicación, lo que lo hace vulnerable a cualquier interceptación, permitiendo recuperar información sensible, alterar y/o aplicar sentencias dañinas; para mejorar la seguridad de este protocolo, se realizan implementaciones como SSL, acrónimo de Secure Sockets Layer, la cual permite realizar un cifrado a la información transmitida entre dos puntos.
          p.mt-4 Asimismo, se cuenta con TLS, Transport Layer Security, la cual es una mejora al SSL agregando una capa de seguridad al transporte; los certificados web se distribuyen actualmente con tecnología TLS, aunque continúen llamándose SSL.
          p.mt-4 Estas implementaciones se realizan con la inclusión de un certificado digital en la operación del servidor web, como Apache, Ngnix o IIS, por nombrar algunos, habilitando el protocolo HTTPS. #[strong En la siguiente figura, puede observar cómo la implementación de cifrado SSL evita que el contenido que circula a través de la red pueda ser leído por terceros no autorizados:]
          .titulo-sexto.color-acento-contenido.mt-5.ms-2
            h5 Figura 9.
            span Tráfico HTTP vs. HTTPS
          figure.mt-4
            img(src="@/assets/curso/tema6/23.svg" alt="La imagen presenta una comparación entre el tráfico HTTP y el HTTPS.")
            figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Basado en B, G (2002).

      .py-4.py-md-5(titulo="FTPS" :icono="require('@/assets/curso/tema6/22.svg')")
        .row.p-4
          h4 FTPS
          p La transferencia de archivos aún sigue siendo un servicio que se consume en algunas organizaciones y es muy útil cuando se realiza transferencia de gran cantidad de archivos o estos son de gran tamaño, para ello se hace uso de protocolos como el FTP; lastimosamente, este servicio, en su implementación, es muy sensible y apetecido por ciberdelincuentes; para reducir estos inconvenientes, se puede realizar la implementación de FTPS (Protocolo de transferencia de archivos con soporte para Seguridad de la capa de transporte (SSL / TLS)).
          p.mt-4 Esta implementación también se realiza incorporando un certificado digital sobre el servicio FTP, como, por ejemplo, Vsftpd, Proftpd o Pure-FTPd.
          p.mt-4 No se debe confundir con SFTP (Protocolo de transferencia de archivos), el cual es un protocolo que permite transferir y manipular archivos a través de cualquier medio. Por lo general, se usa con el protocolo SSH-2. #[strong En la siguiente figura, puede observar algunas de las diferencias en operación de estos protocolos:]
          .titulo-sexto.color-acento-contenido.mt-5.ms-2
            h5 Figura 10.
            span Diferencias entre FTPS Y SFTP
          figure.mt-4
            img(src="@/assets/curso/tema6/24.svg" alt="La imagen presenta las diferencias en operación de los protocolos FTPS y el SFTP.")
            figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Basado en MSP (s. f.).

      .py-4.py-md-5(titulo="SSH" :icono="require('@/assets/curso/tema6/22.svg')")
        .row.p-4
          h4 SSH
          p Uno de los controles que no debe faltar en cualquier estrategia de seguridad es el que nos sugiere asegurar los accesos remotos y seguros, en especial, para la administración de dispositivos críticos, así como de consolas y appliances de seguridad; para abordar este control, se sugiere la implementación de acceso seguro a través de SSH (Secure SHell), el cual es un servicio que hace uso de protocolo de cifrado, como RSA y DSA, este establece las conexiones estableciendo canales seguros y cifrados entre los dos puntos de la conexión, resguardando la información que fluye por el medio.
          p.mt-4 En la siguiente figura, se puede identificar cómo, desde el exterior y haciendo uso de una conexión SSH, puede establecer conexión con un host al interior de la red, implementando un canal cifrado a través de la red pública; este servicio puede utilizarse a través de programas para la conexión remota, como Putty, y de transferencia de archivos segura, como WinSCP:
          .titulo-sexto.color-acento-contenido.mt-5.ms-2
            h5 Figura 11.
            span Funcionamiento de conexión SSH
          figure.mt-4
            img(src="@/assets/curso/tema6/25.png" alt="La imagen presenta cómo se realiza el funcionamiento de conexión SSH desde el host del cliente hasta un host de servicio.")
            figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Basado en Chasco (2015).
      .py-4.py-md-5(titulo="LDAPS" :icono="require('@/assets/curso/tema6/22.svg')")
        .row.p-4
          h4 LDAPS
          p Uno de los controles sugeridos en las organizaciones son los relacionados con una adecuada gestión de usuarios y sobre su administración responsable, por lo cual es muy común encontrar soluciones de servicio de directorio basados en protocolo LDAP (Lightweight Directory Access Protocol), como OpenLDAP o Active de Directory de Microsoft.
          p.mt-4 Estos servicios basados en LDAP permiten implementar directorio de objetos (unidades organizacionales, grupos, usuarios, equipos, entre otros), están estructurados bajo el protocolo X.500 y contienen una estructura de manera jerárquica, esto permite su gestión centralizada, así como la asignación de privilegios a diferentes recursos de la red.
          p.mt-4 Este servicio se aprovecha a nivel de aplicación para que los usuarios se autentiquen y hagan uso de servicios, por ejemplo: inicio de sesión, escritorio remoto, carpetas compartidas, DNS, DHCP, autenticación desde otras aplicaciones, entre otros.
          p.mt-4 Al igual que los servicios anteriormente nombrados, para mejorar la seguridad en la transmisión de información, se recomienda la implementación de LDAPS (LDAP Seguro), #[strong esto se puede realizar con implementación de protocolos como SSL y TLS, los cuales requieren un certificado digital, como se puede observar en la siguiente figura:]
          .titulo-sexto.color-acento-contenido.mt-5.ms-2
            h5 Figura 12.
            span Implementación de protocolo LDAPS
          figure.mt-4
            img(src="@/assets/curso/tema6/26.png" alt="La imagen presenta cómo se realiza la implementación de un protocolo LDAPS.")
            figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Basado en Kuenzler (2014)


    Separador.mt-5

    .titulo-segundo
      h2#t_6_3 6.3 Fuga de información

    .row.justify-content-center
      .col-lg-8.mb-4.mb-lg-0(style="place-self:center")
        p(data-aos="fade-up") La pérdida de información en una organización puede presentarse por varios factores y se puede buscar reducir mediante la adopción de controles que reduzcan este tipo de riesgos.
        p.mt-4(data-aos="fade-up") De acuerdo con AUDEA, se denomina fuga de información #[strong “al incidente (tanto interno como externo, y a la vez intencional o no) que pone en poder de una persona ajena a la organización información confidencial y que solo debería estar disponible para integrantes de la misma”] (AUDEA, 2020). La norma ISO 27001, en su Anexo A, establece controles que buscan mejorar las prácticas con el manejo de los activos de información.
      .col-lg-4.col-8(style="place-self:center")
        figure
          img(src="@/assets/curso/tema6/17.png" data-aos="fade-left")

    .row.mb-5.m-0.mt-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Tipos
    p(data-aos="fade-up") Existen diversos tipos y causas por las cuales se desencadenan fugas o pérdida de información, entre los cuales se pueden encontrar:

    .pt-4.pb-5.cont_6_5.mt-5
      .titulo-sexto.color-acento-contenido.mt-5
        h5 Fuga de la información
      figure.mt-4
        img.d-none.d-lg-block(src="@/assets/curso/tema6/18.svg" data-aos="zoom-in-up")
        img.d-block.d-lg-none(src="@/assets/curso/tema6/19.svg" data-aos="zoom-in-up")

    .row.mb-5.m-0.mt-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Prevención

    p(data-aos="fade-up") Conocer los activos de información se considera el primer paso para tomar decisiones y acciones que ayuden a prevenir incidentes relacionados con fuga o pérdida de información, así que, a continuación, se plantean las siguientes recomendaciones:

    .row.mt-5.cont_6_6(style="border-radius:0px !important;")
      .col-xl-10.m-auto.row.m-0.p-4
        .col-lg-3.mb-4.mb-lg-0(style="place-self:center")
          figure.d-flex.justify-content-center
            img(src="@/assets/curso/tema6/21.svg" data-aos="fade-right" style="max-width:120px")
        .col-lg-9(style="place-self:center")
          ul.lista-ul
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              | Identificar los activos de información que gestiona.
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              | Clasificar los activos de información de acuerdo con su criticidad e importancia para la organización.
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              | Identificar el grado de seguridad actual, es decir, identificar los riesgos a los que está expuesto el activo de información.
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-check-circle(style="color:#40327B;")
              | Implementar los controles que permitan mejorar la seguridad del activo de información.

    p.mt-5(data-aos="fade-up") #[strong A partir de este ejercicio, se pueden establecer los controles necesarios, entre los cuales se pueden encontrar los siguientes tipos:]

    .col-xl-10.m-auto.mt-5
      AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--gris")
        .row.ps-4.pe-4(titulo="Técnicas")
          p Implementación de soluciones de seguridad que permitan detectar y prevenir fuga de información, entre las cuales se consideran:
          ul.lista-ul.mt-2
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-angle-right(style="color:#583AE2;")
              | Cifrado de información confidencial corporativa.
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-angle-right(style="color:#583AE2;")
              | Instalación, configuración y actualización de #[em firewall].
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-angle-right(style="color:#583AE2;")
              | Actualización permanente de aplicaciones.

          p.mt-2 Para grandes organizaciones, se recomienda:

          ul.lista-ul.mt-2
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-angle-right(style="color:#583AE2;")
              | Sistemas de prevención de pérdida de datos o DLP.
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-angle-right(style="color:#583AE2;")
              | Aplicación de controles orientados a la gestión del ciclo de vida de la información o ILM (#[em Information Lifecycle Management]).
            li.mb-1.d-block(data-aos="fade-up")
              i.fas.fa-angle-right(style="color:#583AE2;")
              | Adopción de herramientas que permitan controlar dispositivos externos de almacenamiento, removibles y en línea, para evitar fugas de información.
        .row.ps-4.pe-4(titulo="Organizativas")
          p Estos controles se relacionan con «la forma» en que se maneja o se trata la información, por lo que se recomienda prevenir malas prácticas, como compartir contraseñas o activos confidenciales, o hacer uso de contraseñas que son de conocimiento general. Esto conlleva que se cuente con políticas de seguridad apoyadas en acciones de concienciación a todo el personal.
        .row.ps-4.pe-4(titulo="Jurídicas")
          p Todos los empleados y/o proveedores deben cumplir con las políticas de seguridad, las cuales se deben comunicar y aceptar mediante la firma de acuerdos de confidencialidad y de nivel de servicio (SLA) para proveedores.







</template>

<script>
export default {
  name: 'Tema6',
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
.bg-purple
  background: #D5CEF8
.cont_6_1 *,.cont_6_1
  position: relative
.cont_6_1:before
  content: ''
  position: absolute
  width: 93%
  height: 85%
  top: 7%
  background-color: #B5E4EB
  border-top-right-radius: 150px
  border-bottom-right-radius: 150px
.cont_tarjeta_6_1:hover
  background-color: #2FF980 !important
.cont_6_2 *,.cont_6_2
  position: relative
.cont_6_2:before
  content: ''
  position: absolute
  width: 100%
  height: 90%
  bottom: 0
  background-color: #D5CEF8
.cont_6_3 *
  position: relative
.cont_6_3:before
  content: ''
  position: absolute
  width: 30%
  height: 50%
  right: 0
  top: -10%
  background-color: #D5CEF8
.cont_6_4 *, .cont_6_4
  position: relative
.cont_6_4:before
  content: ''
  position: absolute
  width: 125%
  left: -15%
  height: 100%
  top: 0
  background-color: #F3F1FF
.cont_6_5 *, .cont_6_5
  position: relative
.cont_6_5:before
  content: ''
  position: absolute
  width: 125%
  left: -15%
  height: 100%
  top: 0
  background-color: #ECF8FA
.cont_6_6
  background: url(../assets/curso/tema6/20.png)
  background-repeat: no-repeat
  background-size: cover
  border-radius: 15px
.tabs-b__tab
  border-bottom: 0px !important
.tabs-b__tab__icon img
  filter: grayscale(1)
.tabs-b__tab.tabs-b__tab--active img
  filter: none !important
.tarjeta.tarjeta--gris.acordion__activo
  background-color: #DAF1F5
@media screen and (max-width: 1000px)
  .cont_6_1:before
    width: 100%
    height: 100%
    top: 0
    border-radius: 0px
  .cont_6_2:before
    height: 100%
</style>
