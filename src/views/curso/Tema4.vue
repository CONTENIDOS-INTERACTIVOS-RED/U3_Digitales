<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'4. Publicación y distribución de recursos educativos digitales en plataformas de aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-8
        p(data-aos="fade-left").mb-4 Una vez que un Recurso Educativo Digital (RED), ha sido creado, evaluado y optimizado, el siguiente paso crucial es asegurar que llegue a su audiencia objetivo, de manera efectiva. 
    
        .bg-color-1.p-4(data-aos="fade-left").mb-4
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema4/1.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La #[b publicación y distribución] de RED no se limita a simplemente “colocarlo online”; implica tomar decisiones estratégicas sobre las plataformas adecuadas, los estándares técnicos que facilitarán su uso y reutilización, el licenciamiento que definirá sus condiciones de acceso y modificación, y la aplicación de principios de accesibilidad para garantizar que sea usable por todos. Además, requiere pensar en cómo se difundirá y promocionará para maximizar su alcance e impacto.
    
    
      .col-lg-4
        figure
          img(src="@/assets/curso/tema4/2.png", data-aos="zoom-in")
    


    #t_4_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 4.1] Plataformas de aprendizaje y repositorios de RED
    
    p.mb-5 Existen diversos tipos de plataformas y sistemas donde puede alojar y distribuir sus RED, cada uno con sus propias características, ventajas y limitaciones:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/16.png", alt="").mb-4.mb-lg-0
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Sistemas de Gestión de Aprendizaje (LMS - Learning Management Systems)")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. Moodle, Canvas, Blackboard, Google Classroom, Chamilo, Sakai.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Funcionalidades</b>. Son plataformas robustas diseñadas para administrar, distribuir y controlar actividades de formación online. Permiten organizar contenidos en cursos, gestionar usuarios (estudiantes y docentes), realizar seguimiento del progreso, facilitar la comunicación (foros, mensajería) e integrar herramientas de evaluación.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ventajas para RED</b>. Ofrecen un entorno estructurado y controlado para la distribución de RED a una audiencia específica (ejemplo, estudiantes de un curso). Permiten integrar los RED directamente en secuencias de aprendizaje y realizar seguimiento de su uso.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Limitaciones</b>. Suelen ser entornos cerrados, lo que puede limitar la visibilidad y el acceso a los RED fuera de la comunidad de usuarios registrados. La personalización de la apariencia puede ser limitada.

          .div(titulo="Repositorios educativos")
            p Son bibliotecas digitales diseñadas específicamente para almacenar, preservar y compartir Recursos Educativos Digitales y, por lo general, Recursos Educativos Abiertos (REA).
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Institucionales</b>. Gestionados por universidades u otras organizaciones educativas para sus propios miembros y, a menudo, para el público general (ejemplo, repositorios basados en Dspace o Eprints).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Temáticos o agregadores</b>. Se centran en áreas de conocimiento específicas o agregan RED de múltiples fuentes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. MERLOT (Multimedia Educational Resource for Learning and Online Teaching), OER Commons, Procomún (España), La Referencia (América Latina), Temoa (Tecnológico de Monterrey).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Propósito</b>. Facilitar el descubrimiento, acceso y reutilización de RED de calidad. Suelen contar con sistemas de metadatos para describir los recursos y facilitar su búsqueda.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Cómo buscar y contribuir</b>. Generalmente ofrecen interfaces de búsqueda avanzada. Para contribuir, suelen requerir el registro y la cumplimentación de formularios de metadatos que describen el recurso.
          .div(titulo="Plataformas de contenido específico y MOOCs")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. YouTube (especialmente YouTube Edu), Vimeo (para videos); Khan Academy (microlecciones y ejercicios); Coursera, edX, MiríadaX (plataformas de Cursos Online Masivos y Abiertos - MOOCs, que distribuyen una gran cantidad de RED como parte de sus cursos).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Características</b>. Estas plataformas pueden tener un alcance masivo y estar especializadas en ciertos tipos de contenido (ejemplo, vídeo) o formatos de aprendizaje (ejemplo, cursos cortos). Algunas operan bajo modelos de negocio que pueden influir en cómo se accede o se reutiliza el contenido.
    
    p.mb-5 Criterios para seleccionar la plataforma o repositorio más adecuado:

    .bg-full-width.bg-color-8
      .p-4.p-md-5
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/18.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Tipo de RED
                    p.text-center ¿Es un video, un objeto SCORM, un PDF interactivo, una simulación? Algunas plataformas son más adecuadas para ciertos formatos.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/19.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Audiencia objetivo
                    p.text-center ¿Es para sus propios estudiantes en un curso cerrado (LMS)? ¿O busca un alcance global (repositorio OER, YouTube)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/20.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Objetivos de difusión
                    p.text-center ¿Quiere facilitar la reutilización y adaptación por otros (REA en repositorio)? ¿O principalmente controlar el acceso (LMS)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/21.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Licenciamiento
                    p.text-center ¿La plataforma permite o requiere ciertos tipos de licencias (ejemplo, Creative Commons)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/22.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Funcionalidades de seguimiento
                    p.text-center ¿Necesita rastrear el uso y el progreso de los estudiantes con el RED (LMS con SCORM/xAPI)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/23.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Facilidad de uso y mantenimiento
                    p.text-center ¿Qué tan fácil es subir y gestionar los RED en la plataforma?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/24.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Costos asociados
                    p.text-center Algunas plataformas pueden tener costos de suscripción o alojamiento.
        
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema6/17.png', alt='')
          
    #t_4_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 4.2] Estándares técnicos para la interoperabilidad y seguimiento
    
    p.mb-5 La estandarización técnica es esencial para asegurar que los Recursos Educativos Digitales (RED) puedan ser utilizados, compartidos y evaluados de manera eficaz en distintos entornos virtuales.

    .bg-full-width.bg-color-9.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Estándares técnicos para la interoperabilidad y seguimiento
            p.mb-4(data-aos="fade-right") En el PDF <b>Estándares técnicos para la interoperabilidad y seguimiento</b>, se abordan los principales marcos como SCORM, xAPI y LTI, así como la importancia de los metadatos en la gestión de contenidos digitales. Estos elementos garantizan no solo la compatibilidad entre plataformas, sino también un seguimiento más preciso del aprendizaje y una mejor organización de los recursos disponibles.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_5.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Estándares técnicos para la interoperabilidad y seguimiento.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema6/25.png', alt='')

    #t_4_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 4.3] Licenciamiento de RED: derechos de autor y contenido abierto
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/26.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") Cuando usted crea un RED, automáticamente posee los derechos de autor sobre esa obra (salvo que sea un trabajo por encargo con otras condiciones). Es fundamental que usted decida cómo quiere que otros puedan usar su creación (Chiarani, 2016).
    
        .bg-color-2.p-4(data-aos="fade-left")
          p.mb-0 Conceptos básicos de derechos de autor (Copyright). Otorgan al creador derechos exclusivos sobre la reproducción, distribución, adaptación y comunicación pública de su obra. Por defecto, todas las obras están protegidas por “todos los derechos reservados”, lo que significa que nadie puede usarlas sin permiso explícito del titular.
    
    h2(data-aos="fade-left") Licencias Creative Commons (CC). 
    p.mb-5 Son un conjunto de licencias de derechos de autor estandarizadas y gratuitas que permiten a los creadores compartir sus obras de manera flexible, especificando qué permisos otorgan a otros y bajo qué condiciones. Se basan en cuatro condiciones principales que se pueden combinar:

    div.bg-color-6.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6
          figure
            img(src="@/assets/curso/tema6/27.png", data-aos="zoom-in")
      
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/28.png", alt="").mb-4.mb-lg-0
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="BY (Atribución).")
            p Siempre se debe reconocer la autoría original de la obra. Esta condición está presente en todas las licencias CC.
          .div(titulo="SA (Compartir Igual – Share Alike).")
            p Si se crea una obra derivada (una adaptación o modificación del original), esta debe licenciarse bajo la misma licencia CC (o una compatible) que la obra original.
          .div(titulo="NC (No Comercial – Non-Commercial).")
            p La obra no puede ser utilizada con fines primordialmente comerciales.
          .div(titulo="ND (Sin Obras Derivadas – No Derivatives)")
            p No se permite modificar, transformar o crear obras derivadas a partir del original. Solo se puede copiar y distribuir la obra tal cual.

    p.mb-5 Combinaciones comunes de licencias CC:

    .bg-full-width.bg-color-8
      .p-4.p-md-5
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/30.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY
                    p.text-center La más abierta. Permite cualquier uso (incluso comercial y modificación) siempre que se dé atribución.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/31.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-SA
                    p.text-center Permite cualquier uso, pero las obras derivadas deben compartirse bajo la misma licencia.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/32.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-NC
                    p.text-center Permite uso no comercial, con atribución.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/33.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-NC-SA
                    p.text-center Permite uso no comercial, las obras derivadas deben ser no comerciales y compartirse bajo la misma licencia.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/34.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-ND
                    p.text-center Permite copiar y distribuir (incluso comercialmente), pero no modificar, con atribución.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/35.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-NC-ND
                    p.text-center La más restrictiva de las CC. Permite copiar y distribuir solo para fines no comerciales y sin modificaciones, con atribución.
        
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema6/29.png', alt='')
    
    h2(data-aos="fade-left") ¿Cómo elegir la licencia CC adecuada?
    p.mb-5 Depende de sus objetivos. Si quiere la máxima difusión y reutilización, CC BY es ideal. Si le preocupa el uso comercial o quiere que las adaptaciones también sean abiertas, puede añadir NC o SA.

    .bg-full-width.bg-color-6.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").order-lg-2
                p Implicaciones de usar RED con licencias CC:
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si utiliza un RED creado por otro bajo una licencia CC, debe respetar las condiciones de esa licencia (ejemplo, siempre atribuir, no usar comercialmente si es NC, etc.). 
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 La elección de una licencia para una RED no es una mera formalidad legal; es una declaración sobre su filosofía educativa y su compromiso con el conocimiento compartido y la equidad. Optar por una licencia CC abierta (como CC BY o CC BY-SA) facilita que otros educadores y estudiantes puedan acceder, adaptar, traducir, contextualizar y mejorar su RED. Esto se alinea con los principios del movimiento de Recursos Educativos Abiertos (REA/OER), que promueve el acceso libre y gratuito a materiales de enseñanza, aprendizaje e investigación. 
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Un RED abierto puede tener un impacto mucho mayor y más duradero que uno cerrado, al ser potenciado por una comunidad global. Fomentar el uso de licencias abiertas en la producción de RED puede ser una estrategia institucional clave para promover la innovación, la colaboración y el acceso equitativo al conocimiento. Como futuro diseñador curricular, es vital que usted esté formado para tomar estas decisiones de licenciamiento de manera informada y consciente de sus implicaciones.  <a href="https://unesdoc.unesco.org/ark:/48223/pf0000246687_spa" target="_blank"> (Ver la Declaración de París sobre los REA de la UNESCO, 2012).</a>


                
              .col-lg-4(data-aos="zoom-in").mb-3.mb-lg-0.order-lg-1
                img.img-fluid(src='@/assets/curso/tema6/36.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    #t_4_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 4.4] Principios de accesibilidad web aplicados a RED
    
    p.mb-5 La accesibilidad y la difusión son aspectos fundamentales en la creación y uso de los Recursos Educativos Digitales (RED), ya que garantizan que todos los estudiantes puedan beneficiarse de ellos sin barreras y que su alcance sea amplio y significativo.

    .bg-full-width.bg-color-9.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Principios de accesibilidad web aplicados a RED
            p.mb-4(data-aos="fade-right") En el PDF <b>Principios de accesibilidad web aplicados a RED</b>, se abordan las pautas internacionales de accesibilidad (WCAG), las herramientas de verificación y su relación con el Diseño Universal para el Aprendizaje, así como estrategias clave para promover y diseminar estos recursos. Esta información permite comprender cómo diseñar RED más inclusivos, visibles y con verdadero impacto pedagógico.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_6.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Principios de accesibilidad web aplicados a RED.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema6/37.png', alt='')

    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.



            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://dehesa.unex.es/handle/10662/7052" target="_blank" rel="noopener noreferrer") Sanabria Mesa, A. L., Álvarez Núñez, Q., & Peirats Chacón, J. (2017). Las políticas educativas en la producción y distribución de materiales didácticos digitales. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=ZxZ4RFUPu7E&ab_channel=OpenEducationWeek%28OEWeek%29" target="_blank" rel="noopener noreferrer") Open Education Week (OEWeek). (2013, 12 de marzo). Pilar Saenz - Licencias Creative Commons para recursos educativos, ¿que son? ¿como usarlas?. [Video] YouTube    

       



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema4',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál de las siguientes afirmaciones define mejor la "integración efectiva" de RED en un EVA?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Subir la mayor cantidad posible de archivos digitales a la plataforma.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Utilizar siempre la tecnología más novedosa y sofisticada disponible.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Lograr una sinergia planificada entre el RED, la pedagogía y la tecnología para potenciar el aprendizaje.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Reemplazar todos los materiales impresos por versiones digitales.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              'La evaluación que se realiza durante la interacción del estudiante con el RED para monitorear el aprendizaje y ofrecer retroalimentación se denomina:',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              { id: 'a', texto: 'Evaluación Sumativa', esCorrecta: false },
              { id: 'b', texto: 'Evaluación Diagnóstica', esCorrecta: false },
              { id: 'c', texto: 'Evaluación Formativa', esCorrecta: true },
              { id: 'd', texto: 'Evaluación Institucional', esCorrecta: false },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto: 'El ciclo PDCA es un modelo para:',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'El diseño inicial de un RED desde cero.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'La publicación masiva de RED en repositorios.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'La mejora continua de procesos y productos.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'La evaluación sumativa final de un curso.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Cuál es la función principal de un Sistema de Gestión de Aprendizaje (LMS) en relación con los RED?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Crear automáticamente RED a partir de cualquier documento.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Alojar, distribuir y gestionar el acceso a RED dentro de un curso.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto:
                  'Garantizar que todos los RED sean Recursos Educativos Abiertos.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Traducir automáticamente los RED a múltiples idiomas.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto: 'MERLOT y OER Commons son ejemplos de:',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Sistemas de Gestión de Aprendizaje (LMS).',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Estándares técnicos como SCORM.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Repositorios de Recursos Educativos.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Licencias Creative Commons.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
