<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Valoración cultural de las emociones'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-1.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5 ¿Por qué algunas emociones se celebran mientras otras se silencian?
              p.mb-0 La manera en que las emociones se expresan, se entienden y se valoran no es universal: cada cultura moldea el mundo emocional de las personas de formas únicas y sorprendentes. Comprender esta valoración cultural resulta esencial para acompañar el desarrollo emocional de los niños y las niñas desde una mirada respetuosa e inclusiva.
        p(data-aos="fade-left") A continuación, se invita a explorar cómo la cultura enseña a sentir, a expresar y a interpretar las emociones, y por qué reconocer esta influencia es clave en la educación infantil.

    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] Entendimiento de las emociones desde un enfoque cultural

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/3.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        h5 ¿Cómo las emociones, además de sentirse, también se aprenden a lo largo de la vida?
        p(data-aos="fade-left") Esta pregunta invita a reconocer una dimensión esencial en la comprensión de las emociones: su construcción cultural.
    
        .bg-color-8.p-5.mb-3(data-aos="fade-left")
          p.mb-0 Cuando se habla del entendimiento de las emociones desde un enfoque cultural, se aborda la idea de que las emociones no emergen en un vacío biológico o personal. Cada emoción sentida, expresada o incluso reprimida, se encuentra profundamente impregnada por el contexto cultural en el que cada persona ha crecido.
        p Así, la cultura no solo enseña qué sentir, sino también cómo, cuándo y ante quién es legítimo expresarlo (Gondim y Estramiana, 2010):

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/4.png")
            .col-lg-7
              p Desde la infancia, a través de las relaciones primarias con la familia, la escuela y la comunidad, se internalizan normas culturales sobre las emociones. De manera casi imperceptible, se aprende que hay emociones "buenas" que deben mostrarse y otras que es preferible ocultar. Por ejemplo, en algunas culturas latinoamericanas, es común que se fomente la expresión abierta del afecto y la alegría, reforzando un sentido de cercanía y calidez. En contraste, otras culturas pueden enfatizar la importancia de la moderación emocional, valorando la discreción como un signo de madurez y respeto social (Medina y Vizcarra, 2009).
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/5.png")
            .col-lg-7
              p Comprender esta influencia cultural permite reconocer que las emociones no son universales en su manifestación. Aunque todos los seres humanos experimentan sensaciones como la felicidad, la tristeza o el miedo, la manera en que se interpretan y se expresan varía notablemente. En sociedades colectivistas, por ejemplo, se prioriza la armonía del grupo sobre la expresión emocional individual, mientras que en culturas más individualistas se valora la autenticidad y la autoexpresión, incluso si esto implica mostrar emociones negativas.
    
    p.mb-4 Autores como Markus y Kitayama (1991), sostienen que la cultura moldea la manera en que se configura el "yo" emocional. En su propuesta, explican que:

    .bg-full-width.bg-fondo-1.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-10
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema2/6.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="3%" y="18.5%" numero="+")
                h5 Yo interdependiente
                p El "yo" interdependiente, propio de culturas colectivistas, enseña a sentir emociones que refuercen los vínculos sociales.
    
              .bg-color-white.box-shadow.p-3(x="97%" y="60.5%" numero="+")
                h5 Yo independiente
                p El "yo" independiente, característico de culturas individualistas, favorece emociones que sostienen la autonomía personal.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/7.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") A su vez, Mesquita (2001) argumenta que las emociones son prácticas culturales aprendidas y transmitidas socialmente. No se experimenta simplemente una emoción, sino que se participa en un modo culturalmente situado en el sentir.
    
        .bg-color-4.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/8.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Esta comprensión invita a una reflexión personal: ¿de qué manera la cultura en que se creció ha definido el modo en que se viven y expresan las emociones hoy en día?
        p Realizar este ejercicio de introspección resulta esencial para quienes se forman como educadores infantiles. No solo permitirá analizar el impacto de las emociones en la propia historia de vida, sino también asumir una postura más empática y crítica frente a las emociones de los niños y las niñas que se acompañarán en su desarrollo.
    

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/9.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") Desde esta mirada, no se juzga la expresión emocional como correcta o incorrecta, sino que se comprende como el reflejo de un aprendizaje cultural específico. Esta perspectiva resulta vital para promover entornos educativos más inclusivos y respetuosos, donde cada niño y cada niña pueda expresarse de manera auténtica, sabiendo que su mundo emocional es validado y acogido.
    
        .bg-color-8.p-4.mb-3(data-aos="fade-left")
          p.mb-0 En definitiva, analizar las emociones desde un enfoque cultural amplía la comprensión de los procesos socioemocionales en la infancia. Permite ver más allá de las conductas visibles y entender que cada expresión emocional es el eco de una cultura que la ha moldeado, un puente entre el mundo interior del niño o la niña y su contexto social.
        p Por ello, al trabajar con la infancia, se hace indispensable integrar esta conciencia cultural en las prácticas educativas, reconociendo y valorando la diversidad emocional como una riqueza que enriquece los vínculos y favorece un desarrollo socioemocional más saludable y pleno.

    #t_2_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.2] Manifestaciones emocionales en diferentes contextos sociales

    p.mb-4 La expresión de las emociones está profundamente influida por los entornos en los que se desarrolla la vida social, y su comprensión resulta clave para el acompañamiento afectivo en la infancia.

    .bg-full-width.bg-color-6.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Manifestaciones emocionales en diferentes contextos sociales
            p.mb-4(data-aos="fade-right") En el PDF <b>Manifestaciones emocionales en diferentes contextos sociales</b>, se explora cómo las normas culturales, familiares, escolares y de género modelan la manera en que se perciben y expresan las emociones. A través de una reflexión crítica, se invita a reconocer estas dinámicas para construir espacios educativos más empáticos, respetuosos y emocionalmente conscientes.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Manifestaciones emocionales en diferentes contextos sociales.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/10.png', alt='')

    #t_2_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.3] Impacto de la cultura en la regulación y expresión de las emociones

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema2/11.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-4.p-5.mb-3(data-aos="fade-left")
          h5 ¿Cómo las normas y valores culturales influyen en la forma en que las personas, especialmente los niños, regulan y expresan sus emociones? 
          p.mb-0 Las emociones, aunque universales, no se experimentan ni se gestionan de la misma manera en todas las culturas. Según Rivas (2015), la cultura es un factor determinante que moldea no solo cómo se sienten las emociones, sino también cómo se interpretan, regulan y expresan. 
        p Este proceso comienza desde la infancia, cuando los niños aprenden, casi sin darse cuenta, cómo deben comportarse frente a las emociones, siguiendo las pautas que su entorno cultural les ofrece. A medida que los niños crecen, estos aprendizajes culturales tienen un impacto duradero en su desarrollo emocional y social.

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/12.png", alt="").mb-4.mb-lg-0
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Regulación emocional")
            p Desde un enfoque cultural, la regulación emocional se refiere a la capacidad de los individuos para manejar y controlar sus emociones, de acuerdo con las expectativas sociales y culturales que les rodean. En este contexto, los niños aprenden que ciertas emociones son aceptables o deseables en determinadas situaciones, mientras que otras pueden ser consideradas inapropiadas o inadecuadas (Condori, 2023). Las normas culturales dictan, por ejemplo, que la tristeza puede ser vista con simpatía y apoyo en un contexto, pero en otro puede ser percibida como una debilidad que debe ser superada rápidamente. Este aprendizaje cultural influye directamente en cómo los niños aprenden a gestionar sus emociones, y esta influencia es fundamental en su desarrollo emocional a lo largo de su vida.
    
          .div(titulo="Expresión de las emociones")
            p La expresión de las emociones también está profundamente influenciada por las normas culturales. En algunas culturas, la apertura emocional es vista como una virtud, un medio de conectar con los demás y de expresar los sentimientos de forma clara y directa. En otras, el control emocional y la moderación son aspectos esenciales para mantener la armonía social, por lo que se espera que los niños aprendan a reprimir ciertas emociones, como el enojo o la frustración, para no interrumpir la paz de la comunidad. Este tipo de regulaciones emocionales varían no solo entre culturas, sino también entre diferentes contextos sociales dentro de la misma cultura, lo que muestra la flexibilidad de las normas emocionales que los niños internalizan.
    
          .div(titulo="Impacto cultural")
            p El impacto cultural en la regulación y expresión emocional, también está relacionado con las formas en que los niños aprenden a percibir las emociones de los demás. Si un niño crece en una cultura en la que la empatía es valorada y enseñada activamente, es más probable que aprenda a identificar las emociones en los demás y a responder de manera apropiada. Sin embargo, en culturas donde se prioriza la autodependencia y el control personal sobre las emociones, los niños pueden tener menos oportunidades de practicar la empatía, lo que afecta su capacidad para comprender y responder adecuadamente a las emociones ajenas. Esto tiene consecuencias significativas no solo en el ámbito social del niño, sino también en su capacidad para formar relaciones saludables y resolver conflictos de manera eficaz.
    
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema2/13.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        AcordionA(tipo="b")
          .div(titulo="Contexto familiar")
            p También desempeña un papel esencial en este proceso de aprendizaje emocional. La familia, como primera fuente de socialización, es el lugar donde los niños reciben sus primeras enseñanzas sobre cómo manejar sus emociones. El estilo de crianza, las expectativas culturales dentro de la familia y la manera en que los padres o cuidadores manejan sus propias emociones sirven de modelo para los niños. Si un niño observa que sus cuidadores gestionan sus emociones de manera efectiva, es probable que adquiera habilidades emocionales saludables. Por el contrario, si los padres reprimen o invalidan las emociones del niño, este podría desarrollar dificultades para identificar y gestionar sus propias emociones más adelante.
    
          .div(titulo="Valoran las emociones")
            p La cultura influye también en la manera en que se valoran las emociones. En algunas culturas, las emociones se consideran una parte esencial del ser humano que debe ser entendida y respetada, mientras que en otras, las emociones son vistas como algo que debe ser controlado o incluso suprimido para lograr un comportamiento adecuado dentro de la sociedad. En las culturas donde el control emocional es muy valorado, por ejemplo, el niño puede aprender que no debe mostrar tristeza o frustración abiertamente, puesto que estas emociones son percibidas como signos de debilidad o falta de autocontrol. Esto puede afectar no solo su bienestar emocional, sino también su capacidad para formar relaciones interpersonales saludables.
    
          .div(titulo="Contexto educativo")
            p La importancia del contexto educativo, también es clave. Las instituciones educativas, como escuelas y jardines infantiles, ofrecen un espacio en el que los niños tienen la oportunidad de desarrollar aún más su capacidad para manejar y expresar sus emociones. Los educadores, al igual que los padres, desempeñan un papel crucial en el aprendizaje emocional de los niños. Si las escuelas promueven un enfoque de aceptación y comprensión de las emociones, los niños aprenderán a expresar sus sentimientos de manera adecuada y a relacionarse con los demás de forma empática. Sin embargo, en ambientes donde las emociones se minimizan o son vistas como distracciones del aprendizaje, los niños pueden sentirse inseguros al expresar lo que sienten, lo que puede generar dificultades en su desarrollo emocional.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/14.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-1.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/15.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El impacto cultural en la regulación y expresión de las emociones, no solo afecta a la infancia, sino que tiene repercusiones a lo largo de toda la vida. Las emociones aprendidas en la niñez y las formas en que se gestionan y comunican son esenciales para el bienestar emocional y social de los individuos. Las personas que crecen en culturas que valoran la regulación emocional saludable, la empatía y la expresión equilibrada de las emociones son más propensas a desarrollar relaciones interpersonales positivas, a manejar el estrés de manera efectiva y a tener un sentido de autoestima saludable.
        p(data-aos="fade-left") Tras explorar cómo la cultura influye en la regulación y expresión de las emociones, es esencial entender cómo estas emociones impactan no solo en el bienestar personal, sino también en nuestras relaciones con los demás. En este sentido, la importancia de las emociones en el cuidado de sí mismo y de los otros se convierte en un aspecto clave para el desarrollo socioemocional, dado que nos permite construir relaciones más saludables y una mejor conexión con nuestro entorno. Ahora, profundizaremos en cómo las emociones juegan un papel crucial en este proceso de cuidado.
    
        




    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/47999 " target="_blank" rel="noopener noreferrer") Rimé, B. (2011). La compartición social de las emociones: ( ed.). Editorial Desclée de Brouwer. 



            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/113161 " target="_blank" rel="noopener noreferrer") Smith, M. (2019). Las emociones de los estudiantes y su impacto en el aprendizaje: ( ed.). Narcea Ediciones. 


            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://revistaseug.ugr.es/index.php/profesorado/article/view/8675 " target="_blank" rel="noopener noreferrer") González, E. T., Vacas, E. M. C., González, M. D. C. T., & Lorenzo, C. M. (2020). El papel de las emociones en el aula de educación infantil. Profesorado, revista de currículum y formación del profesorado, 24(1), 226-244. 


            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://papers.uab.cat/article/view/v87-rodriguez " target="_blank" rel="noopener noreferrer") Salazar, T. R. (2008). El valor de las emociones para el análisis cultural. Papers. Revista de Sociología, 87, 145-159. 


            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://dialnet.unirioja.es/servlet/articulo?codigo=4298516 " target="_blank" rel="noopener noreferrer") Rasco, J. F. A. (2012). Cuerpo, emociones, cultura. RIFOP: Revista interuniversitaria de formación del profesorado: continuación de la antigua Revista de Escuelas Normales, (74), 53-74. 


            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://repositori.uji.es/server/api/core/bitstreams/a67d007d-7627-41db-8332-cc246ae153e4/content " target="_blank" rel="noopener noreferrer") OLUCHA, S. R., ALCALÁ, F. R. Q., IVARS, M. B., FLICH, R. S., & VERCHILI, M. C. P. Influencia cultural y universalidad en la expresión de las emociones. 



            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=j9jBqBBg7TM " target="_blank" rel="noopener noreferrer") Psicólogos Pozuelo. (2018, 24 de octubre). Presentación oficial de "La danza de las emociones familiares" escrito por Mercedes Bermejo [Video]. YouTube. 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=qsNCdrlHVpY " target="_blank" rel="noopener noreferrer") Ministerio de Educación Nacional. (2023, 14 de febrero). Las emociones están en todo en toda la vida humana y en la escuela [Video]. YouTube. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=35xO1IkEjVk " target="_blank" rel="noopener noreferrer") Universidad Continental. (2021, 21 de abril). Naturaleza de las Emociones [Video]. YouTube. 

 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=9G2G34apXj4 " target="_blank" rel="noopener noreferrer") Siente, Piensa y Actúa. (2018, 30 de noviembre). Aprendiendo sobre mis emociones - Conciencia y Regulación emocional [Video]. YouTube. 

 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
