<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.mt-5 Estimado aprendiz, a través del siguiente video, podrá conocer los aspectos relevantes que tratará este componente:
    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/oEN7_-2RBPk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.mt-5(data-aos="flip-right")
      .col-12.col-lg-8
        p Para la elaboración de este componente, se abordaron varios autores #[strong conocidos en estructuración de proyectos y propuesta de mercadeo para el sector del deporte], de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido de que el conocimiento es social y, por lo tanto, es para ser usado por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos aquellos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de la #[strong gestión de las organizaciones deportivas.]
      .col-4.offset-4.offset-lg-0.mt-3.mt-lg-0
        figure
          img(src="@/assets/template/tema-0-1.svg", alt="Texto que describa la imagen").floating.w-75.margin-0-auto
    

    
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
