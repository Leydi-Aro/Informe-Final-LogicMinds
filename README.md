<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">


# Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

<hr>

# <center>Desarrollo de Aplicaciones Open Source</center>

## TP REPORT

**Sección:** SV52

**Profesor**: Hugo Allan Mori Paiva

**StartUp Name**: LogicMinds

**Producto**: Rentstate

### Team Members:

| Member                        |    Code    |
|:------------------------------|:----------:|
| Asillo Mendoza, Julio Ernesto | u20201b482 |
| Mamani Aro, Leydi Yaquelin    | u20201b745 |
| Lopez Huaman, Edwin Abdias    | u20201b051 |
| Ruiz Carhuamanca, Angie       | u20201b293 |
| Antonio Salazar, Jhan Clinton | u20201b312 |

<br>

Agosto del 2023

<br><br>

</div>

# Registro de Versiones del Informe

| Versión |   Fecha    |     Autor     | Descripción de modificación                                          |
|:-------:|:----------:|:-------------:|:---------------------------------------------------------------------|
|  1.1.1  | 19/08/2023 | Leydi  Mamani | Descripción de la problemática usando 5W y 2H                        |
|  1.1.2  | 19/08/2023 | Leydi  Mamani | Presentación y análisis de competidores                              |
|  1.1.3  | 19/08/2023 | Jhan Antonio  | Desarrollo del Canvas y diseño de entrevistas                        |
|  1.1.4  | 05/09/2023 |  Edwin Lopez  | Desarrollo del empathy mapping, user mapping y user goal mapping.    |
|  1.1.5  | 05/09/2023 |  Angie Ruiz   | Análisis de entrevistas                                              |
|  1.1.6  | 08/09/2023 |  Edwin Lopez  | Diseño de wireframes y mocks-ups                                     |
|  1.1.7  | 08/09/2023 | Julio Asillo  | Diseño completo de landing page                                      |
|  1.1.8  | 09/09/2023 |  Edwin Lopez  | Diseño completo de la base y explicación de las entidades            |
|  1.1.9  | 09/09/2023 | Jhan Antonio  | Diseño completo del diagrama de clase y explicación de sus atributos |
| 1.1.10  | 09/09/2023 |  Angie Ruiz   | Documentación completa del sprint 1                                  |
| 1.1.11  | 09/09/2023 | Julio Asillo  | Documentación del sprint 2                                           |
|  2.1.1  | 20/09/2023 | Leydi Mamani  | Elaboración del sprint planning y spring backlog 2                   |
|  2.1.2  | 20/09/2023 |  Angie Ruiz   | Desarrollo del formulario para publicar y guardar propiedades        |
|  2.1.3  | 21/09/2023 | Jhan Antonio  | Documentación del sprint 2                                           |
|  2.1.4  | 21/09/2023 |  Edwin Lopez  | Documentación del frontend para mensajería                           |
|  2.1.4  | 21/09/2023 | Julio Asillo  | Documentación de todos los logros obtenidos en el sprint 2           |

<br><br>

# Project Report Collaboration Insights

- TP: Para esta entrega, realizamos como equipo las actividades correspondientes a los capítulos asignados en el siguiente repositorio dentro de nuestra organización de grupo:

    Link del repositorio del Informe Final: [Github - Informe Final LogicMinds](https://github.com/LogicMinds-Group)

    <br>

<br><br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capítulo-iv-product-design)

- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
    - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
    - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

### [Conclusiones](#conclusiones)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

<br><br>

# Student Outcome

| Criterio específico                                                                                                                                                                   | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Conclusiones                                                                                                                                                                                                                                                                      |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.                                  | TB1 <br><br> Julio Asillo <br> - Para esta TB1 participé de manera activa y usé la plataforma de Discord y Github para administrar los avances. <br><br> Mamani Aro, Leydi Yaquelin <br> - Como parte del equipo participé en cada una de las reuniones tanto virtuales (discord) y presenciales. Además, colaboré y me comuniqué constantemente con mi equipo para poder realizar la entrega del proyecto. <br><br> Lopez Huaman, Edwin Abdias <br> - Para esta entrega realice todos los diagramas relacionados con el usuario y análisis de competidores. <br><br> Antonio Salazar, Jhan Clinton <br> - Durante el desarrollo de esta entrega realicé Sprint planning & backlog, class Diagram, DDD Software Architecture. <br><br> Ruiz Carhuamaca, Angie <br> - En esta primera entrega participé en cada reunión programada y estuve en constante comunicación con mi equipo para el desarrollo de los capítulos.                                                                                                                           | TB1 <br> Como equipo hemos trabajado de manera conjunta y colaborativa, realizando entregas en el tiempo estipulado de acuerdo con lo coordinado en cada reunión.                                                                                                                 |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | TB1 <br><br> Julio Asillo <br> - Para esta entrega utilicé HTML y CSS para la creación de la landing page, incluyendo sitios web para el diseño de diagramas. <br><br> Mamani Aro, Leydi Yaquelin <br> - Para este primer entregable realicé el cuadro de Lean UX Canvas, así como también efectué el registro de una entrevista y aporté en colaboración con mi equipo para realizar el sprint 1. <br><br> Lopez Huaman, Edwin Abdias <br> - Para el desarrollo de esta entrega participé activamente en las reuniones de trabajo y el desarrollo de cada uno de los wireframes y diseño de landing page. <br><br> Antonio Salazar, Jhan Clinton <br> - Realicé las user Stories, As-Is Scenario, Antecedentes, Problemática y Diseño de entrevistas. <br><br> Ruiz Carhuamaca, Angie <br> - Para el desarrollo de esta entrega utilicé diferentes sitios web para realizar los wireframes y MockUps de la Landing Page, Web Applications y sus respectivos diagramas, participé en la realización de los Problem Statements y Product Backlog.  | TB1 <br> Planear y conocer bien la estructura del software a desarrollar hace que su implementación sea más fácil.                                                                                         |

<br><br>

# Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Description de la StartUp

Nos encargamos de servir como nexo entre personas interesadas en rentar inmuebles y los interesados en alquilar dichas propiedades. Nuestros objetivos son facilitar el proceso de búsqueda, sistematizar el registro y seguimiento de las cláusulas del contrato. Además de proporcionar un informe general sobre los registros y comentarios de los usuarios.


<div align=center>
    <img src="https://i.ibb.co/6tsYXtg/My-project-3.png" alt="logo" style="margin-bottom: 5px;" width="500"/>
</div>

- **Nombre:** RentState
- **Rubro:** Desarrollo de software
- **Visión:** Convertirnos en el principal medio de renta de inmuebles a nivel nacional.
- **Misión:** Mejorar el proceso de arrendamiento mediante un sistema completo e intuitivo que ayude tanto a arrendadores como a arrendatarios.

### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/Q9HYJT6/angie.png" alt="Angie" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Ruiz Carhuamaca, Angie Nayeli
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Angie Nayeli Ruiz Carhuamaca y estudio la carrera de Ingeniería de Software en la UPC, que se enfoca en la creación de programas informáticos confiables y de calidad. Me considero una persona creativa, responsable y organizada. Al realizar algún trabajo grupal, me gusta escuchar ideas de mis compañeros y buscar métodos que nos ayuden a realizar correctamente el proyecto.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/vqgrN5N/Julio.png" alt="Julio" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Asillo Mendoza, Julio Ernesto
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Julio Asillo, tengo 19 años y estoy cursando el sexto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una persona responsable, activa y comprometida. Al pasar los años en la Universidad he tenido la oportunidad de formar parte de varios equipos, entonces tengo experiencia en trabajos grupales. Presentó los conocimientos de programar en C++, HTML, CSS, Python, etc.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/bd39JFb/leydi.png" alt="Leydi" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Mamani Aro, Leydi Yaquelin
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
         Soy Leydi Yaquelin Mamani Aro, estudio la carrera de Ingeniería de Software porque tuve la oportunidad de aprender temas sobre computación y sistemas, donde adquirí conocimientos e intereses relacionados con la informática, programación y diseño gráfico. Por otro lado, desde que comencé el primer ciclo en la universidad he tenido que elaborar trabajos grupales, por esa razón he fortalecido mi habilidad para trabajar en equipo y poder resolver problemas asertivamente. Me comprometo a ser responsable con cada entregable del curso, esperando que el startup cumpla con los objetivos propuestos.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/Cn1rQNP/edwin.png" alt="Edwin"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            LOpez Huaman, Edwin Abdias
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Edwin Abdias Lopez Huaman. Estudiante de la carrera Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me gusta programar, practicar deportes como la natación, ciclismo, calistenia y también jugar fútbol con mis amigos. Además, otro de mis pasatiempos es jugar.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://i.ibb.co/Hx4CWMX/jhan.png" alt="Jhan"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Antonio Salazar, Jhan Clinton
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
         Actualmente, soy estudiante de ingeniería de software. Me apasiona la tecnología y el desarrollo de soluciones innovadoras para mejorar la vida de las personas. Estoy emocionado de seguir aprendiendo y creciendo en este campo emocionante y en constante evolución.
        </td>
    </tr>
</table>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

- **What?** <br><br>

¿Cuál es el problema?
Dificultad para encontrar inmuebles en renta, no ver información verídica y actualizada del espacio en alquiler para su uso y el consumo de tiempo para poder encontrarlo.<br><br>

- **When?** <br><br>

  ¿Cuándo sucede el problema?
  Cuando las personas quieren encontrar un inmueble en una zona aledaña a un lugar de trabajo o estudio. Asimismo, cuando los propietarios no cuentan con un sistema que los ayude a administrar y difundir sus inmuebles disponibles.<br><br>

- **Where?** <br><br>

  ¿Dónde está la persona cuando sucede el problema?
  Si la persona tiene un manejo de las tecnologías se encuentra en la comodidad de su casa buscando inmuebles por redes sociales o internet. Si es una persona que no maneja estos recursos está buscando estos inmuebles de forma presencial.<br><br>

- **Why?** <br><br>

  ¿Cuál es la causa del problema?
  No contar con una aplicación o portal que ayude a encontrar estos espacios para la renta y que a la vez esté con información actualizada y verificada por otras personas.<br><br>

- **How?** <br><br>

  ¿Cómo se presenta el problema?
  Se presenta mediante el tiempo que las personas invierten en la búsqueda de un inmueble para rentar ideal, muchas veces con poco o ningún éxito.<br><br>

- **How much?** <br><br>

  ¿Qué tan severo es el problema?
  Según el INEI, para el año 2021, el total de hogares que viven en un inmueble alquilado en Perú es 26,7% y para la región Lima, es de 35,8%. Esto significa que más de ¼ de los hogares peruanos tienen que vivir en una búsqueda continua de una vivienda.<br><br>
  
### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Hemos notado que las personas entre los 18 a 25 años que deseen arrendar un inmueble buscan medios digitales que los ayuden a encontrar el inmueble adecuado acorde a sus necesidades. Un factor crítico que dificulta este proceso es la información desactualizada y no verificada que se encuentra registrado de estos inmuebles en redes sociales o internet.
¿Cómo otorgar una búsqueda eficiente sobre inmuebles con información verídica para que las personas logren encontrar el inmueble acorde a sus necesidades?
Una gran cantidad de personas consideran el proceso de búsqueda de inmuebles una actividad estresante y hasta cierto punto frustrante. La selección de un inmueble adecuado acorde a las necesidades puede resultar en una mala experiencia al no poder encontrar rápidamente el inmueble. Un factor crítico es la dificultad de conseguir lo que se desea en la primera oportunidad, ya que depende del presupuesto, lugar y cláusulas que se debe de considerar para recién arrendar un inmueble.
¿Cómo automatizar el proceso de búsqueda y elección de inmuebles según las necesidades del usuario?
Hemos notado que las personas de 25 a 65 años que, arriendan inmuebles buscan formas efectivas para difundir y tener una mejor administración de sus propiedades que están siendo arrendadas, para no desperdiciar demasiado tiempo en dichos procesos. Los factores críticos que afectan en la obtención de resultados es la desorganización de contenido, no actualizar constantemente información, correcto registro, interacción con medios digitales y no manejar una plataforma que pueda satisfacer dichas necesidades.
¿Cómo podemos construir una plataforma que permita al usuario ahorrar tiempo en difusión y administración de su negocio de inmueble para poder satisfacer sus necesidades?


#### 1.2.2.2. Lean UX Assumptions

**Business outcomes:**

- Los usuarios de la aplicación están interesados en iniciar un proyecto doméstico de hidroponía.
- Los usuarios desean obtener guías ofrecidas por expertos calificados en el tema.
- Los usuarios desean una interfaz de aplicación intuitiva, responsive y fácil de usar para la búsqueda y visualización de los cursos.
- Los usuarios buscan funciones adicionales, como que se incluya servicios de equipamiento, nutrientes, y demás implementos.
- Los usuarios deben poder ver y analizar las opciones de forma clara y precisa.
- La aplicación debe ser compatible con múltiples navegadores modernos.
- Los usuarios están dispuestos a pagar por funciones premium o servicios adicionales en la aplicación.

**Users: assumptions**

- **¿Quién es el usuario?**

  Los usuarios interesados en la aplicación son aquellos que buscan toda la información necesaria para iniciar un proyecto propio sobre hidroponía casera y agricultura, además de buscar cursos y guías de expertos en las cuales puedan basarse y realizar de mejor manera su plan agrícola. Nuestros usuarios son: personas mayores de edad que deseen iniciar en la hidroponía, y expertos que desean brindar sus conocimientos a los principiantes.

- **¿Dónde encaja nuestro producto en su trabajo o vida?**

  Nuestra aplicación es aplicable tanto como un pasatiempo inicial, hasta convertirse en un proyecto y trabajo continuo que conlleva mayor inversión de tiempo.

- **¿Qué problema tiene nuestro producto? ¿Cómo se resuelve?**

  El problema que aborda nuestro producto es la dificultad de encontrar información acerca de hidroponía en casa y cómo iniciar tu propio proyecto. Se resuelve al proporcionar una plataforma que pueda conectar principiantes y expertos que puedan guiarlos a realizar su proyecto. Esto brinda la posibilidad de formar una comunidad en la cual puedan compartir experiencias, consejos, tutoriales y demás.

- **¿Cuándo y cómo es usado nuestro producto?**

  Nuestro producto se adecua a los usuarios, por lo que puede ser utilizado en las fechas que ellos prefieran, y cuando consideren que sea conveniente iniciar adecuadamente el proyecto que planean. Al mismo tiempo, los expertos también pueden decidir en qué momento compartir sus conocimientos, realizando buenos cursos para los principiantes.

- **¿Qué características son importantes?**

  La característica más importante es la posibilidad de crear comunidades, dentro de las cuales se pueden compartir diversas características entre los usuarios.

- **¿Cómo debe verse nuestro producto y comportarse?**

  Nuestro producto debe cumplir con su propósito sin presentar errores en su funcionamiento. El producto debe tener un uso sencillo, eficiente y ágil.

#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que nuestra aplicación será de gran utilidad para las personas principiantes en el tema de hidroponía casera. Sabremos que tuvimos éxito cuando las reseñas positivas realizadas por los usuarios sean mayores al 80%.

- Creemos que los expertos en el tema podrán contribuir de manera significativa para el aprendizaje de los principiantes. Sabremos que tuvimos éxito cuando los cursos ofrecidos tengan inscritos más del 70% de usuarios.

- Creemos que nuestra aplicación será utilizada por personas mayores de 18 años, siendo este nuestro segmento objetivo. Sabremos que tuvimos éxito cuando el promedio de edad de los usuarios coincida con nuestro objetivo.

- Creemos que nuestra aplicación será sencilla e intuitiva de usar para nuestros usuarios. Sabremos que tuvimos éxito cuando en las encuestas los usuarios satisfechos sean más del 80%.

- Creemos que las comunidades serán una buena característica en la cual los usuarios puedan compartir sus experiencias y consejos entre sus proyectos. Sabremos que tuvimos éxito cuando la mayoría de los usuarios haga uso de esta característica.

#### 1.2.2.4. Lean UX Canvas

<div align=center>
    <img src="https://i.ibb.co/3v8q06n/c01.png" alt="Canvas"/>
</div>
<div align=center>
    <img src="https://i.ibb.co/mChxT4G/c02.png" alt="Canvas"/>
</div>


## 1.3. Segmentos Objetivo

| Tipo de Usuario | Personas que deseen iniciar en la hidroponía                                                                                                                                                                                                                                 | Expertos que desean brindar sus conocimientos a los principiantes                                                                                                                                                                                                |
| :-------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Geográfico      | País: Perú <br><br> Zona residencial: No es relevante, pueden ser de diferentes zonas del país.                                                                                                                                                                                      | País: Perú <br><br> Zona residencial: No es relevante, pueden ser de diferentes zonas del país.                                                                                                                                                                          |
| Psicográfico    | Clase Social: Mayormente se encuentran desde la clase media baja, hacia clases sociales más elevadas. <br><br> Estilo de vida: Son personas apasionadas por el tema de la agricultura y las granjas en casa, sin embargo no poseen los conocimientos para iniciar su propio proyecto. | Clase Social: Mayormente se encuentran desde la clase media baja, hacia clases sociales más elevadas. <br><br> Estilo de vida: Son personas dedicadas a la hidroponía, con cierto tiempo de experiencia en el tema, por lo que quieren ofrecer ayuda a los principiantes. |
| Demográfico     | Edad: Personas mayores de edad. <br><br> Nivel de Ingreso: No es relevante, ya que depende de los factores que se elijan. <br><br> Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte.                                                    | Edad: Deben ser mayores de edad, preferiblemente mayores de 30 años. <br><br> Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte. <br><br> Estudios: Debe contar con secundaria completa o superior.                          |

<br><br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

<br>
Luego de realizar una investigación en el mercado peruano, hemos encontrado tres proyectos similares a GreenGrow. Por ello, los concideramos como potenciales competidores. Estos son:
<br><br>


- **Hidroponika:**
<br>

  Es un Web browser que cuenta con una gama completa de productos y servicios de calidad relacionados con la hidrocultura. Además, posee soluciones nutritivas para todo tipo de plantas, desde tu propio huerto.
<br>

<div align="center">

  <img src="https://i.imgur.com/sPqvU40.png">

</div>

<br><br>


- **Intagri:**
<br>

  Es un portal que ofrece distintos tipos de información acerca de los distintos tipos de cultivos. Además, ofrece también distintas conferencias y cursos dictados por expertos acerca de la agricultura.
<br>

<div align="center">

  <img src="https://i.imgur.com/Ynnwv7G.jpg">

</div>

<br><br>


- **Mundo Hidroponia:**
<br>

  Es un portal que ofrece una gran cantidad de productos para la hidroponía como nutrientes, huertos, semillas, etc. Además, ofrece también servicios de envío para sus productos hacia sus clientes.
<br>

<div align="center">

  <img src="https://i.imgur.com/pY6oo3B.jpg">

</div>

<br><br>


### 2.1.1. Análisis competitivo

<table>
<tbody><tr><th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th></tr><tr><td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td><td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td></tr><tr><td colspan="5">Este análisis se concretó teniendo como finalidad el poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de ellos.</td></tr><tr><td colspan="3">Nuestro Producto / Competidores</td><td colspan="1" valign="top" style="font-weight: bold;">GreenGrow<br><img src="https://i.imgur.com/jwNgfz4.jpg?width=2002&amp;height=1345" alt="GreenGrow" width="70px"></td><td colspan="1" valign="top" style="font-weight: bold;">Hidroponika<br><img src="https://i.imgur.com/sPqvU40.png?width=600&amp;height=600" alt="Hidroponika" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Intagri<br><img src="https://i.imgur.com/Ynnwv7G.jpg?width=547&amp;height=118" alt="Intagri" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Mundo Hidroponia<br><img src="https://i.imgur.com/pY6oo3B.jpg?width=1447&amp;height=814" alt="Mundo Hidropnia" width="60px"></td></tr><tr><td colspan="1" rowspan="2">Perfil</td><td colspan="2">Overview</td><td colspan="1" valign="top">Aplicación web donde los clientes podrán informarse acerca de la hidroponía, mantenerse informado cada dia sobre diversos temas de la hidroponía y poder realizar cursos interactivos donde aprenda distintas técnicas o materiales a usar.</td><td colspan="1" valign="top">Es una página web que cuenta con una gran variedad de productos y servicios relacionados a la hidroponía, de gran calidad y para distintos lugares.Además posee distintos cursos para iniciar en la hidroponía.</td><td colspan="1" valign="top">Es una página web que ofrece distintos tipos de información sobre agricultura.  Ofrecen capacitaciones y cursos donde explican distintos tipos de métodos a utilizar en la agricultura. Estos cursos los dictan de manera presencial o virtual dependiendo del área que dicten.</td><td colspan="1" valign="top">Es una página web que ofrece distintos productos para la hidroponia como nutrientes para las plantas, huertas donde irán instaladas estas plantas y semillas de distintos tipos.</td></tr><tr><td colspan="2">Ventaja competitiva</td><td colspan="1" valign="top">Una mejor variedad de productos acorde a la economía de las personas y a los distintos lugares del Perú. Además de un continuo seguimiento de nuestros clientes para poder aclarar alguna duda o problema que pueda surgir.</td><td colspan="1" valign="top">Una gran cantidad de productos, packs, soluciones y demás para la hidroponia. Tiene una sólida interfaz donde explican los servicios que ofrece la empresa y los beneficios de realizar hidroponia.</td><td colspan="1" valign="top">Una ventaja que ellos tienen a diferencia de otros es la gran cantidad de cursos que dictan, esto hace que muchas personas elijan sus servicios para aprender más acerca de distintos temas de agricultura y también sobre de la hidroponia.</td><td colspan="1" valign="top">Gran variedad de semillas y nutrientes para la hidroponia. Esto hace que sean un lugar concurrido para las personas que tengan este tipo de huertos.</td></tr><tr><td colspan="1" rowspan="2">Perfil de Marketing</td><td colspan="2">Mercado objetivo</td><td colspan="1" valign="top">Personas de todo el Perú que quieran comenzar a utilizar la técnica de hidroponía para cultivar en sus casas o personas que necesitan materiales para seguir ciudadano sus cultivos</td><td colspan="1" valign="top">Personas de todo el Perú que quieran obtener sus productos o empezar en la hidroponía en sus hogares u otros lugares.</td><td colspan="1" valign="top">Personas que estén interesadas en aprender más sobre la hidroponía, dispuestos a llevar cursos y asistir en charlas que Intagri ofrece.</td><td colspan="1" valign="top">Personas que se dedican a cultivar plantas con la técnica de hidroponía.</td></tr><tr><td colspan="2">Estrategias de marketing</td><td colspan="1" valign="top">Publicidad a través de redes sociales</td><td colspan="1" valign="top">En las principales redes sociales.</td><td colspan="1" valign="top">En las principales redes sociales, linkedin y en empresas aliadas como Fertilab y Proain.</td><td colspan="1" valign="top">Publicidad a través de las principales redes sociales</td></tr><tr><td colspan="1" rowspan="3">Perfil de Producto</td><td colspan="2">Productos &amp; Servicios</td><td colspan="1" valign="top">Brindar un servicio de calidad mediante la información que mostraremos en nuestra página, La creación de cursos didácticos de distintos temas de la hidroponía, además de la creación de comunidades donde las personas puedan contar sus experiencias o recomendar distintas cosas.</td><td colspan="1" valign="top">Gran variedad de productos desde nutrientes para las plantas hasta hidro huertos de distintos tamaños y para distintos tipos de plantas.</td><td colspan="1" valign="top">Los productos que ellos ofrecen son los cursos y capacitaciones sobre distintos temas acerca de la agricultura.</td><td colspan="1" valign="top">Gran variedad de productos desde nutrientes para las plantas hasta huertos de distintos tamaños y para distintos tipos de plantas.</td></tr><tr><td colspan="2">Precios &amp; Costos</td><td colspan="1" valign="top">Los precios y costos por nuestros cursos se mostrarán en la pantalla de compra del producto. Asimismo trataremos de mantener los precios lo más accesible para todo público.</td><td colspan="1" valign="top">Los costos varían desde los más baratos que son las soluciones desde los 20 soles hasta los más caros que son los hidro huertos que pueden pasar los 1000 soles.</td><td colspan="1" valign="top">Sus precios varían entre los cursos que son los más cómodos hasta los diplomados internacionales que valen mucho dinero.</td><td colspan="1" valign="top">Los costos varían desde los más baratos que son los nutrientes y semillas hasta los más caros que son los huertos que pueden costar una gran cantidad de dinero dependiendo del tamaño de estos.</td></tr><tr><td colspan="2">Canales de distribución (Web y/o Móvil)</td><td colspan="1" valign="top">Se contará con una página web en donde se encontrará todo lo que ofrecemos e información acerca de nosotros </td><td colspan="1" valign="top">Se hacen envíos a todo el Perú mediante empresas de courier tanto para Lima metropolitana hasta los distintos departamentos del país.</td><td colspan="1" valign="top">La mayoría de cursos que dictan son virtuales pero los seminarios o congresos que ellos dicten son presenciales.</td><td colspan="1" valign="top">Ofrecen sus servicios por medio de empresas de courier en el territorio argentino.</td><tr></tr><td colspan="1" rowspan="5">Análisis SWOT</td></td></tr><tr><td colspan="2">Fortalezas</td><td colspan="1" valign="top">Brindar información de distintos temas sobre la hidroponía, además de estar validadas por un especialista. Comunicación constante con los clientes.</td><td colspan="1" valign="top">Una gran variedad de productos para ofrecer a todos sus clientes.</td><td colspan="1" valign="top">Una gran variedad de cursos de distintos temas que pueden atraer a distintas personas. Capacitaciones y ponencias de manera presencial hacen que sean más reconocidos por sus demás competidores.</td><td colspan="1" valign="top">Gran variedad de semillas para la plantación de estas, distintos nutrientes que ayudan a la planta a crecer y gran variedad de huertos de distintos tamaños y para distintos propocitos.</td></tr><tr><td colspan="2">Debilidades</td><td colspan="1" valign="top">Falta de credibilidad por ser una startup nueva y no ser tan reconocida en el medio.</td><td colspan="1" valign="top">Falta de comunicación con los clientes. Sus únicos medios de comunicación son las redes sociales y whatsapp, por lo que se puede tardar a la hora de responder algún mensaje.</td><td colspan="1" valign="top">Al tener un catálogo muy amplio de cursos y temas que ofrecen, no pueden enfocarse en un tema en específico por lo que algunas ocasiones no resolverán la duda al cliente.</td><td colspan="1" valign="top">Algunas personas no podrán conocer qué tipos de nutrientes necesitan para sus plantas o que tipos de huertas se acomodan más a su lugar de plantación.</td></tr><tr><td colspan="2">Oportunidades</td><td colspan="1" valign="top">Falta de información por especialistas en el tema.. Falta de plataformas que ofrezcan servicios de hidroponía a nivel nacional.</td><td colspan="1" valign="top">Falta de lugares o webs donde una persona pueda encontrar todo lo relacionado a la hidroponía, soluciones, semillas, huertos, etc.</td><td colspan="1" valign="top">Falta de lugares donde dicten cursos de una gran variedad de temas. Los eventos presenciales muchas veces no son tan completos como sí lo es el de Intagri.</td><td colspan="1" valign="top">Al tener una gran variedad de productos podrán satisfacer las necesidades de sus clientes.</td></tr><tr><td colspan="2">Amenazas</td><td colspan="1" valign="top">Las personas en primera instancia no confiarán en nosotros por ser una nueva empresa. Falta de socios los cuales nos puedan ayudar en el tema económico de la startup.</td><td colspan="1" valign="top">Algunas personas no contarán con el presupuesto suficiente para poder comprar las estaciones esenciales donde cultivar las plantas utilizando esta técnica.</td><td colspan="1" valign="top">Algunas personas no podrán acceder a sus cursos presenciales por falta de tiempo o por la locación de estas capacitaciones.</td><td colspan="1" valign="top">Los mismos productos podrán ser encontrados en otros tipos de páginas</td></tr></tbody></table>

### 2.1.2. Estrategias y tácticas frente a competidores

Debido a las diversas opciones que tienen los usuarios para poder satisfacer la necesidad del usuario cuando busque un lugar donde encontrar todo lo relacionado a la hidroponía y poder estar en una posición competitiva decidimos realizar los siguientes métodos:

#### Liderazgo en costes:

- Tenemos la capacidad de producir y ofrecer nuestro producto de manera gratuita, sin agregar limitaciones a sus funciones principales. De igual manera se ofrecerán a nuestros clientes distintos cursos, los podremos ofrecer de distintos precios según la categoría de estos, para que puedan ser accesible para todo tipo de persona. Nos orientamos principalmente a satisfacer las necesidades de las personas en busca de investigaciones, información y cursos que les ayuden a tener más conocimientos acerca de la hidroponia.

#### Estrategia de diferenciación:

- Tenemos en cuenta que, si queremos sobresalir de entre nuestros competidores, debemos establecer funcionalidades que otras aplicaciones no tengan o mejorarlas. Alguna de estas características es sobre el gran catálogo de temas, opiniones e investigaciones acerca de esta técnica de hidroponía. Todo esto vendrá respaldado por especialistas en el tema, es decir que cada punto que el usuario observe estará validado y puede ser usado en alguna investigación o simplemente para poder informarse. Asimismo contaremos con una amplia cantidad de cursos en línea que serán dictadas por los especialistas que confíen en nosotros y nos ayuden a formar una mejor plataforma de información.

#### Estrategia de enfoque:

- Somos conscientes que el crecimiento de la tecnología y el incremento en el uso de computadoras y smartphones, han generado una gran demanda en los servicios de gestión y guía agrícola. Por ello, tenemos en cuenta que una buena plataforma web sería de gran ayuda para las personas que desde sus propios dispositivos puedan investigar y conocer más acerca de nuestro tema principal.

#### Táctica de expansión:

- A pesar de que la aplicación funciona de manera gratuita. No planeamos saturar de anuncios por cada operación que se realice con ella. Planeamos expandir su uso a través de buenas calificaciones y anuncios.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se han definido una cierta cantidad de preguntas para nuestro segmento objetivo, con la finalidad de obtener información cualitativa como opiniones o descripciones. Esta información nos será de gran ayuda en el desarrollo de nuestra solución.

**Adquisición de información general**

1. ¿Cómo te llamas?
2. ¿Cuántos años tienes?
3. ¿Cuál es su ocupación?
4. Actualmente, ¿en qué lugar reside?

**Preguntas Segmento 1: Personas que deseen iniciar en la hidroponía**

1. ¿Por qué deseas empezar una granja en casa?
2. En tu caso, ¿cómo quisieras que sea tu proyecto de hidroponía doméstica?
3. ¿Cuáles son los principales inconvenientes que se le presentan para conseguir información acerca de hidroponía y granjas en casa?
4. ¿Qué beneficios podría obtener al poder reunir la información necesaria de forma más eficiente?
5. ¿Te sería de utilidad una aplicación en la cual puedas obtener este tipo de servicios, además de contar con comunidades y guías de expertos?
6. ¿Qué facilidades y características considera que deben estar presente en una aplicación como la descrita?

**Segmento 2: Expertos que desean brindar sus conocimientos a los principiantes**

1. ¿Cómo iniciaste con el tema de hidroponía y granjas domésticas? ¿Es complicado?
2. ¿Cómo llevas a cabo tu proyecto actual?
3. ¿Cuáles son los principales inconvenientes que se le presentan al mantener una proyecto de hidroponía doméstica?
4. ¿Es de tu interés brindar apoyo hacia las personas principiantes en hidroponía?
5. ¿Te sería de utilidad una aplicación en la cual puedas conectarte con los principiantes, además de contar con comunidades?
6. ¿Qué facilidades y características considera que deben estar presente en una aplicación como la descrita?

### 2.2.2. Registro de entrevistas

<span class="size" style="font-size:20px">**Segmento 01: Personas que deseen iniciar en la hidroponía**</span>

**Entrevista 01**

Entrevistado 1:

Nombre y apellidos: Jorge Gonzales

Edad: 21 años

Ubicación: Distrito de Santiago de Surco, Lima

Evidencia de la reunión:
<img src="https://i.imgur.com/HfDYnLv.jpg?width=1595&amp;height=897" alt="Canvas" width="90%">

Inicio: 00:04

Fin: 05:04

**Enlace de entrevista:** [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

**Resumen de la entrevista:**
Nuestro entrevistado fue Jorge Gonzales, estudiante de Ingeniería de Software y principiante en el tema de hidroponía casera. Nos comentó que desea iniciar su propio proyecto para poder despejarse de la rutina de sus estudios, además de poder ser una forma de aumentar su concentración y mejorar sus capacidades. Desea poder aprender de una forma rápida y didáctica, debido a que no dispone con mucho tiempo por sus estudios. Uno de los inconvenientes que se le presentan es la información extensa y
difícil de entender para principiantes, por lo que le sería de mucha utilidad una aplicación en la que pueda aprender de manera activa y continua, además de compartir publicaciones y experiencias mediante comunidades.

**Entrevista 02**

Nombre y apellidos: Sebastián Jesús Ramírez Zapata

Edad: 22 años

Ubicación: Ancón, Lima

Evidencia de la reunión:
<img src="https://i.imgur.com/QxEwEFb.jpg?width=1595&amp;height=897" alt="Canvas" width="90%">

Inicio: 05:08

Fin: 10:48

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

**Resumen de la entrevista:**
En la entrevista, Sebastián Jesús Ramírez Zapata, un ingeniero de software de 22 años, expresa su interés en iniciar una granja de hidroponía en su hogar. La motivación surgió tras ver vídeos sobre hidroponía y su viabilidad en espacios pequeños. Él busca cultivar frutas y hierbas en un espacio de aproximadamente 2x1 metros. Sebastián enfrenta dificultades al encontrar información especializada en hidroponía y granjas domésticas. Anhela una aplicación que ofrezca detalles precisos, guías paso a paso, comunidades de usuarios y adaptabilidad a las condiciones locales. Destaca la importancia de comprender las diferencias climáticas y la humedad en el cultivo. En resumen, Sebastián busca una solución integral que lo ayude a implementar su proyecto de granja hidropónica en casa, proporcionando información precisa y herramientas personalizadas.

**Entrevista 03**

Nombre y apellidos: Freddy Arellano

Edad: 38 años

Ubicación: Breña, Lima

Evidencia de la reunión:
<img src="https://i.imgur.com/r5z86D3.jpg?width=1105&amp;height=552" alt="Canvas" width="90%">

Inicio: 10:50

Fin: 12:54

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

Resumen de la entrevista:

En la entrevista el señor Freddy nos comenta que quiere iniciar en la hidroponía ya que desde siempre le han interesado las plantaciones y la agricultura en general. Nos comenta que muchas veces la falta de información que hay por las redes sociales o en páginas web es un gran inconveniente para él y para otras personas más que comparten sus mismos gustos por la hidroponia.

**Entrevista 04**

Nombre y apellidos: Oliver Jesús Tuesta Yoplac

Edad: 19 años

Ubicación: Chorrillos, Lima

Evidencia de la reunión:
<img src="https://i.imgur.com/zui3Xgd.jpg?width=1547&amp;height=690" alt="Canvas" width="90%">

Inicio: 12:55

Fin: 16:28

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

**Resumen de la entrevista:**

En la entrevista Oliver nos cuenta que está interesado en la hidroponía porque le importa la calidad de los alimentos, y que con una granja en casa tendría más control sobre esta, además de reducir la “huella ecológica”. Al ser un estudiante universitario, no cuenta con mucho tiempo libre, por lo que menciona que le gustaría que su granja fuera eficiente y de bajo mantenimiento. Durante su búsqueda de información, se encontró con mucha ambigüedad y falta de guías, y consejos para principiantes en esta actividad. Oliver menciona que una aplicación que facilite su búsqueda de información. y que además cuente con comunidades y expertos, le sería definitivamente útil. Otras características que le gustaría es un foro activo donde se pueda realizar preguntas y ser atendido por la comunidad y/o expertos, también le gustaría que el contenido de la aplicación fuera moderado o validado por los expertos.

<span class="size" style="font-size:20px">**Segmento 02: Expertos que desean brindar sus conocimientos a los principiantes**</span>

**Entrevista 01**

Nombre y apellidos: Paolo Espejo

Edad: 20 años

Ubicación: Huancayo, Junín

Evidencia de la reunión:
<img src="https://i.imgur.com/9dVMKDN.png?width=1105&amp;height=521" alt="Canvas" width="90%">

Inicio: 16:32

Fin: 21:18

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

**Resumen de la entrevista:**

Nuestro entrevistado fue Paolo Espejo, quien se dedica a la cosecha y venta de plantas. Empezó en el trabajo del sector agrícola gracias a un familiar, pero que al inicio es muy complicado ya que existe un desconocimiento general por parte de los principiantes. Por lo tanto, mencionó que está interesado en brindar sus conocimientos a los principiantes para que no cometan los mismos errores, además de que puedan ir desarrollándose en el tema hasta llegar a ser expertos. Considera que es necesaria una aplicación en la que pueda tener comunicación con estas personas, y en la que pueda publicar las enseñanzas necesarias para iniciar con sus proyectos.

**Entrevista 02**

Nombre y apellidos: Karina Campos

Edad: 35 años

Ubicación: Surquillo, Lima

Evidencia de la reunión:
<img src="https://i.imgur.com/NO1C0MS.png?width=1875&amp;height=896" alt="Canvas" width="90%">

Inicio: 21:22

Fin: 23:12

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

**Resumen de la entrevista:**

La entrevistada Karina Campos nos comenta que inició en el mundo de la hidroponía ya que desde siempre le gustaron las actividades de cosecha y cultivar plantas.Esto hizo que al enterarse que había una técnica de plantación que funcionaba en base al crecimiento en huertas y mediante sustancias como minerales y soluciones las plantas podrían crecer en un espacio como su casa. Además nos comenta que está dispuesta a poder enseñar a los que quieren iniciar en la plantación mediante la hidroponía, además nos cuenta qué le parecería bien que exista una plataforma donde ella pueda dar a conocer sus conocimientos y experiencias sobre distintos cuidados que debe de tener esta técnica.

**Entrevista 03**

Nombre y apellidos: Leonel Alessandro Ortega Espinoza

Edad: 19 años

Ubicación: Sayán

Evidencia de la reunión:
<img src="https://i.imgur.com/xuSvuQ4.png?width=1562&amp;height=550" alt="Canvas" width="90%">

Inicio: 23:14

Fin: 27:17

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

Resumen de la entrevista:

Leonel nos cuenta que su familia tiene un negocio familiar relacionado a la hidroponía y que ya ha trabajado en proyectos propios y del trabajo. Nos comenta que estaría dispuesto a ayudar en informar a los principiantes en este negocio, pues cuando era principiante no encontraba mucha información externa sobre la hidroponía. Finalmente menciona que le gustaría la idea de la aplicación.

### 2.2.3. Análisis de entrevistas

**Segmento 1: Personas que deseen iniciar en la hidroponía**

- **Interés en la hidroponía casera:** Todos los entrevistados muestran un interés en la hidroponía casera como un proyecto que les permitiría despejarse de la rutina y mejorar sus habilidades.
- **Limitación de tiempo:** En todas las entrevistas, se menciona la limitación de tiempo debido a las responsabilidades de los estudios o el trabajo. Esto sugiere que las soluciones propuestas deben ser eficientes y de aprendizaje rápido.
- **Dificultad en encontrar información:** Todos los entrevistados enfrentan dificultades al encontrar información específica y de calidad sobre la hidroponía casera, lo que sugiere una brecha en el acceso a recursos educativos.
- **Necesidad de información práctica y didáctica:** Tanto Jorge como Sebastián e incluso Oliver, expresan la necesidad de información que sea fácil de entender y aplicar en la práctica, lo que indica una preferencia por soluciones didácticas y aplicables.
- **Comunidad y compartir experiencias:** Todos los entrevistados valoran la posibilidad de conectarse con comunidades de personas interesadas en la hidroponía casera para compartir experiencias y obtener apoyo.
- **Personalización y adaptabilidad:** Sebastián menciona la importancia de que la información y las herramientas sean adaptables a las condiciones locales, incluyendo factores climáticos y de humedad.
- **Aplicación o plataforma educativa:** En todas las entrevistas, se sugiere la idea de una aplicación o plataforma en línea que brinde información, guías paso a paso y facilite la conexión con comunidades.

**Segmento 2: Expertos que desean brindar sus conocimientos a los principiantes**

Las entrevistas presentan similitudes en términos de la temática central y los puntos clave que los entrevistados discuten:

- **Temática Central:** Agricultura y Cultivo de Plantas: Todas las entrevistas giran en torno al tema de la agricultura y el cultivo de plantas, enfocándose en aspectos específicos como la cosecha, el cultivo de plantas y el deseo de compartir conocimientos.
- **Influencia Familiar y Pasión por la Agricultura:** En las tres entrevistas, los entrevistados mencionan haber sido influenciados por sus intereses y relaciones familiares para involucrarse en la agricultura y el cultivo de plantas. Paolo Espejo menciona que comenzó en el trabajo agrícola gracias a un familiar, mientras que Karina Campos señala que siempre le gustaron las actividades de cosecha y cultivo.
- **Deseo de Compartir Conocimientos:** Tanto Paolo Espejo, Karina Campos y Leonel Ortega expresan un interés en compartir sus conocimientos con aquellos que deseen iniciar en la agricultura o en una técnica específica, como la hidroponía. Los tres entrevistados desean ayudar a los principiantes a evitar cometer los mismos errores y a desarrollarse en el campo.
- **Necesidad de una Plataforma de Comunicación y Enseñanza:** Los entrevistados mencionan la idea de una plataforma en la que puedan comunicarse y compartir sus conocimientos con otros. Paolo Espejo menciona la necesidad de una aplicación para brindar enseñanzas a los principiantes, mientras que Karina Campos sugiere la idea de una plataforma para dar a conocer sus experiencias y cuidados específicos en hidroponía.
- **Enfoque en la Educación y el Desarrollo de Principiantes:** Todos ellos reconocen la dificultad y el desconocimiento que enfrentan los principiantes en el campo de la agricultura. Ambos entrevistados están motivados por ayudar a los principiantes a aprender y desarrollarse, brindándoles la orientación y la información necesaria.
- **Interés en Contribuir a la Expertise:** Todos los entrevistados ven la oportunidad de contribuir a la formación de nuevos expertos en el campo agrícola. Paolo Espejo quiere que los principiantes evolucionen hasta convertirse en expertos, y Karina Campos quiere enseñar sobre la hidroponía y otros cuidados específicos.

## 2.3. Needfinding

### 2.3.1. User Personas

Los User Personas son fundamentales para el éxito del proyecto GreenGrow, ya que brindan una comprensión profunda y concreta de las necesidades, deseos, frustraciones y comportamientos de los usuarios clave. Estos perfiles detallados permiten a la startup diseñar una plataforma y experiencia de aprendizaje altamente enfocada y personalizada, abordando de manera efectiva los desafíos específicos de cada segmento objetivo: desde brindar recursos claros y accesibles a principiantes, hasta ofrecer herramientas para que los expertos compartan su conocimiento

**User Persona del segmento: Personas que deseen iniciar en la hidroponía**

<div align="center">

  <img src="https://i.imgur.com/PSlIthL.png">

</div>

**User Persona del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<div align="center">

  <img src="https://i.imgur.com/Q9gcD49.png">

</div>
### 2.3.2. User Task Matrix

En esta User Task Matrix, se describen las tareas típicas que realizan los dos segmentos de usuarios: personas que deseen iniciar en la hidroponía y expertos que desean brindar sus conocimientos. Se evalúa la frecuencia y la severidad de cada tarea, lo que ayuda a priorizar y entender cuáles son las áreas clave en las que el producto GreenGrow podría intervenir para satisfacer las necesidades y los objetivos de ambos segmentos.

**Segmento Objetivo:** Personas que deseen iniciar en la hidroponía

|                   Tarea                    |  Frecuencia  | Severidad |
| :----------------------------------------: | :----------: | :-------: |
|       Investigar sobre la hidroponía       | Casi siempre |   Baja    |
|          Buscar recursos en línea          | Casi siempre |   Media   |
|      Consultar con amigos y expertos       |   A veces    |   Baja    |
|       Seleccionar el tipo de cultivo       |   A veces    |   Media   |
|       Adquirir suministros y equipos       |   A veces    |   Alta    |
|       Montar el sistema hidropónico        |   A veces    |   Media   |
|      Cultivar y mantener las plantas       | Casi siempre |   Alta    |
| Solucionar problemas (plagas, nutrientes)  |   A veces    |   Media   |
| Participar en una comunidad de aprendizaje |   A veces    |   Baja    |
|      Experimentar con nuevas técnicas      |   Rara Vez   |   Baja    |
|        Evaluar el éxito del cultivo        | Casi siempre |   Media   |

**Segmento Objetivo:** Expertos que desean brindar sus conocimientos a los principiantes

|                     Tarea                     |  Frecuencia  | Severidad |
| :-------------------------------------------: | :----------: | :-------: |
| Compartir consejos en foros y redes sociales  | Casi siempre |   Baja    |
|      Presentar en eventos de agricultura      |   A veces    |   Media   |
|        Responder consultas personales         |   A veces    |   Alta    |
|    Buscar plataformas para cursos en línea    |   A veces    |   Media   |
| Crear contenido educativo (artículos, videos) |   A veces    |   Alta    |
|         Diseñar y estructurar cursos          |   Rara vez   |   Alta    |
|            Ofrecer cursos en línea            |   Rara vez   |   Alta    |
|        Mantener y actualizar contenido        |   Rara vez   |   Media   |
|         Colaborar con otros expertos          |   Rara vez   |   Baja    |
|      Evaluar la eficacia de la enseñanza      |   Rara vez   |   Baja    |

### 2.3.3. User Journey Mapping

**User Journey Mapping del segmento: Personas que deseen iniciar en la hidroponía**

<div align="center">

  <img src="https://i.imgur.com/iFcacsq.png">

</div>

**User Journey Mapping del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<div align="center">

  <img src="https://i.imgur.com/uF8o7iK.png">

</div>


### 2.3.4. Empathy Mapping

Los Mapas de Empatía son esenciales para el proyecto GreenGrow, ya que permiten una comprensión profunda y holística de las experiencias, pensamientos y emociones de los usuarios clave. Estos mapas ofrecen una visión integral de cómo los usuarios piensan, sienten, ven, escuchan, dicen y hacen en relación con la hidroponía y la agricultura en interiores. Al proporcionar una representación visual y detallada de sus perspectivas y necesidades, los Mapas de Empatía guían el desarrollo de la plataforma al asegurar que se aborden los problemas reales y se cumplan las expectativas de los usuarios.

**Empathy Map del segmento: Personas que deseen iniciar en la hidroponía**

<div align="center">

  <img src="https://i.imgur.com/eBSLWNG.png">

</div>

**Empathy Map del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<div align="center">

  <img src="https://i.imgur.com/S0EtpMe.png">

</div>

### 2.3.5. As-is Scenario Mapping

Los escenarios AS-IS son esenciales para el proyecto GreenGrow, ya que brindan una visión detallada de los pasos, pensamientos y emociones de los usuarios antes de conocer el producto. Estos escenarios permiten comprender sus necesidades y desafíos actuales, lo que ayuda al equipo a diseñar una experiencia más efectiva y enfocada en resolver problemas reales. Al analizar los AS-IS, el producto puede ser desarrollado de manera que satisfaga las expectativas y proporcione soluciones alineadas con las experiencias actuales de los usuarios, resultando en un producto más exitoso y relevante.

**As-is Scenario Map del segmento: Personas que deseen iniciar en la hidroponía**

<div align="center">

  <img src="https://i.imgur.com/OIsMvCL.png">

</div>

**As-is Scenario Map del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<div align="center">

  <img src="https://i.imgur.com/9sZtJDe.png">

</div>

# Capítulo III: Requeriments Specifications

## 3.1 To-Be Scenario Mapping

<div align=center>
    <img src="https://i.imgur.com/qWXZ05y.jpg" alt="To-Be scenario mapp Usuarios">
    <br>
    <br>
    <br>
    <img src="https://i.imgur.com/UldAXJx.jpg" alt="To-Be scenario mapp Expertos">
</div>

## 3.2 User Stories

| Epic ID | Titulo de Épica                                    | Descripción de la épica                                                                                                                                                                    |
| :------ | :------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP001   | Definición de funcionalidades de la aplicación web | Como usuario deseo que la página ofrezca información acerca de distintos temas sobre la agricultura, principalmente la hidroponía. Como ayuda para mis plantaciones mediante esta técnica. |
| EP002   | Opciones relacionadas a la cuenta del usuario      | Como usuario deseo poder crear una cuenta en la página así como editarla y agregar información relevante.                                                                                  |
| EP003   | Opciones relacionadas a la cuenta del experto.     | Como experto deseo poder crearme una cuenta asi como poder publicar artículos y cursos de temas de donde me especializo, además de poder potenciar mi cuenta una suscripción..             |
| EP004   | Definición de estructura del landing page          | Como usuario deseo disponer de un landing page con información pertinente para conocer mejor acerca de la aplicación web                                                                   |

<br><br>

| Epic / Story ID | Título                                                                           | Descripción                                                                                                                                                      | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Relacionado con (Epic ID) |
| :-------------- | :------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ |
| **US01**        | Registro de personas                                                             | Como usuario deseo registrarme en la página para observar todo lo que me ofrece la aplicación.                                                                   | **Escenario 1: Crear una cuenta** <br>**Dado** que el usuario se encuentra en sección de inicio **Cuando** el usuario no se encuentra registrado en la página **Entonces** al seleccionar “Crear Cuenta” el sistema le redireccionará al registro.<br> **Escenario 2: Rellenado de datos correctamente.**<br> **Dado** que el usuario se encuentra en la sección de registro **Cuando** al rellenar todos los datos correctamente y se verifique que todo está correcto.**Entonces** el sistema registra sus datos ingresados a la base de datos.<br> **Escenario 3: Rellenado de datos incorrectamente.**<br> **Dado** que el usuario se encuentra en la sección de registro **Cuando** él ingresa los datos incorrectamente o no están completos, **Entonces** el sistema le indicará que “Está incorrecto “o “Falta rellenar este dato·.   | EP002                     |
| **US02**        | Registro de expertos                                                             | Como experto deseo registrarme en la página para poder escribir artículos acerca de mi área de especialidad y tener mejor control de las publicaciones que haga. | **Escenario 1: crear una cuenta.<br>** **Dado** que el experto se encuentra en sección de inicio **Cuando** el experto no se encuentra registrado en la página **Entonces** al seleccionar “Crear Cuenta” el sistema le redireccionará al registro.<br> **Escenario 2: Rellenado de datos correctamente.<br>** **Dado** que el experto se encuentra en la sección de registro **Cuando** al rellenar todos los datos correctamente y se verifique que todo está correcto. **Entonces** el sistema registra sus datos ingresados a la base de datos.<br> **Escenario 3: Rellenado de datos incorrectamente.<br>** **Dado** que el experto se encuentra en la sección de registro **Cuando** él ingrese los datos incorrectamente o no están completos, **Entonces** el sistema le indicará que “Está incorrecto “o “Falta rellenar este dato·. | EP003                     |
| **US03**        | Pago de suscripción de cuenta                                                    | Como usuario deseo poder pagar los cursos que la página ofrezca desde la aplicación para que no se me dificulte en otras formas.                                 | **Escenario 1: Ver cursos disponibles<br>** **Dado** que el usuario se encuentra en la pestaña de cursos **Cuando** el usuario selecciona uno de los cursos a comprar **Entonces** la aplicación le mostrará el saldo final y los métodos de pago con los que podrá comprarlo.<br> **Escenario 2: Escoger métodos de pago<br>** **Dado** que el usuario escogió su curso **Y** el usuario se encuentra en la pantalla de pago **Cuando** el usuario ingrese los datos solicitados por la página **Entonces** la página le mostrará un mensaje diciendo “Pago de curso realizado”.                                                                                                                                                                                                                                                             | EP001                     |
| **US04**        | Observar las distintas informaciones de especialistas con mejores calificaciones | Como usuario deseo poder saber cuales son los artículos actuales con una mejor puntuación y de igual manera con los cursos que ofrecen.                          | **Escenario 1: Visualización general de artículos y cursos<br>** **Dado** que el usuario selecciona “explorar artículos” **Cuando** el usuario filtre los artículos de información por los más votados o con mejores calificaciones **Entonces** se le mostrará cuáles son los artículos de información con mejores calificación por parte de otros usuarios.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EP001                     |
| **US05**        | Visualización de recomendaciones de cursos por parte de los usuarios             | Como usuario quiero visualizar la opinión de otros usuarios hacia los distintos cursos para conocer mejor cuales son los cursos que más valen la pena.           | **Escenario 1: Cuándo hay cursos con calificaciones de otros usuarios<br>** **Dado** que el usuario está en la sección “Explorar cursos” **Cuando** selecciona algún curso en particular **Entonces** el sistema mostrará todos los comentarios del curso seleccionado, así sean positivos o negativos.<br> **Escenario 2: Cuándo hay cursos sin ningún comentario o calificación<br>** **Dado** que el usuario está en la sección “Explorar cursos” **Cuando** selecciona algún curso en particular y este no tiene ningún comentario. **Entonces** lel sistema indicará que por el momento no existe ninguna calificación o comentario en el curso.                                                                                                                                                                                         | EP001                     |
| **US06**        | Ver comentarios de usuarios                                                      | Como experto quiero ver las reseñas de mis cursos para ver el recibimiento de los usuarios.                                                                      | **Escenario 1: Cuándo hay cursos puntuados por los usuarios<br>** **Dado** que el experto está en la sección “Mis cursos” **Cuando** selecciona algún curso en particular **Entonces** el sistema mostrará todos los comentarios que los usuarios han realizado a su curso. <br> **Escenario 2: Cuándo hay cursos sin ningún comentario o calificación<br>** **Dado** que el experto está en la sección “Mis cursos” **Cuando** selecciona algún curso en particular y este no tiene ningún comentario. **Entonces** el sistema indicará que por el momento no existe ninguna calificación o comentario en el curso.                                                                                                                                                                                                                          | EP003                     |
| **US07**        | Registros de los cursos                                                          | Como experto quiero crear mis propios cursos con herramientas que me proporciona la página o con mis propias herramientas.                                       | **Escenario 1: Registro de cursos de manera correctamente<br>** **Dado** que el experto se encuentre en el sector de “Crear curso” **Cuando** se selecciona ingresar videos e ingresa todos los datos requeridos **Entonces** el sistema muestra un mensaje indicando que el curso se ha registrado satisfactoriamente. <br> **Escenario 2: Registro de cursos de manera incorrectamente<br>** **Dado** que el experto se encuentre en el sector de “Crear curso” **Cuando** se selecciona ingresar videos y no ingresa todos los datos requeridos **Entonces** el sistema muestra un mensaje indicando que el curso no se registró correctamente.                                                                                                                                                                                            | EP003                     |
| **US08**        | Visualización del Landing pages                                                  | Como usuario en busca de información deseo visualizar toda la información y así ver lo que ofrece la página.                                                     | **Escenario 1: El usuario visualiza la sección landing page.<br>** **Dado** que el invitado del sector de usuario se encuentra en el landing page **Cuando** ingrese a nuestra landing page **Entonces** verá toda la información que ofrece nuestro producto.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | EP004                     |
| **US09**        | Visualización de los servicios que ofrecen en el landing page                    | Como invitado deseo visualizar los beneficios de la página, así como los servicios que esta ofrece.                                                              | **Escenario 1: El invitado visualiza la sección de servicios<br>** **Dado** que el invitado se encuentra en el landing page **Cuando** llega hasta la sección de servicios **Entonces** podrá informarse acerca de todos los servicios que ofrecerá nuestra página                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | EP004                     |
| **US10**        | Visualización de los testimonios de personas sobre la landing page               | Como invitado deseo visualizar los testimonios de distintas personas acerca de la landing page para ver si es lo que busco o no.                                 | **Escenario 1: El invitado visualiza la sección Testimonios.<br>** **Dado** que el invitado se encuentra en el landing page **Cuando** llega hasta la sección de Testimonios **Entonces** podrá informarse acerca de todos los testimonios de personas acerca de nuestra página                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP004                     |

<br><br>

## 3.3 Impact Mapping

<div align=center>
    <img src="https://i.imgur.com/zjIdX1s.jpg" alt="Impact Mapping">
</div>

<br>

## 3.4 Product Backlog

| # Orden | User Story Id | Título                                                                           | Descripción                                                                                                                                                      | Story Points (1 / 2 / 3 / 5 / 8) |
| :------ | :------------ | :------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------- |
| 1       | UH01          | Registro de personas                                                             | Como usuario deseo registrarme en la página para observar todo lo que me ofrece la aplicación.                                                                   | 3                                |
| 2       | UH02          | Registro de expertos                                                             | Como experto deseo registrarme en la página para poder escribir artículos acerca de mi área de especialidad y tener mejor control de las publicaciones que haga. | 3                                |
| 3       | UH03          | Pago de suscripción de cuenta                                                    | Como usuario deseo poder pagar los cursos que la página ofrezca desde la aplicación para que no se me dificulte en otras formas.                                 | 3                                |
| 4       | UH04          | Observar las distintas informaciones de especialistas con mejores calificaciones | Como usuario deseo poder saber cuales son los artículos actuales con una mejor puntuación y de igual manera con los cursos que ofrecen.                          | 5                                |
| 5       | UH05          | Visualización de recomendaciones de cursos por parte de los usuarios             | Como usuario quiero visualizar la opinión de otros usuarios hacia los distintos cursos para conocer mejor cuales son los cursos que más valen la pena.           | 5                                |
| 6       | UH06          | Ver comentarios de usuarios                                                      | Como experto quiero ver las reseñas de mis cursos para ver el recibimiento de los usuarios.                                                                      | 5                                |
| 7       | UH07          | Registros de los cursos                                                          | Como experto quiero crear mis propios cursos con herramientas que me proporciona la página o con mis propias herramientas.                                       | 3                                |
| 8       | UH08          | Visualización del Landing pages                                                  | Como usuario en busca de información deseo visualizar toda la información y así ver lo que ofrece la página.                                                     | 3                                |
| 9       | UH09          | Visualización de los servicios que ofrecen en el landing page                    | Como invitado deseo visualizar los beneficios de la página, así como los servicios que esta ofrece.                                                              | 2                                |
| 10      | UH10          | Visualización de los testimonios de personas sobre la landing page               | Como invitado deseo visualizar los testimonios de distintas personas acerca de la landing page para ver si es lo que busco o no.                                 | 2                                |

<br>

# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.

Como startup, buscamos que nuestra aplicación GreenGrow cuente con una interfaz en la que los usuarios noten profesionalismo, sencillez y exactitud. Queremos que los usuarios sepan que podrán desarrollar sus proyectos de manera eficiente. Es por esto que empleamos recursos gráficos para captar la atención de nuestros segmentos objetivos. Visualmente hemos utilizado colores relacionados al sector de la agricultura, además de emplear una tipografía que posee distintos tamaños y sobre todo legible.

**Brand Overview:**

Nuestro producto surge bajo la necesidad de los principiantes para poder iniciar un proyecto doméstico de hidroponía, por lo que brindamos una solución tecnológica e innovadora en la cual podrán encontrar todo el conocimiento que necesiten por parte de expertos en el tema.

**Brand Name:**

El nombre que recibe nuestro servicio es GreenGrow, el cual hace referencia al sector agrícola y el proceso de crecimiento de los cultivos producidos por los usuarios, quienes también crecen junto a todo el desarrollo al ir adquiriendo conocimientos, hasta llegar a convertirse en expertos.

**Colores Empleados**

| Color | Descripción |
| :---: |--------------------------------------------------------------------------------------------------------------------------- |
| Color Primario | Nuestro color primario es un verde claro, el cual representa a los cultivos utilizados por los usuarios en sus proyectos. <br> <p style = 'text-align:center;'> <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149177510920212501/image.png" alt="color1"> </p> |
| Color Secundario | Nuestro color secundario es un celeste pastel, el cual transmite frescura y tranquilidad a los usuarios. <br> <p style = 'text-align:center;'> <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149177692592283728/image.png" alt="color2"> </p> |
| Color Terciario | Nuestro tercer color es el blanco, el cual suma contraste a nuestros otros colores, y mejora el aspecto visual. <p style = 'text-align:center;'> <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149177602880327750/image.png" alt="color3"> </p> | 

**Tipografia**

| Tipografía | Fuente | Ejemplo |
| :---: | :---: | :---: |
| Tipografía principal | Fuente: Roboto <br> Tamaño: 25 px - 55 px | <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148057185847361546/logo.png" alt="ejemploTipografia" style="margin-bottom: 5px;" width="250"/> | 

### 4.1.2. Web Style Guidelines

**Landing Page:** Nuestra Landing Page emplea el Patrón Z en su estructura. Este patrón está diseñado para guiar al usuario por la página de manera natural y efectiva. En la parte superior se encontrará la barra de navegación con un tono oscuro, que brinda un aspecto serio y confiable. Esta barra contiene el logo y secciones como "Home", "Servicios", "Quiénes somos", "Testimonios" y "Descargar". Se usaron colores derivados del verde el cual representa el sector agrícola que llevamos en nuestro startup, además de que contrasta con el resto de la página para invitar al usuario a descargar y probar la aplicación.

<br>

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/dhj20Ho.jpg" width="1000">
</p>

## 4.2. Information Architecture.

En esta sección, estableceremos la estructura y forma del software en relación a nuestros segmentos objetivos, así como los elementos y características que se usarán dentro de la navegación de la aplicación.

### 4.2.1. Organization Systems.

Para crear la sección del Landing Page y la Aplicación web, se implementará una estructura visual jerárquica en la página web. Esto permitirá asignar la ubicación apropiada a cada elemento necesario en este desarrollo. Para lograrlo, se considerarán factores como etiquetas, especificaciones de pantalla y resolución. Además, se diseñarán íconos utilizando una matriz, lo que optimizará la visualización de los detalles y contribuirá a mantener un proceso ordenado en todo momento.

**Segmento Objetivo: Personas que deseen iniciar en la hidroponía**

- Jerárquica:
  - Al aplicar los filtros adecuados, los videos, clases, cursos o temas elegidos pueden aparecer con el debido orden, es decir, los artículos con mayor coincidencia aparecerán en primer lugar y así sucesivamente. El usuario tendrá la posibilidad de elegir el resultado de su agrado.
- Secuencial:
  - Cuando se requiera la creación de una cuenta para el uso de la aplicación, la información mostrada en pantalla deberá seguir una secuencia, en el que se deben respetar los pasos necesarios para que se pueda lograr con el cometido.
- Matricial:
  - En la configuración de la cuenta, los usuarios podrán configurar distintos aspectos de la misma de acuerdo a sus preferencias, mostrando los apartados divididos en secciones.

**Segmento Objetivo: Expertos que desean brindar sus conocimientos a los principiantes**

- Jerárquica:

  - Cuando se desee publicar algún tipo de información organizado por tema, podrá elegir el orden en el que quiera que se visualice para los principiantes, por lo que se presentará de forma ordenada.

- Secuencial:

  - Cuando se requiera la creación de una cuenta para el uso de la aplicación, la información mostrada en pantalla deberá seguir una secuencia, en el que se deben respetar los pasos necesarios para que se pueda lograr con el cometido.

- Matricial:
  - En la configuración de la cuenta, los usuarios podrán configurar distintos aspectos de la misma de acuerdo a sus preferencias, mostrando los apartados divididos en secciones.

### 4.2.2. Labeling Systems.

A continuación, se mostrará el sistema de etiquetado que otorgará una descripción breve y clara de la información mostrada en nuestra Landing Page.

Tenemos los siguientes encabezados:

- Home: En esta sección se muestra la sección inicial de la Landing Page, en la que se ofrece la bienvenida a los posibles usuarios, junto a una frase que representa al proyecto.
- Servicios: En esta sección se describen las características que los usuarios podrán encontrar al hacer uso de nuestra aplicación.
- Quiénes somos: En esta sección el cliente puede observar información acerca de nuestro equipo de desarrollo y una descripción breve de nuestro objetivo.
- Testimonios: En esta sección se pueden visualizar las opiniones de los usuarios que probaron el servicio, además de la puntuación que brindaron.
- Descargar: En esta sección se puede visualizar las opciones de descarga que podrán estar disponibles en un posible futuro al desarrollar una versión para dispositivos móviles.

### 4.2.3. SEO Tags and Meta Tags

Estas etiquetas son esenciales para mejorar la visibilidad de la aplicación web en los motores de búsqueda como Google. Las etiquetas SEO incluyen palabras clave relevantes y descripciones concisas para que los motores de búsqueda indexen y clasifiquen el contenido de la aplicación de manera efectiva. Las metaetiquetas proporcionan información adicional sobre la página, como el título y la descripción que se muestran en los resultados de búsqueda.

**Para el Landing Page:**

- Tittle: GreenGrow
- Description: GreenGrow - GrowGenius Official Landing Page
- Keywords: agriculture, crops, hydroponics, domestic
- Authors: GrowGenius team

**Para la aplicación web:**

- Tittle: GreenGrow
- Description: GreenGrow - GrowGenius Official Web Page
- Keywords: agriculture, crops, hydroponics, domestic,
- Authors: GrowGenius team

### 4.2.4. Searching Systems.

Un sistema de búsqueda efectivo es esencial para permitir a los usuarios encontrar información específica dentro de la aplicación web. La búsqueda debe ser rápida, precisa y capaz de manejar consultas complejas. Además, podría considerarse la implementación de filtros y opciones avanzadas de búsqueda para refinar los resultados.

- Landing Page: Los usuarios podrán hacer uso de la barra de navegación ubicada en la parte superior, para poder ubicarse en los distintos apartados en los que está dividido nuestra página, siendo una forma didáctica para interactuar con esta.

- Aplicación Web: Por parte de los principiantes, tendrán la opción de realizar búsquedas de información específica para ellos, por medio de aplicar los filtros necesarios. Los resultados serán mostrados de acuerdo a la coincidencia con la búsqueda establecida. Por parte de los arrendadores, podrán buscar a los clientes con quienes contactaron para realizar un alquiler, por medio de filtros como fecha, lugar, etc.

### 4.2.5. Navigation Systems.

Los sistemas de navegación son cómo los usuarios se desplazan por la aplicación web. Esto incluye menús, barras de navegación y enlaces contextuales. Una navegación clara y coherente es esencial para que los usuarios puedan moverse sin esfuerzo entre las diferentes secciones de la aplicación. La navegación debe ser intuitiva y brindar una experiencia fluida, permitiendo a los usuarios acceder rápidamente a la información que están buscando.
En nuestro Landing Page, encontramos la sección de la barra de navegación en la parte superior, la cual nos permite navegar directamente a un apartado dentro de la página. Esta barra de navegación será visible en todo momento, para que el usuario pueda dirigirse a otra sección que desee visualizar. De esta manera, generamos una navegación más fluida y dinámica para el usuario.
En nuestra aplicación web, utilizaremos un proceso similar al descrito, con diversas opciones que variarán de acuerdo al segmento objetivo que esté utilizando el servicio. Estos podrán hacer uso de filtros para poder encontrar de mejor manera la información precisa que necesiten.

## 4.3. Landing Page UI Design.

### 4.3.1. Landing Page Wireframe.

En la etapa de diseño de la interfaz de usuario (UI) de la página de destino (landing page), uno de los primeros pasos cruciales es la creación del "Landing Page Wireframe". Este wireframe actúa como el esqueleto inicial de la página, proporcionando una representación estructural y funcional de los elementos clave que compondrán la interfaz final. En este caso presentamos las secciones: Navbar (dentro de Hero), Hero, Services, About, Testimonials, Download y Footer.

Link al Figma: [Figma Wireframe](https://www.figma.com/file/sGF7WJc6aMsS1pPWvWMWLp/Landing-Page---Wireframes?type=design&node-id=0%3A1&mode=design&t=mvFXcGkT2cnZlT3Y-1)

- **Hero:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149181184295829604/image.png" width="1000">
</p>
<br>

- **Services:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149181423908036688/image.png" width="1000">
</p>
<br>

- **About us:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149181676816187463/image.png" width="1000">
</p>
<br>

- **Testimonials:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149181901513429063/image.png" width="1000">
</p>
<br>

- **Download:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149182063598125226/image.png" width="1000">
</p>
<br>

- **Footer:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149182384462385262/image.png" width="1000">
</p>
<br>

A continuación se muestran los wireframes para dispositivos móviles de las mismas secciones:

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149182824340000868/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149183074639294545/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149183527603142717/image.png" width="1000">
</p>
<br>

### 4.3.2. Landing Page Mock-up.

En la fase de diseño de la interfaz de usuario de la página de destino (landing page), el siguiente paso fundamental es la creación del "Landing Page Mock-up". Este mock-up representa la materialización visual de nuestra página, brindando una vista detallada y práctica de cómo se verá y funcionará la interfaz final.

- **Navbar & Hero:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149183900459991090/image.png" width="1000">
</p>
<br>

- **Services:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149184102738690068/image.png" width="1000">
</p>
<br>

- **About us:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149184275812462684/image.png" width="1000">
</p>
<br>

- **Testimonials:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149184510290837534/image.png" width="1000">
</p>
<br>

- **Download:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149184687152058408/image.png" width="1000">
</p>
<br>

- **Footer:**

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149184819675267112/image.png" width="1000">
</p>
<br>

A continuación se muestran los mockus para dispositivos móviles de las mismas secciones:

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149185360300101745/image.png" width="1000">
</p>
<br>

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.

En el desarrollo de aplicaciones web, los "Wireframes" son herramientas esenciales que proporcionan una representación esquemática y visual de la estructura y diseño de la aplicación. En este contexto, presentamos nuestras "Web Applications Wireframes", que son los planos iniciales de la aplicación web de nuestro proyecto, brindando una vista previa de su diseño y funcionalidad básica. Estos wireframes son una piedra angular en la creación y planificación de la interfaz de usuario, ayudándonos a visualizar y perfeccionar la experiencia del usuario antes de la implementación completa.

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149185601002803271/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149186166898298980/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149186447082012722/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149186687927328838/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149186888935153674/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149187449042505808/image.png" width="1000">
</p>
<br>

### 4.4.2. Web Applications Wireflow Diagrams.

Los "Wireflow Diagrams" representan visualmente cómo los usuarios logran objetivos específicos. Exploraremos tres escenarios: Ingresar a la pantalla principal de la aplicación, encontrar comunidades y comprar un curso. Estos diagramas nos ayudan a comprender la lógica subyacente del diseño de la aplicación y cómo satisface las necesidades de los usuarios.

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149189075891400754/image.png" width="1000">
</p>
<br>

Enlace del diagrama: [Ver Web Applications Wireflow Diagrams en Figma](https://lucid.app/lucidchart/1b3d01fb-00b5-4053-b32e-e060b20e76f9/edit?view_items=mpHs-Ifoft0B%2CmpHsiDKtOwvA%2CmpHsaTTu6khk%2CmpHsaPCphKy4%2CmpHsoO526UuE%2CmpHsnoNa0rGK%2CmpHsBmJ0NgRd%2CmpHsmVKxsxNV%2CmpHsnprsfz_C%2CmpHsmCIy2svS%2C.qHspq2XNNLy%2CmpHsFvLx5-7H%2CmpHsC-t7uvsG%2CmpHsvsyhWlOm%2CmpHsCg7F4wuW%2CmpHs9T2Q~dfG%2CmpHsqvy7Rog5%2CmpHs9_hN97Ob%2CmpHsFaPJdHaW%2CmpHsGS135712%2CHpHsD7kdbVNG&invitationId=inv_06a7e981-5a28-4c28-ab04-0b09b1328fe7)

**User goal:** Ingresar a la pantalla principal de la aplicación
<p style = 'text-align:center;'>
  <img src="https://media.discordapp.net/attachments/1148057148522233868/1149316713402339398/uf-1.png" width="1000">
</p>
<br>

**User goal:** Encontrar comunidades dentro de la aplicación
<p style = 'text-align:center;'>
  <img src="https://media.discordapp.net/attachments/1148057148522233868/1149316742775054456/Diagrama_en_blanco.png" width="1000">
</p>
<br>

**User goal:** Comprar un curso
<p style = 'text-align:center;'>
  <img src="https://media.discordapp.net/attachments/1148057148522233868/1149316767555002408/Diagrama_en_blanco_1.png" width="1000">
</p>
<br>

### 4.4.3. Web Applications Mock-ups.
Los "Web Applications Mock-ups" representan la siguiente etapa en la evolución de nuestro proyecto de aplicación web. Estos mock-ups van más allá de los simples esquemas de diseño al proporcionar una representación más detallada y visualmente rica de la interfaz de usuario. En esta fase, damos vida a la apariencia final de nuestra aplicación web, presentando una vista más realista de cómo se verá y funcionará.  
<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149187779100688404/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149187927583244339/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149188124942008421/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149188439229595799/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149188617793716304/image.png" width="1000">
</p>
<br>

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149188823025197118/image.png" width="1000">
</p>
<br>

### 4.4.4. Web Applications User Flow Diagrams.

- **User Goal:** Ingresar a la pantalla principal de la aplicación

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149380693453967360/Diagrama_en_blanco_7.png">
</p>
<br>

- **User Goal:** Comprar Curso

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149380163264590015/Diagrama_en_blanco_6.png">
</p>
<br>

Enlace al diagrama: [Ver Diagramas en Figma](https://lucid.app/lucidchart/59722d95-caa7-4ff6-89bb-d5a64418a64b/edit?viewport_loc=-2185%2C-1332%2C5548%2C2815%2C0_0&invitationId=inv_332207b3-98c3-403b-b9ec-faaa43e526c1)

<br>

### 4.5. Web Applications Prototyping.

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149189527454359623/image.png" width="1000">
</p>
<br>


Enlace del Prototipo:[Ver Prototipo](https://www.figma.com/proto/fAJmI8dYTS40y8ZLlrFqat/Web-application---MockUps?page-id=0%3A1&type=design&node-id=3940-1467&viewport=-113%2C47%2C0.1&t=0rp94hmRnpjqDzYx-1&scaling=scale-down&starting-point-node-id=3954%3A3513&mode=design)


Mobile Prototyping:
<p style = 'text-align:center;'>
  <img src="https://media.discordapp.net/attachments/1148057148522233868/1149318658703761549/proto-mobile.png" width="1000">
</p>
<br>

Enlace del Prototipo:[Ver Prototipo](https://www.figma.com/proto/fAJmI8dYTS40y8ZLlrFqat/Web-application---MockUps?page-id=3977%3A423&type=design&node-id=3995-484&viewport=-569%2C314%2C0.58&t=D1oGDKeRMQPic9Am-1&scaling=scale-down&mode=design)


Enlace de la explicación del prototipo: [Ver video de explicación de Prototipo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EbP0Jpb7ckJOsUDyXZ7iFysB_P_eDE3tBFgBncHMF5Xi4g?e=ckRoBp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

## 4.6. Domain-Driven Software Architecture.

### 4.6.1. Software Architecture Context Diagram.

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149190539703496805/image.png" width="1000">
</p>
<br>

### 4.6.2. Software Architecture Container Diagrams.

<p style = 'text-align:center;'>
  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149190784587943977/image.png" width="1000">
</p>
<br>

### 4.6.3. Software Architecture Components Diagrams.

Community Context

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/ww5aPMt.png" width="1000">
</p>
<br>

Course Context

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/jAtSH8s.png" width="1000">
</p>
<br>

Educational Content Context

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/dUZBVGB.png" width="1000">
</p>
<br>

Login Context

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/lBxZAIX.png" width="1000">
</p>
<br>

Sign Up Context

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/wDNmEtn.png" width="1000">
</p>
<br>

## 4.7. Software Object-Oriented Design.

### 4.7.1. Class Diagrams.

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/og66LLF.png">
</p>
<br>

Enlace del diagrama: [Ver diagrama](https://lucid.app/lucidchart/11cb49ec-ba2e-4ad8-a9ba-7fc357807121/edit?viewport_loc=839%2C847%2C4387%2C2218%2CigbrYPu~LT7U&invitationId=inv_02a216e5-4ebc-4600-a7ea-afd4cb3cac4e)

### 4.7.2. Class Dictionary.

En el presente diccionario; se mostrarán la utilidad de las clases diseñadas y presentadas en el apartado anterior, así como las relaciones entre cada una de ellas y como estas optimizan sus procesos:

  - Person: Esta clase sirve como clase padre para otras 2 clases más. Aquí es donde se indica que tipo de persona está conectada actualmente. Al ser clase padre tendrá atributos que se compartirán con la de sus hijas como el nombre, apellido y demás datos. <br><br>

  - User: Esta clase es una clase hija, aquí es donde se van a guardar todos los datos que sean referente cuando la persona es un usuario que quiere buscar información en nuestra página, además de saber que comentario fue que escribió el usuario y a que cursos esta inscrito. De aquí las demás clases que requieran de que la persona solo sea el usuario pueda realizar distintas conexiones.<br><br>

  - Expert: Esta clase es una clase hija y viene a ser la parte para la persona Experto, aquí se almacenará todo lo referente al experto en nuestra página. De aquí tendrá conexiones para las distintas clases que requieran del experto como los cursos, los artículos que escriba, etc.<br><br>

  - Account: Esta clase representa la cuenta de la persona registrada. Aquí habrá distintas funciones como el login o el register. Además de que en esta clase se podrán guardar el correo y contraseña de la persona, además de haber funciones para recuperar la contraseña o cambiar el email.<br><br>

  - Suscription: Esta clase maneja todo el tema de la suscripción del usuario. Aquí se guardaran atributos como a qué cuenta va a ir dirigida esta suscripción y validar a qué tipo de persona le pertenece la cuenta para que solo se aplique para usuarios. Además de tener métodos para saber el tipo de pago y el estado de la suscripción.<br><br>

  - Course: Esta clase tendrá como función principal obtener como atributo el nombre del curso y su descripción, así como toda la información que tendrá el curso tanto videos como otro tipo de información.<br><br>

  - ExpertCourse: Esta clase es una que está ligada tanto a la clase expertos como la clase cursos, aquí se tendrá registro del experto que creó el curso asi como la información de todo el curso en mención. Además podremos saber por cual usuario fue comprado y el rating que este curso tuvo por parte de los distintos usuarios.<br><br>

  - Articles: Esta clase trata sobre los artículos de infomracion que escriben los expertos. Aquí se podrá encontrar por cual experto fue creado y la fecha en que fue publicada.<br><br>

  - Comments: Esta clase trata sobre los comentarios que el usuario pueda hacer a las distintas publicaciones que haga el experto. Aquí podremos saber el contenido del comentario y a que articulo va dirigido.<br><br>

  - Community: Esta clase trata sobre las distintas comunidades que los usuarios podrán crear dentro de nuestra página, aquí tendremos una lista de todos los usuarios que estén inscritos en una comunidad así como funciones en donde podremos crear la comunidad en sí y que los usuarios puedan tener una comunicación entre ellos.<br><br>

  - SuscriptionPrice: Esta clase trata sobre el precio de la suscripción y la frecuencia de este. Esta tabla está relacionada con la tabla enumeration de Frequency la cual al ser un enumeration tendrá como variables el tipo de frecuencia de la suscripción Monthly si es una suscripción mensual y Annual si es una suscripción anual.<br><br>

## 4.8. Database Design.

### 4.8.1. Database Diagram.

<p style = 'text-align:center;'>
  <img src="https://i.imgur.com/iz2EHlW.png ">
</p>
<br>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.

#### Project Management:

**Discord:** Aunque originalmente se diseñó como una plataforma de comunicación para gamers, Discord también se utiliza para diseñar y crear comunidades en línea y mejorar la experiencia de usuario a través de la comunicación y colaboración en grupos.

**WhatsApp:** WhatsApp es una aplicación de mensajería instantánea que se utiliza para la comunicación en tiempo real. Aunque no es una herramienta de gestión de proyectos, se puede usar para mantenerse en contacto con miembros del equipo y colaborar en cierta medida.

**Zoom:** Zoom es una plataforma de comunicación que ofrece videoconferencias y reuniones en línea. Aunque se utiliza principalmente para comunicarse y realizar reuniones virtuales, también puede ser útil para la gestión de proyectos remotos y la colaboración en tiempo real.

**Desarrollo del Landing Page:** Para el desarrollo del landing page, se decidió hacer uso de herramientas tales como HTML, JS y CSS. Para llevarlo a cabo se eligieron diversas herramientas tecnológicas de las cuales el equipo ya está familiarizado y tiene  dominio.

#### Requirements Management:

**Miro:** Miro es una plataforma de pizarra en línea que se utiliza para colaborar en la ideación, planificación y diseño de proyectos. Es especialmente útil para la colaboración visual, como la creación de mapas mentales, diagramas y prototipos.

**Google Docs:** Google Docs es una suite de aplicaciones de procesamiento de texto, hojas de cálculo y presentaciones en línea. Aunque no es específicamente una herramienta de gestión de requisitos, se puede utilizar para documentar y colaborar en la definición y seguimiento de requisitos de proyectos.

#### Product UX/UI Design:

**Figma:** Figma es una herramienta de diseño de interfaz de usuario (UI) y experiencia de usuario (UX) basada en la nube. Se utiliza para crear prototipos interactivos, diseños de aplicaciones y colaboración en tiempo real en proyectos de diseño.

**UXPressia:** UXPressia es una herramienta especializada en la creación de mapas de experiencia de usuario, perfiles de clientes y otros elementos relacionados con el diseño de UX. Ayuda a visualizar y comprender la experiencia del usuario en un producto o servicio.

#### Software Development:

**Visual Studio Code:** Visual Studio Code es un editor de código fuente altamente configurable y ampliable. Se utiliza principalmente para la codificación, depuración y desarrollo de software en varios lenguajes de programación.

**Git:** Git es un sistema de control de versiones distribuido. Aunque no es un programa en sí mismo, es una tecnología esencial para el desarrollo de software y se usa para rastrear cambios en el código fuente y facilitar la colaboración entre programadores.

#### Software Documentation:

**GitHub:** GitHub es una plataforma de desarrollo colaborativo que utiliza el sistema de control de versiones Git. Se utiliza para alojar, revisar y colaborar en proyectos de desarrollo de software, lo que facilita la colaboración entre desarrolladores.

#### Software Testing:

**Lenguaje Gherkin:** El lenguaje Gherkin es un lenguaje de dominio específico utilizado para escribir pruebas de aceptación en un formato legible por humanos. Se utiliza junto con herramientas de prueba de comportamiento, como Cucumber, para automatizar pruebas funcionales.

### 5.1.2. Source Code Management.

Para mantener el orden al desarrollar una solución y evitar conflictos o superposiciones de información, los proyectos se trabajaron en un organización de GitHub y dentro de esta se encuentran los diferentes repositorios para cada proyecto cuyos enlaces de los repositorios son los siguientes:

1. Repositorio para el landing page: https://github.com/GreenGrow-OpenSource-SW53/landing-page/tree/release/1.0
2. Repositorio para los tests de aceptación: https://github.com/GreenGrow-OpenSource-SW53/acceptance-test
3. Repositorio de la aplicación web: **En desarrollo**

Para la implementación de Gitflow, se llevará a cabo de la siguiente manera:

Para cada commit que se realice, ya sea para el landing page o los archivos .feature, se utilizará el formato de mensaje "Conventional Commits" para ayudar a reconocer mejor lo que se hizo en los commits y de esta forma conocer mejor el estado del proyecto.

Cada repositorio de código tendrá sus respectivas ramas tal como lo describe Vincent Driessen en su artículo “A successful Git branching model”, donde estará presente la rama Master (que almacenará las versiones estables y finales), Develop (donde se irán integrando los cambios implementados por cada feature y estará en constante actualización), Release (donde se encontrará el código final de las versiones release) y Hotfix.

Además, cada feature desarrollado tendrá su propia rama que seguirá la siguiente convención para el nombre: feature/\<actividad-realizada>

### 5.1.3. Source Code Style Guide & Conventions.

A continuación, se darán a conocer las convenciones, formatos, estilos y entre otras propiedades de los lenguajes trabajados en la presente solución las cuales son: HTML, JavaScript/TypeScript, CSS:

- **HTML:** Se hará uso de la guía “HTML Style Guide and Coding” de la página W3Schools, la cual menciona las convenciones y estándares de este lenguaje de etiquetas. Hemos considerado las siguientes como las más importantes:

  - **Declarar siempre el tipo documento:** Es decir, colocar siempre la etiqueta <!DOCTYPE  html> en la primera línea del código.

  - **Utilizar el nombre de las etiquetas y sus atributos en minúscula:** Por un tema de estética y orden del código para que este se vea más limpio y sea más fácil de escribir.

  - **Cerrar todas las etiquetas:** Esto evita futuros problemas o errores de sintaxis.

  - **Siempre coloca comillas para los valores de los atributos de las etiquetas:** De esta forma los valores son más fáciles de leer y se deben utilizar obligatoriamente si este contiene espacios.

  - **Especificar siempre los atributos alt, width y height para las imágenes:** Es importante en caso de que la imagen no se pueda mostrar por algún motivo y también ayuda con el tema de la accesibilidad de los usuarios.

  - **No omitir la etiqueta ni los metadatos:** Estas etiquetas son importantes para la optimización de motores de búsqueda (SEO).

- **CSS:** Se siguió la guía “Google HTML/CSS Style Guide” donde se indican las convenciones, reglas y buenas prácticas para este lenguaje. Hemos considerado las siguientes recomendaciones como las más destacadas:

  - **Nombre de clases:** Se recomienda usar nombres generales para las clases, no deben ser específicas por la razón de que deben comportarse como padres.

  - **Usar nombres de clase cortos:** Se recomienda utilizar nombres de clase que sean cortos y descriptivos, para transmitir la idea de lo que representa de manera concisa.

  - **Usar delimitadores de nombres de clase adecuados:** Se debe de separar las palabras en los nombres de clase con solo guiones.

  - **Evitar los selectores de ID:** No se recomienda implementar este tipo de selectores, por la razón de que estos deben ser únicos en toda la página y en proyectos grandes que tengan muchos componentes es difícil de garantizar esa unicidad, es preferible usar selectores de clase.

  - **Usar propiedades abreviadas:** Es muy recomendable usar propiedades que soporten ser declarados de forma abreviada (por ejemplo, la propiedad padding, margin, border, etc.) por la razón de que reduce de forma significativa la cantidad de líneas de código, y es más legible para el programador o diseñador.

- **JavaScript:** Se consideró importante seguir una guía de buenas prácticas para un mejor desarrollo del código, para este caso se eligió la guía de la wiki “JavaScript best practices“ del World Wide Web (W3C). Lo cual se destaca lo siguiente:

  - **Usar nombres cortos y fáciles de leer:** Es recomendable nombrar adecuadamente las variables, clases, funciones y otros elementos para que sea más sencillo de leer y comprender.

  - **Evitar el uso de variables globales (keyword “var”):** No se recomienda el uso de este tipo de variables en un proyecto, porque pueden generar muchos errores a medida que el proyecto crece y estas pueden sobrescribirse fácilmente afectando el valor y se pueden declarar otros elementos como funciones con el mismo nombre de la variable y generar errores.

  - **Comentar y documentar lo necesario:** Se recomienda comentar líneas de código que son complejos de entender a simple vista explicando o dejando mensajes para que otros programadores lo entiendan.

  - **Usar notaciones sencillas de entender:** Javascript cuenta con diversas notaciones y operadores para crear o modificar ciertas estructuras de datos como objetos, arrays, selectivas, etc.

- **Gherkin:** Se consideró conveniente usar la guía y convenciones que se mencionan en “Gherkin Conventions for Readable Specifications” para una correcta realización de las pruebas. A continuación, se mencionan los puntos que consideramos más importantes para nuestro trabajo:

  - **Los bloques “Give-When-Then” deben ser diferenciados:** Se recomienda usar una correcta indentación de esos bloques para identificar mejor las secciones de la prueba y también añadiendo la keyword “And” para añadir otra línea en los pasos y otro bloque.

  - **Usar tablas para los pasos:** Si uno de los pasos requiere de más información es recomendable usar tablas para organizar dicha información y tenga un aspecto más ordenado.

  - **Usar comillas simples para los parámetros:** Se recomienda esta práctica para una mejor legibilidad de los parámetros en un paso y tener una sintaxis más simple.

  - **Separar los escenarios con comentarios:** Si se da el caso de tener muchos escenarios en una prueba, es usar los comentarios como separadores para que visualmente sea más organizado, fácil de leer y distinguir mejor.

  ![Gitflow evidence](https://cdn.discordapp.com/attachments/1148057148522233868/1148113641275670579/image.png)


### 5.1.4. Software Deployment Configuration.

En esta entrega, hemos realizado nuestra Landing Page. El código realizado se encuentra alojado en un repositorio específico dentro de nuestra comunidad pública. A partir de este repositorio, utilizamos Github Pages para el despliegue de la página, visualizando correctamente para un buen entendimiento por parte de los usuarios.

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1.

| Sprint 1                         | Implementación de funcionalidades y diseño de la aplicación.                                                                                    |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Sprint Planning Background       |
| Date                             | 30/08/2023                                                                                                                                      |
| Time                             | 17:00                                                                                                                                           |
| Location                         | Reunión realizada mediante Discord                                                                                                              |
| Prepared By                      | Checa Apolinario, Paolo Sebastián                                                                                                               |
| PAttendees (to planning meeting) | Checa Apolinario, Paolo Sebastián/Rodríguez Peña, Jorge Andrés /Pozo Campos, Rodrigo Jair /Arenas Conde, José Anthony/Cáceres Bueno, Arnol Omar |
| **Sprint Goal & User Stories**   |
| Sprint 1 Goal                    | Realizar y desplegar el Landing Page                                                                                                            |
| Sprint 1 Velocity                | 40                                                                                                                                              |
| Sum of Story Points              | 34                                                                                                                                              |

#### 5.2.1.2. Sprint Backlog 1.

| id   | Title                  | Id  | Title                                                    | Description                                                                                                   | Estimations(Hours) | Assigned To   | Status(To-do /InProcess/ToReview/Done) |
| ---- | ---------------------- | --- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------------ | ------------- | -------------------------------------- |
| GW01 | Apartado del Header    | G01 | Header responsivos (Desarrollado en HTML y CSS).         | Desarrollo e implementación de los estilos que corresponden al encabezado (Header). Debe ser responsive.      | 3                  | Rodrigo Pozo  | Done                                   |
| GW02 | Apartado del Footer    | G02 | Footer responsivos (Desarrollado en HTML y CSS).         | Desarrollo e implementación de los estilos que corresponden al pie de página (Footer). Debe ser responsive.   | 2                  | Arnol Cáceres | Done                                   |
| GW03 | Apartado Hero          | G03 | (Desarrollado en HTML y CSS)                             | Desarrollo e implementación de los estilos que corresponden a la sección Hero. Debe ser responsive.           | 3                  | Paolo Checa   | Done                                   |
| GW04 | Barra de navegación    | G04 | (Desarrollado en HTML y CSS)                             | Desarrollo e implementación de los estilos que corresponden a la barra de navegación. Debe ser responsive.    | 2                  | Rodrigo Pozo  | Done                                   |
| GW05 | Testimonials           | G05 | Sección "Testimonios"(Desarrollado en HTML y CSS)        | Desarrollo e implementación de los estilos que corresponden a la sección Testimonios. Debe ser responsive.    | 3                  | José Arenas   | Done                                   |
| GW06 | Sección Sobre Nosotros | G06 | Información del equipo (Desarrollado en HTML y CSS)      | Desarrollo e implementación de los estilos que corresponden a la información del equipo. Debe ser responsive. | 3                  | Franco Yance  | Done                                   |
| GW07 | Función de botones     | G07 | Funcionalidad de los Botones(Desarrollado en HTML y CSS) | Desarrollo e implementación de los estilos que corresponden a los botones de la página. Debe ser responsive.  | 3                  | Arnol Cáceres | Done                                   |
| GW08 | Interfaz Responsive    | G08 | Desarrollo responsive de la página                       | Desarrollo e implementación de un estilo responsive en toda la página.                                        | 2                  | Paolo Checa   | Done                                   |

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149376508817842367/image.png">

</div>


Link del trello: https://trello.com/b/4pRdktH4/sprint-1

#### 5.2.1.3. Development Evidence for Sprint Review.

| Repository   | Branch                                      | Commit Id | Commit Message                   | Commit Message Body | Commited on (Date) |
| ------------ | ------------------------------------------- | --------- | -------------------------------- | ------------------- | ------------------ |
| landing-page | feature/navbar-footer-styles (then develop) | 9f63be8   | feature: navbar, footer y styles | -                   | 03/09/2023         |
| landing-page | feature/hero-application                    | d92b8d4   | feature: hero y application      | -                   | 03/09/2023         |
| landing-page | feature/services                            | 3ea75ac   | feature: services                | -                   | 04/09/2023         |
| landing-page | feature/about                               | 6a7cee5   | feature: about                   | -                   | 03/09/2023         |
| landing-page | feature/testimonial                         | 91c2d4d   | feature: testimonial             | -                   | 03/09/2023         |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Para esta entrega, no se implementó el conjunto de apartados relacionados con Web Services, ya que el desarrollo se hizo en base al Landing Page.

### 5.2.1.5. Execution Evidence for Sprint Review.

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149378286510673973/image.png">

</div>

Link al video: [Ver video de Ejecución del Landing Page](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EZI9nioV7QtOvsZURheFR6IBDwsCNI6uZxu6Wy6Bu-Xlow?e=c0gYhM&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

### 5.2.1.6. Services Documentation Evidence for Sprint Review.

Este primer Sprint solo trata la implementación del landing page, por lo que no se empleó ningún servicio adicional.

### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para realizar el despliegue automático de nuestra Landing Page, utilizamos la herramienta Github Pages, el cual permite generar páginas web desde un repositorio público dentro del cual se aloja el código con el que se implementa la página. El link de nuestra Landing Page es el siguiente: https://greengrow-opensource-sw53.github.io/landing-page/

### 5.2.1.8. Team Collaboration Insights during Sprint.

Para la realización de los commits de nuestro primer Sprint, hemos hecho uso de la herramienta Visual Studio Code, además del uso de Git. Uno de los integrantes realizó un primer commit para la creación del repositorio, luego utilizando Git clonamos el repositorio, para luego realizar los cambios en Visual Code y crear los branches correspondientes a dichos cambios, para finalmente realizar el commit, el cual deberá ser revisado dentro del repositorio de Github.

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148382759249793064/image.png">

</div>

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148382593964838942/image.png">

</div>


## Conclusiones

- Con el análisis de competidores podemos conocer nuestras fortalezas y debilidades, para poder ofrecer un producto que cumplan con las necesidades del usuario.<br><br>

- Hemos utilizado diversas herramientas como user personas, empathy maps, user journey maps, as-is, to-be, product backlog, diagramas y diseños de base de datos, etc. para crear nuestra aplicación y asegurarnos de que satisfaga las necesidades de nuestros usuarios.<br><br>

- Las entrevistas a los usuarios fueron importantes para entender de primera mano cuales son sus necesidades verdaderas, para intentar solventarlas con nuestra propuesta.<br><br>

- Al realizar esta primera entrega pudimos realizar distintas propuestas  para obtener distinta soluciones a partir de nuestra problematica. Ademas se tuvo que indagar como podriamos satisfacer esas necesidades que requierian nuestros segmentos objetivos.<br><br>

- Con el análisis de competidores y las entrevistas, hemos logrado identificar los elementos clave que serán abordados en este informe. Hemos explorado diversos aspectos, con un enfoque particular en la problemática que estamos buscando resolver.<br><br>



## Bibliografía

Beltrano, J., & Gimenez, D. O. (2015). Cultivo en hidroponía. Editorial de la Universidad Nacional de La Plata (EDULP). Recuperado de [http://sedici.unlp.edu.ar/bitstream/handle/10915/46752/documento_completo.pdf?sequence=1](http://sedici.unlp.edu.ar/bitstream/handle/10915/46752/documento_completo.pdf?sequence=1) [Consulta: 01/09/2023]

Carrijo, O. A., Makishima, N., CARRIJO, O. A., & MAKISHIMA, N. (2000). Principios de hidroponia. Recuperado de [https://www.infoteca.cnptia.embrapa.br/bitstream/doc/769981/1/CNPHDOCUMENTOS22PRINCIPIOSDEHIDROPONIA.pdf](https://www.infoteca.cnptia.embrapa.br/bitstream/doc/769981/1/CNPHDOCUMENTOS22PRINCIPIOSDEHIDROPONIA.pdf) [Consulta: 01/09/2023]

Díaz, G. G. (2010). Hidroponía en casa: una actividad familiar. Recuperado de [https://www.mag.go.cr/bibliotecavirtual/F08-8691.pdf](https://www.mag.go.cr/bibliotecavirtual/F08-8691.pdf) [Consulta: 01/09/2023]

El comercio (2019). Alternativas sostenibles para un mejor futuro de la agricultura. El Comercio. Recuperado de [https://archivo.elcomercio.pe/labuenavecindad/comunidad/alternativas-sostenibles-mejor-futuro-agricultura-noticia-1994510](https://archivo.elcomercio.pe/labuenavecindad/comunidad/alternativas-sostenibles-mejor-futuro-agricultura-noticia-1994510) [Consulta: 01/09/2023]

<br><br>

## Anexos

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148057185847361546/logo.png">

</div>

<br>

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149177510920212501/image.png">

</div>

<br>

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149177602880327750/image.png">

</div>

<br>

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149177692592283728/image.png">

</div>

<br>

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149183900459991090/image.png">

</div>

<br>

<div align="center">

  <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1149188823025197118/image.png">

</div>
