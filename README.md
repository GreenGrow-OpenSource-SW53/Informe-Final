![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

<hr>

# <center>Desarrollo de Aplicaciones Open Source</center>
## TB1 REPORT

Sección SW53

**Profesor**: Elio Jefferrson Navarrete Vilca

**StartUp Name**: GrowGenius

**Producto**: GreenGrow

### Team Members:
| Member | Code |
|:----|:----:|
| Checa Apolinario, Paolo Sebastián| u202112749 |
| Pozo Campos, Rodrigo Jair | u20181e187 |
| Arenas Conde, José Anthony | u20211d744 |
| Cáceres Bueno, Arnol Omar | u20201b338 |
| Yance Gutierrez, Franco Felix | u202013614 |

Link al video de exposición:

Agosto del 2023

<br><br>

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación | 
|:-------:|:-----:|:-----:|:----------------------------| 
| | | 

<br><br>

# Project Report Collaboration Insights




<br><br>

# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capc3adtulo-i-introduccic3b3n-1)
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

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)
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

### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capc3adtulo-iv-product-design-1)
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

### [Capítulo V: Product Implementation, Validation & Deployment](#capc3adtulo-v-product-implementation-validation--deployment-1)
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

### [Conclusiones](#conclusiones-1)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

### [Bibliografía](#bibliografc3ada-1)
### [Anexos](#anexos-1)

<br><br>

# Student Outcome
| Criterio específico | Acciones realizadas | Conclusiones | 
|:---|:-----|:-----|
|Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Checa Apolinario, Paolo Sebastián TB1:** Se hizo un análisis para poder identificar a los segmentos objetivos, y de esta manera generar soluciones innovadoras. **Arenas Conde, José Anthony TB1:** Se realizó una investigación para comprender el problema que estamos abordando y así identificar a los segmentos objetivos, para poder reconocer sus necesidades y ofrecer un producto que las satisfaga. ||
|Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Checa Apolinario, Paolo Sebastián TB1:** Plasmamos nuestras ideas en nuestro plan de solución para el desarrollo de nuestro servicio. **Arenas Conde, José Anthony TB1**: Se realizó un informe con distintos puntos importantes para la realización del proyecto, desde una investigación de la problemática, hasta algunos prototipos de solución. ||
<br><br>

# Capítulo I: Introducción
## 1.1. StartUp Profile
### 1.1.1. Description de la StartUp

GrowGenius es una startup que nace con la finalidad de brindar conocimientos y habilidades a personas apasionadas por la hidroponía y la creación de granjas en casa. Ofrecemos una experiencia de aprendizaje integral que combina cursos en línea, recursos prácticos y una comunidad activa de entusiastas. Desde principiantes hasta expertos, nuestra plataforma proporciona las herramientas necesarias para adentrarse en el emocionante mundo de la agricultura en interiores. A través de contenido didáctico de alta calidad y asesoramiento personalizado, estamos transformando la forma en que las personas realizan el proceso de cultivo, promoviendo la sostenibilidad y la autosuficiencia en entornos urbanos y rurales por igual.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148057185847361546/logo.png" alt="logo" style="margin-bottom: 5px;" width="500"/>
</div>

- **Visión:** Aspiramos a ser líderes en la educación y tecnología que respaldan la revolución verde en interiores, transformando la forma en que se cultiva, consume y comparten los distintos tipos de cultivos.

- **Misión:** Proporcionar una plataforma educativa integral y de vanguardia que capacite a individuos interesados en la hidroponía y la agricultura en casa.

### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src=" " alt="Franco Felix Yance Gutierrez" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Yance Gutierrez, Franco Felix 
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
        Soy una persona apasionada por la tecnología y la programación, siempre interesado en estar al día con las últimas tendencias y avances en el área. Me encanta trabajar en equipo y colaborar para idear soluciones innovadoras y efectivas a problemáticas de la vida real. También me atrae el mundo de las start-ups y cómo pueden tener un impacto positivo en la sociedad a través de la tecnología. Me caracterizo por tener un pensamiento analítico y creativo, y siempre busco dar distintos puntos de vista a la hora de realizar un trabajo. Estoy comprometido en seguir aprendiendo y contribuyendo al desarrollo de la industria de la tecnología. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148059889537662976/pic_1.jpg" alt="Checa Paolo" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Checa Apolinario, Paolo Sebastián
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
        Poseo conocimientos en programación en el entorno del lenguaje C++. Estoy dispuesto a aportar nuevas ideas al equipo, tengo fácil adaptación a los roles designados y buena organización. Soy responsable y dispongo de la capacidad para aportar ideas innovadoras en beneficio de nuestro proyecto.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148303043629162647/054020181E187.jpg" alt="Pozo Rodrigo" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Pozo Campos, Rodrigo Jair
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
        Soy estudiante de la carrera de ingeniería de software, me considero una persona responsable en mis entregas y apasionada por el mundo tecnológico. Siento que puedo aportar mucho de mi en este grupo para poder realizar un buen producto. Tengo conocimientos en algunos lenguajes de programación como C++, Python y en desarrollo web. Pienso que nuestro grupo de trabajo puede generar resultados satisfactorios en base a los entregables y evidencias que mostremos a lo largo del curso.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148370399395074108/Diseno_sin_titulo.png" alt="Arenas José"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Arenas Conde, José Anthony
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
        Por lo general, me veo a mí mismo como alguien capaz de superar adversidades y hábil en varios campos, como la expresión verbal y escrita. También poseo conocimientos en la elaboración de productos, adquiridos a través de cursos previos. Como miembro de este equipo, mi meta es contribuir a la creación de un producto de calidad que satisfaga las necesidades de nuestros usuarios. Asimismo, soy alguien que sabe trabajar en conjunto y ha participado en numerosas empresas grupales en el pasado. Tengo la habilidad de escuchar y comprometerse con mis colegas, además de estar dispuesto a aceptar responsabilidades y contribuir con mi esfuerzo para alcanzar las metas del equipo.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148239074021351464/intranet_2020.jpg" alt="Cáceres Arnol"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Cáceres Bueno, Arnol Omar
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
        Me considero a mí mismo como una persona responsable, y apasionada por la tecnología. Poseo conocimientos en programación, en lenguajes como C++, C#, Java y Python. Me gusta aprender cosas nuevas y mejorar mis conocimientos, cuando no estoy estudiando me gusta leer, y escuchar música. Una de mis mejores cualidades es el trabajo en equipo, me considero alguien resiliente y productivo.
        </td>
    </tr>
</table>

## 1.2. Solution Profile

- **Nombre del Producto:**

    Nuestra aplicación web recibe el nombre de “GreenGrow”, ya que hacemos referencia a los cultivos que serán empleados por nuestros usuarios en la creación de sus proyectos caseros, quienes a su vez irán creciendo con nosotros, al adquirir conocimientos constantemente y mejorar sus habilidades en el sector agrícola.


- **Descripción del Producto:**

    Nuestra propuesta es un servicio novedoso e innovador, ofrecemos a nuestros usuarios la posibilidad de desarrollar sus propios proyectos domésticos basados en hidroponía, empezando con un nivel de principiantes hasta lograr convertirse en todos unos expertos en el tema. Nuestro servicio será intuitivo, sencillo y fácil de utilizar para cualquier persona que haga uso de la aplicación.

- **Monetización:**

    Nuestra aplicación generará ganancias por medio de anuncios, los cuales estarán relacionados con el tema agrícola. La publicidad mostrada podrá ser de insumos, equipamiento, productos, etc. Además, los expertos podrán ofrecer cursos Premium a los principiantes, lo que supondría una ganancia tanto para ellos como un porcentaje para nuestro equipo de trabajo. Por lo tanto, nuestro servicio será un entorno completo, ya que los usuarios podrán adquirir estos insumos y mejorar en el desarrollo de sus proyectos caseros.

### 1.2.1. Antecedentes y problemática

-   **What?**

    El problema de nuestros usuarios es la falta de conocimiento acerca de la creación de una granja en casa, así como su mantención a lo largo del tiempo.

-   **When?**

    El problema descrito se presenta cada vez que nuestros usuarios buscan información acerca de hidroponía, impidiendo que puedan tener su propias granjas domésticas.

-   **Where?**

    El problema se encuentra en la poca información que se puede llegar a recopilar en distintos medios, y lo poco que se consigue resulta ser dificultoso de entender.


- **Why?**

    Usualmente los usuarios no logran encontrar la información necesaria sobre hidroponía y granjas domésticas, por lo que deben buscar por medio de internet, preguntar a familia o amigos para encontrar la mayor información posible.

-   **How?**

    Resulta muy complicado para los principiantes poder encontrar los pasos necesarios para iniciar una granja en casa. Debido a esta problemática, surge nuestra aplicación, la cual servirá de apoyo a todos aquellos entusiastas a poner en práctica su pasión por la hidroponía y lograr su objetivo.

-   **How much?**

    La problemática se origina debido a que existe poca información que podemos encontrar sobre hidroponía en el hogar, y la que se encuentra puede resultar complicada para las personas nuevas en el tema. Además, la información proporcionada en páginas web llega a presentarse de forma desordenada, lo que genera más obstáculos para los usuarios.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

La hidroponía es una de las actividades que posee gran cantidad de practicantes, a la vez que existen personas que desean aventurarse en la hidroponía y la creación de granjas en casa. A menudo, estas personas se enfrentan a barreras que dificultan su acceso a la información y los recursos necesarios. La falta de una plataforma educativa integral y práctica hace que la curva de aprendizaje sea empinada y desafiante. Además, la falta de interacción significativa con una comunidad activa de personas con ideas afines puede hacer que este proceso se sienta aislado. Es por este motivo que, como startup, abordaremos la resolución de la siguiente cuestión: ¿Cómo podemos aplicar nuestro conocimiento tecnológico para ofrecer un servicio novedoso que pueda ofrecer la información necesaria para los principiantes en la hidroponía?
    
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
    <img src="https://i.imgur.com/96Ok3zu.jpeg" alt="Canvas"/>
</div>

## 1.3. Segmentos Objetivo

| Tipo de Usuario | Personas que deseen iniciar en la hidroponía | Expertos que desean brindar sus conocimientos a los principiantes |
|:---|:-----|:-----|
| Geográfico | País: Perú, Zona residencial: No es relevante, pueden ser de diferentes zonas del país. | País: Perú, Zona residencial: No es relevante, pueden ser de diferentes zonas del país. |
| Psicográfico | Clase Social: Mayormente se encuentran desde la clase media baja, hacia clases sociales más elevadas. Estilo de vida: Son personas apasionadas por el tema de la agricultura y las granjas en casa, sin embargo no poseen los conocimientos para iniciar su propio proyecto. | Clase Social: Mayormente se encuentran desde la clase media baja, hacia clases sociales más elevadas. Estilo de vida: Son personas dedicadas a la hidroponía, con cierto tiempo de experiencia en el tema, por lo que quieren ofrecer ayuda a los principiantes.
| Demográfico | Edad: Personas mayores de edad. Nivel de Ingreso: No es relevante, ya que depende de los factores que se elijan. Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte. | Edad: Deben ser mayores de edad, preferiblemente mayores de 30 años. Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte. Estudios: Debe contar con secundaria completa o superior.

<br><br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
<br>
Luego de realizar una investigación en el mercado peruano, hemos encontrado tres proyectos similares a GreenGrow. Por ello, los concideramos como potenciales competidores. Estos son:
<br>
**Hidroponika:**
<br>
Es un Web browser que cuenta con una gama completa de productos y servicios de calidad relacionados con la hidrocultura. Además, posee soluciones nutritivas para todo tipo de plantas, desde tu propio huerto.
<br>
<img src="https://i.imgur.com/sPqvU40.pngwidth=600&amp;height=600" style="max-width: 460px; width: 25%;">
<br>
**Intagri:**
<br>
Es un portal que ofrece distintos tipos de información acerca de los distintos tipos de cultivos. Además, ofrece también distintas conferencias y cursos dictados por expertos acerca de la agricultura.
<br>
<img src="https://i.imgur.com/Ynnwv7G.jpg?width=547&amp;height=118" style="max-width: 600px; width: 40%;">
<br>
**Mundo Hidroponia:**
<br>
Es un portal que ofrece una gran cantidad de productos para la hidroponía como nutrientes, huertos, semillas, etc. Además, ofrece también servicios de envío para sus productos hacia sus clientes.
<br>
<img src="https://i.imgur.com/pY6oo3B.jpg?width=1447&amp;height=814" style="max-width: 600px; width: 60%;">
<br>

### 2.1.1. Análisis competitivo

<table>
<tbody><tr><th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th></tr><tr><td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td><td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td></tr><tr><td colspan="5">Este análisis se concretó teniendo como finalidad el poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de ellos.</td></tr><tr><td colspan="3">Nuestro Producto / Competidores</td><td colspan="1" valign="top" style="font-weight: bold;">GreenGrow<br><img src="https://i.imgur.com/jwNgfz4.jpg?width=2002&amp;height=1345" alt="GreenGrow" width="70px"></td><td colspan="1" valign="top" style="font-weight: bold;">Hidroponika<br><img src="https://i.imgur.com/sPqvU40.png?width=600&amp;height=600" alt="Hidroponika" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Intagri<br><img src="https://i.imgur.com/Ynnwv7G.jpg?width=547&amp;height=118" alt="Intagri" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Mundo Hidroponia<br><img src="https://i.imgur.com/pY6oo3B.jpg?width=1447&amp;height=814" alt="Mundo Hidropnia" width="60px"></td></tr><tr><td colspan="1" rowspan="2">Perfil</td><td colspan="2">Overview</td><td colspan="1" valign="top">Aplicación web donde los clientes podrán informarse acerca de la hidroponía, mantenerse informado cada dia sobre diversos temas de la hidroponía y poder realizar cursos interactivos donde aprenda distintas técnicas o materiales a usar.</td><td colspan="1" valign="top">Es una página web que cuenta con una gran variedad de productos y servicios relacionados a la hidroponía, de gran calidad y para distintos lugares.Además posee distintos cursos para iniciar en la hidroponía.</td><td colspan="1" valign="top">Es una página web que ofrece distintos tipos de información sobre agricultura.  Ofrecen capacitaciones y cursos donde explican distintos tipos de métodos a utilizar en la agricultura. Estos cursos los dictan de manera presencial o virtual dependiendo del área que dicten.</td><td colspan="1" valign="top">Es una página web que ofrece distintos productos para la hidroponia como nutrientes para las plantas, huertas donde irán instaladas estas plantas y semillas de distintos tipos.</td></tr><tr><td colspan="2">Ventaja competitiva</td><td colspan="1" valign="top">Una mejor variedad de productos acorde a la economía de las personas y a los distintos lugares del Perú. Además de un continuo seguimiento de nuestros clientes para poder aclarar alguna duda o problema que pueda surgir.</td><td colspan="1" valign="top">Una gran cantidad de productos, packs, soluciones y demás para la hidroponia. Tiene una sólida interfaz donde explican los servicios que ofrece la empresa y los beneficios de realizar hidroponia.</td><td colspan="1" valign="top">Una ventaja que ellos tienen a diferencia de otros es la gran cantidad de cursos que dictan, esto hace que muchas personas elijan sus servicios para aprender más acerca de distintos temas de agricultura y también sobre de la hidroponia.</td><td colspan="1" valign="top">Gran variedad de semillas y nutrientes para la hidroponia. Esto hace que sean un lugar concurrido para las personas que tengan este tipo de huertos.</td></tr><tr><td colspan="1" rowspan="2">Perfil de Marketing</td><td colspan="2">Mercado objetivo</td><td colspan="1" valign="top">Personas de todo el Perú que quieran comenzar a utilizar la técnica de hidroponía para cultivar en sus casas o personas que necesitan materiales para seguir ciudadano sus cultivos</td><td colspan="1" valign="top">Personas de todo el Perú que quieran obtener sus productos o empezar en la hidroponía en sus hogares u otros lugares.</td><td colspan="1" valign="top">Personas que estén interesadas en aprender más sobre la hidroponía, dispuestos a llevar cursos y asistir en charlas que Intagri ofrece.</td><td colspan="1" valign="top">Personas que se dedican a cultivar plantas con la técnica de hidroponía.</td></tr><tr><td colspan="2">Estrategias de marketing</td><td colspan="1" valign="top">Publicidad a través de redes sociales</td><td colspan="1" valign="top">En las principales redes sociales.</td><td colspan="1" valign="top">En las principales redes sociales, linkedin y en empresas aliadas como Fertilab y Proain.</td><td colspan="1" valign="top">Publicidad a través de las principales redes sociales</td></tr><tr><td colspan="1" rowspan="3">Perfil de Producto</td><td colspan="2">Productos &amp; Servicios</td><td colspan="1" valign="top">Brindar un servicio de calidad mediante la información que mostraremos en nuestra página, La creación de cursos didácticos de distintos temas de la hidroponía, además de la creación de comunidades donde las personas puedan contar sus experiencias o recomendar distintas cosas.</td><td colspan="1" valign="top">Gran variedad de productos desde nutrientes para las plantas hasta hidro huertos de distintos tamaños y para distintos tipos de plantas.</td><td colspan="1" valign="top">Los productos que ellos ofrecen son los cursos y capacitaciones sobre distintos temas acerca de la agricultura.</td><td colspan="1" valign="top">Gran variedad de productos desde nutrientes para las plantas hasta huertos de distintos tamaños y para distintos tipos de plantas.</td></tr><tr><td colspan="2">Precios &amp; Costos</td><td colspan="1" valign="top">Los precios y costos por nuestros cursos se mostrarán en la pantalla de compra del producto. Asimismo trataremos de mantener los precios lo más accesible para todo público.</td><td colspan="1" valign="top">Los costos varían desde los más baratos que son las soluciones desde los 20 soles hasta los más caros que son los hidro huertos que pueden pasar los 1000 soles.</td><td colspan="1" valign="top">Sus precios varían entre los cursos que son los más cómodos hasta los diplomados internacionales que valen mucho dinero.</td><td colspan="1" valign="top">Los costos varían desde los más baratos que son los nutrientes y semillas hasta los más caros que son los huertos que pueden costar una gran cantidad de dinero dependiendo del tamaño de estos.</td></tr><tr><td colspan="2">Canales de distribución (Web y/o Móvil)</td><td colspan="1" valign="top">Se contará con una página web en donde se encontrará todo lo que ofrecemos e información acerca de nosotros </td><td colspan="1" valign="top">Se hacen envíos a todo el Perú mediante empresas de courier tanto para Lima metropolitana hasta los distintos departamentos del país.</td><td colspan="1" valign="top">La mayoría de cursos que dictan son virtuales pero los seminarios o congresos que ellos dicten son presenciales.</td><td colspan="1" valign="top">Ofrecen sus servicios por medio de empresas de courier en el territorio argentino.</td></tr><tr><td colspan="1" rowspan="5">Análisis SWOT</td><td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td></tr><tr><td colspan="2">Fortalezas</td><td colspan="1" valign="top">Brindar información de distintos temas sobre la hidroponía, además de estar validadas por un especialista. Comunicación constante con los clientes.</td><td colspan="1" valign="top">Una gran variedad de productos para ofrecer a todos sus clientes.</td><td colspan="1" valign="top">Una gran variedad de cursos de distintos temas que pueden atraer a distintas personas. Capacitaciones y ponencias de manera presencial hacen que sean más reconocidos por sus demás competidores.</td><td colspan="1" valign="top">Gran variedad de semillas para la plantación de estas, distintos nutrientes que ayudan a la planta a crecer y gran variedad de huertos de distintos tamaños y para distintos propocitos.</td></tr><tr><td colspan="2">Debilidades</td><td colspan="1" valign="top">Falta de credibilidad por ser una startup nueva y no ser tan reconocida en el medio.</td><td colspan="1" valign="top">Falta de comunicación con los clientes. Sus únicos medios de comunicación son las redes sociales y whatsapp, por lo que se puede tardar a la hora de responder algún mensaje.</td><td colspan="1" valign="top">Al tener un catálogo muy amplio de cursos y temas que ofrecen, no pueden enfocarse en un tema en específico por lo que algunas ocasiones no resolverán la duda al cliente.</td><td colspan="1" valign="top">Algunas personas no podrán conocer qué tipos de nutrientes necesitan para sus plantas o que tipos de huertas se acomodan más a su lugar de plantación.</td></tr><tr><td colspan="2">Oportunidades</td><td colspan="1" valign="top">Falta de información por especialistas en el tema.. Falta de plataformas que ofrezcan servicios de hidroponía a nivel nacional.</td><td colspan="1" valign="top">Falta de lugares o webs donde una persona pueda encontrar todo lo relacionado a la hidroponía, soluciones, semillas, huertos, etc.</td><td colspan="1" valign="top">Falta de lugares donde dicten cursos de una gran variedad de temas. Los eventos presenciales muchas veces no son tan completos como sí lo es el de Intagri.</td><td colspan="1" valign="top">Al tener una gran variedad de productos podrán satisfacer las necesidades de sus clientes.</td></tr><tr><td colspan="2">Amenazas</td><td colspan="1" valign="top">Las personas en primera instancia no confiarán en nosotros por ser una nueva empresa. Falta de socios los cuales nos puedan ayudar en el tema económico de la startup.</td><td colspan="1" valign="top">Algunas personas no contarán con el presupuesto suficiente para poder comprar las estaciones esenciales donde cultivar las plantas utilizando esta técnica.</td><td colspan="1" valign="top">Algunas personas no podrán acceder a sus cursos presenciales por falta de tiempo o por la locación de estas capacitaciones.</td><td colspan="1" valign="top">Los mismos productos podrán ser encontrados en otros tipos de páginas</td></tr></tbody></table>

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

Edad: 35  años

Ubicación: Surquillo, Lima

Evidencia de la reunión:
<img src="https://i.imgur.com/NO1C0MS.png?width=1875&amp;height=896" alt="Canvas" width="90%">

Inicio: 21:22

Fin: 23:12


Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112749_upc_edu_pe/EWbJoHEqXipGj3qaPPhq4SsBNkgCc1rfTp7IRdmZaZNykA?e=GeWqmo)

**Resumen de la entrevista:**

La entrevistada Karina Campos nos comenta que inició en el mundo de la hidroponía ya que desde siempre le gustaron las actividades de cosecha y cultivar plantas.Esto hizo que  al enterarse que había una técnica de plantación que funcionaba en base al crecimiento en huertas y mediante sustancias como minerales y soluciones las plantas podrían crecer en un espacio como su casa. Además nos comenta que está dispuesta a poder enseñar a los que quieren iniciar en la plantación mediante la hidroponía, además nos cuenta qué le parecería bien que exista una plataforma donde ella pueda dar a conocer sus conocimientos y experiencias sobre distintos cuidados que debe de tener esta técnica.

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

**Segmento 1:  Personas que deseen iniciar en la hidroponía**

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
<img src="https://i.imgur.com/PSlIthL.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">


**User Persona del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<img src="https://i.imgur.com/Q9gcD49.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">

### 2.3.2. User Task Matrix
En esta User Task Matrix, se describen las tareas típicas que realizan los dos segmentos de usuarios: personas que deseen iniciar en la hidroponía y expertos que desean brindar sus conocimientos. Se evalúa la frecuencia y la severidad de cada tarea, lo que ayuda a priorizar y entender cuáles son las áreas clave en las que el producto GreenGrow podría intervenir para satisfacer las necesidades y los objetivos de ambos segmentos.

**Segmento Objetivo:** Personas que deseen iniciar en la hidroponía


| Tarea | Frecuencia | Severidad |
|:----------:|:----------:|:----------:|
| Investigar sobre la hidroponía| Casi siempre | Baja |
|Buscar recursos en línea| Casi siempre | Media|
| Consultar con amigos y expertos| A veces | Baja |
| Seleccionar el tipo de cultivo | A veces   | Media |
| Adquirir suministros y equipos| A veces  | Alta |
| Montar el sistema hidropónico | A veces  | Media |
| Cultivar y mantener las plantas| Casi siempre| Alta |
| Solucionar problemas (plagas, nutrientes)| A veces | Media |
| Participar en una comunidad de aprendizaje|A veces|Baja|
| Experimentar con nuevas técnicas| Rara Vez | Baja |
|Evaluar el éxito del cultivo |Casi siempre | Media |


**Segmento Objetivo:** Expertos que desean brindar sus conocimientos a los principiantes

| Tarea | Frecuencia | Severidad |
|:----------:|:----------:|:----------:|
|Compartir consejos en foros y redes sociales |Casi siempre | Baja |
|Presentar en eventos de agricultura | A veces  | Media|
| Responder consultas personales|  A veces | Alta |
| Buscar plataformas para cursos en línea| A veces| Media |
|Crear contenido educativo (artículos, videos)| A veces | Alta |
| Diseñar y estructurar cursos|Rara vez|Alta|
| Ofrecer cursos en línea |Rara vez|Alta|
| Mantener y actualizar contenido	 |Rara vez|Media|
| Colaborar con otros expertos |Rara vez|Baja|
| Evaluar la eficacia de la enseñanza |Rara vez|Baja|

### 2.3.3. User Journey Mapping

**User Journey Mapping del segmento: Personas que deseen iniciar en la hidroponía**
<img src="https://i.imgur.com/iFcacsq.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">


**User Journey Mapping del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<img src="https://i.imgur.com/uF8o7iK.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">

### 2.3.4. Empathy Mapping

Los Mapas de Empatía son esenciales para el proyecto GreenGrow, ya que permiten una comprensión profunda y holística de las experiencias, pensamientos y emociones de los usuarios clave. Estos mapas ofrecen una visión integral de cómo los usuarios piensan, sienten, ven, escuchan, dicen y hacen en relación con la hidroponía y la agricultura en interiores. Al proporcionar una representación visual y detallada de sus perspectivas y necesidades, los Mapas de Empatía guían el desarrollo de la plataforma al asegurar que se aborden los problemas reales y se cumplan las expectativas de los usuarios.


**Empathy Map del segmento: Personas que deseen iniciar en la hidroponía**
<img src="https://i.imgur.com/eBSLWNG.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">


**Empathy Map del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<img src="https://i.imgur.com/S0EtpMe.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">

### 2.3.5. As-is Scenario Mapping
Los escenarios AS-IS son esenciales para el proyecto GreenGrow, ya que brindan una visión detallada de los pasos, pensamientos y emociones de los usuarios antes de conocer el producto. Estos escenarios permiten comprender sus necesidades y desafíos actuales, lo que ayuda al equipo a diseñar una experiencia más efectiva y enfocada en resolver problemas reales. Al analizar los AS-IS, el producto puede ser desarrollado de manera que satisfaga las expectativas y proporcione soluciones alineadas con las experiencias actuales de los usuarios, resultando en un producto más exitoso y relevante.

**As-is Scenario Map del segmento: Personas que deseen iniciar en la hidroponía**
<img src="https://i.imgur.com/OIsMvCL.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">


**As-is Scenario Map del segmento: Expertos que desean brindar sus conocimientos a los principiantes**

<img src="https://i.imgur.com/9sZtJDe.pngwidth=600&amp;height=600" style="max-width: 1000px; width: 80%;">

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
| Epic ID  | Titulo de Épica | Descripción de la épica | 
|:---|:-----|:-----|
|EP001|Definición de funcionalidades de la aplicación web|Como usuario deseo que la página ofrezca información acerca de distintos temas sobre la agricultura, principalmente la hidroponía. Como ayuda para mis plantaciones mediante esta técnica.|
|EP002|Opciones relacionadas a la cuenta del usuario|Como usuario deseo poder crear una cuenta en la página así como editarla y agregar información relevante.|
|EP003|Opciones relacionadas a la cuenta del experto.|Como experto deseo poder crearme una cuenta asi como poder publicar artículos y cursos de temas de donde me especializo, además de poder potenciar mi cuenta una suscripción..|
|EP004|Definición de estructura del landing page |Como usuario deseo disponer de un landing page con información pertinente para conocer mejor acerca de la aplicación web |
<br><br>

| Epic / Story ID | Título | Descripción |Criterios de Aceptación |Relacionado con (Epic ID)|
|:---------|:---------|:--------|:--------|:------|
|**US01**|Registro de personas|Como usuario deseo registrarme en la página para observar todo lo que me ofrece la aplicación.|**Escenario 1: Crear una cuenta** <br>**Dado** que el usuario se encuentra en sección de inicio **Cuando** el usuario no se encuentra registrado en la página **Entonces** al seleccionar “Crear Cuenta” el sistema le redireccionará al registro.<br> **Escenario 2: Rellenado de datos correctamente.**<br> **Dado** que el usuario se encuentra en la sección de registro **Cuando** al rellenar todos los datos correctamente y se verifique que todo está correcto.**Entonces** el sistema registra sus datos ingresados a la base de datos.<br> **Escenario 3: Rellenado de datos incorrectamente.**<br> **Dado** que el usuario se encuentra en la sección de registro **Cuando** él ingresa los datos incorrectamente o no están completos, **Entonces** el sistema le indicará que “Está incorrecto “o “Falta rellenar este dato·.|EP002|
|**US02**|Registro de expertos|Como experto deseo registrarme en la página para poder escribir artículos acerca de mi área de especialidad y tener mejor control de las publicaciones que haga.|**Escenario 1: crear una cuenta.<br>** **Dado** que el experto se encuentra en sección de inicio **Cuando** el experto no se encuentra registrado en la página **Entonces** al seleccionar “Crear Cuenta” el sistema le redireccionará al registro.<br> **Escenario 2: Rellenado de datos correctamente.<br>** **Dado** que el experto se encuentra en la sección de registro **Cuando** al rellenar todos los datos correctamente y se verifique que todo está correcto. **Entonces** el sistema registra sus datos ingresados a la base de datos.<br> **Escenario 3: Rellenado de datos incorrectamente.<br>** **Dado** que el experto se encuentra en la sección de registro **Cuando** él ingrese los datos incorrectamente o no están completos, **Entonces** el sistema le indicará que “Está incorrecto “o “Falta rellenar este dato·.|EP003|
|**US03**|Pago de suscripción de cuenta|Como usuario deseo poder pagar los cursos que la página ofrezca desde la aplicación para que no se me dificulte en otras formas.|**Escenario 1: Ver cursos disponibles<br>** **Dado** que el usuario se encuentra en la pestaña de cursos **Cuando** el usuario selecciona uno de los cursos a comprar **Entonces** la aplicación le mostrará el saldo final y los métodos de pago con los que podrá comprarlo.<br> **Escenario 2: Escoger métodos de pago<br>** **Dado** que el usuario escogió su curso **Y** el usuario se encuentra en la pantalla de pago **Cuando** el usuario ingrese los datos solicitados por la página **Entonces** la página le mostrará un mensaje diciendo “Pago de curso realizado”.|EP001|
|**US04**|Observar las distintas informaciones de especialistas con mejores calificaciones |Como usuario deseo poder saber cuales son los artículos actuales con una mejor puntuación y de igual manera con los cursos que ofrecen.|**Escenario 1: Visualización general de artículos y cursos<br>** **Dado** que el usuario selecciona “explorar artículos” **Cuando** el usuario filtre los artículos de información por los más votados o con mejores calificaciones **Entonces** se le mostrará cuáles son los artículos de información con mejores calificación por parte de otros usuarios.|EP001|
|**US05**|Visualización de recomendaciones de cursos por parte de los usuarios |Como usuario quiero visualizar la opinión de otros usuarios hacia los distintos cursos para conocer mejor cuales son los cursos que más valen la pena.|**Escenario 1: Cuándo hay cursos con calificaciones de otros usuarios<br>** **Dado** que el usuario está en la sección “Explorar cursos” **Cuando** selecciona algún curso en particular **Entonces** el sistema mostrará todos los comentarios del curso seleccionado, así sean positivos o negativos.<br> **Escenario 2: Cuándo hay cursos sin ningún comentario o calificación<br>** **Dado** que el usuario está en la sección “Explorar cursos” **Cuando** selecciona algún curso en particular y este no tiene ningún comentario. **Entonces** lel sistema indicará que por el momento no existe ninguna calificación o comentario en el curso.|EP001|
|**US06**|Ver comentarios de usuarios |Como experto quiero ver las reseñas de mis cursos para ver el recibimiento de los usuarios.|**Escenario 1: Cuándo hay cursos puntuados por los usuarios<br>** **Dado** que el experto está en la sección “Mis cursos” **Cuando** selecciona algún curso en particular **Entonces** el sistema mostrará todos los comentarios que los usuarios han realizado a su curso.  <br> **Escenario 2: Cuándo hay cursos sin ningún comentario o calificación<br>** **Dado** que el experto está en la sección “Mis cursos” **Cuando** selecciona algún curso en particular y este no tiene ningún comentario. **Entonces** el sistema indicará que por el momento no existe ninguna calificación o comentario en el curso.|EP003|
|**US07**|Registros de los cursos |Como experto quiero crear mis propios cursos con herramientas que me proporciona la página o con mis propias herramientas.|**Escenario 1: Registro de cursos de manera correctamente<br>** **Dado** que el experto se encuentre en el sector de “Crear curso”  **Cuando** se selecciona ingresar videos e ingresa todos los datos requeridos **Entonces** el sistema muestra un mensaje indicando que el curso se ha registrado satisfactoriamente.  <br> **Escenario 2: Registro de cursos de manera incorrectamente<br>** **Dado** que el experto se encuentre en el sector de “Crear curso”  **Cuando** se selecciona ingresar videos y no ingresa todos los datos requeridos  **Entonces** el sistema muestra un mensaje indicando que el curso no se registró correctamente.|EP003|
|**US08**|Visualización del Landing pages |Como usuario en busca de información deseo visualizar toda la información y así ver lo que ofrece la página.|**Escenario 1: El usuario visualiza la sección landing page.<br>** **Dado** que el invitado del sector de usuario se encuentra en el landing page **Cuando** ingrese a nuestra landing page **Entonces** verá toda la información que ofrece nuestro producto.|EP004|
|**US09**|Visualización de los servicios que ofrecen en el landing page |Como invitado deseo visualizar los beneficios de la página, así como los servicios que esta ofrece.|**Escenario 1: El invitado visualiza la sección de servicios<br>** **Dado** que el invitado se encuentra en el landing page  **Cuando** llega hasta la sección de servicios **Entonces** podrá informarse acerca de todos los servicios que ofrecerá nuestra página|EP004|
|**US10**|Visualización de los testimonios de personas sobre la landing page |Como invitado deseo visualizar los testimonios de distintas personas acerca de la landing page para ver si es lo que busco o no.|**Escenario 1: El invitado visualiza la sección Testimonios.<br>** **Dado** que el invitado se encuentra en el landing page   **Cuando** llega hasta la sección de Testimonios **Entonces** podrá informarse acerca de todos los testimonios de personas acerca de nuestra página|EP004|
<br><br>

## 3.3 Impact Mapping
<div align=center>
    <img src="https://i.imgur.com/zjIdX1s.jpg" alt="Impact Mapping">
</div>

## 3.4 Product Backlog
| # Orden | User Story Id | Título |Descripción |Story Points (1 / 2 / 3 / 5 / 8)|
|:---------|:---------|:--------|:--------|:------|
|1|UH01|Registro de personas|Como usuario deseo registrarme en la página para observar todo lo que me ofrece la aplicación.|3|
|2|UH02|Registro de expertos|Como experto deseo registrarme en la página para poder escribir artículos acerca de mi área de especialidad y tener mejor control de las publicaciones que haga.|3|
|3|UH03|Pago de suscripción de cuenta|Como usuario deseo poder pagar los cursos que la página ofrezca desde la aplicación para que no se me dificulte en otras formas.|3|
|4|UH04|Observar las distintas informaciones de especialistas con mejores calificaciones |Como usuario deseo poder saber cuales son los artículos actuales con una mejor puntuación y de igual manera con los cursos que ofrecen.|5|
|5|UH05|Visualización de recomendaciones de cursos por parte de los usuarios |Como usuario quiero visualizar la opinión de otros usuarios hacia los distintos cursos para conocer mejor cuales son los cursos que más valen la pena.|5|
|6|UH06|Ver comentarios de usuarios |Como experto quiero ver las reseñas de mis cursos para ver el recibimiento de los usuarios.|5|
|7|UH07|Registros de los cursos |Como experto quiero crear mis propios cursos con herramientas que me proporciona la página o con mis propias herramientas.|3|
|8|UH08|Visualización del Landing pages |Como usuario en busca de información deseo visualizar toda la información y así ver lo que ofrece la página.|3|
|9|UH09|Visualización de los servicios que ofrecen en el landing page |Como invitado deseo visualizar los beneficios de la página, así como los servicios que esta ofrece.|2|
|10|UH10|Visualización de los testimonios de personas sobre la landing page |Como invitado deseo visualizar los testimonios de distintas personas acerca de la landing page para ver si es lo que busco o no.|2|
