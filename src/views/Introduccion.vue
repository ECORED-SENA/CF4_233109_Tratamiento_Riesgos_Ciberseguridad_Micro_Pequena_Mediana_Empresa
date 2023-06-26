<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p(data-aos="fade-up") La gestión de la ciberseguridad en las organizaciones está cobrando cada vez mayor importancia dadas las últimas amenazas que se presentan de manera global, donde Colombia no ha sido ajeno, algunas organizaciones se vieron afectadas por incidentes de robo de información, cifrado, acceso abusivo y daños que repercuten en la calidad del servicio y, en algunos casos, en la imagen de confiabilidad que estas tienen y deben generar frente a sus interesados.

    p.mt-4(data-aos="fade-up") A continuación, vamos a revisar algunos de los controles para acceder a los activos de información de la empresa sugeridos y que se consideran de los más importantes:

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/R_0yRa7YXYo" title="Controles de seguridad" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Controles de seguridad

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
