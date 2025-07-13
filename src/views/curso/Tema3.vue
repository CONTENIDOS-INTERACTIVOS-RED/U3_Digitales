<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Mejora y optimización de materiales digitales según retroalimentación y análisis de datos'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-2.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema6/1.png', alt='')
        .col-lg.order-1.mb-3.mb-lg-0
          .p-4
            p.mb-0(data-aos="fade-up") La creación de un Recurso Educativo Digital (RED) no culmina con su primera versión o implementación. De hecho, este es solo el comienzo de un ciclo vital en el que la mejora continua y la optimización son fundamentales para asegurar su relevancia, efectividad y alineación con las necesidades cambiantes de los estudiantes y los contextos educativos. Este tema le guiará a través de los procesos para transformar la retroalimentación y los datos de uso en acciones concretas de mejora.

    #t_3_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.1] El Ciclo de Mejora Continua (PDCA/Deming) Aplicado a RED
    
    p.mb-5 El concepto de mejora continua, popularizado por W. Edwards Deming (Soberanis Pacheco, 2021), se materializa en el Ciclo PDCA (Plan-Do-Check-Act), también conocido como ciclo de Deming o ciclo de Shewhart. Este modelo iterativo de cuatro fases, es perfectamente aplicable a la optimización de RED:

    .bg-full-width.bg-fondo-3
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-10
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema6/2.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="2.8%" y="43.3%" numero="+")
                h5 Actuar (Act)
                p Con base en los resultados de la fase de verificación, se toman decisiones:
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si los cambios fueron exitosos y se alcanzaron los objetivos, se estandarizan las mejoras, se documentan y se implementan de forma generalizada en el RED.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si los cambios no produjeron los resultados esperados o surgieron nuevos problemas, se analizan las causas, se ajusta el plan y se inicia un nuevo ciclo PDCA.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si se identifican nuevas oportunidades de mejora, también se incorporan al siguiente ciclo de planificación.
    
              .bg-color-white.box-shadow.p-3(x="17.3%" y="8.5%" numero="+")
                h5 Planificar (Plan)
                p En esta fase, se identifican las áreas de mejora del RED basándose en la evaluación de su impacto, la retroalimentación de los usuarios (estudiantes, docentes), el análisis de datos de uso, o los cambios en los objetivos de aprendizaje o el currículo. Se establecen objetivos claros para la mejora, se definen las modificaciones específicas que se realizarán en el RED y se planifica cómo se implementarán y evaluarán estos cambios.
    
              .bg-color-white.box-shadow.p-3(x="97.2%" y="31%" numero="+")
                h5 Verificar (<em>Check</em>)
                p Una vez implementados los cambios, se evalúa su efectividad. Se recolectan datos para determinar si las modificaciones han logrado los objetivos planteados en la fase de planificación. ¿Mejoró la comprensión del estudiante? ¿Aumentó el engagement? ¿Se resolvieron los problemas de usabilidad identificados? Se comparan los resultados con los datos previos a la modificación.
    
              .bg-color-white.box-shadow.p-3(x="65.8%" y="55%" numero="+")
                h5 Hacer (<em>Do</em>)
                p Se implementan los cambios planificados en el RED. Esto puede implicar modificar contenidos, rediseñar actividades interactivas, mejorar la interfaz de usuario, añadir nuevos elementos, corregir errores, etc. Es recomendable realizar estos cambios en un entorno de prueba o con un grupo piloto si las modificaciones son sustanciales.
    
    .bg-full-width.bg-color-10.mb-5
      .px-4.px-md-5.py-4
        p.mb-0.text-white La aplicación sistemática de este ciclo fomenta una cultura de revisión y adaptación constante, donde el RED es visto como un producto dinámico que evoluciona y mejora con el tiempo, en lugar de una obra estática y definitiva. Este enfoque es vital en el ámbito de la tecnología educativa, donde las herramientas, las pedagogías y las necesidades de los usuarios están en permanente transformación.
    
    #t_3_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.2] Recolección sistemática de retroalimentación (<em>feedback</em>)
    
    .row.mb-5
      .col-lg-3.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema6/3.svg", data-aos="zoom-in")
      .col-lg-9.order-lg-1
        p(data-aos="fade-left") La retroalimentación de los usuarios es una de las fuentes de información más valiosas para la mejora de los RED. Para que sea útil, su recolección debe ser sistemática y planificada.
        p Fuentes de retroalimentación:
    
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema6/4.png")
            .col-lg-7
              h5 Estudiantes
              p Son los usuarios directos del RED y pueden ofrecer perspectivas cruciales sobre su claridad, utilidad, nivel de dificultad, atractivo y los problemas que encontraron. Su <em>feedback</em> puede recogerse a través de encuestas de satisfacción, comentarios en foros de discusión del EVA, entrevistas individuales o grupales, pruebas de usabilidad específicas, o incluso a través de canales informales si se crea un ambiente de confianza.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema6/5.png")
            .col-lg-7
              h5 Docentes / Pares
              p Otros educadores que utilizan o han revisado el RED pueden aportar una visión pedagógica experta, identificar posibles desajustes con el currículo, sugerir mejoras en las actividades o en la forma de integrar el RED. Esto puede lograrse mediante revisiones colaborativas, observaciones de clase (si el RED se usa en contextos híbridos), o en el marco de comunidades de práctica docente.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema6/6.png")
            .col-lg-7
              h5 Expertos en contenido y diseño
              p Especialistas en la materia del RED pueden validar la precisión y actualidad del contenido, mientras que expertos en diseño instruccional o diseño de interfaces pueden ofrecer recomendaciones sobre la estructura pedagógica, la usabilidad y la accesibilidad del recurso.
    
    p.mb-5 Métodos para recolectar <em>feedback</em> efectivo:
    
    .bg-full-width.bg-color-5
      .p-4.p-md-5
        TabsC.color-primario.mb-5
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Diseño de instrumentos" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0
                h4 Diseño de instrumentos
                p Utilizar una combinación de preguntas cerradas (para obtener datos cuantitativos sobre aspectos específicos) y preguntas abiertas (para recoger opiniones, sugerencias y explicaciones detalladas). Las preguntas deben ser claras, concisas y enfocadas en los aspectos que se desean mejorar.
        
              .col-md-8.col-lg-5.col-xl-4.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema6/7.png', alt='')
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Creación de un ambiente de confianza" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0
                h4 Creación de un ambiente de confianza
                p Es fundamental que los usuarios se sientan cómodos para expresar críticas constructivas sin temor a represalias. El anonimato en las encuestas puede ayudar, así como una comunicación clara sobre el propósito de la recolección de <em>feedback</em> (la mejora del recurso para beneficio de todos).
        
              .col-md-8.col-lg-5.col-xl-4.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema6/8.png', alt='')
        
        p.mb-5 Momentos claves para solicitar feedback:

        div.row.justify-content-center.align-items-stretch.mb-3
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/9.svg" alt="" style="width: 90px")
              h5.text-center Durante el pilotaje
              p.mb-0.text-center Antes de un lanzamiento a gran escala, probar el RED con un grupo reducido de usuarios y recoger sus impresiones es crucial para identificar problemas mayores.
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/10.svg" alt="" style="width: 90px")
              h5.text-center Durante el uso regular
              p.mb-0.text-center Integrar mecanismos para que los estudiantes puedan reportar problemas o hacer sugerencias mientras usan el RED (ejemplo, un botón de “feedback”). 
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/11.svg" alt="" style="width: 90px")
              h5.text-center Después de un uso extensivo o al finalizar una unidad/curso
              p.mb-0.text-center Solicitar una valoración más global de la experiencia con el RED.
    
    #t_3_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.3] Análisis de la retroalimentación y los datos de uso

    p.mb-5 El análisis de datos es una etapa fundamental para comprender la eficacia y la experiencia del uso de los Recursos Educativos Digitales (RED).

    .bg-full-width.bg-color-9.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Análisis de la retroalimentación y los datos de uso
            p.mb-4(data-aos="fade-right") En el PDF <b>Análisis de la retroalimentación y los datos de uso</b>, se explican métodos cualitativos y cuantitativos para interpretar comentarios de los usuarios y patrones de navegación en plataformas virtuales, con el fin de identificar oportunidades de mejora. Esta información, cuando se triangula adecuadamente, permite tomar decisiones informadas para optimizar tanto el diseño instruccional como la funcionalidad de los RED.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_4.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Análisis de la retroalimentación y los datos de uso.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema6/12.png', alt='')

    #t_3_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.4] Principios de diseño iterativo para la optimización de RED
    
    .bg-full-width.bg-color-7.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-6.order-lg-2.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema6/13.svg", data-aos="zoom-in")
          .col-lg-6.order-lg-1
            p(data-aos="fade-left").mb-4 Para conocer sobre la temática, lo invitamos a escuchar el siguiente podcast.
    
            TarjetaAudio.color-acento-botones.bg-color-white.mb-3(
              texto="Principios de diseño iterativo para la optimización de RED"
              tiempo
              :audio="require('../../assets/curso/podcast/podcast1.mp3')"
            )

    #t_3_5.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.5] Casos prácticos de optimización de RED
    
    p.mb-5 Para ilustrar cómo se aplican estos principios, consideremos algunos ejemplos:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema6/14.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        AcordionA(tipo="b")
          .div(titulo="Caso 1. Mejorar la navegabilidad")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Los estudiantes comentan que “es difícil encontrar la información” y las analíticas muestran que muchos abandonan el RED desde la página de inicio o navegan erráticamente. Los mapas de calor indican que no hacen clic en los enlaces del menú principal.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Rediseñar el menú de navegación para que sea más visible e intuitivo, usar etiquetas más claras, añadir un mapa del sitio o un índice interactivo. Probar el nuevo diseño con un grupo de usuarios antes de implementarlo para todos.

          .div(titulo="Caso 2. Ajustar el nivel de dificultad de actividades interactivas")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Muchos estudiantes se quejan de que un quiz es “demasiado difícil” y las tasas de respuestas correctas son muy bajas. Otros, en cambio, lo encuentran “muy fácil”.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Revisar las preguntas del quiz. Si es posible, ofrecer diferentes niveles de dificultad o pistas opcionales. Añadir retroalimentación más detallada para las respuestas incorrectas que explique el error. Considerar si el contenido previo preparó adecuadamente a los estudiantes para el quiz.
          .div(titulo="Caso 3. Añadir recursos de apoyo donde se detectan dificultades")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Las analíticas muestran que los estudiantes pasan mucho tiempo en una sección que explica un concepto complejo y, aún así, sus resultados en las actividades relacionadas son bajos. Los comentarios indican “necesito más ejemplos”.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Añadir un vídeo explicativo corto, un glosario de términos clave para esa sección, ejemplos resueltos adicionales, o un foro específico donde puedan plantear dudas sobre ese concepto.
          .div(titulo="Caso 4. Mejorar la claridad de las instrucciones")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Varios estudiantes preguntan “¿qué se supone que tengo que hacer aquí?” en una actividad que requiere el uso de una herramienta externa integrada en el RED.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Reescribir las instrucciones de la actividad para que sean más explícitas, paso a paso. Incluir capturas de pantalla o un breve videotutorial mostrando cómo usar la herramienta externa en el contexto de la tarea.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/15.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") Una vez realizadas las mejoras, es importante comunicar los cambios a los usuarios, especialmente si son significativos. Esto no solo les ayuda a aprovechar las nuevas funcionalidades o el contenido mejorado, sino que también demuestra que su feedback es valorado y tomado en cuenta, lo que puede fomentar una mayor disposición a participar en futuros procesos de retroalimentación.
        p.mb-5 Es importante reconocer que la resistencia al cambio (tanto por parte de los diseñadores que pueden sentirse apegados a su creación original, como de los usuarios que ya se habían acostumbrado a una versión anterior) puede ser una barrera para la mejora continua. 
        .bg-color-3.p-4(data-aos="fade-left")
          p.mb-0 Una cultura organizacional e institucional que valore la experimentación, que vea el “error” o el feedback crítico como una oportunidad de aprendizaje, y que asigne tiempo y recursos para los procesos de revisión y optimización, es crucial para superar estas barreras. La mejora continua de RED no es solo una responsabilidad individual del diseñador; se ve facilitada (o dificultada) por el contexto institucional y las políticas de apoyo a la innovación educativa. Esto tiene implicaciones para el liderazgo educativo y la gestión del cambio en las organizaciones que buscan fomentar la calidad en la educación digital.
        

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.scielo.org.ar/scielo.php?pid=S1850-00132014000100005&script=sci_arttext" target="_blank" rel="noopener noreferrer") Aguilar Juárez, I., Ayala De la Vega, J., Lugo Espinosa, O., & Zarco Hidalgo, A. (2014). Análisis de criterios de evaluación para la calidad de los materiales didácticos digitales. Revista iberoamericana de ciencia tecnología y sociedad, 9(25), 73-89.


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=fplS9vfMzDs&ab_channel=KeisenConsultores  " target="_blank" rel="noopener noreferrer") Keisen Consultores. (2020, 18 de septiembre). 034 - Tip PDCA 2: Diferencia Ciclo PDCA vs Ciclo de Deming. [Video] YouTube 


          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
</template>
