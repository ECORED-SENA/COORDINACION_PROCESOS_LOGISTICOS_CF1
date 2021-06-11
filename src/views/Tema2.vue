<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Gestión de la cadena de suministros
    p La cadena de suministro es una red de proveedores, fábricas, almacenes, centros de distribución y ventas al por menor; a través de los cuales se adquieren y se transforman las materias primas, para entregar al cliente productos o servicios.
    .row.align-items-center
      .col-lg-6
        p Con base en Bautista, Martínez y Fernández (2015) se debe entender que la cadena de suministros se ocupa de cuestiones estratégicas, tales como la integración de los procesos de negocio internos y externos, el desarrollo de vínculos estrechos entre los socios del canal, y la gestión de los productos y la información a medida que avanzan a través de fronteras organizativas y empresariales; en otro nivel, puede ser una herramienta táctica y operativa aplicada a la gestión de las actividades operacionales en curso. Estas actividades pueden incluir: el servicio al cliente, el control de los flujos de entrada y salida de materiales e información, la eliminación de las ineficiencias de los canales y los costos, que se extienden desde la adquisición de materias primas hasta la fabricación, distribución, consumo y el retorno final a través del canal por medio de reciclaje o eliminación. 
      .col-lg-4.p-4.mx-auto
        img(src='@/assets/curso/tema2/f1.svg', alt='T2-F1')
    .separador-custom
    #t_2_1.titulo-segundo-cab.mb-4
      h2 2.1. Cadena de valor
    p Este término acuñado por Porter (1991) identifica, entonces, “las principales actividades que crean un valor para los clientes y las actividades de apoyo relacionadas”. La cadena permite también identificar los distintos costos en los que incurre una organización a través de las distintas actividades que conforman su proceso productivo, por lo que constituye un elemento indispensable para determinar la estructura de costos de una compañía. 
    p Según Quintero y Sánchez (2006), desde el punto de vista estratégico “la cadena de valor de una compañía y la forma en la cual desempeña cada actividad refleja la evolución de su propio negocio y de sus operaciones internas”; la estrategia, los enfoques que utiliza en su ejecución y la economía fundamental de las actividades mismas también son relacionadas por los autores fortaleciendo el concepto. 
    p Es indispensable en el proceso formativo que relaciona estos conceptos de manera directa, por eso debe leer el documento “Cadena de valor y cadena logística versus cadena de suministros” de Núñez y López (2015).
    .row.g1.tarjeta.align-items-center.justify-content.between.p-4
      .col-lg-2
        img(src='@/assets/curso/tema1/f4.svg', alt='T1-F4')._93px.mx-auto.my-4
      .col
        p.texto-blanco <b>Base de Datos:</b> biblioteca SENA<br><b>Recursos:</b> e-libro<br><b>Libro: </b><i>La logística en la empresa: un área estratégica para alcanzar ventajas competitivas</i><br>Autor: Núñez y López (2015)<br><b>Página:</b> 61 al 64
        p.texto-blanco <span style="font-size:.8rem">Estimado aprendiz, debe recordar que para ingresar a las bases de datos del Sena se ingresa con el número del documento de identidad sin puntos en el campo de usuario y contraseña.</span>
      .col-lg-2
        a.boton.color-acento-botones.mx-auto.indicador__container(
          href="https://elibro-net.bdigital.sena.edu.co/es/ereader/senavirtual/48968?page=62"
          target="_blank"
          @mouseover="mostrarIndicador = false"
        )
          span.texto-blanco Ir al sitio
          i.fas.fa-file-download.texto-blanco
          .indicador--click(v-if="mostrarIndicador")
    .separador-custom
    #t_2_2.titulo-segundo-cab.mb-4
      h2 2.2. Redes logísticas
    p La cadena logística es la vía imaginaria mediante la cual se realiza el movimiento de mercancías desde su origen hasta el consumidor final, esta movilización se lleva a cabo a través del servicio, la manipulación, transformación, desplazamiento y almacenamiento que sufren los productos desde que son materia prima hasta su elaboración como mercancía final. Estas cadenas se diseñan para que puedan cubrir los diferentes modos de transporte a saber: marítimo, terrestre (férreo y carretera), aéreo, y en su construcción participan diferentes actores.
    .col-lg-8.mx-auto.py-4
      h4.text-center.mb-4 Medios de transporte
      img(src='@/assets/curso/tema2/f3.svg', alt='T2-F3').mb-4
      p.text-center La gestión de estos procesos nos ayuda a direccionar las tres grandes logísticas de la empresa: aprovisionamiento, producción y distribución.
    .col-lg-8.mx-auto.py-4
      h4.text-center.mb-4 Tres grandes logísticas de la empresa
      img(src='@/assets/curso/tema2/f4.svg', alt='T2-F4').mb-4
    .separador-custom
    #t_2_3.titulo-segundo-cab.mb-4
      h2 2.3.	Clasificación de macroprocesos como actores de la cadena
    p Cumplirle al cliente tiene una serie de novedades que no se pueden enumerar en algunos casos, pues “son muchos los puntos críticos que se manejan durante la gestión de la cadena, y para su administración y cumplimiento debemos contar con elementos de apoyo imprescindibles para gestionarla correctamente” (Rojas, Guisao y Cano, 2001). Al gestionar estas logísticas se logra identificar y establecer la movilización entre las diferentes unidades, a diseñar diferentes pasos o caminos para lograr su fin principal: cumplirle al cliente.
    p A continuación, se presentan los actores de la cadena:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta fondo-purpura-clarito")
      .row(titulo="Logística de entrada")
        p Contempla las actividades necesarias para cumplir con el abastecimiento de los productos, garantizando los recursos disponibles para su transformación o venta. Esto implica actividades de: pronóstico de la demanda, aprovisionamiento y compras, gestión de inventarios y gestión de almacenamiento de materias primas.
      div(titulo="Logística interna")
        figure
          p Abarca las actividades involucradas en la transformación de materias primas en productos terminados, y en las actividades de adición de valor a bienes o servicios durante su fabricación, involucra procesos como son la estandarización de métodos y tiempos de procesos (ingeniería básica), la programación de producción, el mantenimiento productivo total, sistemas de planeación y ejecución de producción como los sistemas justo a tiempo (JIT), entre otros.
      div(titulo="Logística de salida")
        figure
          p Define el momento de verdad para la operación logística de una organización, donde se evalúa la eficiencia y efectividad de los procesos integrados en la cadena de suministro. Incluye todas las actividades inherentes a la administración del producto terminado (recibo, almacenamiento y despacho), esta operación se ejecuta a través de herramientas y procedimientos específicos como el picking, el crossdocking, la valoración y elección del modo de transporte adecuado según el tipo de mercancía que se manipula, además de la implementación de tecnologías de información y comunicación (TIC) que permita contar con datos reales en tiempo real y que se materializan en decisiones oportunas y un incremento en la capacidad de respuesta para el cliente y todos los actores involucrados como competencia y proveedores.
    .col-lg-8.mx-auto.py-4
      h4.text-center Divisiones de la logística
      img(src='@/assets/curso/tema2/f5.svg', alt='T2-F5').mb-4.p-4
      p.fondo-casi-blanco <span style="font-size:.8rem">Nota. Tomada de Rojas, Guisao y Cano (2011)</span>
    .col-lg-8.mx-auto
      .cajon.color-acento-botones.fondo-rojizo-clarito.p-4
        p.mb-0 <span style="font-size:1.2rem">Al gestionar estas tres logísticas, se busca convertir la cadena de suministro de la empresa en un proceso eficiente para la satisfacción del cliente, es decir, <b>la efectividad de toda la cadena debe ser más importante que la efectividad de cada una por separado</b>, a través de sus diferentes funciones.</span>
    .separador-custom
    #t_2_4.titulo-segundo-cab.mb-4
      h2 2.4.	Clasificación de los subproceso de la cadena de abastecimiento
    p Es fundamental contar con el apoyo de los demás integrantes de la cadena de abastecimiento, los cuales se relacionan a continuación.
    h3 Logística de aprovisionamiento.
    p Es la gestión de asegurar el abastecimiento de las mercancías necesarias para la producción, con el fin de evitar faltantes a los clientes. El aprovisionamiento contempla todos procesos y actividades destinadas a controlar el suministro que realizan los diferentes proveedores con los que cuenta la empresa en el desarrollo de sus operaciones. 
    p Según Anaya (2015) “aprovisionar es una función destinada a poner a disposición de la empresa todos aquellos productos y servicios del exterior que le son necesarios para su funcionamiento”, mientras que las compras constituyen una función más restringida, que tiene por objeto adquirir aquellos bienes y servicios que la empresa necesita, garantizando el abastecimiento de las cantidades requeridas en términos de tiempo, calidad y precio. En otras palabras, se debe definir con claridad cuánto, cuándo y dónde comprar, qué productos hay que reponer, cuánto producto hay que comprar, cuándo hay que realizar el pedido y dónde hay que situar el producto.
    .col-lg-7.mx-auto.py-4
      h5.text-center Ciclo del abastecimiento
      img(src='@/assets/curso/tema2/f6.svg', alt='T2-F6').mb-4.p-4
      p.fondo-casi-blanco <span style="font-size:.8rem">Nota. Tomada de Universidad Tecnológica de Chile (2017)</span>
    p En consecuencia, en toda actividad de aprovisionamiento se implican unas actividades y acciones a nivel operativo y administrativo a saber:
    AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta fondo-casi-blanco")
      .row(titulo="Decisión")
        p Se debe tener en cuenta la planeación de la compra, la selección, evaluación y calificación de los proveedores y el desarrollo de los mismos.
        ul.lista-ul.mb-5
          li 
            i.fas.fa-angle-right.cab-color
            p La función más importante de la gestión de compras es buscar al proveedor adecuado antes de realizar el requerimiento.
          li 
            i.fas.fa-angle-right.cab-color
            p Se debe realizar un proceso de búsqueda y selección de proveedores de bienes y servicios más adecuados a sus necesidades.
          li 
            i.fas.fa-angle-right.cab-color
            p El propósito es establecer una lista de las empresas que fabrican los productos que se requieren para solicitar la información y luego seleccionar la más adecuada a las necesidades de la empresa.
          li 
            i.fas.fa-angle-right.cab-color
            p No es muy recomendable tener a un solo proveedor y hacerle todo el pedido que necesitamos.
        .col-lg-6
          h5.text-center Aspectos clave para la selección de proveedores
          img(src='@/assets/curso/tema2/f7.svg', alt='T2-F7').p-4
          p <span style="font-size:.8rem">Nota. Tomada de Castellanos (2015)</span>
      div(titulo="Compra")
        p Debe tener en cuenta la evaluación de las ofertas, los documentos de la compra, el envío la recepción de los pedidos, la calidad y el precio.
        ul.lista-ul.mb-5
          li 
            i.fas.fa-angle-right.cab-color
            p <b>Preparación de la negociación:</b> recolección de la información, fijación de los objetivos e identificación de las oportunidades
          li 
            i.fas.fa-angle-right.cab-color
            p <b>Desarrollo de la negociación:</b> la organización material de la negociación y búsqueda de información complementaria.
          li 
            i.fas.fa-angle-right.cab-color
            p <b>Concreción del resultado:</b> firma y cierre del acuerdo.
      div(titulo="Postcompra")
        p Se enmarca el manejo de mercancía, el tipo de carga, el almacenamiento, inventario y la estantería.
        ul.lista-ul.mb-5
          li 
            i.fas.fa-angle-right.cab-color
            p <b>Almacenamiento:</b> dar ubicación específica a cualquier material (materias primas, productos semielaborados terminados), con el fin de ubicarlos oportunamente cuando sea requerido y optimizar los espacios.<br><br>La función principal de la gestión del almacén o bodega consiste en optimizar los flujos físicos, además de definir los criterios para seleccionar los materiales que saldrán a atender una petición.<br><br>En el proceso de almacenamiento se interrelacionan actividades, tales como pedidos, inventarios, etc., los cuales se resumen en el siguiente esquema:
          h5.text-center Actividades de la gestión de almacenamiento
          img(src='@/assets/curso/tema2/f8.svg', alt='T2-F8').p-4
          p <span style="font-size:.8rem">Nota Tomada de Castellanos (2015)</span>
      div(titulo="Servicio")
        p De acuerdo con lo establecido en la negociación, se encuentra el mantenimiento y el servicio al cliente.
    h3 Logística de producción
    p Es la parte donde se gestionan los flujos físicos y administrativos de la transformación de los materiales, el ensamble de las piezas y elementos y el almacenamiento de productos terminados, con el fin de disponerlos para su distribución.
    p.mb-5 La logística de producción conlleva una serie de actividades que se inician cuando el productor o fabricante de un bien, adquiere elementos para que el producto que se elabore llegue a buen término y coordine la entrega hacia el consumidor final, a través de la gestión de stock, compras, almacenaje, y distribución.
    .col-lg-6.mx-auto
      h4.text-center Gestión de coordinación de procesos de producción
      img(src='@/assets/curso/tema2/f9.svg', alt='T2-F9').p-4
      p.fondo-casi-blanco <span style="font-size:.8rem">Nota. Tomada de Castellanos (2015)</span>
    h3 Logística de distribución
    p Una vez los productos han sido elaborados, terminados y almacenados, el siguiente paso consiste en organizar la distribución y transporte de los productos, a fin de cubrir la demanda del mercado y llevarlos hasta su destino final.
    .col-lg-8.mx-auto.mb-5
      .cajon.color-acento-botones.fondo-rojizo-clarito.p-5
        p.mb-0 La gestión de distribución es la más crítica en las empresas, ya que supone el contacto con el cliente. Además, porque aquí se desarrollan todas aquellas actividades que ayudan a completar las órdenes de pedido con el fin de asegurar el servicio al cliente.
    h4.text-center Gestión de coordinación de procesos
    img(src='@/assets/curso/tema2/f10.svg', alt='T2-F10').p-4
    p.text-center.fondo-casi-blanco <span style="font-size:.8rem">Nota. Tomada de Castellanos (2015)</span>
    .separador-custom
    #t_2_5.titulo-segundo-cab.mb-4
      h2 2.5.	Logística inversa o de reversa
    p La definición dada por el Consejo Ejecutivo de Logística Inversa de Estados Unidos, según la cual la retrologística es:
    p <b>El proceso de planificación, implantación y control eficiente del flujo efectivo de costes y almacenaje de materiales, inventarios en curso y productos terminados, así como de la información relacionada, desde el punto de consumo al punto de origen, con el fin de recuperar valor o asegurar su correcta eliminación (Revista de Logística Legis, 2016) </b>
    p Es decir, que la logística inversa es la parte de la logística que mayor atención presta a las mercancías, puesto que gestiona su regreso dentro de la cadena de suministros, buscando que se lleve a cabo de la forma más efectiva y adecuada posible de este fenómeno convirtiéndolo en una oportunidad de mejora en la reducción de costos de las empresas.
    p.mb-5 Las causas que motivan este proceso se encuentran enmarcadas en devoluciones y/o inconformidades que presenta el producto terminado, puesto que acarrea la <b>recogida</b> de los productos en las instalaciones de los clientes; y, una <b>puesta de conformidad</b>, enmarcado en el proceso de garantía por reparación, producto defectuoso, daño por obsolescencia, etc.
    h4.text-center.mb-5 Actividades de logística inversa
    .col-lg-10.mx-auto.tarjeta.fondo-purpura-clarito.py-4.mb-5
      img(src='@/assets/curso/tema2/f11.svg', alt='T2-F11').mb-4
      p <span style="font-size:.8rem">Nota. Tomada de Castellanos (2015)</span>
    .col-lg-8.mx-auto
      .cajon.color-acento-botones.fondo-rojizo-clarito.p-4
        p.mb-0 Para la implementación de una política de devoluciones, se debe tener claridad del proceso y establecer los plazos, estado del producto, documentación necesaria, etc.
    .separador-custom
    #t_2_6.titulo-segundo-cab.mb-4
      h2 2.6. E-logisticis
    p El e-commerce o comercio electrónico abarca los términos de compra, venta, distribución y desarrollo de todas las herramientas, así como el aprovisionamiento de información al consumidor acerca de un producto o servicio a través de internet. 
    p Dentro de este servicio, se encuentra la logística del comercio electrónico o e-logistics, que ha revolucionado el proceso de consumo, puesto que el consumidor está a un clic de distancia de acceder a diversidad de productos y compañías. Este escenario tiene su foco puesto en la logística, con lo cual este aspecto se vuelve un tema central. El tiempo y forma en que cada producto llegará a su comprador, construirá la experiencia de compra de ese consumidor y obliga a las empresas a revisar la cadena de abastecimiento y a replantear su estructura logística para satisfacer las necesidades.
    .col-lg-10.mx-auto.mb-4
      .cajon.color-acento-botones.fondo-rojizo-clarito.p-4
        p.mb-0 Las empresas DotCom (.com) o empresas que realiza la mayor parte de sus actividades online, implementan los procesos de logística, almacenamiento, manejo de inventarios, control de stocks, empaquetado, y, en algunos casos, cobro contra entrega, reembolso de los productos, y distribución, necesarios para llevar los productos que ofrecen hasta las manos de los consumidores y así adaptar su actual estructura a las exigencias del mercado.
    p Como la logística del e-commerce no sigue los patrones de la logística tradicional, la solución está en los canales de distribución online, que cuenta con las siguientes ventajas:
    .col-lg-10.mx-auto.mb-4
      h4.text-center Comparativos de beneficios e-logistics entre empresa y clientes
      .tabla-a.color-acento-contenido.mb-5.tablaAzul
        table._4060
          caption Nota. Tomada de Riveros (2015)
          thead
            tr
              th Beneficios para la empresa
              th Beneficios para los clientes
          tbody
            tr
              td Aumento sustancial de la demanda.
              td Tiene accesibilidad a la tienda virtual las 24 horas del día.
            tr
              td Acceso a nuevos mercados.
              td Frente a la oferta tradicional, la oferta online puede brindar precios menores a los clientes.
            tr
              td Globalización de la empresa.
              td Eliminación de los costos para adquirir el producto.
            tr
              td Costo de inversión reducido.
              td Mayor variedad de elección.
            tr
              td Ventas de productos con un inventario reducido o sin inventario, atendiendo la demanda de forma personalizada.
              td Agilidad en la respuesta de reclamos.
            tr
              td Menor inversión publicitaria.
              td La oferta de productos a través de internet genera una oferta y demanda global, lo que expande el público objetivo y demanda.
            tr
              td Canal directo que agiliza el proceso logístico.
              td Mayor relación y comunicación entre la empresa y el consumidor, lo que mejora el servicio al cliente y la imagen de la empresa.
    .separador-custom
    #t_2_7.titulo-segundo-cab.mb-4
      h2 2.7.	CPFR o la planificación, pronosticación y reabastecimiento colaborativos
    p Según Granillo, Hernández y Santana (2013):
    p <b>… el CPFR, acrónimo de Planificación Colaborativa, Pronóstico y Reabastecimiento, es un proceso de colaboración por el que los socios comerciales de la cadena de suministro pueden planificar conjuntamente las actividades clave de la cadena de suministro”, se debe tener en cuenta desde la producción y el suministro de materias primas a la producción hasta la entrega de productos finales a los clientes finales. La colaboración abarca la planificación empresarial, la previsión de ventas, y todas las operaciones necesarias para reponer las materias primas y productos terminados.</b>
    p El objetivo de CPFR es mejorar la integración de la cadena de suministro convirtiéndola de un aislado, ineficaz e ineficiente sistema “push” o de forma coordinada, a un sistema “pull” basado en la demanda del cliente final.
    p La CPFR es una práctica de negocios que establece una planeación, reabastecimiento y pronósticos compartidos a través de toda la cadena de suministro fundamentado en una visibilidad total de la información de entrada en toda la cadena. Crea necesidad de sistemas integrados de comunicación con el fin de identificar patrones de conducta del cliente que contribuya al mejoramiento del pronóstico de ventas, creación de programas de gestión de inventarios y estándares de empaque; esta dinámica proporciona a la empresa una plataforma clara para llevar a cabo el reabastecimiento, de una manera planeada y en consenso.
    h5.text-center Proceso CPFR
    .col-lg-10.mx-auto.py-4.mb-5
      img(src='@/assets/curso/tema2/f12.svg', alt='T2-F12').mb-4
      .col-lg-3.mx-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/CF1_4_GRAFICO_INTERACTIVO.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Proceso CPFR 
    p Las mejores prácticas en las cadenas de abastecimiento garantizan mejoras en todos los procesos de la empresa, por eso, se hace obligatorio conocer cómo trabajan los operadores logísticos que se convierten en articulaciones de las empresas y para eso es un requisito que haga la siguiente lectura:
    .row.g1.tarjeta.align-items-center.justify-content.between.p-4
      .col-lg-2
        img(src='@/assets/curso/tema1/f4.svg', alt='T1-F4')._93px.mx-auto.my-4
      .col
        p.texto-blanco <b>Base de Datos:</b> biblioteca SENA<br><b>Recursos:</b> e-book 7-24<br><b>Libro: </b><i>Gestión logística integral. Las mejores prácticas en la cadena de abastecimiento</i><br>Autor: (Mora, L. A., 2010)<br><b>Página:</b> 249 al 254 del libro, el tema es “4.2.3. Operadores logísticos de mercancía”
        p.texto-blanco <span style="font-size:.8rem">Estimado aprendiz, debe recordar que para ingresar a las bases de datos del Sena se ingresa con el número del documento de identidad sin puntos en el campo de usuario y contraseña.</span>
      .col-lg-2
        a.boton.color-acento-botones.mx-auto.indicador__container(
          href="https://elibro-net.bdigital.sena.edu.co/es/ereader/senavirtual/96908?page=275"
          target="_blank"
          @mouseover="mostrarIndicador = false"
        )
          span.texto-blanco Ir al sitio
          i.fas.fa-file-download.texto-blanco
          .indicador--click(v-if="mostrarIndicador")




</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    mostrarIndicador: true,
  }),
}
</script>

<style lang="sass" scoped></style>
