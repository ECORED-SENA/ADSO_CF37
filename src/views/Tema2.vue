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
    
    .BG40.p-4.mb-4
      .row.justify-content-between.align-items-center
        .col-lg-7
          p.mb-0 En resumen, se puede decir que el blockchain o cadena de bloques es un gran libro digital de cuentas en donde sus bloques (registros) se encuentran conectados y cifrados con el objetivo de proteger la privacidad y la seguridad de cualquier tipo de transacciones. 
        .col-lg-2
          figure
            img(src='@/assets/curso/tema2/img03.svg', alt='Blockchain')
    
    p.mb-4 #[strong En la siguiente figura se muestra gráficamente la comparación entre un sistema tradicional y un sistema blockchain.]

    .titulo-sexto.color-acento-contenido
      h5 Figura 3.
      span Sistema tradicional vs Sistema blockchain
    
    .row.mb-5
      .col-md-6
        figure
          img(src='@/assets/curso/tema2/img04.svg', alt='Blockchain')
      .col-md-6
        figure
          img(src='@/assets/curso/tema2/img05.svg', alt='Blockchain')
    
    #t2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Historia
    
    p El blockchain tuvo su inicio en los años de 1991-2008, en un primer trabajo Stuart Haber y Scott realizaron tareas en una cadena de bloques que era protegida criptográficamente, esto quería decir que no se podía realizar ningún tipo de manipulación en las marcas de tiempo de los documentos. En el año 1991 se añadieron árboles de Merkle que lograron una mejor eficiencia, permitiendo que en un solo bloque se recopilara más de un documento. Pero es en el año 2008 que el blockchain inicia su crecimiento cuando Satoshi Nakamoto y un grupo de personas lanzan su trabajo con bitcoin, creando la primera aplicación de registro digital que permitía administrar la red del bitcoin, permitiendo la interacción por medio de foros entre los interesados.

    .row.justify-content-between
      .col-md-6
        p Desde los años 2008 al 2013 emerge el bitcoin y las transacciones, es importante aclarar que no hay que confundir el concepto de blockchain y bitcoin, ya que muchas personas piensan que es lo mismo, y no es así debido a que blockchain es la tecnología en que se fundamentan las aplicaciones y una de ellas es la criptomoneda. El nacimiento del bitcoin fue en 2008 y fue la primera aplicación que incluía la tecnología blockchain, la definición dada por Satoshi Nakamoto en su artículo fue que se trataba de un sistema eléctrico peer to peer (punto a punto) (Nakamoto, 2008). 

        p Satoshi estableció el bloque origen de donde salieron otros bloques, los cuales se interconectaban obteniendo como resultado una gran cadena de bloques que enviaban varios fragmentos de información y transacciones. Desde el momento en que el bitcoin que es una aplicación de blockchain se puso en conocimiento han surgido una gran variedad de aplicaciones que tienen como objetivo el aprovechamiento de la tecnología digital.

      .col-md-5
        figure
          img(src='@/assets/curso/tema2/img06.jpg', alt='Blockchain')

    p Ya para los años 20013-2015 blockchain evolucionó a su versión 2.0 y trajo con esta versión los llamados contratos inteligentes (smart contracts) desarrollo realizado por Vitalik Butterin y al que llamaron Ethereum, que incorporaba una función que ofrece a los individuos registrar otro tipo de activos como lo son los contratos, ampliando a una plataforma que también desarrolla aplicaciones descentralizadas. Un contrato inteligente es un conjunto de instrucciones que se almacenan en un blockchain, las cuales se ejecutan automáticamente dependiendo de los parámetros programados, esta ejecución se realiza de forma segura e inmutable. 

    p.mb-4 A partir del 2018 surgen una serie de proyectos explotando la gran capacidad de la tecnología blockchain, estos proyectos buscaban tratar las fallas de Ethereum y Bitcoin, incluyendo también nuevas características. Una de las aplicaciones más representativas fueron IOTA y NEO enfocadas en proporcionar más seguridad y escalabilidad que las aplicaciones iniciales de blockchain.

    p.mb-4 #[strong Revise la siguiente línea de tiempo que resume la historia del blockchain.]

    .tarjeta.BG41.p-4.mb-5
      LineaTiempoC.color-primario(text-small)
        .row.mx-5(titulo="1991 – 2008")
          .col-md-6.mb-4.mb-md-0
            p Stuar Haber y Scott Stornetta trabajan en el primer #[i blockchain].      
          .col-md-3
            figure
              img(src='@/assets/curso/tema2/img12.svg', alt='Texto que describa la imagen')


        .row.mx-5(titulo="2009")
          .col-md-6.mb-4.mb-md-0
            p Satoshi Nakamoto lanza el #[i whitepaper] de #[i bitcoin].      
          .col-md-2
            figure
              img(src='@/assets/curso/tema2/img11.svg', alt='Texto que describa la imagen')
        
        .row.mx-5(titulo="2010")
          .col-md-6.mb-4.mb-md-0
            p La primera compra de #[i bitcoin] tiene lugar 10.000 BTC.      
          .col-md-3
            figure
              img(src='@/assets/curso/tema2/img13.svg', alt='Texto que describa la imagen')
        
        .row.mx-5(titulo="2013")
          .col-md-6.mb-4.mb-md-0
            p El mercado de bitcoin supera los $1 mil millones Vitalik Buterín lanza el #[i whitepaper] de Ethereum.     
          .col-md-2
            figure
              img(src='@/assets/curso/tema2/img11.svg', alt='Texto que describa la imagen')
        
        .row.mx-5(titulo="2014")
          .col-md-6.mb-4.mb-md-0
            p Ethereum blockchain es financiado por crowdsale La tecnología blockchain R3 se forma e inicia un consorcio de más de 40 compañías financieras legadas para implementar la tecnología blockchain.  
          .col-md-3
            figure
              img(src='@/assets/curso/tema2/img10.svg', alt='Texto que describa la imagen')
        
        .row.mx-5(titulo="2015")
          .col-md-6.mb-4.mb-md-0
            p El bloque Génesis de Ethereum es creado Linux foundation presenta hyperledger para mejorar.
          .col-md-3
            figure
              img(src='@/assets/curso/tema2/img07.svg', alt='Texto que describa la imagen')
        
        .row.mx-5(titulo="2016")
          .col-md-6.mb-4.mb-md-0
            p Error en el código de Ethereum DAO explotado y atacado.
          .col-md-3
            figure
              img(src='@/assets/curso/tema2/img09.svg', alt='Texto que describa la imagen')
        
        .row.mx-5(titulo="2017")
          .col-md-6.mb-4.mb-md-0
            p EOS es presentado por Blockone como un nuevo protocolo de blockchain para el despliegue de aplicaciones descentralizadas.
    
    p.mb-4 Es así como podemos concluir que el blockchain se define como un tipo de comercio donde interactúan criptomonedas y transacciones, aunque la realidad es que es más que un seguro sistema bancario en línea, porque permite además, el fácil intercambio de objetos e ideas.

    p.mb-4 #[strong Las características principales son:]

    .row.gx-4.mb-4.justify-content-center
      .col-lg-5.mb-4
        .BG10.p-4
          .row
            .col-3
              figure
                img(src='@/assets/curso/tema2/img14.svg', alt='Texto que describa la imagen')
            .col-9
              p #[strong Inmutabilidad:] los datos grabados en las cadenas son irreversibles.


      .col-lg-5.mb-4
        .BG10.p-4
          .row
            .col-3
              figure
                img(src='@/assets/curso/tema2/img15.svg', alt='Texto que describa la imagen')
            .col-9
              p #[strong Transparencia:] cada uno de los bloques se pueden consultar y son visibles.
      
      .col-lg-5.mb-4
        .BG10.p-4
          .row
            .col-3
              figure
                img(src='@/assets/curso/tema2/img16.svg', alt='Texto que describa la imagen')
            .col-9
              p #[strong Sin intermediarios:] se sostiene con una cantidad de computadores en el mundo, no existe ninguna entidad o empresa intermediaria.


      .col-lg-5.mb-4
        .BG10.p-4
          .row
            .col-3
              figure
                img(src='@/assets/curso/tema2/img17.svg', alt='Texto que describa la imagen')
            .col-9
              p #[strong Distribuido:] la información se transmite por un conjunto de computadores que comparten información, donde todos están de acuerdo con esta.  
      
      .col-lg-5.mb-4
        .BG10.p-4
          .row
            .col-3
              figure
                img(src='@/assets/curso/tema2/img18.svg', alt='Texto que describa la imagen')
            .col-9
              p #[strong Veloz:] solo se necesitan unos pocos minutos para realizar transacciones internacionales.


      .col-lg-5.mb-4
        .BG10.p-4
          .row
            .col-3
              figure
                img(src='@/assets/curso/tema2/img19.svg', alt='Texto que describa la imagen')
            .col-9
              p #[strong Global:] solo es necesario Internet para que la información pueda ser vista.
    
    p.mb-4 En el siguiente recurso se muestra el proceso de funcionamiento del blockchain que inicia con el envío de bitcoin, seguido de la cantidad de bitcoins y destinatarios; una vez definido se realiza la transacción y es incluida en un bloque que es distribuido por toda la red, después la red valida la transacción dando un premio en bitcoins al primero que valide el bloque se termina la transacción y se agrega el bloque al blockchain.

    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    p.mb-4 A continuación, se describen unos puntos de funcionamiento del bitcoin:

    .cajon.color-acento-botones.p-4.mb-5
      ul.lista-ul--color.mb-0
        li 
          i.fas.fa-check
          | Los bloques pueden ser creados por cualquier persona desde su computador.
        li 
          i.fas.fa-check
          | Los bloques se crean utilizando un software especial.
        li 
          i.fas.fa-check
          | La capacidad de registro de un bloque está entre 2000 y 2400 transacciones.
        li 
          i.fas.fa-check
          | La recompensa que gana el primero que realice la validación es de 50 bitcoins.
        li 
          i.fas.fa-check
          | Para agregar un bloque nuevo la persona que lo genere lo debe enviar al resto de la red.
        li 
          i.fas.fa-check
          | No se pueden modificar ni borrar los bloques estos son permanentes.

    #t2_1.titulo-segundo.color-acento-contenido
      h2 2.2 Aplicaciones
    
    p.mb-5 Son muchas las aplicaciones que en la actualidad proporciona blockchain, que son utilizadas por empresas o instituciones. A continuación, se nombran unos ejemplos:

    #MapaGroup01.mb-5
      .row.justify-content-center
        .col-md-11
          .row.justify-content-center.align-items-end
            .col-md-2
              img.mb-4.ChangeSRC01(src='@/assets/curso/tema2/img20.svg', alt='botón 1' data-bs-toggle='collapse' data-bs-target='.multi-collapse1' aria-expanded='true' aria-controls='.multi-collapse1')
              img.w-25.mx-auto.mb-0.multi-collapse1.collapse.show(src='@/assets/curso/tema2/ind.svg', alt='indicador 1' data-bs-parent='#MapaGroup01')
            .col-md-2
              img.mb-4.ChangeSRC02(src='@/assets/curso/tema2/img21.svg', alt='botón 2' data-bs-toggle='collapse' data-bs-target='.multi-collapse2' aria-expanded='false' aria-controls='.multi-collapse2' @mouseover="indicadorTarjetaFlip = false")
              img.w-25.mx-auto.mb-0.multi-collapse2.collapse(src='@/assets/curso/tema2/ind.svg', alt='indicador 1' data-bs-parent='#MapaGroup01')
            .col-md-2
              img.mb-4.ChangeSRC03(src='@/assets/curso/tema2/img22.svg', alt='botón 3' data-bs-toggle='collapse' data-bs-target='.multi-collapse3' aria-expanded='false' aria-controls='.multi-collapse2' @mouseover="indicadorTarjetaFlip = false")
              img.w-25.mx-auto.mb-0.multi-collapse3.collapse(src='@/assets/curso/tema2/ind.svg', alt='indicador 1' data-bs-parent='#MapaGroup01')
            .col-md-2
              img.mb-4.ChangeSRC04(src='@/assets/curso/tema2/img23.svg', alt='botón 4' data-bs-toggle='collapse' data-bs-target='.multi-collapse4' aria-expanded='false' aria-controls='.multi-collapse2' @mouseover="indicadorTarjetaFlip = false")
              img.w-25.mx-auto.mb-0.multi-collapse4.collapse(src='@/assets/curso/tema2/ind.svg', alt='indicador 1' data-bs-parent='#MapaGroup01')
            .col-md-2
              img.mb-4.ChangeSRC05(src='@/assets/curso/tema2/img24.svg', alt='botón 5' data-bs-toggle='collapse' data-bs-target='.multi-collapse5' aria-expanded='false' aria-controls='.multi-collapse2' @mouseover="indicadorTarjetaFlip = false")
              img.w-25.mx-auto.mb-0.multi-collapse5.collapse(src='@/assets/curso/tema2/ind.svg', alt='indicador 1' data-bs-parent='#MapaGroup01')
            .col-md-2
              img.mb-4.ChangeSRC06(src='@/assets/curso/tema2/img25.svg', alt='botón 6' data-bs-toggle='collapse' data-bs-target='.multi-collapse6' aria-expanded='false' aria-controls='.multi-collapse2' @mouseover="indicadorTarjetaFlip = false")
              img.w-25.mx-auto.mb-0.multi-collapse6.collapse(src='@/assets/curso/tema2/ind.svg', alt='indicador 1' data-bs-parent='#MapaGroup01')
        
      .bgESP01.bordbtn01.p-5.mb-4.multi-collapse1.collapse.show(data-bs-parent='#MapaGroup01')
        h4 Industria alimentaria
        p.mb-0 Por medio de la tecnología blockchain la industria alimentaria puede realizar un seguimiento a cada uno de los productos, partiendo desde donde nacen hasta su destino final.
      
      .bgESP01.bordbtn01.p-5.mb-4.multi-collapse2.collapse(data-bs-parent='#MapaGroup01')
        h4 Sector energético
        p.mb-0 Por medio del blockchain se puede pensar en una red entre varias casas para vender y comprar energía.
      
      .bgESP01.bordbtn01.p-5.mb-4.multi-collapse3.collapse(data-bs-parent='#MapaGroup01')
        h4 Sector bancario
        p.mb-0 Por medio de las criptodivisas los bancos pueden realizar transacciones a un costo menor con una mayor eficiencia, segura y sin intermediarios.
      
      .bgESP01.bordbtn01.p-5.mb-4.multi-collapse4.collapse(data-bs-parent='#MapaGroup01')
        h4 Agricultura
        p.mb-0 Al igual que la industria alimentaria en la agricultura el blockchain se enfoca en optimizar la calidad de los alimentos con aplicaciones que monitorean en tiempo real el estado de las hortalizas y verduras.
      
      .bgESP01.bordbtn01.p-5.mb-4.multi-collapse5.collapse(data-bs-parent='#MapaGroup01')
        h4 Sector inmobiliario
        p.mb-0 Gracias a los contratos inteligentes se puede formalizar acuerdos con tal solo ingresar las condiciones y almacenarlas en blockchain, una vez se cumplan las condiciones se ejecuta el contrato de forma automática.

      .bgESP01.bordbtn01.p-5.mb-4.multi-collapse6.collapse(data-bs-parent='#MapaGroup01')
        h4 Sistemas de votación
        p.mb-0 La aplicación de blockchain en los sistemas de votación facilita la regulación de estas empresas norteamericanas, ya que han utilizado estas metodologías para garantizar la votación electrónica.

    #t2_3.titulo-segundo.color-secundario
      h2 2.3 Desarrollos
    
    p.mb-5 En la actualidad existen muchos desarrollos que incorporan blockchain. A continuación, se nombran uno de los más novedosos:

    TabsB.color-primario
      .py-4.py-md-5.BGcolorH(titulo="<i>IBM Food Trust</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema2/img26.jpg', alt='IBM Food Trust')
          .col-md-6.bg-white.p-4
            p Es una plataforma de intercambio soportado en blockchain que favorece a los usuarios participantes de una red de alimentos para mayoristas, productores y distribuidores, que permite administrar datos de transacciones, procesamientos y procedencia de los alimentos, entre otros, logrando reducir la pérdida de los alimentos.
      
      .py-4.py-md-5.BGcolorH(titulo="<i>Pylon Network</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema2/img27.jpg', alt='Pylon Network')
          .col-md-6.bg-white.p-4
            p Desarrollado por una empresa española que permite la venta y compra de energía renovable sin intermediarios, este desarrollo lanzó su proyecto de código abierto (Open-source) concretamente para las condiciones del sector energético. 
      
      .py-4.py-md-5.BGcolorH(titulo="<i>Steemit</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema2/img28.jpg', alt='Steemit')
          .col-md-6.bg-white.p-4
            p Consiste en una red social no centralizada que incorpora la tecnología steemit blockchain, su principal función es premiar a todos los usuarios bitcoin que estén activos, esta se consigue realizando publicaciones, comentarios, etc.
      
      .py-4.py-md-5.BGcolorH(titulo="<i> Koibanx</i>")
        .row.justify-content-evenly.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema2/img29.jpg', alt=' Koibanx')
          .col-md-6.bg-white.p-4
            p Es una plataforma basada en blockchain para el sector financiero que permite hacer el proceso de pagos, gestión de costos, plazos, fidelización de programas a bancos, cooperativas, fiduciarias, etc.

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
