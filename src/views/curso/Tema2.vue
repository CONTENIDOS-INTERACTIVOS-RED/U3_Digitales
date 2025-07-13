<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Evaluación del impacto de los recursos digitales en la enseñanza y el aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden


    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left").mb-4 Una vez que un Recurso Educativo Digital (RED), ha sido diseñado e integrado en una experiencia de aprendizaje, surge una pregunta fundamental: ¿qué impacto real está teniendo en la enseñanza y, sobre todo, en el aprendizaje de los estudiantes? 
        .bg-color-1.p-4(data-aos="fade-left")
          p.mb-0 La evaluación de este impacto es un proceso esencial que va más allá de una simple medición; busca comprender en profundidad la efectividad del RED y, a partir de ello, fundamentar decisiones para su mejora continua y la optimización de las estrategias pedagógicas. 
    
  
    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] Fundamentos de la evaluación del RED
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema5/18.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-2.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema5/19.svg", style="max-width: 90px").mx-auto
            .col-lg
              p El propósito primordial de evaluar un RED no es emitir un juicio de valor definitivo sobre si es "bueno" o "malo", sino comprender su funcionamiento en un contexto real y generar conocimiento útil para mejorar tanto el recurso en sí como las prácticas educativas asociadas a él.
              p.mb-0 Es crucial distinguir entre la evaluación del RED como producto (su calidad intrínseca, diseño, usabilidad técnica, corrección del contenido) y la evaluación de su impacto en el proceso de aprendizaje de los estudiantes (cómo influye en su motivación, comprensión, desarrollo de habilidades, etc.). Ambas dimensiones son importantes, pero este tema se centrará principalmente en la segunda.
        p(data-aos="fade-left") Antes de iniciar cualquier proceso evaluativo, es indispensable definir con claridad, qué se va a evaluar. 
    

    .bg-full-width.bg-color-5
      .p-4.p-md-5
        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/20.svg" alt="" style="width: 90px")
              h5.text-center Primero
              p.mb-0.text-center ¿Se busca medir la mejora en la comprensión de conceptos específicos? 
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/20.svg" alt="" style="width: 90px")
              h5.text-center Segundo
              p.mb-0.text-center ¿El desarrollo de habilidades de pensamiento crítico?  
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/20.svg" alt="" style="width: 90px")
              h5.text-center Tercero
              p.mb-0.text-center ¿El nivel de compromiso (<em>engagement</em>) de los estudiantes con el material? 
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/20.svg" alt="" style="width: 90px")
              h5.text-center Cuarto
              p.mb-0.text-center ¿La eficiencia en el tiempo de aprendizaje?  
    
    .bg-full-width.bg-color-10.mb-5
      .px-4.px-md-5.py-4
        p.mb-0.text-white Estos objetivos de evaluación, deben estar directamente alineados con los objetivos de aprendizaje que el RED pretendía apoyar. Sin esta claridad inicial, la selección de métodos e instrumentos de evaluación, carecerá de foco y los resultados serán difíciles de interpretar, de manera significativa.
    
    #t_2_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.2] Tipos de evaluación aplicados a RED
    
    p.mb-5 La evaluación del RED puede adoptar diferentes enfoques, según su propósito y el momento en que se realiza. Los principales tipos son:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema5/21.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        AcordionA(tipo="b")
          .div(titulo="Evaluación formativa")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Definición y propósito</b>. Se realiza durante la interacción de los estudiantes con el RED o a lo largo de la unidad didáctica que lo integra. Su objetivo principal es monitorear el progreso del aprendizaje del estudiante y proveer retroalimentación continua y oportuna que le permita identificar sus fortalezas y áreas de mejora. Para el docente, ofrece información valiosa para ajustar su enseñanza, identificar dificultades comunes y, si es necesario, modificar la forma en que se está utilizando el RED.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. Quizzes interactivos integrados en el propio RED con retroalimentación inmediata, actividades de autoevaluación, preguntas reflexivas, observación directa de cómo los estudiantes interactúan con el recurso (en entornos presenciales o mediante el análisis de su comportamiento en plataformas online), análisis de las primeras entregas de tareas que utilizan el RED, o incluso el uso de analíticas de aprendizaje en tiempo real para detectar patrones de dificultad.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Uso de resultados</b>, Los datos de la evaluación formativa son fundamentales para la toma de decisiones ágil, permitiendo realizar ajustes "sobre la marcha" tanto en la estrategia pedagógica como en aspectos del propio RED, que puedan estar generando confusión o dificultades.

          .div(titulo="Evaluación sumativa")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Definición y propósito</b>. Se lleva a cabo al finalizar la interacción con el RED o al concluir una unidad de aprendizaje o curso donde el RED ha jugado un papel relevante. Su finalidad es valorar el grado de logro de los objetivos de aprendizaje establecidos y, en algunos casos, certificar el aprendizaje. Aunque su enfoque es más global, también puede proporcionar información útil para la revisión futura del RED y de la estrategia de integración.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. Pruebas o exámenes que requieren la aplicación de conocimientos o habilidades adquiridos o practicados a través del RED, desarrollo de proyectos donde el RED es una herramienta o fuente de información clave, creación de portafolios digitales que evidencian el aprendizaje, o la evaluación del desempeño en tareas auténticas que simulan contextos reales.
          .div(titulo="Evaluación diagnóstica")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Definición y propósito</b>. Se realiza antes de una intervención educativa o de la introducción de un RED específico. Su objetivo es identificar los conocimientos previos, habilidades, intereses o necesidades particulares de los estudiantes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Cómo los RED pueden ayudar</b>. Algunos RED, como cuestionarios interactivos o simulaciones que revelan concepciones erróneas, pueden ser herramientas útiles para realizar esta evaluación diagnóstica, permitiendo al docente adaptar la enseñanza y la selección o el enfoque de uso de otros RED a las características del grupo.

    #t_2_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.3] Indicadores de Impacto de los RED
    
    p.mb-5 La evaluación del impacto de los Recursos Educativos Digitales (RED) es fundamental para valorar su eficacia en el proceso de enseñanza y aprendizaje.

    .bg-full-width.bg-color-9.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Indicadores de Impacto de los RED
            p.mb-4(data-aos="fade-right") En el PDF <b>Indicadores de Impacto de los RED</b>, se presentan criterios e instrumentos para identificar cómo estos recursos influyen en aspectos cognitivos, afectivos y comportamentales del estudiante, mediante el uso de indicadores observables y técnicas de recolección de datos. Esta evaluación permite fortalecer el diseño instruccional y la integración pedagógica de los RED, garantizando su contribución significativa al aprendizaje.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_2.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Indicadores de Impacto de los RED.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/22.png', alt='')
    
    #t_2_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.4] Herramientas y tecnologías para la evaluación de RED
    
    p.mb-5 La evaluación rigurosa de los Recursos Educativos Digitales (RED) requiere no solo indicadores adecuados, sino también herramientas y tecnologías que faciliten la recolección, el análisis y la interpretación de datos relevantes.

    .bg-full-width.bg-color-9.mb-0
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Herramientas y tecnologías para la evaluación de RED
            p.mb-4(data-aos="fade-right") En el PDF <b>Herramientas y tecnologías para la evaluación de RED</b>, se presentan soluciones como funcionalidades de LMS, encuestas online, software de análisis cualitativo y dashboards analíticos que permiten valorar el impacto de los RED desde múltiples enfoques. Esta información proporciona una base técnica y pedagógica para realizar evaluaciones fundamentadas, éticas y orientadas a la mejora continua del aprendizaje.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_3.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Herramientas y tecnologías para la evaluación de RED.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/23.png', alt='')

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.


            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://revistas.unibe.edu.ec/index.php/qualitas/article/view/263" target="_blank" rel="noopener noreferrer") Mera, I. E. Z., & García, L. C. (2024). Impacto de las tecnologías digitales en el aprendizaje y la enseñanza en entornos educativos. Revista Qualitas, 28(28), 054-068. 

 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://revistas.unae.edu.ec/index.php/mamakuna/article/view/810" target="_blank" rel="noopener noreferrer") Sanaguaray, E. I. M., Duy, K. D. C., & Crespo, L. E. G. (2023). Impacto de los recursos digitales en la enseñanza de las Ciencias Naturales. Mamakuna, (20), 36-47. 
           


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=NZIWEfkrVPY&ab_channel=INTEF" target="_blank" rel="noopener noreferrer") INTEF. (2022, 31 de enero). NOOC Calidad de los Recursos Educativos Digitales Didáctica sub. [Video] YouTube  
                   

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>
