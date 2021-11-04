<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 3
      h1 Grupo de planificación del proyecto

    .row.mt-5.p-5.bg-amarillo-claro.rounded-15(data-aos="fade-right")
      .col-12.col-lg-7
        p Este grupo es el encargado de la estructuración de una serie de acciones que se llevan a cabo para cumplir los objetivos del proyecto. Debe anticiparse a eventos que pueden representar una amenaza u oportunidad. De ese modo, busca reducir los impactos negativos de dichas contingencias e impulsar los positivos. 
        p.mt-3 En este tema del componente, se abordan los elementos más relevantes para planificar el proyecto. Por lo que, en esta fase del proyecto, se establece un plan, contemplando los alcances, recursos y todo lo necesario para que se dé el cumplimiento conforme a los objetivos y requerimientos de las partes interesadas.
      .col-lg-5.d-none.d-lg-block.px-4.align-self-center
        figure
          img(src="@/assets/template/tema-3-1.svg", alt="Texto que describa la imagen")
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_1.h2 3.1  Plan de gestión del alcance del proyecto 
    figure.mt-4(data-aos="flip-up")
      img(src="@/assets/template/tema-3-2.png", alt="Texto que describa la imagen")
    p.mt-5 En este proceso, se describe de forma detallada el proyecto y producto o servicio final esperado. Además, se identifican las necesidades y requerimientos de las partes interesadas y se subdividen los entregables del proyecto y el trabajo requerido para producirlos. Sus componentes son:
    .row.mt-5.text-center.text-white      
      .col-sm-6.col-lg-4.p-1.text-center
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3.d-flex           
              .row.align-self-center   
                figure
                  img(src="@/assets/template/tema-3-3.svg", alt="Texto que describa la imagen").px-5.px-sm-3.px-xl-4.w-50.margin-0-auto.px-3
                .h4.mt-3.px-5.px-sm-3 Requerimientos de las partes interesadas 
            .tarjeta-flip__contenido.p-3.bg-azul-claro.d-flex
              .row.pt-4.align-self-center    
                .h4.pt-4.px-4 Requerimientos de las partes interesadas 
                p.mt-3.pb-4.pb-xl-5.mb-4.px-5 Identificación de las necesidades de cada una de las partes interesadas.
      .col-sm-6.col-lg-4.p-1
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor.text-center
            .tarjeta-flip__img.p-3.d-flex           
              .row.align-self-center   
                figure
                  img(src="@/assets/template/tema-3-4.svg", alt="Texto que describa la imagen").px-5.px-sm-3.px-xl-4.w-50.margin-0-auto.px-3
                .h4.mt-3.px-5.px-sm-3 Definición del alcance
            .tarjeta-flip__contenido.p-3.bg-azul-claro.d-flex
              .row.pt-4.align-self-center    
                .h4.pt-4.px-4.text-center Definición del alcance 
                ul.lista-ul.acento-contenido.mt-3.mb-4.px-5.text-left
                  li 
                    i.fas.fa-angle-right
                    | Descripción detallada del proyecto.
                  li.mt-1 
                    i.fas.fa-angle-right
                    | Descripción del producto final del proyecto.
      .col-sm-6.col-lg-4.offset-sm-3.offset-lg-0.p-1.text-center
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3.d-flex           
              .row.align-self-center   
                figure
                  img(src="@/assets/template/tema-3-5.svg", alt="Texto que describa la imagen").px-5.px-sm-3.px-xl-4.w-50.margin-0-auto.px-3
                .h4.mt-3.px-5.px-sm-3 Estructura desagregada del trabajo (EDT) 
            .tarjeta-flip__contenido.p-3.bg-azul-claro.d-flex
              .row.pt-4.align-self-center    
                .h4.pt-4.px-4 Estructura desagregada del trabajo (EDT) 
                ul.lista-ul.acento-contenido.mt-3.mb-4.px-5.text-left
                  li 
                    i.fas.fa-angle-right
                    | Subdivisión de entregables del proyecto y el trabajo requerido para producirlo.
                  li.mt-1 
                    i.fas.fa-angle-right
                    | Agrupación en una estructura jerárquica que representa el alcance del proyecto.
    separador.mt-3
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_2.h2 3.2  Plan de gestión del cronograma del proyecto
    .row.mt-5
      .col-4.col-lg-2.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-6.svg", alt="Texto que describa la imagen").px-4.floating
      .col-12.col-lg-10
        p El cronograma es una herramienta esencial para elaborar calendarios de trabajo o actividades. Es uno de los componentes más importantes dentro de la fase de planificación del proyecto, ya que permite establecer todas las actividades y tareas necesarias para cumplir el plan de conformidad con el tiempo y los recursos estipulados.
        p.mt-3 A continuación, se presentan los componentes que integran la planificación del cronograma de un proyecto:
    SlyderB.mt-5(:datos="datosSlyder")(data-aos="slide-right")
    .row.mt-5
      .col-4.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-11.svg", alt="Texto que describa la imagen").margin-0-auto.floating
      .col-12.col-lg-8.align-self-center
        p La gestión del cronograma abarca su planificación, la definición, secuenciamiento y estimación de la duración de las actividades que lo componen; su desarrollo, y, finalmente, el control del mismo durante la ejecución del proyecto.
        p.mt-3 Para lograr su gestión de forma exitosa, se debe determinar:
        ul.lista-ul.mt-3.acento-contenido
          li 
            i.fas.fa-angle-right
            | Las métricas de desempeño. 
          li.mt-2 
            i.fas.fa-angle-right
            | Cómo y cuándo se recopilarán los datos para evaluar el desempeño.
          li.mt-2 
            i.fas.fa-angle-right
            | Cómo se emplearán los datos para mantener el proyecto encaminado.
          li.mt-2 
            i.fas.fa-angle-right
            | Qué se hará cuando se produzcan variaciones.
    separador.mt-3
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_3.h2  3.3  Plan de gestión de costos del proyecto 
    .row.mt-5
      .col-4.col-lg-2.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-12.svg", alt="Texto que describa la imagen").px-4.floating
      .col-12.col-lg-10
        p Se refiere a los procesos involucrados en estimar, presupuestar y controlar los costos de modo que se complete el proyecto dentro del presupuesto aprobado. Debe tener en cuenta los requisitos de las partes interesadas para la obtención de los costos, ya que los diversos interesados medirán los costos del proyecto de diferentes maneras y en tiempos diferentes. Identificar los costos del proyecto y planificar su gestión es de gran importancia, ya que sin este componente no se podrá poner en marcha el proyecto. Observe:
    
    .row.justify-content-center(data-aos="fade-down").mt-5.text-white
      .col-10.col-md-6
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.rounded-15.box-shadow.px-0
            figure
              img(src="@/assets/template/tema-3-13.png", alt="Texto que describa la imagen")
            .text.p-lg-3.p-4
              .row.text-center.px-1.pt-1.mt-md-0.pt-md-0.mt-lg-4.mt-xl-5
                .h4.small-text.mt-sm-3.mt-md-0.mt-lg-2 Estimación de costos
                p.mt-3.small-text Valor monetario aproximado de los recursos necesarios para la ejecución de las actividades del proyecto.

      .col-10.col-md-6
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.rounded-15.box-shadow.px-0
            figure
              img(src="@/assets/template/tema-3-14.png", alt="Texto que describa la imagen")
            .text.p-lg-3.p-4
              .row.text-center.px-1.pt-1.mt-1.mt-md-0.mt-lg-4.mt-xl-5.pt-md-0
                .h4.small-text.mt-3.mt-md-0.mt-lg-2 Determinación del presupuesto 
                p.mt-3.small-text Estimados los costos de las actividades y de los paquetes de trabajo con base en la línea base de costos, se medirán los rendimientos en costos logrados durante el proyecto.

    .row.mt-5
      .col-12.col-lg-10
        p La gestión de costos inicial puede determinar la vida o muerte del proyecto. Si el proyecto avanza, la gestión puede ser un factor en la definición del alcance del proyecto. Si la gestión de costos arroja como resultado que su estimación es demasiado alta, se puede decidir reducir el proyecto en función de lo que se pueda pagar, o lo que es muy común, empezar a obtener financiación para el proyecto. Una vez que el proyecto está en marcha, la estimación de costos se utiliza para gestionar todos sus costos asociados, a fin de que el proyecto se ajuste al presupuesto.
      .col-4.col-lg-2.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-15.svg", alt="Texto que describa la imagen").px-4.floating
    separador.mt-3
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_4.h2 3.4  Plan de gestión de calidad del proyecto
    .row.mt-5.rounded-15.bg-amarillo-claro.p-5.zoom-in(data-aos="slide-left")
      .col-12.col-lg-8
        p En el plan de gestión de calidad del proyecto, se establecen los requerimientos de calidad que deben cumplir los entregables del proyecto.
        p.mt-3 Al finalizar cada una de las fases del proyecto, surgen entregables, para los cuales, desde la fase de planificación del proyecto, se deben establecer parámetros de calidad esperados.
        p.mt-3 Es importante entender previamente el concepto de calidad, entendida como un proceso continuo, sin fin, de mejora aplicable a todas las fases y componentes del proyecto, con el fin de mejorar los productos y servicios que la organización ofrece.
        p.mt-3 La ISO 9000 define la calidad como “la totalidad de rasgos y características de un producto o servicio que son relevantes en su habilidad para satisfacer las necesidades declaradas o implícitas del cliente”. Por otro lado, el IPMA define la calidad de un proyecto como “la base de la calidad de un proyecto son las prácticas de dirección de calidad por la organización permanentemente implicada y contribuye a los procesos y resultados del proyecto”.
        p.mt-3 La gestión de calidad comprende los siguientes componentes:
        ul.lista-ul.mt-3
          li 
            i.fas.fa-angle-right
            | Política de calidad.
          li.mt-2 
            i.fas.fa-angle-right
            | Objetivos de calidad.
          li.mt-2 
            i.fas.fa-angle-right
            | Aseguramiento de la calidad.
          li.mt-2 
            i.fas.fa-angle-right
            | Control de la calidad.
          li.mt-2 
            i.fas.fa-angle-right
            | Auditoría de calidad.
          li.mt-2 
            i.fas.fa-angle-right
            | Plan del programa de calidad.
      .col-4.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-16.svg", alt="Texto que describa la imagen")
    separador.mt-3
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_5.h2 3.5  Plan de gestión de recursos humanos  
    .row.mt-5.rounded-15.bg-amarillo-claro.p-5.zoom-in(data-aos="slide-right")
      .col-4.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-17.svg", alt="Texto que describa la imagen")
      .col-12.col-lg-8
        p La gestión del recurso humano es un conjunto integrado de procesos de la organización, diseñado para atraer, gestionar, desarrollar, motivar y retener a los colaboradores. El plan de gestión de recursos humanos se organiza y estructura a partir de todas las personas que conforman el proyecto, estableciendo responsables y responsabilidades con el proyecto. Este componente es de suma importancia, ya que se deberá tener una visión estratégica para el máximo aprovechamiento del talento humano, identificando las fortalezas y las competencias del equipo en función de las requeridas en el proyecto.
        p.mt-3 Dentro de las características que debe poseer un buen plan de recursos humanos, se tiene:
        ul.lista-ul.mt-3
          li 
            i.fas.fa-angle-right
            | Tener en cuenta las necesidades del proyecto, tanto las pasadas, las presentes, como las futuras.
          li.mt-2 
            i.fas.fa-angle-right
            | Determinar el personal necesario para cubrir esas necesidades detectadas.
          li.mt-2 
            i.fas.fa-angle-right
            | Definir correctamente cada puesto de trabajo.
          li.mt-2 
            i.fas.fa-angle-right
            | Determinar los contratos más adecuados para cada caso.
          li.mt-2 
            i.fas.fa-angle-right
            | Definir los canales y medios de captación de nuevos candidatos, así como el proceso de reclutamiento y selección, y los criterios asociados.
          li.mt-2 
            i.fas.fa-angle-right
            | Debe tener actualizada la información de la plantilla.
          li.mt-2 
            i.fas.fa-angle-right
            | Debe contemplar planes de crecimiento y formación.
    p.mt-5 Para alcanzar buenos resultados que apunten al logro de los objetivos del proyecto, se deben desarrollar tres principales tareas.
    .row.mt-5(data-aos="fade-up")
      .col-10.col-lg-8.offset-1.offset-lg-2
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Precisar perfiles y puestos")
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-3-18.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-12.col-lg-10.align-self-center
              p.text-small Es necesario definir dos factores fundamentales: las tareas de cada puesto de trabajo y el número de horas que se requieren para ejecutar dichas funciones. Esto permitirá conocer qué personal requiere el proyecto para operar y el tipo de horario que se aplicará.

          .row(numero="2" titulo="Establecer las políticas")
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-3-19.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-12.col-lg-10.align-self-center
              p.text-small Es clave, en esta tarea, especificar la política de reclutamiento, la tabla de remuneración, los lineamientos para medir el desempeño de los colaboradores y el cronograma o plan de programas informativos que implementará el proyecto.   
          .row(numero="3" titulo="Señalar las políticas operativas ")
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-3-20.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-12.col-lg-10.align-self-center
              p.text-small Aquí deben estar contemplados los horarios, normas disciplinarias, evaluaciones, pago de salarios, mecanismos para reclamaciones, políticas de seguridad en cuanto a protección de datos, entre otros.
    p.mt-5 Una vez desarrolladas las anteriores tareas, el plan de gestión de recursos humanos se convertirá en una herramienta vital para gestionar el personal del proyecto de forma eficiente, optimizar procesos, identificar las necesidades en tiempo oportuno y encaminar a la empresa hacia el logro de sus objetivos.
    separador.mt-3
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_6.h2  3.6  Plan de gestión de comunicaciones  
    .row.mt-5
      .col-12.col-lg-8.align-self-center
        p La gestión de las comunicaciones, según la PMBOK (2003), incluye los procesos necesarios para garantizar la adecuada y oportuna recopilación, distribución, almacenamiento, recuperación y disposición final de la información del proyecto.
        p.mt-3 La comunicación eficaz permite un puente entre las diferentes partes interesadas en el proyecto, suministrar la información requerida, a la persona requerida, en el momento oportuno, empleando el medio, formato y técnica más apropiados.
        p.mt-3 En la gestión de comunicaciones del proyecto, es importante tener en cuenta:
        ul.lista-ul.mt-3.acento-contenido
          li 
            i.fas.fa-angle-right
            | Qué información requiere.
          li.mt-2 
            i.fas.fa-angle-right
            | Cuándo la necesita.
          li.mt-2 
            i.fas.fa-angle-right
            | Quién necesita la información.
          li.mt-2 
            i.fas.fa-angle-right
            | Cómo se debe presentar la información.
        p.mt-3 El plan de gestión de comunicaciones se establece para informar aspectos inherentes al proyecto a las diferentes partes interesadas. Siendo así, observe lo siguiente:
      .col-4.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-21.svg", alt="Texto que describa la imagen").margin-0-auto.floating
    .row.mt-5
      .col-10.col-lg-8.offset-1.offset-lg-2
        figure
          img(src="@/assets/template/tema-3-22.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-5.align-self-center.d-none.d-lg-block
        figure
          img(src="@/assets/template/tema-3-23.png", alt="Texto que describa la imagen")
      .col-12.col-lg-7.align-self-center
        p En la fase de planeación del proyecto, se establece cómo será el plan de gestión de comunicaciones del proyecto, estableciendo:
        ul.lista-ul.acento-contenido.mt-3
          li 
            i.fas.fa-angle-right
            | Cómo y con qué periodicidad se comunicarán los miembros del equipo.
          li.mt-1 
            i.fas.fa-angle-right
            | Cómo informan el estado del proyecto las diferentes partes del equipo.
          li.mt-1 
            i.fas.fa-angle-right
            | Cómo se reciben los requerimientos e información necesaria de clientes, proveedores y demás partes interesadas del proyecto.
    separador.mt-3
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_7.h2 3.7  Plan de gestión del riesgo del proyecto 
    figure(data-aos="flip-up")
      img(src="@/assets/template/tema-3-24.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-4.col-lg-2.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-25.svg", alt="Texto que describa la imagen").px-4.floating
      .col-12.col-lg-10
        p La ISO 31000 define la gestión de riesgos como todas aquellas acciones coordinadas para dirigir y controlar los riesgos a los que puedan estar abocadas las organizaciones. Se identifican, valoran y controlan los riesgos asociados al proyecto.
        p.mt-3 Los proyectos están expuestos a múltiples riesgos que deberán ser identificados con antelación para evitar contratiempos e impedimentos en su implementación. Aunque los riesgos son diversos y dependen del tipo de proyecto y contexto en el que se desenvuelva. Siendo así, a continuación, se presentan algunos de los riesgos más frecuentes:
    .row.mt-5
      .col-10.offset-1.box-shadow.rounded-20(data-aos="slide-up")
        .row.p-4
          .col-2.d-none.d-lg-flex.border-azul-der.align-items-center
            figure
              img(src="@/assets/template/tema-3-26.svg", alt="Texto que describa la imagen").px-lg-2.px-xl-4
          .col-12.col-lg-10.pl-4
            .h4 Riesgos que afecten el desarrollo de los servicios o productos finales del proyecto:
            p.mt-3 Cambios en políticas estatales, factores ambientales, factores climáticos, pandemia, paros, huelgas, resistencia al cambio de un grupo poblacional, entre otros.
      .col-10.offset-1.box-shadow.rounded-20.mt-5(data-aos="slide-right")
        .row.p-4
          .col-2.d-none.d-lg-flex.border-azul-der.align-items-center
            figure
              img(src="@/assets/template/tema-3-27.svg", alt="Texto que describa la imagen").px-lg-2.px-xl-4
          .col-12.col-lg-10.pl-4
            .h4 Riesgos que afecten los equipos, máquinas y herramientas empleadas en el proyecto: 
            p.mt-3 Virus, daños del software que impliquen pérdida de la información, daño, deterioro del equipo que implique pérdida de tiempo y/o dinero, entre otros.
      .col-10.offset-1.box-shadow.rounded-20.mt-5(data-aos="slide-left")
        .row.p-4
          .col-2.d-none.d-lg-flex.border-azul-der.align-items-center
            figure
              img(src="@/assets/template/tema-3-28.svg", alt="Texto que describa la imagen").px-lg-2.px-xl-4
          .col-12.col-lg-10.pl-4
            .h4 Riesgos que afecten el talento humano y/o usuario del proyecto: 
            p.mt-3 Accidentes, enfermedades, e incluso la muerte asociada por actividades relacionadas con el proyecto. 
    p.mt-5 En la fase de planeación del proyecto, se diseña y documenta el plan de gestión del riesgo. Se establecen las estrategias, el método para la identificación, análisis de riesgos, desarrollo del plan, monitoreo, control y evaluación. 
    separador.mt-3
    
    .titulo-segundo.mt-5.color-acento-contenido
      #t_3_8.h2 3.8  Plan de gestión de adquisiciones del proyecto 
    .row.mt-5
      .col-4.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-29.svg", alt="Texto que describa la imagen").margin-0-auto.floating
      .col-12.col-lg-8.align-self-center
        p Se entiende por gestión de adquisiciones todo servicio o producto que la organización debe contratar o proveer ante una persona u organización externa, por lo que es importante identificar qué hay que aprovisionar, cómo, por qué, cuánto y cuándo.
        p.mt-3 Se especifican los requerimientos en materia de adquisición de productos o servicios necesarios para la ejecución del proyecto, asimismo, se identifican los posibles suministradores, proveedores, plan de contratación y recursos para tal fin.
        p.mt-3 El proceso de gestión de adquisiciones comprende:
    .row.mt-5
      .col-10.offset-1
        .titulo-sexto.color-acento-contenido.mt-5
          h5 Tabla 1
          span Proceso de gestión de adquisiciones
        .tabla-a.color-acento-contenido.mt-5 
          table
            caption.mt-3 Nota SENA (2021)
            thead
              tr
                th.py-3 Proceso
                th Descripción
            tbody
              tr
                td.py-3 Planificación de adquisiciones.
                td Se determina qué aprovisionar y en qué momento.
              tr
                td.py-3 Planificación de la petición de ofertas.
                td Se documentan las especificaciones del producto y se identifican potenciales proveedores.
              tr
                td.py-3 Petición de ofertas.
                td Se obtienen los presupuestos, ofertas y propuestas.
              tr
                td.py-3 Selección de suministradores.
                td Se escogen los proveedores.
              tr
                td.py-3 Administración del contrato.
                td Se gestionan y dirigen todas las relaciones formalizadas en un contrato con los suministradores.
              tr
                td.py-3 Cierre del contrato.
                td Se da por finalizada la relación contractual.
    .row.mt-5
      .col-12.col-lg-10
        p Recapitulando, es así como se han identificado los elementos conceptuales de la gestión de proyectos, el grupo de inicio del proyecto con sus principales acciones y los diversos grupos de planificación del proyecto en conjugación con sus diferentes actividades y tareas. Todo lo anterior, apuntando más hacia la gestión interna, con los colaboradores e integrantes del proyecto. Ahora, se dará inicio al tema de la formulación de la propuesta de mercado, es decir, la gestión externa del proyecto, la cual tiene como objetivo darle al cliente una idea clara, concisa y transparente de cómo un negocio en particular puede ser relevante para él. Observe.
      .col-4.col-lg-2.d-none.d-lg-block.align-self-center
        figure
          img(src="@/assets/template/tema-3-30.svg", alt="Texto que describa la imagen").px-4.floating
      
    



</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
    datosSlyder: [
      {
        titulo: 'Definición de actividades ',
        texto:
          'Identificar las acciones que se deben realizar para llevar a cabo los entregables del proyecto.',
        imagen: require('@/assets/template/tema-3-7.png'),
      },
      {
        titulo: 'Secuencia lógica de actividades  ',
        texto:
          'Establecer las relaciones entre las actividades del proyecto y definir una secuencia lógica para el desarrollo eficiente de las actividades.',
        imagen: require('@/assets/template/tema-3-8.png'),
      },
      {
        titulo: 'Estimar los recursos para las actividades',
        texto:
          'Definir las cantidades, materiales, equipos, recursos humanos, e insumos necesarios para desarrollar cada actividad.',
        imagen: require('@/assets/template/tema-3-9.png'),
      },
      {
        titulo: 'Estimar duración de las actividades',
        texto:
          'Se refiere al periodo de tiempo necesario para el desarrollo de cada actividad.',
        imagen: require('@/assets/template/tema-3-10.png'),
      },
    ],
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

<style lang="sass">
.tarjeta-flip
  background-color: #3357F0 !important
.border-azul-der
  border-right: 3px solid #0D2380
</style>
