<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.mb-4
      .col-lg-12
        img(src='@/assets/curso/temas/intro/1.png', alt='')
    
    p La acelerada evolución de las Tecnologías de la Información y la Comunicación (TIC) ha generado profundas transformaciones en la forma en que las organizaciones gestionan, procesan y almacenan la información. Por ello, la computación en la nube se ha consolidado como uno de los principales motores de la transformación digital, al ofrecer soluciones tecnológicas flexibles, escalables y accesibles que responden a las necesidades de un entorno cada vez más dinámico y conectado.



    p La apropiación de estos conocimientos resulta fundamental para el desarrollo de competencias demandadas por el sector productivo actual, el cual requiere talento humano capaz de implementar soluciones tecnológicas eficientes, seguras y alineadas con los procesos de transformación digital. En consecuencia, al finalizar este componente, el aprendiz contará con los elementos necesarios para analizar escenarios tecnológicos, seleccionar servicios adecuados, participar en procesos de migración hacia la nube y contribuir al fortalecimiento de la infraestructura digital de las organizaciones.
    
    .row.justify-content-center.align-items-center           
      .col-lg-12
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/vdPrCjWJSHo?si=X4NxENRo3LLXAua_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

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
