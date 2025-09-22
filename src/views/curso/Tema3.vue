<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3.	Importancia de las emociones en el cuidado de sí y de los otros'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema3/1.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        h5 ¿Cómo las emociones pueden influir en el bienestar tanto personal como en las relaciones con los demás? 
        p.mb-5(data-aos="fade-left") Las emociones son mucho más que simples reacciones: son una parte esencial de nuestra interacción con el mundo. En el ámbito de la educación infantil, entender la importancia de las emociones en el cuidado de sí mismo y de los otros puede marcar la diferencia. 
    
        .bg-color-4.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Este tema invita a explorar cómo el reconocimiento y la gestión emocional no solo benefician al individuo, sino que también son claves para fomentar relaciones saludables, empáticas y respetuosas. Descubramos cómo las emociones impactan directamente en el desarrollo y en la conexión humana ¡Vamos!
    
    
    #t_3_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.1] Autoconciencia emocional y autocuidado

    p.mb-4 La autoconciencia emocional y el autocuidado son competencias esenciales en el desarrollo integral de niñas y niños, ya que les permiten comprender sus emociones y actuar con mayor equilibrio frente a los desafíos cotidianos.

    .bg-full-width.bg-color-6.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Autoconciencia emocional y autocuidado
            p.mb-4(data-aos="fade-right") En el PDF <b>Autoconciencia emocional y autocuidado</b>, se analizan los elementos que conforman la capacidad de autorreflexión emocional, así como las estrategias que favorecen el bienestar personal desde la infancia. Este enfoque contribuye a formar individuos emocionalmente responsables, con habilidades para construir relaciones sanas y entornos afectivos seguros.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_3.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Autoconciencia emocional y autocuidado.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/3.png', alt='')

    #t_3_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.2] Empatía como base para el cuidado emocional de los otros

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/4.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        h5 ¿Cómo puede la empatía transformar la manera en que nos relacionamos y cuidamos de los demás, especialmente cuando se trata de las emociones?
        p(data-aos="fade-left") Según Gómez (2016), la empatía es una capacidad fundamental en la interacción humana y es, sin lugar a dudas, un pilar esencial en el cuidado emocional de los otros. Cuando se trata de la infancia, esta habilidad no solo promueve una mejor comprensión de las emociones ajenas, sino que también facilita la creación de vínculos más profundos y saludables. 
    
        .bg-color-3.p-5.mb-3(data-aos="fade-left")
          p.mb-0 En el contexto de la educación infantil, la empatía se convierte en una herramienta indispensable para los futuros educadores, debido a que les permite abordar las necesidades emocionales de los niños de manera efectiva y respetuosa (López, Hernández y Caro, 2021). 
        p Por eso, resulta crucial reflexionar sobre cómo la empatía no solo nos permite comprender las emociones de los demás, sino que también juega un papel esencial en el apoyo emocional que brindamos, tanto a los niños como a los demás miembros de la comunidad educativa.
    
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/5.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="b")
          .div(titulo="La empatía en el desarrollo infantil: un pilar de relación y cuidado emocional 1")
            p Desde una edad temprana, los niños empiezan a desarrollar la capacidad de entender y compartir los sentimientos de las personas que los rodean. Este proceso, sin embargo, no se da de manera inmediata ni aislada; depende de las interacciones con los cuidadores y el ambiente que los rodea. Los niños aprenden a reconocer las emociones a través de la observación de expresiones faciales, el lenguaje corporal y las respuestas emocionales que reciben de los adultos cercanos. Así, el papel de los educadores y cuidadores en el desarrollo de la empatía es esencial: modelar conductas empáticas, validar las emociones de los niños y ofrecer respuestas emocionales adecuadas son acciones clave para fomentar la empatía en los más pequeños.
    
          .div(titulo="La empatía en el desarrollo infantil: un pilar de relación y cuidado emocional 2")
            p La empatía, como base para el cuidado emocional de los otros, se fundamenta en la capacidad de no solo reconocer una emoción, sino también comprender su origen y la experiencia que la acompaña. Es decir, no basta con notar que alguien está triste, sino que se trata de entender las razones detrás de esa tristeza y ofrecer una respuesta empática y reconfortante. En el contexto infantil, esto puede traducirse en validar el dolor de un niño al perder su juguete, por ejemplo, y acompañarlo en ese proceso de tristeza. Al hacerlo, no solo se muestra comprensión, sino que se está enseñando al niño a identificar y expresar sus propias emociones de manera saludable. Este tipo de interacción fortalece el vínculo afectivo y establece un modelo de comportamiento que los niños tenderán a replicar.
    
          .div(titulo="La empatía: un ciclo de apoyo emocional mutuo 1")
            p El impacto de la empatía no se limita al individuo que recibe el cuidado emocional, sino que también genera un ciclo positivo en el que tanto el que da como el que recibe el apoyo emocional se benefician. Cuando un niño recibe un cuidado empático, se siente validado en su experiencia emocional, lo que le permite desarrollar una mayor seguridad emocional y, a su vez, una mayor capacidad para empatizar con los demás. Este ciclo de empatía contribuye al bienestar emocional de todos los involucrados y es clave para la creación de un ambiente afectivo positivo y respetuoso.
            p Además, la empatía facilita el aprendizaje de habilidades socioemocionales cruciales para la vida cotidiana, como la resolución de conflictos, la cooperación y la comunicación efectiva. Los niños que aprenden a reconocer las emociones de los demás y a responder de manera apropiada desarrollan competencias sociales que les permitirán establecer relaciones más saludables y armónicas a lo largo de su vida.

    
          .div(titulo="La empatía: un ciclo de apoyo emocional mutuo 2")
            p En el ámbito educativo, fomentar la empatía también contribuye a la creación de un ambiente inclusivo y equitativo, donde todos los niños se sienten escuchados y respetados, independientemente de sus diferencias. Los niños que experimentan la empatía en su educación no solo aprenden a ser más sensibles y comprensivos, sino que también desarrollan un sentido de comunidad, lo que favorece la convivencia y la cooperación en el aula.
          .div(titulo="El rol de los educadores en el fomento de la empatía")
            p Para los futuros profesionales de la educación infantil, la enseñanza de la empatía es un componente esencial en la formación de una práctica pedagógica basada en el cuidado emocional. Como educadores, no solo es importante que comprendan la teoría detrás de las emociones, sino que también sean capaces de aplicar esos conocimientos en su interacción diaria con los niños. Esto implica ser modelos de empatía, ofrecer respuestas emocionales adecuadas y enseñar a los niños a reconocer, expresar y gestionar sus emociones de manera saludable.
    
    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Además, el fomento de la empatía también pasa por la creación de un entorno que favorezca la expresión emocional y el respeto hacia las emociones de los demás. Esto se logra a través de actividades que promuevan el diálogo emocional, la resolución pacífica de conflictos y la construcción de relaciones interpersonales positivas dentro del aula. De esta forma, los educadores contribuyen a que los niños no solo aprendan a identificar sus propias emociones, sino que también desarrollen la capacidad de ponerse en el lugar de los demás, favoreciendo la convivencia y el cuidado mutuo.
    
    #t_3_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.3] La emocionalidad como eje fundamental de las relaciones educativas
    
    .bg-full-width.bg-color-5
      .p-4.p-md-5
        .row.mb-5
          .col-lg-4.order-lg-2.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema3/7.png", data-aos="zoom-in")
          .col-lg-8.order-lg-1
            .bg-color-1.p-5.mb-3(data-aos="fade-left")
              h5 ¿Qué papel juegan las emociones en el proceso educativo de un niño?
              p.mb-0 Desde el momento en que un niño llega al mundo, las emociones juegan un papel esencial en su desarrollo y aprendizaje. Las emociones no son solo una respuesta reactiva ante estímulos, sino que son una fuerza poderosa que impacta profundamente en cómo los niños se relacionan con el mundo que los rodea. En el ámbito educativo, las emociones son el eje central que guía tanto las interacciones como la disposición para aprender. Es imposible separar el aprendizaje de las emociones, dado que estas son los motores que mueven la atención, la memoria, la motivación y las interacciones sociales, elementos esenciales en el proceso de enseñanza-aprendizaje.
            p(data-aos="fade-left") A medida que los niños crecen, sus emociones se convierten en el puente entre su mundo interno y el entorno social. La forma en que un niño se siente en un contexto educativo influye directamente en cómo percibe la escuela, sus compañeros y sus maestros:

        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-4.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema3/8.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center 01
                p.mb-0 Si el niño experimenta seguridad emocional y apoyo, será más propenso a involucrarse activamente en el proceso educativo, a participar con confianza y a compartir sus ideas y sentimientos. 
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema3/9.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center 02
                p.mb-0 Un niño que se siente comprendido y validado emocionalmente por su entorno será capaz de afrontar los retos académicos y sociales con una actitud positiva y constructiva. 
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema3/10.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center 03
                p.mb-0 Sin embargo, cuando el entorno educativo no favorece la expresión y gestión adecuada de las emociones, pueden surgir sentimientos de ansiedad, frustración o desconexión, que impactan negativamente en el aprendizaje.

    p.mb-4 El vínculo emocional entre el educador y el niño es crucial en la construcción de una experiencia educativa exitosa:

    
    TabsC.color-primario.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Relación empática" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Relación empática
            p Un maestro que logra establecer una relación empática con el estudiante tiene el poder de transformar el ambiente de aprendizaje, creando un espacio donde el niño se sienta seguro para expresarse, preguntar y explorar. La empatía no solo se refiere a entender las emociones del otro, sino también a validarlas, a ofrecer respuestas adecuadas y a guiar al niño a comprender sus propios sentimientos. Este tipo de relación empática facilita el aprendizaje emocional y social, puesto que el niño aprende a reconocer, gestionar y expresar sus emociones de manera adecuada, lo cual es fundamental para su desarrollo integral.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/11.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Emocionalidad" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Emocionalidad
            p La emocionalidad también influye directamente en la manera en que los niños interactúan con sus compañeros y con los adultos en su entorno. Las emociones positivas, como la alegría, el entusiasmo y la satisfacción, fomentan relaciones de cooperación y empatía entre los niños, creando un ambiente social saludable donde el respeto y la comprensión mutua son valores centrales. Las emociones negativas, como la tristeza o la ira, si no se gestionan adecuadamente, pueden generar conflictos, malentendidos o rechazo entre los niños, afectando el clima social del aula. Así, el manejo adecuado de las emociones en el contexto educativo no solo favorece el bienestar individual, sino que también fortalece la cohesión social y el sentido de comunidad dentro del aula.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/12.png', alt='')
    
    .bg-full-width.bg-color-5
      .p-4.p-md-5
        p.mb-4 Es importante reconocer que las emociones no son un obstáculo para el aprendizaje, sino que son una herramienta poderosa para fortalecer las relaciones interpersonales y enriquecer el proceso educativo:

        div.row.justify-content-center.align-items-stretch
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/13.svg" alt="" style="width: 90px")
              h5.text-center 01
              p.mb-0.text-center Cuando las emociones se validan y se gestionan de manera adecuada, se crea un entorno donde el aprendizaje fluye de manera natural y armoniosa.
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/14.svg" alt="" style="width: 90px")
              h5.text-center 02
              p.mb-0.text-center Los niños, al sentirse comprendidos y apoyados emocionalmente, se sienten más motivados y dispuestos a aprender, porque perciben el aula como un espacio seguro y estimulante..
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/15.svg" alt="" style="width: 90px")
              h5.text-center 03
              p.mb-0.text-center En cambio, si las emociones son ignoradas o reprimidas, los niños pueden experimentar sentimientos de inseguridad, ansiedad o miedo que dificultan su capacidad para aprender y relacionarse.
    
    .bg-full-width.bg-color-2
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 La creación de un ambiente emocionalmente seguro en el aula es fundamental para promover el bienestar de los niños y su desarrollo académico. Un entorno donde los niños se sienten aceptados y valorados, donde sus emociones son comprendidas y respetadas, les permite desarrollar una autoestima sólida y una mayor confianza en sí mismos. Además, esta seguridad emocional facilita el proceso de aprendizaje, debido a que los niños pueden concentrarse en las actividades académicas sin estar distraídos por emociones no gestionadas. Los educadores juegan un papel clave en este proceso, porque son ellos quienes deben modelar conductas empáticas, ofrecer respuestas emocionales adecuadas y proporcionar apoyo constante para ayudar a los niños a regular sus emociones.
    
      
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
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/56274 " target="_blank" rel="noopener noreferrer") Cabero Jounou, M. (2011). El benestar emocional: ( ed.). Editorial UOC. 



            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.murciaeduca.es/cpjaracarrillo/sitio/upload/Inteligencia_Emocional_Infantil_y_Juvenil._Daniel_Goleman.pdf" target="_blank" rel="noopener noreferrer") Lantieri, L., & Goleman, D. (2016). Inteligencia emocional infantil y juvenil: ejercicios para cultivar la fortaleza interior en niños y jóvenes. Aguilar.  


            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://dialnet.unirioja.es/descarga/articulo/5763104.pdf " target="_blank" rel="noopener noreferrer") Chauvie, P. (2015). Empatía: Efectos de los vínculos primarios. Trabajo de Grado, Universidad de la república, facultad de psicología, Montevideo, Uruguay. 



            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=_tsXLKutClY" target="_blank" rel="noopener noreferrer") PsicoSocial🧠. (2020, 31 de julio). Inteligencia emocional- psicología de las emociones (2021) [Video]. YouTube.  

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=25MGZ7EzYmE " target="_blank" rel="noopener noreferrer") Emoconciencia. (2018, 13 de febrero). Conciencia Emocional [Video]. YouTube. 
 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=5_gsFW0zxRQ " target="_blank" rel="noopener noreferrer") Clínica Fuensalud. (2022, 18 de julio). ¿Qué es la empatía? [Video]. YouTube. 





          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Taller Subjetividad del Maestro',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál es el papel de las emociones en la infancia, según el contenido del taller?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Deben ser controladas para evitar distracciones en el aprendizaje.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Se desarrollan de forma espontánea sin necesidad de acompañamiento.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Son una herramienta educativa clave que moldea la socialización y el desarrollo integral.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Son reacciones pasajeras sin impacto en la vida futura del niño o niña.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              'Según el contenido del taller, ¿qué papel cumple la empatía en el desarrollo socioemocional de los niños y niñas?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Facilita la comprensión y validación de las emociones de los demás, fortaleciendo vínculos. ',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto:
                  'Favorece el distanciamiento emocional entre pares para lograr independencia.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Permite que los niños desarrollen autonomía sin necesidad de apoyo afectivo.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Reduce la necesidad de expresar emociones en contextos escolares.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Qué caracteriza un vínculo afectivo seguro en la infancia?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Se basa exclusivamente en el cumplimiento de normas y rutinas.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Proporciona al niño seguridad emocional, apoyo y bienestar, fortaleciendo su autoestima.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Depende del grado de autonomía alcanzado por el niño.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Surge cuando el niño evita apegos para formar independencia emocional.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Cómo influye la cultura en la regulación emocional infantil según el documento?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'No influye, ya que las emociones son universales y biológicas.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Establece las emociones que deben ser reprimidas durante la adolescencia únicamente.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Determina las capacidades cognitivas necesarias para expresar emociones.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Define qué emociones pueden o no ser expresadas y en qué contextos.',
                esCorrecta: true,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué se entiende por autoconciencia emocional según Goleman (2010)?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'La capacidad de reconocer las emociones de los demás en contextos escolares.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Un proceso de expresión libre de emociones sin restricción cultural.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'La habilidad de observar y comprender el mundo emocional propio, reconociendo fortalezas y debilidades.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'El desarrollo exclusivo de emociones positivas para evitar conflictos interpersonales.',
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
