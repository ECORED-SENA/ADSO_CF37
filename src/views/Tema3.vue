<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos="fade")
      .titulo-principal__numero
        span.text-white 3
      h1 #[i Machine learning]

    .row.my-5(data-aos="fade-down")
      .col-lg-6.BGcolorH.p-5.mb-4.mb-lg-0
        p
          | El #[i machine learning] es una rama de la AI (Inteligencia Artificial) que 
          span.etiqueta consiste en lograr que las máquinas aprendan automáticamente sin necesidad de ser programadas. 
          | El inicio de #[i machine learning] se da en el año 1943 cuando el neurofisiólogo Warren McCulloch y el matemático Walter Pitts dan a conocer el concepto de inteligencia artificial y en el trabajo que presentaron plantearon que se analizaría el cerebro como un ente computacional y la creación de supercomputadoras capaces de funcionar mucho mejor que la red neuronal humana, es aquí donde el mundo iniciaría a inquietarse por qué tanta inteligencia llegará a tener una máquina y qué implicaciones traería. (Hinestroza, 2018). En el siguiente material puede revisar la evolución del #[i machine learning].
      .col-lg-6.bgESP01
        img.w-50.mx-auto.mNeg01(src='@/assets/curso/tema3/img01.png', alt='AI' data-aos="flip-left")
    
    .tarjeta.BG41.p-4.mb-5(data-aos="fade-up")
      h3.mb-4 La Historia #[i Machine learning]
      LineaTiempoC.color-primario(text-small)
        .row.mx-5(titulo="1950")
          p Gracias al científico Alan Mathison Turing que crea el “#[i Test de Turing]”, cuyo objetivo principal consistía en determinar la inteligencia de una computadora por medio de una conversación con un humano, la idea era imitar el comportamiento del ser humano sin que se diera cuenta que estaba conversando con una máquina.

        .row.mx-5(titulo="1952")
          p El informático y profesor Arthur Samuel lanza el primer programa para computadores preparado para aprender. El #[i software] consistía en un juego de damas que almacenaba información y estrategias de juego y que entre más partidas se jugaba había un mayor mejoramiento en el juego.

        .row.mx-5(titulo="1956")
          p Con el apoyo de Minsky, John McCarthy, Claude Shannon y Nathan Rochester dan nacimiento a la inteligencia artificial.
        
        .row.mx-5(titulo="1958")
          p Rosenblat da a conocer la primera red neuronal artificial.
        
        .row.mx-5(titulo="Años 70")
          p Se crea el robot “Stanford Car”, un robot móvil que tenía la capacidad de moverse de manera autónoma en un cuarto sin chocar con obstáculos y también Neighbor implementa el reconocimiento de patrones en computadores, dando inicio al #[i machine learning], debido a que cuando se le daba la posibilidad a una máquina el aprendizaje de patrones la solución de respuesta era muy efectiva.
        
        .row.mx-5(titulo="Años 80")
          p La revolución se enfoca en el campo del procesamiento de datos cuando Gerald Dejong incorpora el concepto de “#[i Explanation Based Learning]” (EBL), que se trataba de una especie de aprendizaje automático, el computador realiza el análisis de datos entrenados y genera reglas cuyo objetivo es filtrar los datos que tienen menos importancia.
        
        .row.mx-5(titulo="2003")
          p Se hace la publicación de un estudio referente a un sistema distribuido de ficheros que recibe el nombre de “#[i Google File System]” (GFS), y toma más fuerza el año 2004 debido a que Google muestra la creación de un nuevo paradigma llamado “Map & Reduce” enfocado al procesamiento distribuido.
        
        .row.mx-5(titulo="2006")
          p Sigue el crecimiento y apoyando Google este progreso crea “#[i Cloud Bigtable]” que se trata del servicio de bases de datos NoSQL de #[i Big Data] culminando con Hadoop que es una plataforma “#[i Big Data Open Source]”.
        
        .row.mx-5(titulo="2010")
          p En adelante Muchas de las grandes empresas como Amazon, IBM, Google, Facebook, iniciaron a desarrollar sus propios productos con #[i machine learning].
        
        .row.mx-5(titulo="Actualidad")
          p No paran los grandes avances relacionándose con aplicaciones del mundo empresarial que se benefician del #[i Machine Learning] logrando crear estrategias para la creación de completos mercados incorporando cada vez más sectores.
    
    #t3_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 3.1 Conceptos
    
    p.mb-5(data-aos="fade-down") Existen muchos conceptos alrededor del #[i machine learning]. A continuación, se describen los más importantes:

    .bgESP02.p-4.d-inline-block(data-aos="flip-down")
      h4.text-white.mb-0 Inteligencia artificial
    .BGcolorH.p-4.mb-5(data-aos="fade")
      p Consiste en aplicar técnicas sistematizadas que proporcionan a las computadoras recibir algunas características que tiene la inteligencia humana, como por ejemplo, reconocer el significado de objetos y poder identificarlos, resolución de problemas autónomamente, aprendizaje de tareas nuevas, procesamiento de lenguaje natural, reconocimiento de imágenes, entre otros.
      
      p Se tiende a confundir mucho el concepto de inteligencia artificial con #[i machine learning], pero son diferentes, #[i machine learning] es una rama de la inteligencia artificial que se fundamenta en el potencial que tienen las máquinas para recoger un grupo de datos y aprender por sí mismo, apropiando los algoritmos a medida que se va aprendiendo de la información procesada. 

      p.mb-4 La siguiente figura muestra otras de las características que diferencian los dos conceptos.

      .titulo-sexto.color-acento-contenido(data-aos="fade")
        h5 Figura 4.
        span  AI vs. #[i Machine Learning]
      h4.mb-4.text-center Inteligencia Artificial vs. #[i Machine Learning] 
      figure.mb-4
        img.mb-3(src='@/assets/curso/tema3/img02.svg', alt='Texto que describa la imagen')
        figcaption.bg-white Nota: Tomado de Future space https://www.futurespace.es/machine-learning-los-origenes-y-la-evolucion/
      
      p.mb-4 Existen varios tipos de #[i machine learning], ver figura.
      .titulo-sexto.color-acento-contenido
        h5 Figura 5.
        span  Tipos de #[i machine learning]
      h4.mb-4.text-center Tipos de #[i Machine Learning]
      .row.justify-content-center
        .col-lg-8
          figure.mb-4
            img.mb-3(src='@/assets/curso/tema3/img03.svg', alt='Texto que describa la imagen')
    
    .bgESP02.p-4.d-inline-block(data-aos="flip-down")
      h4.text-white.mb-0 Aprendizaje supervisado
    .BGcolorH.p-4.mb-5(data-aos="fade")
      p.mb-4 En este tipo de aprendizaje se utiliza información de entrenamiento llamada #[i dataset], en donde lo que se hace es entrenar con muchas imágenes (#[i labels]) un modelo para que finalmente pueda determinar de cuál #[i label] se trata. Básicamente es un grupo de técnicas, cuya función es permitir hacer predicciones fundamentadas en conductas que son analizadas en datos que han sido históricamente etiquetados. Ver figura.

      .titulo-sexto.color-acento-contenido
        h5 Figura 6.
        span  Tipos de #[i machine learning]

      .row.justify-content-center.mb-4
        .col-lg-10
          figure.mb-4
            img.mb-3(src='@/assets/curso/tema3/img04.svg', alt='Texto que describa la imagen')
            figcaption.bg-white Nota: Tomado de (https://www.diegocalvo.es/aprendizaje-supervisado/)
      
      p La figura 6 muestra un ejemplo que contiene un grupo de datos que están etiquetados a propósito: 1. Manzana, 2. Cítricos, 3. Sandías y 4. Plátanos. Después, por medio de un vector son extraídas las características de todo el grupo y con esta información se realiza el entrenamiento al algoritmo de aprendizaje automático. Lo que hace el algoritmo es crear un modelo al que se le pueden agregar nuevos grupos de datos para que sean clasificados nuevos elementos nunca vistos, aplicando lo aprendido en el entrenamiento inicial.

      p.mb-4(data-aos="fade") El aprendizaje supervisado se clasifica en dos tipos de métodos: clasificación y regresión. La clasificación consiste, como su nombre lo dice, en hacer una clasificación en un grupo reconociendo datos que ya han sido etiquetados anteriormente. En la figura 7 se puede ver el ejemplo de este método cuando se clasifican las frutas por su color o forma.

      .titulo-sexto.color-acento-contenido(data-aos="fade-down")
        h5 Figura 7.
        span #[i Método de clasificación]
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-4
          figure.mb-4
            img.mb-3(src='@/assets/curso/tema3/img05.svg', alt='Texto que describa la imagen')
      
      p(data-aos="flip-left") El método de regresión realiza la predicción de datos continuos partiendo de datos etiquetados históricamente, un ejemplo es predecir lluvias o el cambio del valor de un producto, etc.

    .bgESP02.p-4.d-inline-block(data-aos="flip-down")
      h4.text-white.mb-0 Aprendizaje no supervisado
    .BGcolorH.p-4.mb-5(data-aos="fade")
      p Al contrario del aprendizaje supervisado, el no supervisado no tiene etiquetas, su objetivo es entender y abstraer patrones de información; se clasifica en #[i clustering] y en reducción.

      p.mb-4 La figura 8 muestra el proceso de aprendizaje no supervisado.

      .titulo-sexto.color-acento-contenido
        h5 Figura 8.
        span  #[i Proceso aprendizaje no supervisado]

      .row.justify-content-center.mb-4
        .col-lg-10
          figure.mb-4
            img.mb-3(src='@/assets/curso/tema3/img06.svg', alt='Texto que describa la imagen')
    
    .bgESP02.p-4.d-inline-block(data-aos="flip-down")
      h4.text-white.mb-0 Aprendizaje por refuerzo
    .BGcolorH.p-4.mb-5(data-aos="fade")

      p.mb-4(data-aos="flip-left") Se trata de realizar el entrenamiento de un algoritmo para crear un modelo que esté capacitado para obtener una salida con el resultado más óptimo. El entrenamiento del modelo se hace programando que cada acción tenga sus premios o penalidades, así por cada prueba y error logrará encontrar el resultado que propague los premios. Ver figura.

      .titulo-sexto.color-acento-contenido
        h5 Figura 9.
        span  #[i Aprendizaje por refuerzo]

      .row.justify-content-center.mb-4
        .col-lg-7
          figure
            img.mb-3(src='@/assets/curso/tema3/img07.svg', alt='Texto que describa la imagen')
            figcaption.bg-white Nota: Tomado de https://www.aprendemachinelearning.com
    
    #t3_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 3.2 Aplicaciones
    
    p.mb-5(data-aos="fade-down") El #[i machine learning] se aplica en muchas cosas de nuestra vida cotidiana, a continuación, se nombrarán algunos de los ejemplos donde se aplica y que hacen un gran aporte:

    .row.justify-content-center.mb-4(data-aos="fade-left")
      .col-lg-7
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          div(titulo="Reconocimiento de imágenes")
            p.mb-0 Para este proceso existen aplicaciones que comparan las letras, las agrupan y descifran aquellos textos que contienen imágenes. Un ejemplo más claro es el reconocimiento facial que realizan aplicaciones como Nequi o Facebook por medio de redes neuronales complejas.

          div(titulo="Reconocimientos de voz")
            p.mb-0 Los modelos entrenados para el reconocimiento de voz detectan el sonido y pueden entender las órdenes dadas desde nuestro celular o computador y un ejemplo de estos son Cortana y Siri.          

          div(titulo="Predicción de datos")
            p.mb-0 #[i Machine learning] facilita predecir efectivamente datos que se obtienen a través del ingreso de estos a un sistema, se utilizan normalmente en estrategias de comercialización.

          div(titulo="Coches autónomos")
            p.mb-0 Se aplican los modelos que realizan reconocimiento en tiempo real, los cuales permiten que los carros se desplacen de forma autónoma. Uno de los ejemplos de la actualidad son los carros Tesla.
          
          div(titulo="Sistemas de recomendación")
            p.mb-0 Es uno de los ejemplos que aplica #[i machine learning] con el que se interactúa en la cotidianidad, ya que aplica algoritmos que siguen patrones de comportamiento según lo que  se vea, por ejemplo, las plataformas de películas como Netflix o las aplicaciones de música como YouTube y Spotify.
          
          div(titulo="Watson")
            p.mb-0 #[i Software] de inteligencia artificial creado por IBM que puede dar respuesta a preguntas realizadas en un lenguaje natural.

          div(titulo="DeepFace")
            p.mb-0 Algoritmo creado por Facebook que reconoce personas en fotos.
    
    #t3_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 3.3 #[i Deep learning]
    
    p.mb-4 El #[i Deep learning] se fundamenta también en la inteligencia artificial (AI), es traducido en inglés como aprendizaje profundo y está compuesto por redes neuronales profundas. Su objetivo es tratar de hacer modelos muy similares al aprendizaje que utilizan los humanos para adquirir conocimiento de algo. Aunque se tiende a pensar que el #[i machine learning] y el #[i Deep learning] es lo mismo no es así, ya que los algoritmos que utiliza el #[i machine learning] son tradicionales y lineales, mientras que los del #[i Deep learning] son fuertemente complejos.

    figure.mb-4(data-aos="flip-down")
      img.mb-3(src='@/assets/curso/tema3/img08.svg', alt='Texto que describa la imagen')
    
    figure.mb-4(data-aos="flip-up")
      img.mb-3(src='@/assets/curso/tema3/img09.svg', alt='Texto que describa la imagen')

    p.mb-4 Algunos objetivos del #[i Deep learning] son:

    .cajon.color-acento-botones.p-4.mb-5
      ul.lista-ul--color.mb-0
        li 
          i.fas.fa-check
          | Lograr que los computadores se instruyan para poder clasificar sonidos, imágenes y textos sin que un humano intervenga.
        li 
          i.fas.fa-check
          | Perfeccionar los procesos pesados respondiendo a necesidades de los humanos, resolviendo problemas de la sociedad.
        li 
          i.fas.fa-check
          | Exactitud, lograr un comportamiento que supere al del humano.
    
    p(data-aos="fade") Un ejemplo claro es la recomendación de amigos que hacen las redes sociales como Facebook, identificar las caras y fotos para etiquetar.

</template>

<script>
export default {
  name: 'Tema3',
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
