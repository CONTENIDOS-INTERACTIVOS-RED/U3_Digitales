<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:subTitulo="'1. Estrategias para la integración de recursos digitales en entornos virtuales de aprendizaje (EVA)'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
  
      .bg-color-2.mb-5(data-aos="fade-up")
        .row.justify-content-center.align-items-center
          .col-lg-auto.order-2
            figure
              img(src='@/assets/curso/tema5/1.png', alt='')
          .col-lg.order-1.mb-3.mb-lg-0
            .p-4
              p.mb-0(data-aos="fade-up") La mera presencia de recursos digitales en un Entorno Virtual de Aprendizaje (EVA), no garantiza una mejora en el aprendizaje. La clave reside en una integración estratégica y pedagógicamente fundamentada. Para esto se debe tener en cuenta una serie de aspectos que se abordan a continuación.
  
      #t_1_1.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.1] La integración de RED en EVA
      
      p.mb-5 La integración de Recursos Educativos Digitales (RED) en los Entornos Virtuales de Aprendizaje (EVA) requiere más que una simple inclusión de archivos digitales: implica una planificación estratégica que articule los objetivos pedagógicos con el uso significativo de la tecnología.
      
      .bg-full-width.bg-color-9.mb-5
        .px-4.p-md-5
          .row.justify-content-center.align-items-center
            .col-lg-7.order-2
              h2.mb-4(data-aos="flip-up") La integración de RED en EVA
              p.mb-4(data-aos="fade-right") En el PDF <b>La integración de RED en EVA</b>, se estudia cómo modelos teóricos como SAMR y TPACK orientan la selección e implementación de recursos que transforman las experiencias de aprendizaje, fomentando la participación activa, el pensamiento crítico y la apropiación del conocimiento.
      
              a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
                .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p <strong>Anexo. </strong> La integración de RED en EVA.
      
            .col-lg-5.order-1.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema5/2.png', alt='')
      
      #t_1_2.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.2] Alineación de los RED con el diseño instruccional del curso/unidad
      
      p.mb-5 La selección e integración de cualquier RED debe estar firmemente anclada en el diseño instruccional general del curso o unidad. Esto significa que la decisión de usar un RED específico, debe derivarse directamente de:
  
      div.row.justify-content-center.align-items-stretch.mb-3
        div.col-lg-3.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/3.svg" alt="" style="width: 90px")
            h5.text-center Primero
            p.mb-0.text-center Los objetivos de aprendizaje que se espera que los estudiantes alcancen.
      
        div.col-lg-3.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/4.svg" alt="" style="width: 90px")
            h5.text-center Segundo
            p.mb-0.text-center Las competencias que se busca desarrollar.
      
        div.col-lg-3.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/5.svg" alt="" style="width: 90px")
            h5.text-center Tercero
            p.mb-0.text-center Las actividades de aprendizaje planificadas para lograr dichos objetivos y competencias.
        div.col-lg-3.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/6.svg" alt="" style="width: 90px")
            h5.text-center Cuarto
            p.mb-0.text-center Las estrategias de evaluación que permitirán verificar el aprendizaje.
      
      .row.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/7.png", data-aos="zoom-in")
        .col-lg-8.order-lg-1
          .bg-color-2.p-4.mb-5(data-aos="fade-left")
            p.mb-0 Los RED pueden desempeñar múltiples funciones dentro de un diseño instruccional: pueden servir para introducir nuevos conceptos de manera atractiva (ejemplo, videos, simulaciones), facilitar la práctica y la aplicación de conocimientos (ej. ejercicios interactivos, laboratorios virtuales), apoyar la evaluación formativa (ejemplo, quizzes auto-corregibles), o fomentar la colaboración y la construcción conjunta de conocimiento (ejemplo, wikis, foros multimedia).
          p(data-aos="fade-left") Para asegurar la coherencia, es fundamental que se pregunte: 
      
      .bg-full-width.bg-color-5
        .p-4.p-md-5
          div.row.justify-content-center.align-items-stretch.mb-3
            div.col-lg-4.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/8.svg" alt="" style="width: 90px")
                p.mb-0.text-center ¿Cómo este RED específico me ayuda para que mis estudiantes logren este objetivo de aprendizaje particular? 
          
            div.col-lg-4.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/8.svg" alt="" style="width: 90px")
                p.mb-0.text-center ¿De qué manera se articula con las actividades previas y posteriores? 
          
            div.col-lg-4.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(src="@/assets/curso/tema5/8.svg" alt="" style="width: 90px")
                p.mb-0.text-center ¿Cómo complementa o enriquece los otros materiales del curso? 
          p Esta alineación es crucial para evitar que los RED se perciban como elementos aislados o accesorios, y para que contribuyan de manera efectiva, al flujo de aprendizaje diseñado.
  
      #t_1_3.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.3] Fomento de la interacción y colaboración a través de RED integrados
      
      p.mb-5 Los EVA, por su naturaleza, pueden facilitar diversos tipos de interacción que son fundamentales para el aprendizaje:
  
      TabsC.color-primario.mb-5
        .tabs-content.border.px-4.p-md-5.py-3(titulo="Interacción estudiante-contenido" :icon="require('@/assets/bullets/1.svg')")
          .row.justify-content-center.align-items-center
            .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 Interacción estudiante-contenido
              p El estudiante interactúa con los materiales de aprendizaje. Los RED bien diseñados (interactivos, multimedia, adaptativos) pueden hacer esta interacción más rica y motivadora.
      
            .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema5/9.png', alt='')
        .tabs-content.border.px-4.p-md-5.py-3(titulo="Interacción estudiante-estudiante" :icon="require('@/assets/bullets/1.svg')")
          .row.justify-content-center.align-items-center
            .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 Interacción estudiante-estudiante
              p Los estudiantes aprenden unos de otros a través de la discusión, la colaboración y el feedback entre pares.
      
            .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema5/10.png', alt='')
        .tabs-content.border.px-4.p-md-5.py-3(titulo="Interacción estudiante-docente" :icon="require('@/assets/bullets/1.svg')")
          .row.justify-content-center.align-items-center
            .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 Interacción estudiante-docente
              p El docente guía, facilita, retroalimenta y apoya el proceso de aprendizaje de los estudiantes.
      
            .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema5/11.png', alt='')
      
      .row.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/12.png", data-aos="zoom-in")
        .col-lg-8.order-lg-1
          p(data-aos="fade-left") Muchos RED tienen un gran potencial para mediar y potenciar estas interacciones. Por ejemplo, un foro enriquecido con la posibilidad de adjuntar archivos multimedia, puede fomentar debates más profundos; una wiki puede ser el espacio para la construcción colaborativa de un glosario o un proyecto; herramientas de creación conjunta en tiempo real (como documentos compartidos), pueden facilitar el trabajo en equipo a distancia.
      
          .bg-color-2.p-4(data-aos="fade-left")
            .row.align-items-start
              .col-lg-auto
                img(src="@/assets/curso/tema5/13.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 Al integrar estos RED, es importante diseñar actividades que explícitamente requieran y aprovechen su potencial interactivo y colaborativo. No basta con proporcionar la herramienta; es necesario proponer tareas que motiven a los estudiantes a usarla para comunicarse, discutir, crear conjuntamente y aprender unos de otros, con la guía y el andamiaje adecuados por parte del docente.
      
      #t_1_4.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.4] Consideraciones prácticas para la integración en EVA
      
      p.mb-5 Finalmente, una integración exitosa también depende de atender una serie de aspectos prácticos:
  
      .bg-full-width.bg-fondo-slider.mb-5
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.mb-3.mb-lg-0
                figure
                  img(src="@/assets/curso/tema5/14.png")
              .col-lg-7
                h5 Aspectos técnicos
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Compatibilidad</b>. Asegurar que el RED sea compatible con el LMS/EVA, utilizado por la institución y que funcione correctamente en los dispositivos y navegadores que probablemente usarán los estudiantes.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Formatos</b>. Utilizar formatos de archivo estándar y accesibles.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Navegabilidad</b>. El RED debe ser fácil de encontrar y acceder dentro del EVA. Si el RED es externo, el enlace debe ser claro y funcional.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Peso y carga</b>. Considerar el tamaño de los archivos para no generar problemas de descarga o visualización, especialmente para estudiantes con conexiones a internet limitadas.
      
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.mb-3.mb-lg-0
                figure
                  img(src="@/assets/curso/tema5/15.png")
              .col-lg-7
                h5 Aspectos pedagógicos
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Instrucciones claras</b>. Proporcionar instrucciones precisas sobre cómo y para qué utilizar el RED en el contexto de la actividad de aprendizaje.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Andamiaje (<em>Scaffolding</em>)</b>. Ofrecer el apoyo necesario para que los estudiantes puedan utilizar el RED de manera autónoma y efectiva, especialmente si la herramienta es nueva o compleja.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Rol del docente</b>. El docente debe estar preparado para actuar como facilitador, modelar el uso del RED, y resolver dudas.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.mb-3.mb-lg-0
                figure
                  img(src="@/assets/curso/tema5/16.png")
              .col-lg-7
                h5 Accesibilidad
                p Un aspecto crucial es asegurar que la integración del RED no cree barreras para estudiantes con diversidad funcional. Esto implica considerar desde el diseño del RED hasta su presentación en el EVA, siguiendo pautas de accesibilidad web.
      
      .row.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/17.png", data-aos="zoom-in")
        .col-lg-8.order-lg-1
          p(data-aos="fade-left") La "funcionalidad técnica" de un RED es necesaria, pero no suficiente. Lo que determina su verdadero valor es su "usabilidad pedagógica": cuán fácil y efectivo resulta para docentes y estudiantes, utilizar el RED para lograr objetivos de aprendizaje significativos. 
          p.mb-5 Un RED técnicamente sofisticado puede ser subutilizado o mal utilizado si su propósito pedagógico no es evidente, si es difícil de navegar o si las instrucciones no son claras. Por lo tanto, la fase de implementación va más allá de simplemente "subir un archivo"; requiere una cuidadosa planificación de la experiencia del usuario (tanto docente como estudiante), la provisión de guías claras y, posiblemente, instancias de capacitación. Estos aspectos deben ser anticipados como diseñador curricular, integrando principios de Diseño Centrado en el Usuario (DCU), en el ámbito educativo. 
      
          .bg-color-9.p-4(data-aos="fade-left")
            p.mb-0 La usabilidad pedagógica debe ser un criterio clave en la selección, diseño e integración de RED, tan importante como la calidad del contenido o la innovación tecnológica que pueda ofrecer.
  
      .bg-full-width.border-top.color-primario
        .p-4.p-md-5
          h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
          .row.material-complementario
            .col-12.col-md-6.col-lg-7
              p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://dialnet.unirioja.es/servlet/articulo?codigo=9385151" target="_blank" rel="noopener noreferrer") Chávez, C. T. Q. (2024). Integración de tecnologías de la información y la comunicación en el proceso de enseñanza-aprendizaje de entornos virtuales de aprendizaje. Didasc@ lia: Didáctica y Educación, 15(1), 418-448.

              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://www.scielo.sa.cr/scielo.php?script=sci_arttext&pid=S1409-47032021000100429" target="_blank" rel="noopener noreferrer") Campos Retana, R. (2021). Modelos de integración de la tecnología en la educación de personas que desempeñan funciones ejecutivas y de dirección: el TPACK y el SAMR. Actualidades investigativas en educación, 21(1), 429-456. 


              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://www.youtube.com/watch?v=MjI6leNM3uc&ab_channel=INDEE" target="_blank" rel="noopener noreferrer") GAMIFIKT. (2022, 09 de marzo). Modelo SMAR. [Video] YouTube

                    

            .col-12.col-md-6.col-lg-3.offset-lg-1
              figure
                img(src='@/assets/componentes/material-complementario.svg', alt='')
</template>
