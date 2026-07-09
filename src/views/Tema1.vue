<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Escalado manual de prendas
    
    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Introducción y conceptualización - escalado

    .row.justify-content-center.mb-5
      .col-lg-12.col-md-12.col-12
        .caja2.p-4
          .row.justify-content-center.align-items-center
            .col-lg-8.col-md-12.col-12.mb-3.mb-lg-0
              h4.mb-4.negro ¿Qué es el escalado?
              p.mb-0 Es el método o técnica implementada para ampliar o reducir proporcionalmente un patrón base, molde o trazo de una talla a otra. Las proporciones se identifican de acuerdo con el cuadro de tallas o medidas estandarizadas, para llevar a cabo un escalado se implementan planos cartesianos que permiten identificar puntos de referencia, en las medidas de largos, anchos y contornos con sus proporciones, que se diferencian entre una talla y otra.
            .col-lg-3.col-md-8.col-8
              img(src='@/assets/curso/tema1/img1.svg', alt='')
              

    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Plano cartesiano

    p.mb-4 Está formado por dos rectas perpendiculares, una horizontal y otra vertical, que se entrecruzan en un punto.
    
    .row.justify-content-center.mb-4
      .col-lg-12.col-md-12.col-12
        .caja3.p-4
          .row.justify-content-center.align-items-center
            .col-lg-3.col-md-8.col-8.mb-3.mb-lg-0
              img(src='@/assets/curso/tema1/img2.svg', alt='')
            .col-lg-7.col-md-12.col-12
              ul.lista-ul--color.color-primario
                li.mb-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 #[b La recta horizontal,] es llamada eje de las abscisas o de las equis #[b (X)].
                li.mb-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 #[b La recta vertical,] eje de las ordenadas o de las yes #[b (Y)].
                li.mb-0.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 #[b El punto donde se cortan] recibe el nombre de origen #[b (punto cero o punto muerto)].
    
    p.mb-4 El plano cartesiano tiene como finalidad describir la posición de puntos, los cuales se representan por sus coordenadas o pares ordenados. Para la implementación del plano cartesiano, trabajaremos con el sistema de medidas de mayor dominio.

    .row.justify-content-center.mb-4(data-aos="fade")
      .col-lg-8.col-md-12.col-12
        .bg1.rad.p-4
          p.mb-0.text-center Sistema de medida universal: #[b metro - centímetro - milímetro]
    
    .bg5.p-4.mb-4(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-lg-3.col-md-8.col-8.d-none.d-lg-block
          img(src='@/assets/curso/tema1/img3.svg', alt='')
        .col-lg-7.col-md-12.col-12
          p.mb-4.negro Ejemplo:
          p Considerando que el ancho es representado por la línea X. Y el largo por la línea Y. 
          p.mb-4 Si tomamos como punto de partida el punto de origen al hablar de reducir o aumentar, podríamos acudir a los espacios negativos o positivos del plano cartesiano, según corresponda.
          .row.justify-content-center
            .col-lg-6.col-md-6.col-12
              .bg6.rad.p-4.mb-3
                p.mb-3.negro.text-center Aumenta
                  .cajablanca.radi.mb-3
                    p.mb-0.text-center Ancho: 3 - Largo: 1
                  .cajablanca.radi
                    p.mb-0.text-center Ancho: 1 - Largo: 3
            .col-lg-6.col-md-6.col-12
              .bg6.rad.p-4.mb-3
                p.mb-3.negro.text-center Reduce
                  .cajablanca.radi.mb-3
                    p.mb-0.text-center Ancho: -3 - Largo: -1
                  .cajablanca.radi
                    p.mb-0.text-center Ancho: -1 - Largo: -3
    
    p.mb-4 En las siguientes gráficas se presenta la ubicación de los puntos en el plano cartesiano:
    

    .mb-5(data-aos="fade")
      .titulo-sexto.color-acento-contenido.mb-3
        h5 Figura 1. 
        span.mb-0 Ubicación de los puntos en el plano cartesiano  
      figure
        img(src='@/assets/curso/tema1/fig1.svg', alt='Tres planos cartesianos que muestran el aumento y reducción de ancho y largo usando valores positivos y negativos para el escalado de patrones.')    

    p.mb-4 Para entender cómo funciona el escalado desde el plano cartesiano, se toma como referencia un cuadrado, el cual es el molde base o talla base a trabajar; su ubicación en el plano se presenta en la siguiente figura:	
    
    .row.justify-content-center(data-aos="fade")
      .col-lg-4.col-md-12.col-12.mb-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 2. 
          span.mb-0 Punto de origen
        figure
          img(src='@/assets/curso/tema1/fig2.svg', alt='Plano cartesiano con ejes X y Y que destaca el punto de origen en el centro, usado como referencia para ubicar y realizar el escalado de patrones.')
    
    p.mb-4 Para mayor comprensión de este cuadrado, se deben dibujar dos cuadrados más; en total serían tres cuadrados, donde el primero es el punto intermedio entre los otros dos, así como se presenta en la siguiente figura:

    .row.justify-content-center(data-aos="fade")
      .col-lg-4.col-md-12.col-12.mb-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 3. 
          span.mb-0 Tres cuadrados
        figure
          img(src='@/assets/curso/tema1/fig3.svg', alt='Plano cartesiano con tres cuadrados concéntricos (pequeño, mediano y grande), centrados justo en el origen de los ejes X y Y para el tallaje.')
    
    .row.justify-content-center.mb-4(data-aos="fade")
      .col-lg-8.col-md-12.col-12
        .caja22.rad.p-2
          .row.justify-content-center
            .col-lg-5.col-md-12.col-12
              ul.lista-ul--color.color-secundario
                li.mb-0.my-3.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 La diferencia de ancho es 2 cm
            .col-lg-5.col-md-12.col-12
              ul.lista-ul--color.color-secundario
                li.mb-0.my-3.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 La diferencia de alto es 2 cm
    
    .row.align-items-center.justify-content-center.mb-5(data-aos="fade")
      .col-lg-10.col-md-12.col-12
        .row.justify-content-center.align-items-center
          .col-2
            .avatar
              img.d-none.d-lg-block(src="@/assets/curso/tema1/img7.svg")
          .col-lg-10.col-md-12.col-12.bg7.p-3
            .row
              .col-1
              .col-10
                p.my-2 Se debe sacar un cuadrado más pequeño y un cuadrado más grande. Recuerde que todos los lados del cuadrado deben quedar iguales.
    
    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Análisis sobre plano cartesiano

    p.mb-0 #[b Ubicación en plano cartesiano:] punto de origen.
    p.mb-4 #[b Distribución desde punto de origen:] 1 cm a cada lado.
    
    .row.justify-content-center.mb-4
      .col-lg-8.col-md-12.col-12
        .caja22.rad.p-2
          .row.justify-content-center
            .col-lg-5.col-md-12.col-12
              ul.lista-ul--color
                li.mb-0.my-3.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 Aumento por largo eje Y: 2 cm
            .col-lg-5.col-md-12.col-12
              ul.lista-ul--color
                li.mb-0.my-3.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 Aumento por ancho eje X: 2 cm
    
    p.mb-4 Puntos para tener en cuenta: en este caso, por el punto de origen y el incremento de la figura, no se contemplan puntos como negativos o positivos, únicamente los lados que deben aumentar.
    
    .fondo21.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-1.img-a.img-t(src="@/assets/curso/tema1/img8.svg", alt="")        
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.mb-1 Análisis sobre plano cartesiano
              p.mb-0 Consulte el documento Analisis_sobre_plano_cartesiano.pdf ubicado en la carpeta de anexos.
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexos/Analisis_sobre_plano_cartesiano.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Conclusiones
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade")
      .col-lg-12.col-md-12.col-12
        .row.justify-content-center.mb-0
          .col-lg-8.col-md-12.col-12
            .cajon.color-primario.p-4.mb-4
              p.mb-0 El manejo del punto de origen - punto cero - punto muerto, es el primer acercamiento a la comprensión de trasladar, modificar, mover puntos de referencia o construcción.
            p.mb-4 El concepto de positivo o negativo sobre el plano depende del punto de origen; aplicar en escalado se refiere a cada vez que se trabaja una medida sobre el plano cartesiano:
            .row.justify-content-center.mb-0
              .col-lg-9.col-md-12.col-12
                .caja22.rad.p-2
                  .row.justify-content-center
                    .col-lg-5.col-md-12.col-12
                      ul.lista-ul--color.color-primario.mb-0
                        li.mb-0.my-2.d-flex
                          i.fas.fa-chevron-right
                          p.mb-0 #[b Negativa:] reducción
                    .col-lg-5.col-md-12.col-12
                      ul.lista-ul--color.color-primario.mb-0
                        li.mb-0.my-2.d-flex
                          i.fas.fa-chevron-right
                          p.mb-0 #[b Positiva:] aumento          
          .col-lg-4.col-md-8.col-8
            img.d-none.d-lg-block(src='@/assets/curso/tema1/img9.png', alt='')


    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Proporciones
    
    p En escalado son medidas de los aumentos o disminuciones secuenciales para obtener tallas mayores o menores, moldes o bases. 
    p.mb-4 Se debe identificar la diferencia en unidades de medida usada, es decir, centímetros, entre talla y talla, en cada medida del cuerpo (largos, anchos, contornos). La medida identificada como diferencia es sobre la que se hace el análisis de construcción, dependiendo del tipo de plano, molde o trazo. 

    .bg5.p-4.mb-5(data-aos="fade-right")
      .row.justify-content-center.align-items-center
        .col-lg-3.col-md-8.col-8
          img.d-none.d-lg-block(src='@/assets/curso/tema1/img3.svg', alt='')
        .col-lg-7.col-md-12.col-12
          p.mb-4.negro Ejemplo:
          p.mb-4 Para identificar las proporciones a usar, se debe trabajar con las siguientes medidas. En este caso, el punto base o el punto de partida es el mediano; la diferencia entre medida y medida es:
            strong 2 cm para aumentar y -2 cm para reducir. 
          p.mb-4 Para aplicar el escalado se trabaja con las proporciones, no con la diferencia. 
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Tabla 1. 
            span.mb-0 Proporciones
          .tabla-a.tabl.color-acento-contenido
            table
              thead
                tr
                  th Medidas
                  th Pequeño
                  th Mediano
                  th Grande
              tbody
                tr.cy
                  td.hor Largo
                  td.hor 2
                  td.hor.text-center
                    .row.justify-content-center
                      .col-lg-3.col-md-3.col-3
                        img.wi.my-3(src='@/assets/curso/tema1/fi.png', alt='')
                      .col-lg-5.col-md-5.col-6
                        .bgrr.p-2
                          p.mb-0 4
                      .col-lg-3.col-md-3.col-3
                        img.wi.my-3(src='@/assets/curso/tema1/fd.png', alt='')
                  td.hor 6
                tr.cy
                  td Ancho
                  td 2
                  td.text-center 
                    .row.justify-content-center
                      .col-lg-3.col-md-3.col-3
                        img.wi.my-3(src='@/assets/curso/tema1/fi.png', alt='')
                      .col-lg-5.col-md-5.col-6
                        .bgrr.p-2
                          p.mb-0 4
                      .col-lg-3.col-md-3.col-3
                        img.wi.my-3(src='@/assets/curso/tema1/fd.png', alt='')          
                    .row.justify-content-between
                      .col-5
                        p.mb-0 -2 cm      
                      .col-5        
                        p.mb-0 2 cm
                  td Ancho 


    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Cómo identificar las proporciones 
            
    p.mb-4 Si la diferencia entre una medida y otra es de 2 cm. La proporción equivale a la manera en la que se aplica en el plano, es decir: 

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade")
      .col-lg-9.col-md-12.col-12
        .row.align-items-center
          .col-lg-4.mnl-1.d-none.d-lg-block
            img(src='@/assets/curso/tema1/img11.png', alt='')
          .col-lg-9.col-md-12.col-12
            .caja5p.p-4.ps-lg-5
              p.mb-0.ps-lg-5
              ul.lista-ul--color.color-primario.my-3
                li.mb-3.mx-4.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 Si sobre el plano se aplica la medida completa, dicha medida equivale a una proporción; entonces, una proporción será 2 cm. 
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 Si sobre el plano se aplica la mitad de la medida, esto equivale a 1/2 proporción; 1/2 proporción será 1 cm.
        
    TabsC.color-primario.mb-4(data-aos="fade")
      .py-3.py-md-4.px-3(titulo="Plano completo")
        .row.justify-content-center
          .col-lg-5.col-md-9.my-3
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Figura 4. 
              span.mb-0 Plano completo
            figure
              img(src='@/assets/curso/tema1/img41.svg', alt='Cuadrado dividido por líneas punteadas cruzadas en el centro, utilizado como referencia de ubicación y coordenadas para el escalado de patrones.')
          .col-lg-7.col-md-12.my-3
            p.mb-4 En este caso se aplica una proporción porque en el plano se está trabajando la medida total. 
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 2. 
              span.mb-0 Proporción completa
            .tabla-a.tabla-peque
              table.text-center
                thead
                  tr.bl
                    th.h4 #[b Medidas]
                    th.h4 #[b Diferencia por talla ]
                    th.h4 #[b Proporción]
                    th.h4 #[b Medida aplicar en escalado]
                tbody.bg-white
                  tr.p-1
                    td Largo
                    td 2 cm
                    td Completa
                    td 2 cm
                  tr.p-1
                    td.ba Ancho
                    td.ba 2 cm
                    td.ba Completa
                    td.ba 2 cm            
      .py-3.py-md-4.px-3(titulo="Plano por la mitad")
        .row.justify-content-center
          .col-lg-5.col-md-9.my-3
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Figura 5. 
              span.mb-0 Plano por la mitad
            img(src='@/assets/curso/tema1/img42.svg', alt='Rectángulo vertical alineado con ejes de coordenadas discontinuos, ubicado sobre un fondo que resalta el contraste de las formas.')
          .col-lg-7.col-md-12.my-3
            p.mb-4 En este caso en el ancho se debe aplicar 1/2 proporción, porque en el plano se está trabajando la mitad de la medida total. 
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 3. 
              span.mb-0 Proporción media
            .tabla-a.tabla-peque
              table.text-center
                thead
                  tr.bl
                    th.h4 #[b Medidas]
                    th.h4 #[b Diferencia por talla]
                    th.h4 #[b Proporción]
                    th.h4 #[b Medida aplicar en escalado]
                tbody
                  tr.p-1
                    td Largo
                    td 2 cm
                    td Completa
                    td 1 cm

                  tr.p-1
                    td.ba Ancho
                    td.ba 2 cm
                    td.ba 1/1
                    td.ba 1 cm
          
    .row.justify-content-center.mb-4(data-aos="fade-right")
      .col-lg-12.col-md-12.col-12
        .caja2.p-4
          .row.justify-content-center.align-items-center
            .col-lg-6.col-md-12.col-12
              h4 Ejercicio de análisis 
              p.mb-4 Realice el escalado de la siguiente figura teniendo en cuenta: 
              ul.lista-ul--color.color-primario.fa-ul
                li.mb-1.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 El cuadro de tallas asignado.
                li.mb-1.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 La talla base y las medidas.
                li.mb-1.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 Las diferencias entre talla y talla.
                li.mb-1.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 La asignación de proporciones, según tipo de plano a trabajar.
                li.mb-1.d-flex
                  i.fas.fa-chevron-right
                  p.mb-0 El punto de origen sobre el plano cartesiano y la ubicación de la figura.
            .col-lg-5.col-md-8.col-8
              img(src='@/assets/curso/tema1/img12.svg', alt='')
    
    .row.justify-content-center.mb-4(data-aos="fade-right")
      .col-lg-4.col-md-12.col-12.mb-4
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 6. 
          span.mb-0 Cuadro de tallas asignado
        figure
          img(src='@/assets/curso/tema1/im12.svg', alt='Patrón base talla M con indicaciones de medidas de ancho (A.a, A.b, A.c) y largo (Largo 1, Largo 2) para el proceso de escalado técnico.')
            
    .row.justify-content-center.mb-4
      .col-lg-5.col-md-12.mb-4
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 4. 
          span.mb-0 Escalado de medidas por talla (XS a XL) 
        .tabla-a.tabla-peque
          table.text-center
            thead.ru
              tr
                th.h4 #[b Medidas]
                th.h4 #[b XS]
                th.h4 #[b S]
                th.h4 #[b M]
                th.h4 #[b L]
                th.h4 #[b XL]
            tbody.pp
              tr
                td Largo T.
                td 5.5
                td 6
                td 6.5
                td 7
                td 7.5
              tr
                td.ba Largo 1
                td.ba 2
                td.ba 2.25
                td.ba 2.5
                td.ba 2.75
                td.ba 3
              tr
                td Largo 2
                td 3.5
                td 3.75
                td 4
                td 4.25
                td 4.5
              tr
                td.ba A.a
                td.ba 3
                td.ba 5
                td.ba 7
                td.ba 9
                td.ba 11
              tr
                td B.b
                td 6
                td 8
                td 10
                td 12
                td 14
              tr
                td.ba A.c
                td.ba 5
                td.ba 7
                td.ba 9
                td.ba 11
                td.ba 13
      .col-lg-7.col-md-12.mb-4
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 5. 
          span.mb-0 Proporciones y medidas aplicadas en el escalado de patrones 
        .tabla-a.tabla-peque
          table.text-center
            thead
              tr.bl
                th.h4 #[b Medidas]
                th.h4 #[b Diferencia por talla]
                th.h4 #[b Proporción por medida]
                th.h4 #[b Medida aplicar en escalado]
            tbody.pp
              tr
                td Largo T.
                td 0.5 cm
                td 1 proporción
                td 0.25 cm
              tr
                td.ba Largo 1
                td.ba 0.25 cm
                td.ba 1 proporción
                td.ba 0.25 cm
              tr
                td Largo 2
                td 0.25 cm
                td 1 proporción
                td 0.25 cm
              tr
                td.ba A.a
                td.ba 2 cm
                td.ba 1/2 proporción
                td.ba 1 cm
              tr
                td B.b
                td 2 cm
                td 1/2 proporción
                td 1 cm
              tr
                td.ba A.c
                td.ba 2 cm
                td.ba 1/2 proporción
                td.ba 1 cm
             
    .caja5.p-4.mb-4(data-aos="fade-right")
      .row.justify-content-center.align-items-center.mb-0
        .col-lg-4.col-md-8.col-12.mb-3.mb-lg-0
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 7. 
            span.mb-0 Punto de origen 1
          figure
            img(src='@/assets/curso/tema1/img13.svg', alt='Patrón con punto de origen que muestra la aplicación de incrementos en ancho y largo para el proceso de escalado de tallas.')
        .col-lg-6.col-md-12.col-12
          p En este caso, el punto de origen está en un punto que divide el largo total. 
          p Se debe tomar la proporción y aplicar mitad hacia arriba y mitad hacia abajo para el largo total, con el fin de no perder la proporción de la figura.

    .caja5.p-4.mb-5(data-aos="fade-right")
      .row.justify-content-center.align-items-center.mb-0
        .col-lg-4.col-md-8.col-12.mb-3.mb-lg-0
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 8. 
            span.mb-0 Punto de origen 2
          figure
            img(src='@/assets/curso/tema1/img14.svg', alt='Escalado con el incremento de ancho y largo desde el punto de origen para transformar un patrón de talla M a talla grande.')
        .col-lg-6.col-md-12.col-12
          p En este caso, el punto de origen está en un punto base de construcción. 
          p Se debe tomar la proporción y aplicar toda hacia arriba para el largo total y no perder la proporción de la figura. 
          p Sin embargo, debe tener en cuenta que el vértice A.b modifica su altura para no perder la proporción de la figura.


    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Tipos de escalado

    TabsC.color-primario.mb-5(data-aos="fade")
      .py-3.py-md-4.px-3(titulo="Escalado monobásico")
        .row.justify-content-center
          .col-lg-4.col-md-6.col-8.my-3
            img(src='@/assets/curso/tema1/img43.png', alt='')
          .col-lg-7.col-md-12.my-3
            p.mb-0 Partiendo de tallas base, se obtienen las demás por aumento o reducción. 
            p.mb-0 En este caso, los incrementos entre tallas se mantienen constantes en toda la serie. 
            p.mb-4 Crecimiento de estatura: se produce aumentando ancho y largos, llamándose también escalado de crecimiento real. 
            ul.lista-ul--color.color-primario
              li.mb-4.d-flex.mx-0
                i.fas.fa-chevron-right
                p #[b Simple o relativo/diferencial:] se aplica cuando los incrementos de tallas varían dentro de la serie. Ejemplo, no se produce incremento de estatura, solo anchos. 
              li.mb-0.d-flex.mx-0
                i.fas.fa-chevron-right
                p #[b Compuesto o absoluto proporcional:] los incrementos entre tallas se mantienen constantes en toda la serie; por ejemplo, se produce incremento de estatura, se aumentan anchos y largos, llamado también escalado de crecimiento real.
      .py-3.py-md-4.px-3(titulo="Escalado bibásico")
        .row.justify-content-center
          .col-lg-4.col-md-6.col-8.my-3
            img(src='@/assets/curso/tema1/img44.png', alt='')
          .col-lg-7.col-md-12.my-3
            p Tomamos dos tallas básicas para obtener una intermedia; lo ideal es disponer de dos patrones, talla prototipo y talla límite. 
            p Superponer patrón prototipo en el patrón límite con base en líneas comunes, una horizontal y una vertical. 
            p.mb-0 Las tallas intermedias se trazan uniendo los vértices de ambos patrones por medio de puntos y dividiéndolos por el número de patrones a hallar. 
      .py-3.py-md-4.px-3(titulo="Escalado tribásico")
        .row.justify-content-center
          .col-lg-4.col-md-6.col-8.my-3
            img(src='@/assets/curso/tema1/img45.png', alt='')
          .col-lg-7.col-md-12.my-3
            p.mb-0 Se toman tres tallas para obtener una intermedia, por ejemplo, 10 - 14 - 18 para obtener la intermedia 12 - 16. 


    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Análisis de cuadros de tallas
      
    p.mb-4 Para el análisis de cuadros de tallas se determina:
    
    .row.justify-content-center.mb-5(data-aos="fade-down") 
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido.mh-375
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h4 Límites
              p La más pequeña y la más grande. 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img46.svg')})`}")
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido.mh-375(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h4 Frecuencia
              p Aumento de medida talla a talla (secuencial y no secuencial - constantes y variables).
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img47.svg')})`}")
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido.mh-375
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h4 Incremento
              p Magnitud de crecimiento de la medida talla por talla. 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img48.svg')})`}")

    .row.justify-content-center.mb-4
      .col-lg-8.col-md-12.col-12
        .caja2.rad.p-4
          p.mb-0 El análisis de los anteriores dará como resultado: 
            strong valores - proporciones - rupturas de talla.
    
    p.mb-5 En este caso se hace el análisis desde la talla base hasta la ruptura, identificando las medidas a aplicar en el escalado del patrón base. 
    
    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/tema1/subt.svg', alt='')
        h3.mb-0.ms-2 Procedimiento de escalado

    p.mb-4 A continuación, se presentan ejemplos de escalado en diferentes prendas; cabe resaltar que para iniciar el proceso de escalado es necesario tener en cuenta una serie de operaciones previas, como lo son: 

    .row.justify-content-center.align-items-center.mb-0(data-aos="fade-right")
      .col-lg-9.col-md-12.col-12
        .row.align-items-center
          .col-lg-4.mnl-2.d-none.d-lg-block
            img(src='@/assets/curso/tema1/img22.png', alt='')
          .col-lg-9.col-md-12.col-12
            .caja5pw.p-3.ps-lg-5
              ul.lista-ul--color.color-primario.mb-0
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 Definir la metodología y lógica de construcción de la prenda.
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 Conocer la pieza que se va a escalar.
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 Definir si es un básico o es un desarrollo de diseño.
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 Definir si se va a incluir margen de costura.
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 Definir el tipo de escalado que se va a trabajar.
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right
                  span.mb-0 Analizar el cuadro de tallas.
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right.mb-0
                  span.mb-0 Analizar la diferencia por talla e identificar la medida a aplicar en el escalado.
                li.mb-0.mx-4.d-flex
                  i.fas.fa-chevron-right.mb-0
                  span.mb-0 Analizar los puntos de escalado que se van a referenciar o modificar.
  

    Separador 
    #t_1_1.titulo-segundo.mb-4
      h2 1.1 Escalado de falda

    p.mb-4 Para iniciar el proceso de escalado, se debe tener en cuenta el procedimiento anteriormente mencionado y las especificaciones para trabajar en esta prenda, haciendo claridad de que es un molde que no tiene margen de costura y tampoco es una prenda. Importante verificar, por ejemplo, el escaldo en las pinzas, y que las medidas sean iguales en lateral delantero y posterior, entre otras. 

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-left")
      .col-lg-12.col-12.col-md-12
        figure.py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/-YYkMqxaJfg?si=tntlvF1mIUOoNlqB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Escalado de falda femenino
    
    .fondo21.p-4(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-1.img-a.img-t(src="@/assets/curso/tema1/img8.svg", alt="")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.mb-1 Plantilla escalado de falda 
              p.mb-0 Para complementar los conocimientos sobre el escalado de falda, consulte el documento Plantilla_escalado_de_falda.pdf, ubicado en la carpeta de anexos.
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexos/Plantilla_escalado_de_falda.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
  
    Separador 
    #t_1_2.titulo-segundo.mb-5
      h2 1.2 Escalado de base con pinzas superior
    
    .row.align-items-center.justify-content-center.mb-4(data-aos="fade-left")
      .col-lg-10.col-md-12.col-12
        .row.justify-content-center.align-items-center
          .col-2
            .avatar
              img.d-none.d-lg-block(src="@/assets/curso/tema1/img49.svg")
          .col-lg-10.col-md-12.col-12.caj.p-2
            .row
              .col-1
              .col-10
                p.my-3 El proceso de escalado debe ser seguido conforme a lo planteado anteriormente, haciendo claridad de que es un molde que no tiene margen de costura y tampoco es una prenda. Es importante analizar el escalado de pinzas, además de verificaciones en medidas laterales, cintura, entre otras.	 

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-left")
      .col-lg-12.col-12
        figure.py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/5w_UnxRLOBQ?si=e2QvetrlparUOtWa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Escalado de base con pinzas - superior
    
    .fondo21.p-4(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-1.img-a.img-t(src="@/assets/curso/tema1/img8.svg", alt="")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.mb-1  Escalado de base con pinzas superior
              p.mb-0 Para aprender más sobre el escalado de base con pinzas - superior, consulte el documento Escalado_de_base_con_pinzas_superior.pdf, ubicado en la carpeta de anexos.
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexos/Escalado_de_base_con_pinzas_superior.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download


    Separador 
    #t_1_3.titulo-segundo.mb-5
      h2 1.3 Escalado básico de pantalón

    .row.justify-content-center.mb-4(data-aos="fade")
      .col-lg-1.col-md-12.col-12
        img.d-none.d-lg-block(src='@/assets/curso/tema1/img25.svg', alt='')
      .col-lg-11.col-md-12.col-12
        p.mb-0 En el caso de trabajar un básico de pantalón, se sigue el procedimiento de escalado; quiere decir un molde que no tiene margen de costura, ni es una prenda. Para este caso es importante verificar todas las medidas y su correspondencia, tanto en posterior como en delantero, por ejemplo, que las medidas de los laterales sean iguales, además en la entrepierna. Otro lado de especial atención es el tiro, para que no afecte la horma de la prenda. 

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-left")
      .col-lg-12.col-12
        figure.py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/sgGEl_vjJTc?si=EcXiXWbOoh3GVwDr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Escalado básico de pantalón
    
    .fondo21.p-4(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-1.img-a.img-t(src="@/assets/curso/tema1/img8.svg", alt="")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.mb-1 Escalado básico de pantalón
              p.mb-0 Para ampliar la información sobre el escalado básico de pantalón, consulte el documento Escalado_basico_de_pantalon.pdf, ubicado en la carpeta de anexos. 
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexos/Escalado_basico_de_pantalon.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download


    Separador 
    #t_1_4.titulo-segundo.mb-4
      h2 1.4 Escalado aplicado a cortes y piezas complementarias (manga y cuello)

    p.mb-4 Se ha mencionado en los anteriores escalados trabajados que se debe seguir el procedimiento para estos casos; se hace referencia a prendas que ya han sido modificadas, que pueden tener margen de costura y validaciones como producto final. 

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade")
      .col-lg-8.col-md-12.col-12
        .cajon.color-primario.p-4
          p.mb-0 Es importante analizar la simetría requerida en las piezas, en el caso de cortes, la distribución de las proporciones a escalar. 
      
    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-left")
      .col-lg-12.col-12
        figure.py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/_GM6Ni5lDW8?si=muadyKU5HtcWPxaU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Escalado aplicado a cortes y piezas complementarias (manga y cuello)
    
    .fondo21.p-4(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-1.img-a.img-t(src="@/assets/curso/tema1/img8.svg", alt="")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.mb-1 Escalado cortes, manga, cuello
              p.mb-0 Para complementar los conocimientos sobre el escalado: cortes, manga, cuello, consulte el documento Escalado_de_base_con_pinzas_superior.pdf, ubicado en la carpeta de anexos.
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexos/Escalado_de_base_con_pinzas_superior.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
    

    Separador 
    #t_1_5.titulo-segundo.mb-4
      h2 1.5 Análisis de escalado bibásico en la base superior masculina
    
    .row.justify-content-center.align-items-center.mb-0(data-aos="fade")
      .col-lg-12.col-md-12.col-12
        .row.justify-content-center.mb-4
          .col-lg-8.col-md-12.col-12
            p.mb-4 En la metodología del manual de patronaje SENA se identifican análisis y modificaciones en cada una de las líneas; la línea femenina tiene un manejo diferente en masculino e infantil. En infantil y masculino, se suele trabajar con medidas deducidas, partiendo en la mayoría de las ocasiones con solo dos medidas del cuerpo y dejando de lado el cuadro de tallas. 
            p.mb-4 Con el fin de explorar y afianzar las diferentes formas y técnicas de escalado, se abordará un escalado bibásico tomando como referencia dos moldes de diferentes tallas o, en su defecto tallas de por medio. En el video “Base superior masculina - análisis de escalado bibásico” podrá identificar la manera de hacer el trazo y el análisis de los aspectos a trabajar. 
            .cajon.color-primario.p-4
              p.mb-0 Este tipo de escalado se implementa para evitar el análisis del cuadro de tallas; se realiza el análisis desde la construcción o de la parte anatómica lógica del molde, despiece o la pieza. 
          .col-lg-4.col-md-8.col-8
            img.d-none.d-lg-block(src='@/assets/curso/tema1/img28.png', alt='')
    
    .row.justify-content-center.align-items-center.mb-0(data-aos="fade-left")
      .col-lg-12.col-12
        figure.py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/pMZ7Uxb1cl8?si=I_eNzxV9nGJrEgrc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Análisis de escalado bibásico en la base superior masculina
    

    Separador 
    #t_1_6.titulo-segundo.mb-5
      h2 1.6 Estructura de tallaje masculino y matrices de escalado DxT

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade")
      .col-lg-4.col-md-8.col-8
        img.d-none.d-lg-block(src='@/assets/curso/tema1/img30.png', alt='')
      .col-lg-8.col-md-12.col-12
        p En la metodología del manual de patronaje SENA la línea de masculino e infantil se debe identificar bajo la fórmula o el tipo de construcción de los planos o moldes para poder tener las medidas e incrementos por talla que se van a trabajar en el escalado, si bien se identifica en el manual un cuadro de tallas para cada una de estas líneas, se debe tener en cuenta que desde la construcción, por lo menos en las bases superiores, no se trabaja con el cuadro de tallas, es decir, que se debe hacer la construcción y el análisis del cuadro de tallas basándose en las fórmulas que indica cada una de las construcciones de las bases que se están trabajando, con el fin de poder identificar las diferencias por tallas que se van a aplicar en el escalado. 
        p Ya después de tener la construcción del cuadro de tallas o identificar las tallas reales que se aplican sobre el trazo o molde, se debe hacer el análisis de los puntos y movimientos de escalado que se van a referenciar o modificar. 

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-left")
      .col-lg-12.col-12
        figure.py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/KcHaLNoyFVI?si=jHAmhuKiAFODs9Nx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Estructura de tallaje masculino y matrices de escalado DxT
    
    .fondo21.p-4(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-1.img-a.img-t(src="@/assets/curso/tema1/img8.svg", alt="")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.mb-1 Análisis y construcción de cuadro de tallas masculino
              p.mb-0 Para profundizar en el análisis y construcción de cuadro de tallas masculino, consulte el documento Análisis_y _construcción_de_cuadro_de_tallas_masculino.pdf, ubicado en la carpeta de anexos. 
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexos/Analisis_y_construccion_de_cuadro_de_tallas_masculino.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download


    Separador 
    #t_1_7.titulo-segundo.color-primario.mb-5
      h2 1.7 Modificación de moldes y análisis sobre medidas
    
    .row.mb-4.align-items-center.justify-content-center(data-aos="fade")
      .col-lg-10.col-md-12.col-12
        .row.justify-content-center.align-items-center.mb-0
          .col-2
            .avatar
              img.d-none.d-lg-block(src="@/assets/curso/tema1/img49.svg")
          .col-lg-10.col-md-12.col-12.caj.p-2
            .row
              .col-1
              .col-10
                p.my-3 Para el desarrollo de prendas y escalado de moldes, se debe tener en cuenta que en algunas ocasiones se hace un análisis sobre medidas o sobre requerimientos de clientes específicos; algunas de ellas pueden ser modificaciones por talles, por anchos o por contornos. Este tipo de modificaciones se debe tener en cuenta al momento de realizar las prendas.                 
    
    p.mb-4 En el presente video se podrá encontrar una explicación general sobre cómo y de qué manera se puede implementar este tipo de modificaciones, con mayor relevancia en los moldes que se han desarrollado a lo largo del programa.

    .row.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-12.col-12
        figure.py-2
          .video.mb-1
            iframe(width="560" height="315" src="https://www.youtube.com/embed/AD1BNSkDZOY?si=53iUJctgMarEzq_f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video. Modificación de moldes y análisis sobre medidas


</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
    indicadorTarjetaSlide: true,
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
