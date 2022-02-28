<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="fade")
      .titulo-principal__numero
        span
          i.fas.fa-info.text-white
      h1 Introducción
    
    p.mb-4(data-aos="fade-down") Bienvenido a este material de formación. A continuación, se invita a ver el siguiente recurso.

    figure.mb-5(data-aos="flip-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/4_sAijp9mJ0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
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
