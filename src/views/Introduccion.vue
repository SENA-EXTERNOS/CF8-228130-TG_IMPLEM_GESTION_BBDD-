<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/intro/img1.svg')})`}"
      )
      .bloque-texto-g__texto.p-4.mb-5.borde-lineas
        p.mb-0 Bienvenidos al desarrollo de este componente formativo, a través del cual conocerán sobre la historia de los sistemas operativos de red, licenciamientos y sus tipos, así como conceptos de #[em networking]; antes de empezar, se sugiere visualizar el siguiente video para identificar el contexto de aprendizaje.
              
    figure.mb-5
    .video
      iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p.mb-0 #[br]#[br]Muchos éxitos en este proceso de aprendizaje.

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
