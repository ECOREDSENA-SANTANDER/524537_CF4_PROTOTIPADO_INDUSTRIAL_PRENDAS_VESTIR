<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5

      #Actividad                
        <Actividad :cuestionario="cuestionario"/>

</template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Escalado digital',
      titulo: 'Cuestionario',
      introduccion:
        '<b>Objetivo:</b> verificar la apropiación de los fundamentos técnicos relacionados con el escalado manual y digital, el análisis de cuadros de tallas, la aplicación de proporciones y el uso de herramientas digitales para escalado de patrones. ',
      barajarPreguntas: true,
      titulo_aprobado: '¡Excelente! Ha superado la actividad',
      titulo_reprobado: 'No ha superado la actividad',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es la finalidad principal del proceso de escalado en el desarrollo de patrones de prendas de vestir?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Ampliar o reducir proporcionalmente un patrón base para obtener tallas mayores o menores según el cuadro de tallas.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Cambiar únicamente el color del molde base para diferenciar visualmente las piezas durante el corte industrial.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Eliminar las verificaciones del prototipo para iniciar directamente la producción sin análisis de medidas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Sustituir el patronaje por ilustraciones comerciales sin aplicar proporciones, incrementos ni referencias técnicas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia comprensión del escalado como técnica para ampliar o reducir patrones de forma proporcional entre tallas.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 2,
          texto:
            '¿Qué elemento técnico debe tomarse como punto de partida para realizar un escalado manual o digital?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La tendencia comercial de temporada, porque define por completo los incrementos entre tallas y piezas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'El cuadro de tallas, porque permite analizar diferencias, incrementos y proporciones aplicables al patrón.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'La etiqueta de marca, porque determina automáticamente largos, anchos y contornos de todas las prendas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'El empaque final, porque orienta la ubicación de los puntos de referencia sobre el plano cartesiano.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se reconoce el cuadro de tallas como insumo fundamental para identificar diferencias e incrementos aplicables al escalado.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 3,
          texto:
            '¿Cómo se define el plano cartesiano utilizado para ubicar puntos de referencia en escalado?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Como una tabla de medidas anatómicas organizada únicamente por contornos, largos y anchos corporales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Como una ficha técnica que registra insumos, materiales, operaciones de confección y tiempos de producción.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Como dos rectas perpendiculares, una horizontal y otra vertical, que se cruzan en un punto de origen.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Como una plantilla de corte que reemplaza los puntos de escalado y elimina las coordenadas del molde.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia apropiación del plano cartesiano como sistema de coordenadas para ubicar movimientos de escalado.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 4,
          texto:
            '¿Qué representa el punto de origen dentro del análisis de escalado sobre plano cartesiano?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La línea decorativa que permite identificar el color principal y secundario del diseño final.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'El margen de costura que se añade siempre a todas las piezas sin revisar el tipo de prenda.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'El nombre comercial asignado al molde antes de iniciar el proceso de industrialización.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'El punto cero desde el cual se interpretan aumentos, reducciones y desplazamientos del patrón.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se demuestra comprensión del punto de origen como referencia central para interpretar aumentos y reducciones en el escalado.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 5,
          texto:
            '¿Qué significado tienen los valores positivos y negativos al aplicar movimientos en el plano cartesiano?',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Los valores positivos indican aumento y los negativos indican reducción, según la ubicación del punto de origen.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Los valores positivos indican error de trazo y los negativos indican corrección automática del patrón.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Los valores positivos corresponden a costura interna y los negativos a margen externo de ruedo.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Los valores positivos reemplazan los contornos y los negativos eliminan los largos del cuadro de tallas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se reconoce la relación entre valores positivos, negativos, aumento y reducción dentro del plano cartesiano.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 6,
          texto:
            '¿Qué son las proporciones dentro del proceso técnico de escalado de patrones?',
          imagen: require('@/assets/actividad/imagen6.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Medidas decorativas utilizadas para definir colores, texturas y acabados comerciales de una colección.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Medidas de aumentos o disminuciones secuenciales que permiten obtener tallas mayores o menores.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Operaciones de ensamble aplicadas para unir piezas después del corte y antes del planchado.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Registros administrativos empleados para controlar inventario, empaque y distribución de prendas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia comprensión de las proporciones como aumentos o disminuciones secuenciales aplicadas al escalado.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 7,
          texto:
            '¿Qué ocurre cuando la diferencia entre tallas es de 2 cm y el plano trabaja la medida completa?',
          imagen: require('@/assets/actividad/imagen7.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Se aplica una reducción fija de medio centímetro en todos los vértices sin revisar el cuadro de tallas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Se elimina el incremento porque la medida completa no puede distribuirse sobre planos de escalado.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Se aplica una proporción completa de 2 cm, porque el plano trabaja la totalidad de la medida.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Se cambia el sistema métrico por pulgadas para evitar el cálculo de proporciones entre tallas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se demuestra dominio de la proporción completa cuando el plano trabaja la totalidad de la diferencia entre tallas.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 8,
          texto:
            '¿Qué ocurre cuando la diferencia entre tallas es de 2 cm y el plano trabaja la mitad de la medida?',
          imagen: require('@/assets/actividad/imagen8.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Se aplica la medida completa de 2 cm en cada mitad para duplicar el crecimiento del patrón.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Se ignora el escalado porque los planos por mitad no permiten aumento o reducción proporcional.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Se elimina el punto de origen y se reemplaza por una línea de margen de costura.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Se aplica media proporción de 1 cm, porque el plano representa solo la mitad de la medida total.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia comprensión de la media proporción cuando el plano representa solo una mitad de la medida total.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 9,
          texto:
            '¿Cuál es la característica principal del escalado monobásico en patronaje de prendas?',
          imagen: require('@/assets/actividad/imagen9.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Parte de una talla base para obtener otras tallas mediante aumentos o reducciones proporcionales.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Requiere tres tallas base obligatorias para construir todos los puntos intermedios del patrón.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Elimina el análisis de incrementos porque trabaja únicamente con medidas de prenda terminada.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Se utiliza solo para modificar colores, nombres comerciales y acabados externos de la prenda.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se reconoce el escalado monobásico como método que parte de una talla base para generar tallas por aumento o reducción.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 10,
          texto:
            '¿Qué caracteriza al escalado bibásico dentro del análisis técnico de patrones?',
          imagen: require('@/assets/actividad/imagen10.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Trabaja únicamente desde una talla central y descarta el uso de talla prototipo o talla límite.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Toma dos tallas básicas para obtener tallas intermedias mediante líneas comunes y división de vértices.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Usa solo fichas de confección para calcular tiempos de ensamble, máquinas y operaciones manuales.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Se aplica exclusivamente a prendas terminadas con margen de costura y empaque final definido.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia apropiación del escalado bibásico como procedimiento que compara dos tallas para obtener intermedias.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 11,
          texto:
            '¿Qué caracteriza al escalado tribásico en la obtención de tallas intermedias?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Parte de una sola talla base y genera toda la serie mediante una proporción constante.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Utiliza únicamente medidas comerciales sin considerar vértices, límites ni patrones de referencia.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Toma tres tallas para obtener intermedias, por ejemplo, 10, 14 y 18 para hallar 12 y 16.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Se limita a escalar márgenes de costura sin modificar largos, contornos ni anchos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se demuestra comprensión del escalado tribásico como método que emplea tres tallas de referencia para obtener tallas intermedias.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 12,
          texto:
            '¿Qué aspectos deben analizarse en un cuadro de tallas antes de aplicar el escalado?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Color, textura, tendencia, vitrina, fotografía, redes sociales y sistema de empaque comercial.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Tipo de puntada, aguja, hilo, prensatelas, planchuela y tensión de máquina de confección.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Referencia de marca, precio de venta, código de barras, etiqueta y canal de distribución.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Límites, frecuencia, incremento, valores, proporciones y posibles rupturas entre tallas.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se reconoce el análisis de límites, frecuencia, incremento y rupturas como base para interpretar cuadros de tallas.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 13,
          texto:
            '¿Qué indica una ruptura de talla dentro del análisis de un cuadro de medidas?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Una variación que rompe la secuencia regular de incrementos entre una talla y otra.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Una costura abierta que debe corregirse durante el ensamble de la muestra física.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Una línea decorativa que permite dividir la prenda en paneles de diseño comercial.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Una etiqueta de talla mal ubicada en el empaque final de una prenda terminada.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia comprensión de la ruptura de talla como cambio en la secuencia regular de incrementos del cuadro.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 14,
          texto:
            '¿Qué operación previa es necesaria antes de escalar una pieza o molde de prenda?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Seleccionar solamente el nombre comercial de la prenda para reemplazar el análisis de construcción.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Definir la metodología de construcción, tipo de molde, margen de costura y puntos de escalado.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Eliminar el cuadro de tallas para trabajar únicamente desde la apariencia visual del diseño.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Escoger el empaque final antes de identificar proporciones, incrementos y validaciones del patrón.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se demuestra dominio de las operaciones previas requeridas para iniciar un escalado técnicamente organizado.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 15,
          texto:
            '¿Qué debe verificarse en el escalado de una falda base sin margen de costura?',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'La ubicación de botones, bolsillos de parche y pechera como si se tratara de una camisa.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'La cantidad de aros, copas y tirantes necesarios para el desarrollo de ropa interior.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'El comportamiento de pinzas y la igualdad de medidas laterales entre delantero y posterior.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'La programación de máquinas de ensamble antes de analizar el cuadro de tallas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se reconoce la verificación de pinzas y laterales como control técnico en el escalado de falda base.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 16,
          texto:
            '¿Qué revisión resulta fundamental en el escalado de un básico de pantalón?',
          imagen: require('@/assets/actividad/imagen6.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Revisar que los laterales, entrepiernas y tiro conserven correspondencia para no afectar la horma.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Verificar únicamente el color del textil sin revisar contornos, largos ni puntos de construcción.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Eliminar los incrementos de talla porque los pantalones no requieren proporciones en escalado.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Escalar solo la pretina sin considerar delantero, posterior, entrepierna, tiro ni costados.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia comprensión de la importancia de revisar laterales, entrepiernas y tiro en el escalado del pantalón.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 17,
          texto:
            '¿Qué particularidad tiene el escalado de cortes, manga y cuello frente a un básico sin modificar?',
          imagen: require('@/assets/actividad/imagen7.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Corresponde únicamente a cuadrados geométricos sin relación con simetría, cortes ni piezas de prenda.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Corresponde solo a cuadros de tallas masculinos sin considerar proporciones ni puntos de escalado.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Corresponde a operaciones de planchado que no alteran medidas, largos, anchos ni recorridos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Corresponde a piezas de diseño que pueden tener margen de costura y validaciones como producto final.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se reconoce que el escalado de cortes, manga y cuello exige analizar piezas modificadas, simetría y validaciones del producto.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 18,
          texto:
            '¿Por qué en línea masculina e infantil puede requerirse construir o analizar un cuadro de tallas propio?',
          imagen: require('@/assets/actividad/imagen8.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Porque siempre se elimina el uso de fórmulas y se trabaja únicamente por observación comercial.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Porque los moldes se construyen desde fotografías sin medidas anatómicas ni deducciones técnicas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Porque algunas bases se desarrollan con medidas deducidas y fórmulas, no solo con el cuadro existente.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Porque el escalado masculino solo modifica etiquetas, sin relación con patrones o medidas del cuerpo.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se evidencia comprensión de la necesidad de analizar fórmulas y medidas deducidas en cuadros de tallas masculino e infantil.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 19,
          texto:
            '¿Qué tipo de modificaciones pueden presentarse en el análisis sobre medidas durante el escalado de moldes?',
          imagen: require('@/assets/actividad/imagen9.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Modificaciones por talles, anchos o contornos, según requerimientos específicos de cliente o prenda.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Modificaciones solo por color, etiqueta y nombre comercial, sin alterar medidas ni construcción.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Modificaciones exclusivamente de empaque, inventario y canal de venta de la prenda terminada.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Modificaciones de publicidad visual que reemplazan el análisis técnico del molde base.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se reconoce el análisis sobre medidas como recurso para ajustar talles, anchos o contornos según requerimientos específicos.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
        {
          id: 20,
          texto:
            '¿Qué relación existe entre el escalado manual y el escalado digital en Optitex?',
          imagen: require('@/assets/actividad/imagen10.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'El escalado digital elimina todo análisis manual y no requiere cuadro de tallas ni proporciones.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'El escalado digital aplica el mismo análisis técnico, pero mediante herramientas e interfaz del <em>software</em>.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'El escalado manual solo sirve para colorear moldes y el digital solo para imprimir etiquetas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'El escalado en Optitex se aplica únicamente a falda y no permite trabajar otras bases o prendas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Muy bien! Se demuestra comprensión de Optitex como herramienta digital que conserva la lógica técnica del escalado manual.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. Se recomienda revisar nuevamente los contenidos del componente formativo para fortalecer la comprensión de los conceptos técnicos abordados.',
        },
      ],
      mensaje_final_aprobado:
        'Ha superado la actividad y se evidencia apropiación de los fundamentos técnicos del escalado digital, el análisis de cuadros de tallas, la aplicación de proporciones y el uso de herramientas para escalar patrones.',
      mensaje_final_reprobado:
        'No ha superado la actividad. Se recomienda revisar nuevamente el componente formativo e intentar otra vez la actividad didáctica.',
    },
  }),
}
</script>
