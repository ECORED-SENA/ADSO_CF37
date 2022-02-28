<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .titulo-principal.color-acento-contenido(data-aos="fade")
      .titulo-principal__numero
        span.text-white 1
      h1 Internet de las cosas (IoT)

    .bloque-texto-g.py-md-5.mb-4(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img01.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4.BGcolorH
        p.mb-0 Debido a la gran importancia y progreso que ha logrado la IoT es valorada como una de las tecnologías de mayor impacto a 2025, debido a que se intuye que a una gran cantidad y variedad de objetos se les incorporará variados tipos de sensores que estarán conectados a Internet produciendo un flujo de datos muy grande, el cual debe ser tratado, almacenado y expuestos de una forma sencilla y fácil de entender (Molano, 2015).
    
    .BGcolor01.p-5.BR01.mb-4(data-aos="flip-left")
      p.mb-0.text-white El concepto de IoT (Internet de las cosas) fue presentado por primera vez en Proctor y Gamble en el año de 1999 por Kevin Ashton, describiendo que consistía en la generalización de una variedad de diferentes cosas, objetos o elementos de tipo cotidiano integrados como etiquetas de identificación por medio de radiofrecuencias (RFID), los cuales eran controlados por Internet, generando una gran cantidad de datos que necesitaban ser recolectados y almacenados, razón por la cual IoT se integra con Cloud Computing para que estos datos se alojen en Internet facilitando que estén en continua disponibilidad, para que las empresas, usuarios puedan acceder desde cualquier lugar.
    
    .row.justify-content-center(data-aos="flip-left")
      .col-lg-7
        img(src='@/assets/curso/tema1/img02.svg', alt='agrupación de sensores y equipos electrónicos')
    .cajon.color-acento-botones.py-4.px-5.mb-4.BG40(data-aos="flip-down")
      p.mb-0 En resumen, se puede decir que IoT es la agrupación de sensores y equipos electrónicos conectados entre sí con el objetivo de calcular, recolectar y mandar datos a un servicio de almacenamiento en la nube.
    
    p.mb-5(data-aos="fade") El IoT en la actualidad está organizado por una recolección extendida de diferentes redes y con propósitos distintos, por ejemplo, los carros modernos cuentan con una cantidad variada de redes para moderar la puesta en marcha del motor, el monitoreo de comunicación, los sistemas de seguridad, etc., de manera parecida los centros comerciales, las oficinas, los apartamentos manejan diferentes sistemas que permiten controlar la calefacción, el aire acondicionado, los sistemas de seguridad, etc., en tanto que el IoT avanza todas estas redes quedarán conectadas incorporando medidas de análisis, administración y seguridad, haciendo del IoT una herramienta todavía más poderosa. Ver figura 1.

    .titulo-sexto.color-acento-contenido
      h5 Figura 1.
      span Internet de las cosas red de redes
    .row.justify-content-end.mb-3
      h4.text-center.mb-4 Internet de las cosas
      .col-lg-9
        figure
          img(src='@/assets/curso/tema1/img03.svg', alt='Internet de las cosas')
    .row.justify-content-center.mb-5
      .col-md-3
          figcaption Nota: Tomado de Cisco IBSG (2011).
    
    #t1_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 1.1 Aplicaciones
    
    p.mb-4(data-aos="fade-down") Entre las diferentes áreas de aplicación que tiene el mundo del IoT se destacan las siguientes:

    .bgImg01.p-5.mb-5.BR01(data-aos="flip-left")
      SlyderA(tipo="b")
        .row.justify-content-evenly.align-items-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/img05.svg', alt='Domótica')
        
          .col-md-5
            h4 Domótica
            p Consiste en la sistematización de una edificación, casa, o inmueble, conectando entre sí diferentes tipos de servicios como (energía, agua, ventilación) y dispositivos como (cerrojos, electrodomésticos), optimizando la seguridad y eficiencia energética garantizando un mejor bienestar para el usuario.
          
        .row.justify-content-evenly.align-items-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/img06.svg', alt='Domótica')
        
          .col-md-5
            h4 Automatización y control de procesos de producción
            p Se emplea la tecnología de IoT para incrementar la eficiencia en la fabricación de los productos conseguidos, así como su fiabilidad y el continuo seguimiento del producto en la fábrica.
        
        .row.justify-content-evenly.align-items-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/img07.svg', alt='Domótica')
        
          .col-md-5
            h4 Transporte y logística
            p Consiste en monitorizar medios de transporte y el proceso de envío de productos, validar estados de conservación, ubicación, evitando robos o pérdidas, logrando realizar análisis de mejores rutas o administración de tráfico. Unos ejemplos donde son utilizados son en las empresas de envíos o en las plataformas de servicios de carros o como se puede ver en la figura 5 gestión de tiempos de traslados, gestión y control de vehículos.
        
        .row.justify-content-evenly.align-items-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/img08.svg', alt='Domótica')
        
          .col-md-5
            h4 Agricultura, ganadería y silvicultura
            p Al igual que en las fábricas IoT es utilizado para la automatización de trabajos primordiales con lo relacionado del agro, como por ejemplo, sistema de riego, sistema de detector de temperatura para siembra, detección de enfermedades de los animales, etc.
        
        .row.justify-content-evenly.align-items-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/img09.svg', alt='Domótica')
        
          .col-md-5
            h4 Videovigilancia y seguridad
            p Consiste en la configuración y control de una variedad de equipos de seguridad tales como sensores de movimiento, alarmas inteligentes, detección de amenazas para proteger la seguridad de edificaciones, casas y así contar con una prevención cuando se presenten situaciones de riesgo.es, etc.
        
        .row.justify-content-evenly.align-items-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/img10.svg', alt='Domótica')
        
          .col-md-5
            h4 Medicina
            p Sus objetivos son detectar de una persona sus signos vitales, así como las variaciones para suministro de medicinas. Aunque la orientación es más a los humanos es posible también monitorear el estado de salud de los animales domésticos. La incorporación de IoT en el sector de la salud transformará el cuidado médico, ya que los centros de atención serán mucho más eficientes, brindando al personal de la salud datos muy importantes de los pacientes en tiempos más cortos, para poder agilizar los procesos médicos.

    #t1_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 1.2 Desarrollos
    
    div(data-aos="fade-down")
      p En la actualidad existen muchos desarrollos que incorporan IoT en sus diferentes áreas de aplicación. 
      p.mb-4 A continuación se nombran unos de los más novedosos y curiosos.

    TabsB.color-primario(data-aos="fade")
      .py-4.py-md-5.BGcolorH(titulo="<i>Hidrate Spark</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema1/img11.jpg', alt='Hidrate Spark')
          .col-md-6.bg-white.p-4
            p Se trata de un termo de agua que tiene colores metálicos muy llamativos, que informa el tiempo en que se debe tomar agua y reporta la cantidad de agua tomada según lo que se configure, este funciona por medio de un sensor que recolecta cada trago de agua y lo envía al celular por medio de #[i bluetooth].
      
      .py-4.py-md-5.BGcolorH(titulo="<i>Ability MyCite</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema1/img12.jpg', alt='Ability MyCite')
          .col-md-6.bg-white.p-4
            p Es una pastilla inteligente que fue creada por Otsuka Pharmacutical Co y Proteus Digital utilizada para tratar a las personas que sufren de trastorno bipolar o esquizofrenia, la pastilla incluye un sensor que envía señales a una APP, el sensor es activado cuando la pastilla se disuelve con los ácidos gástricos del estómago, permitiendo así realizar un seguimiento al paciente verificando la hora de toma del medicamento y si en efecto se lo está tomando.
      
      .py-4.py-md-5.BGcolorH(titulo="<i>Waymo</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema1/img13.jpg', alt='Waymo')
          .col-md-6.bg-white.p-4
            p Es el primer carro autónomo creado por Google, que permite a un automóvil conducirse autónomamente por carreteras, detecta señales de tráfico, peatones y otros carros, inicialmente el nombre del proyecto era Google self-driving car Project y luego recibió el nombre de #[i Waymo].
      
      .py-4.py-md-5.BGcolorH(titulo="<i>Google Glass</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema1/img14.jpg', alt='Google Glass')
          .col-md-6.bg-white.p-4
            p Son unas gafas desarrolladas por Google para realidad aumentada, su función principal es poder manejar aplicaciones sin utilizar las manos, solo con comandos de voz, estas gafas incorporan un miniproyector que muestra una imagen virtual al ojo. Estas gafas son usadas en diferentes áreas como la educación, la industria, la medicina, etc.

</template>

<script>
export default {
  name: 'Tema1',
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
