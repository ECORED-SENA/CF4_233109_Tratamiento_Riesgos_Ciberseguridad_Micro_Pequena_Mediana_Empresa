<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Infraestructuras críticas

    .row.cont_8_1(style="position:relative;")
      .col-lg-10.col-md-8.mb-4.mb-md-0
        p.mb-0(data-aos="fade-up") A continuación, se van a abordar algunos conceptos importantes en el aseguramiento de infraestructuras críticas, las cuales son las industrias principales de un país.
        p.mt-4(data-aos="fade-up") #[strong Dentro de los conceptos relacionados con infraestructuras críticas, se encuentran los siguientes:]
      .col-lg-2.col-md-4(style="place-self:center")
        figure.d-flex.justify-content-center
          img(src="@/assets/curso/tema8/1.svg" data-aos="fade-left" style="max-width:100px;")

    .row.mt-5.col-xl-10.m-auto
      .col-lg-6.mb-5.mb-lg-0
        .p-4.pt-5.h-100.cont_scale_1
          figure
            img(src="@/assets/curso/tema8/2.png" data-aos="zoom-in-up")
          h4.mt-4.text-center(data-aos="fade-up") Infraestructura crítica
          p.mt-4(data-aos="fade-up") LISA Institute define una infraestructura crítica como #[strong “las infraestructuras estratégicas, que proporcionan servicios esenciales y cuyo funcionamiento es indispensable y no permite soluciones alternativas, por lo que su perturbación o destrucción tendría un grave impacto sobre los servicios esenciales”]. (LISA Institute, 2020)
      .col-lg-6.mb-5.mb-lg-0
        .p-4.pt-5.h-100.cont_scale_2
          figure
            img(src="@/assets/curso/tema8/3.png" data-aos="zoom-in-up")
          h4.mt-4.text-center(data-aos="fade-up") Servicio esencial
          p.mt-4(data-aos="fade-up") LISA Institute lo define como #[strong “el servicio necesario para el mantenimiento de las funciones sociales básicas, la salud, la seguridad, el bienestar social y económico de los ciudadanos, o el eficaz funcionamiento de las Instituciones del Estado y las Administraciones Públicas”]. (LISA Institute, 2020)

    .row.mb-5.m-0.mt-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Tipos

    p(data-aos="fade-up") Las infraestructuras críticas abordan sectores primordiales para el desarrollo de las regiones, entre los que se pueden encontrar:

    .row.mt-5
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/5.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Sistema financiero y tributario:] entidades bancarias, información, valores e inversiones.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/6.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Centrales y redes de energía:] producción, almacenamiento y distribución.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/7.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Industria química:] producción, almacenamiento y transporte de mercancías peligrosas, materiales químicos, etc.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/8.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Administración:] servicios básicos, instalaciones, redes de información, principales activos y monumentos del patrimonio nacional.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/9.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Educación:] las TIC ya sean infraestructuras críticas en sí mismas, como recks de comunicaciones o den servicio de información a otras estructuras críticas.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/10.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Investigación:] laboratorios que dispongan, o produzcan materiales, sustancias o elementos críticos o peligrosos.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/11.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Agua:] embalses, almacenamiento, tratamiento y redes.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/12.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Instalaciones relacionadas con el espacio exterior]
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/13.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Salud:] sector e infraestructura sanitaria.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/14.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Alimentación:] producción, almacenamiento y distribución.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/15.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Centrales nucleares:] producción, almacenamiento y transporte de mercancías peligrosas, materiales químicos, etc.
      .col-lg-4.mb-4
        .row.m-0.h-100.p-3.cont_tarjeta_8_1
          .col-auto(style="place-self:center")
            figure
              img(src="@/assets/curso/tema8/16.svg" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") #[strong Transportes:] aeropuertos, instalaciones intermodales, ferrocarriles, redes de transporte público, sistemas de control de tráfico.

    Separador.mt-5

    .titulo-segundo
      h2#t_8_1 8.1 Características

    .row
      .col-lg-4.mb-4.mb-lg-0(style="place-self:center")
        figure
          img(src="@/assets/curso/tema8/17.png" data-aos="fade-left")
      .col-lg-8(style="place-self:center")
        p(data-aos="fade-up") Las infraestructuras críticas presentan algunas características especiales que las diferencian de una organización en particular, entre ellas, está definido que estas infraestructuras brindan servicios esenciales para la sociedad y que si estas llegan a ser afectadas, podrían afectar negativamente la estabilidad de un país.
        p.mt-4(data-aos="fade-up") #[strong Su conformación y complejidad son de gran tamaño, dada la responsabilidad y los activos de información que deben gestionar, así como la obligación de mantener estos servicios casi que siempre disponibles.]
        p.mt-4(data-aos="fade-up") Algo que hay que recalcar es que estas infraestructuras críticas, por lo general, están interconectadas con otras infraestructuras, por lo que su interrupción afectaría negativamente el desempeño de algunas otras.

    Separador.mt-5

    .titulo-segundo
      h2#t_8_2 8.2 Marco para mejorar la ciberseguridad de la infraestructura crítica

    p(data-aos="fade-up") Para la gestión de las infraestructuras críticas, dada su complejidad, es importante contar con un marco que le permita realizar una mejora continua a su nivel de seguridad.

    .tarjeta.color-primario.p-4.mt-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/tema8/18.svg" data-aos="fade-right")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.mb-1.text-white(data-aos="fade-up") #[em Framework for Improving Critical Infrastructure Cybersecurity]
              p.mb-0.text-white(data-aos="fade-up") El NIST (National Institute of Standards and Technology), en el año 2018, público el Framework for Improving Critical Infrastructure Cybersecurity, con el cual busca promover una adecuada gestión de los riesgos de la ciberseguridad en las organizaciones, adoptando las mejores prácticas de ISO, ITU, CIS, NIST, entre otros. Para conocerlo, haga clic en el enlace.
            .col-sm-auto
              a.boton.color-acento-botones(href="https://www.nist.gov/cyberframework" target="_blank" data-aos="fade-left")
                span Ir a enlace

    .row.mb-5.m-0.mt-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Estructura del marco NIST

    p(data-aos="fade-up") El framework de NIST se encuentra compuesto por 3 secciones, como se puede identificar en la siguiente tabla:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Tabla 1.
      span Componentes del Framework de NIST
    .tabla-a.color-acento-contenido.mt-4
      table
        caption(style="background-color:#F6F6F6;font-weight:400;") #[strong Nota.] Basado en Gómez (2009)
        thead
          tr
            th Marco básico (#[em Framework core])
            th Niveles de implementación del marco #[br] (#[em Framework implementation Tiers])
            th Perfiles del marco (#[em Framework profiles])
        tbody
          tr(style="background-color:#fff;")
            td.p-4(style="border:0;border-right:1px #E1E1E1 solid;")
              p El core es un conjunto de actividades y resultados de ciberseguridad deseados, organizados en categorías y alineados con referencias informativas a estándares adoptados por la industria.
              p.mt-4 Está diseñado para ser intuitivo y actuar como una capa de traducción, para permitir la comunicación entre equipos multidisciplinarios mediante el uso del lenguaje simplista y no técnico.
              p.mt-4 El core consta de tres partes: #[br] funciones, categorías y subcategorías. Incluye cinco funciones de alto nivel: identificar, proteger, detectar, responder y recuperar.
            td.p-4(style="border:0;border-right:1px #E1E1E1 solid;") Los niveles de implementación le permiten a la organización catalogarse en un umbral predefinido en función de las prácticas actuales de gestión del riesgo, el entorno de amenazas, los requerimientos legales y regulatorios, los objetivos y misión del negocio y las restricciones de la propia empresa.
            td.p-4(style="border:0;") Los perfiles se emplean para describir el estado actual (#[em current profile]) y el estado objetivo (#[em target profile]) de determinadas actividades de ciberseguridad. El análisis diferencial entre perfiles, permite la identificación de brechas que deberían ser gestionadas para cumplir con los objetivos de gestión de riesgos.

    p.mt-5(data-aos="fade-up") Así, el core del #[em Framework] plantea acciones de ciberseguridad para las infraestructuras críticas. #[strong Por otra parte, el núcleo del marco propone 5 funciones básicas secuenciales, como se muestra a continuación:]

    .col-xl-8.m-auto.mt-5
      .titulo-sexto.color-acento-contenido.mt-5
        h5 Figura 16.
        span Funciones básicas del #[em Framework] de NIST
      figure.mt-4
        img.d-none.d-lg-block(src="@/assets/curso/tema8/19.svg" data-aos="zoom-in-up" alt="La imagen presenta las funciones básicas del framewok de NIST, las cuales son: identificar, proteger, detectar, responder y recuperar.")
        img.d-block.d-lg-none(src="@/assets/curso/tema8/20.svg" data-aos="zoom-in-up" alt="La imagen presenta las funciones básicas del framewok de NIST, las cuales son: identificar, proteger, detectar, responder y recuperar.")

    p.mt-5(data-aos="fade-up") De igual manera, propone cuatro elementos que enmarcan las actividades y referentes para la aplicación del presente marco, como se puede observar a continuación:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 17.
      span Elementos que determinan las actividades a realizar
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema8/21.svg" data-aos="zoom-in-up" alt="La imagen presenta los cuatro elementos que determinan las actividades a realizar, las cuales son: las funciones, las categorías, las subcategorías y las referencias informativas.")
      img.d-block.d-lg-none(src="@/assets/curso/tema8/22.svg" data-aos="zoom-in-up" alt="La imagen presenta los cuatro elementos que determinan las actividades a realizar, las cuales son: las funciones, las categorías, las subcategorías y las referencias informativas.")
      figcaption(style="font-weight:400;background-color:#F6F6F6;") #[strong Nota.] Basado en Gómez (2009).

    p.mt-5(data-aos="fade-up") Estas funciones y categorías se articulan para generar un modelo que permita gestionar la ciberseguridad en las organizaciones, así:

    .col-xl-10.m-auto.mt-5
      .titulo-sexto.color-acento-contenido
        h5 Tabla 2.
        span Categoría de función y de identificadores únicos
      .tabla-a.color-acento-contenido.mt-4
        table
          caption(style="background-color:#F6F6F6;font-weight:400;") #[strong Nota.] Basado en Gómez (2009)
          thead
            tr
              th Función #[br] Identificador Único
              th Funciones
              th Categoría Identificador #[br] Único
              th Categorías
          tbody
            tr(style="background-color:#fff;")
              td.p-4.text-center(style="font-weight:bold;") ID
              td.p-4.text-center(style="font-weight:bold;") Identificar
              td.p-4.text-center ID.AM #[br] ID.BE #[br] ID.GV #[br] ID.RA #[br] ID.RM #[br] ID.SC
              td.p-4 Gestión de activos #[br] Ambiente de negocios #[br] Gobernanza #[br] Evaluación de riesgos #[br] Estrategia de gestión de riesgos #[br] Gestión del riesgo de la cadena de suministro
            tr(style="background-color:#fff;")
              td.p-4.text-center(style="font-weight:bold;") PR
              td.p-4.text-center(style="font-weight:bold;") Proteger
              td.p-4.text-center PR.AC #[br] PR.AT #[br] PR.DS #[br] PR.IP #[br] PR.MA #[br] PR.PT
              td.p-4 Gestión de identidad, autenticación y control de acceso #[br] Conciencia y capacitación #[br] Seguridad de datos #[br] Procesos y procedimientos de protección de la información #[br] Mantenimiento #[br] Tecnología de protección
            tr(style="background-color:#fff;")
              td.p-4.text-center(style="font-weight:bold;") DE
              td.p-4.text-center(style="font-weight:bold;") Detectar
              td.p-4.text-center DE.AE #[br] DE.CM #[br] DE.DP
              td.p-4 Anomalías y eventos #[br] Monitoreo continuo de seguridad #[br] Procesos de detección
            tr(style="background-color:#fff;")
              td.p-4.text-center(style="font-weight:bold;") RS
              td.p-4.text-center(style="font-weight:bold;") Responder
              td.p-4.text-center RS.RP #[br] RS.CO #[br] RS.AN #[br] RS.MI #[br] RS.IM
              td.p-4 Planificación de respuesta #[br] Comunicaciones #[br] Análisis #[br] Mitigación #[br] Mejoras
            tr(style="background-color:#fff;")
              td.p-4.text-center(style="font-weight:bold;") RC
              td.p-4.text-center(style="font-weight:bold;") Recuperar
              td.p-4.text-center RC.RP #[br] RC.IM #[br] RC.CO
              td.p-4 Planificación de la recuperación #[br] Mejoras #[br] Comunicaciones

    p.mt-5(data-aos="fade-up") #[strong Ahora bien, a medida que las organizaciones realizan su implementación, se puede determinar su nivel de acuerdo con la siguiente clasificación propuesta:]

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Tabla 3.
      span Niveles de implementación
    .tabla-a.color-acento-contenido.mt-4
      table
        caption(style="background-color:#F6F6F6;font-weight:400;") #[strong Nota.] Basado en Gómez (2009)
        thead
          tr
            th Nivel
            th Tipo
            th Programa de gestión de procesos
            th Programa de gestión integrada #[br] de riesgos
            th Participación externa
        tbody
          tr(style="background-color:#fff;")
            td.p-4.text-center(style="font-weight:bold;") 1
            td.p-4.text-center(style="font-weight:bold;") Parcial
            td.p-4 No se formalizan las prácticas organizativas de gestión de riesgos de ciberseguridad y se gestiona el riesgo de manera ad hoc y a veces reactiva.
            td.p-4 Se conoce muy poco el riesgo de ciberseguridad a nivel organizativo y no se ha establecido un enfoque de gestión del riesgo de ciberseguridad en toda la organización.
            td.p-4 Puede no tener los procesos establecidos para participar en la coordinación o colaboración con otras entidades.
          tr(style="background-color:#fff;")
            td.p-4.text-center(style="font-weight:bold;") 2
            td.p-4.text-center(style="font-weight:bold;") Riesgo #[br] informado
            td.p-4 Las prácticas de gestión de riesgos son aprobadas por la administración por la administración pero no pueden establecerse como políticas de toda la organización.
            td.p-4 Se conoce el riesgo de ciberseguridad a nivel organizativo, pero no se ha establecido un enfoque a nivel de toda la organización.
            td.p-4 La organización conoce su papel en el ecosistema más grande, pero no ha formalizado sus capacidad para interactuar y compartir información externamente.
          tr(style="background-color:#fff;")
            td.p-4.text-center(style="font-weight:bold;") 3
            td.p-4.text-center(style="font-weight:bold;") Repetible
            td.p-4 Las prácticas de gestión de riesgos de la organización son formalmente aprobadas y expresadas como políticas.
            td.p-4 Existe un enfoque a nivel de toda la organización para gestionar el riesgo de ciberseguridad.
            td.p-4 La organización entiende sus dependencias y socios y recibe información que permite la colaboración y las decisiones de gestión basadas en el riesgo.
          tr(style="background-color:#fff;")
            td.p-4.text-center(style="font-weight:bold;") 4
            td.p-4.text-center(style="font-weight:bold;") Adaptable
            td.p-4 La organización adapta sus prácticas de ciberseguridad basadas en las lecciones aprendidas y los indicadores predictivos.
            td.p-4 Existe un enfoque a nivel de toda la organización para gestionar el riesgo de ciberseguridad que utiliza políticas, proceso y procedimientos.
            td.p-4 La organización gestiona el riesgo y comparte activamente la información con los socios para garantizar que se distribuye información precisa para mejorar la ciberseguridad antes de que se produzca un evento.

    .row.mb-5.m-0.mt-5(style="background-color:#40327B;border-top-right-radius:150px;border-bottom-right-radius:150px;max-width:fit-content;")
      .col-auto.p-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema5/23.svg" data-aos="fade-right")
      .col(style="place-self:center;")
        h3.text-white.mb-0(data-aos="fade-up") Implementación

    p.mt-4(data-aos="fade-up") El marco se puede implementar en cualquier organización. A continuación, se revisarán los pasos básicos para su adopción:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 18.
      span  Pasos para la implementación de CSF en una organización
    figure.mt-4
      img.d-none.d-lg-block(src="@/assets/curso/tema8/23.svg" data-aos="zoom-in-up" alt="La imagen presenta los pasos básicos para la implementación del CSF en una organización: priorizar el alcance, orientar, crear un perfil actual, realizar una evaluación de riesgos, crear un perfil de destino, determinar, analizar y priorizar brechas, e implementar un plan de acción.")
      img.d-block.d-lg-none(src="@/assets/curso/tema8/23.svg" data-aos="zoom-in-up" alt="La imagen presenta los pasos básicos para la implementación del CSF en una organización: priorizar el alcance, orientar, crear un perfil actual, realizar una evaluación de riesgos, crear un perfil de destino, determinar, analizar y priorizar brechas, e implementar un plan de acción.")

    p.mt-5(data-aos="fade-up") A continuación, se amplía cada uno de los pasos de acuerdo con su papel en la implementación NIST CSF:

    .cont_8_3.mt-5.pt-5.pb-5
      .col-xl-8.m-auto
        PasosA.color-acento-contenido(tipo="n")
          .row
            .col-md-6.mb-4.mb-md-0
              h4(data-aos="fade-right") Priorizar el alcance
              p.mt-4(data-aos="fade-right") La organización debe identificar sus objetivos de negocio / misión y las prioridades organizacionales de alto nivel para tomar las decisiones estratégicas relacionadas con la implementación.
            .col-md-6
              figure
                img(src='@/assets/curso/tema8/25.png' data-aos="fade-left")
          .row
            .col-md-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema8/26.png' data-aos="fade-left")
            .col-md-6
              h4(data-aos="fade-right") Orientación
              p.mt-4(data-aos="fade-right" style="text-align:left") Se identifican los sistemas, activos, requerimientos regulatorios, amenazas y vulnerabilidades vinculadas al entorno de aplicabilidad definido.
          .row
            .col-md-6.mb-4.mb-md-0
              h4(data-aos="fade-right") Crear un perfil actual o literal
              p.mt-4(data-aos="fade-right") A través de las funciones del marco básico y empleando las categorías y subcategorías, se obtienen los resultados de implementación de controles en el entorno.
            .col-md-6
              figure
                img(src='@/assets/curso/tema8/27.png' data-aos="fade-left")
          .row
            .col-md-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema8/28.png' data-aos="fade-left")
            .col-md-6
              h4(data-aos="fade-right"  style="text-align:left") Ejecutar un análisis de riesgos
              p.mt-4(data-aos="fade-right" style="text-align:left") Se ejecuta un análisis de riesgos que permita determinar la probabilidad y el impacto de eventos de ciberseguridad en el entorno analizado.
          .row
            .col-md-6.mb-4.mb-md-0
              h4(data-aos="fade-right" ) Crear un perfil objetivo
              p.mt-4(data-aos="fade-right" style="text-align:left") Se establecen los objetivos que, en términos de ciberseguridad, la organización pretende cubrir.
            .col-md-6
              figure
                img(src='@/assets/curso/tema8/29.png' data-aos="fade-left")
          .row
            .col-md-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema8/30.png' data-aos="fade-left")
            .col-md-6
              h4(data-aos="fade-right"  style="text-align:left") Determinar, analizar y priorizarlas brechas detectadas
              p.mt-4(data-aos="fade-right" style="text-align:left") Mediante el análisis diferencial entre el perfil actual y el perfil objetivo, se define un plan de acción priorizado en términos de coste/beneficio, que permita la determinación de recursos y acciones de mejora.
          .row
            .col-md-6.mb-4.mb-md-0
              h4(data-aos="fade-right") Implementar el plan de acción
              p.mt-4(data-aos="fade-right"  style="text-align:left") Se procede con la alineación de controles y despliegue de mejoras, de forma paulatina y monitorizada.
            .col-md-6
              figure
                img(src='@/assets/curso/tema8/31.png' data-aos="fade-left")





</template>

<script>
export default {
  name: 'Tema8',
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
.cont_8_1 *
  position: relative
.cont_8_1:before
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
.cont_tarjeta_8_1
  background: url(../assets/curso/tema8/4.png)
  background-repeat: no-repeat
  background-size: 100% 100%
.cont_8_3 *, .cont_8_3
  position: relative
.cont_8_3:before
  position: absolute
  content: ''
  width: 125%
  height: 100%
  left: -15%
  top: 0
  background: url(../assets/curso/tema8/24.png)
  background-size: 100% 100%
.pasos-a.color-acento-contenido .pasos-a__circle div
  color: white
</style>
