<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 2
      h1 Blockchain
    
    p.mb-4 En la siguiente figura se explica en qué consiste esta tecnología.

    .titulo-sexto.color-acento-contenido
      h5 Figura 2.
      span #[i Blockchain]
    
    figure.mb-4
      img(src='@/assets/curso/tema2/img01.svg', alt='Blockchain')
    
    p.mb-4 El problema que quiere solucionar esta tecnología se puede explicar en el siguiente ejemplo: 

    .row.mb-4
      .col-lg-6
        p.p-5.BGcolorH.mb-0 Cuando una persona llamada Pepito quiere realizar un envío de un millón de pesos a otra persona llamada Mario normalmente se hace por medio de un banco, donde el banco actúa como intermediario de esta transacción haciendo una centralización efectiva para hacer el movimiento de un lado al otro. En este proceso, ni Pepito ni Mario intervienen, son totalmente dependientes del banco y a las condiciones de este como comisiones, por ejemplo, es aquí donde el blockchain o cadena de bloques interviene, porque su principal objetivo es eliminar los intermediarios haciendo una gestión totalmente descentralizada, donde el control ya no va a hacer de los bancos si no de los usuarios convirtiéndose estos en una conexión de muchos nodos del banco. 
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img02.svg', alt='Ejemplo')
    
    .BG40.p-4
      .row.justify-content-between.align-items-center
        .col-lg-7
          p.mb-0 En resumen, se puede decir que el blockchain o cadena de bloques es un gran libro digital de cuentas en donde sus bloques (registros) se encuentran conectados y cifrados con el objetivo de proteger la privacidad y la seguridad de cualquier tipo de transacciones. 
        .col-lg-2
          figure
            img(src='@/assets/curso/tema2/img03.svg', alt='Blockchain')


</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
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

<style lang="sass"></style>
