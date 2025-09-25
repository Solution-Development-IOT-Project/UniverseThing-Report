
<hr>

# <center>Informe de Trabajo Final</center>

<h3 align="center"> Universidad Peruana de Ciencias Aplicadas </h3>

<h3 align="center"> Ingeniería de Software </h3>

<h3 align="center">Ciclo 2025 - 2</h3>


<div align="center">
  <img width=250 src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"/>
</div>


<h1 align="center"> TB1 Report </h1>

<h3 align="center"> Docente: Marco Antonio Leon Baca </h3>

<h3 align="center"> 1ASI0572 - Desarrollo de Soluciones IoT </h3>

<h4 align="center"> NRC: 3414 </h4>


<h3> Startup: UniverseThing </h3>

<h3> Product: AgroPre </h3>

<h3> Team Members: </h3>

<div align="center">

| Member                         |    Code    |
|:-------------------------------|:----------:|
| Loarte Matos, Anthony Brahan   |            |
| Cipriano Chumbes, Bruce Andres |            |
| Quispe Tipo, Godofredo         | U202120772 |
| Riegas Salas, Jose Miguel      |     U202211254     |
| Ruiz Torres Erick Hernan       | U202118946 |

</div>

<h3 align="center">Agosto, 2025</h3>

<br><br>

# Registro de Versiones del Informe

| Versión |   Fecha    |                                                                                                                                                                                                                                                                                                                                           Descripción                                                                                                                                                                                                                                                                                                                                            |               Autor               |
|:-------:|:----------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------:|
|   0.1   | 2025-09-18 |                                                                            Desarrollo de los ítems: 1.1. Startup Profile, que incluye los subítems 1.1.1. Descripción de la Startup y 1.1.2. Perfiles de integrantes del equipo. Luego se presenta el 1.2. Solution Profile, que contiene los apartados 1.2.1. Antecedentes y problemática y 1.2.2. Lean UX Process, el cual se desglosa en 1.2.2.1. Lean UX Problem Statements, 1.2.2.2, 1.2.2.3 y 1.2.2.4. Finalmente, se desarrolla la sección 1.3. Lean UX Assumptions, que incluye los ítems Lean UX Hypothesis Statements, Lean UX Canvas y Segmentos objetivo.                                                                            |         Godofredo Quispe          |
|   0.2   | 2025-09-19 |    Desarrollo de los ítems: La sección 2 del informe está compuesta por varios apartados clave, comenzando con el 2.1. Competidores, que abarca los subítems 2.1.1. Análisis competitivo y 2.1.2. Estrategias y tácticas frente a competidores. Luego se desarrolla el 2.2. Entrevistas, que incluye 2.2.1. Diseño de entrevistas, 2.2.2. Registro de entrevistas y 2.2.3. Análisis de entrevistas. A continuación, se presenta el 2.3. Needfinding, compuesto por 2.3.1. User Personas, 2.3.2. User Task Matrix, 2.3.3. User Journey Mapping, 2.3.4. Empathy Mapping y 2.3.5. As-is Scenario Mapping. Finalmente, se cierra esta parte del informe con el apartado 2.4. Ubiquitous Language.    | Anthony Loarte y Godofredo Quispe |
|   0.3   | 2025-09-20 |                                                                                                                                                                                                                                                                          Desarrollo de los ítems: 3.1. To-Be Scenario Mapping, 3.2. Avance de las User Stories, 3.3. Impact Mapping y 3.4. Avance del Product Backlog.                                                                                                                                                                                                                                                                           |   Bruce Cipriano y Jose Riegas    |
|   0.4   | 2025-09-20 |                                   Desarrollo de los ítems: 3.2. Finalizacion de las User Stories, 3.4. Finalizacion del Product Backlog, 4.1. Strategic-Level Domain-Driven Design y comprende los siguientes subítems: 4.1.1. EventStorming, que a su vez incluye 4.1.1.1. Candidate Context Discovery, 4.1.1.2, 4.1.1.3. Domain Message Flows Modeling y Bounded Context Canvases. También se desarrolla el apartado 4.1.2. Context Mapping y 4.1.3. Software Architecture, que contiene 4.1.3.1. Software Architecture Context Level Diagrams, 4.1.3.2. Software Architecture Container Level Diagrams y 4.1.3.3 Software Architecture Deployment Diagrams.                                   |           Erick Riegas            |
0.5   | 2025-09-20 |                                   Desarrollo de los ítems: 4.1. Strategic-Level Domain-Driven Design y comprende los siguientes subítems: 4.1.1. EventStorming, que a su vez incluye 4.1.1.1. Candidate Context Discovery, 4.1.1.2, 4.1.1.3. Domain Message Flows Modeling y Bounded Context Canvases. También se desarrolla el apartado 4.1.2. Context Mapping y 4.1.3. Software Architecture, que contiene 4.1.3.1. Software Architecture Context Level Diagrams, 4.1.3.2. Software Architecture Container Level Diagrams y 4.1.3.3 Software Architecture Deployment Diagrams.                  4.2. Tactical-Level Domain-Driven Design,Bounded Context, Domain Layer Interface Layer,Application Layer, Infrastructure Layer, Bounded Context Software Architecture Component Level Diagrams,Bounded Context Software Architecture Code Level Diagrams,Bounded Context Domain Layer Class Diagrams,Bounded Context Database Design Diagram                 |           Erick Ruiz Torres          |

<br><br>

# Project Report Collaboration Insights
El enlace a github del reporte del proyecto es el siguiente: <a href="https://github.com/Solution-Development-IOT-Project/UniverseThing-Report">https://github.com/Solution-Development-IOT-Project/UniverseThing-Report</a>
<br><br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción-1)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hyphotesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-1)

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
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Solutions Software Design](#capítulo-iv-solution-software-design)

- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded COntext Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
    - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
    - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
    - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.X. Bounded Context: <Bounded Context name>](#42x-bounded-context)
    - [4.2.X.1. Domain Layer](#42x1-domain-layer)
    - [4.2.X.2. Interface Layer](#42x2-interface-context)
    - [4.2.X.3. Application Layer](#42x3-application-context)
    - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-context)
    - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
    - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
      - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)

### [Capítulo V: Solution UI/UX Design](#capítulo-v-solutions-uiux-design)

- [5.1. Style Guidelines](#51-style-guidelines)
  - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
  - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
  - [5.2.1. Organization Systems](#521-organization-systems)
  - [5.2.2. Labeling Systems](#522-labeling-systems)
  - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
  - [5.2.4. Searching Systems](#524-searching-systems)
  - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
  - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
  - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-web-applications-uxui-design)
  - [5.4.1. Applications Wireframes](#541-web-applications-wireframes)
  - [5.4.2. Applications Wireflow Diagrams](#542-web-applications-wireflow-diagrams)
  - [5.4.3. Applications Mock-ups](#543-web-applications-mock-ups)
  - [5.4.4. Applications User Flow Diagrams](#544-web-applications-user-flow-diagrams)
- [5.5. Aplications Prototyping](#55-applications-prototyping)

### [Capítulo VI: Product Implementation, Validation \& Deployment](#capítulo-vi-product-implementation-validation--deployment)

- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
  - [6.1.2. Source Code Management](#612-source-code-management)
  - [6.1.3. Source Code Style Guide \& Conventions](#613-source-code-style-guide--conventions)
  - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page, Services \& Applications Implementation](#62-landing-page-services--applications-implementation)
  - [6.2.X. Sprint X](#62x-sprint-n)
    - [6.2.X.1. Sprint Planning 1](#62x1-sprint-planning-n)
    - [6.2.X.2. Sprint Backlog 1](#62x2-sprint-backlog-n)
    - [6.2.X.3. Development Evidence for Sprint Review](#62x3-development-evidence-for-sprint-review)
    - [6.2.X.4. Testing Suite Evidence for Sprint Review](#62x4-testing-suite-evidence-for-sprint-review)
    - [6.2.X.5. Execution Evidence for Sprint Review](#62x5-execution-evidence-for-sprint-review)
    - [6.2.X.6. Services Documentation Evidence for Sprint Review](#62x6-services-documentation-evidence-for-sprint-review)
    - [6.2.X.7. Software Deployment Evidence for Sprint Review](#62x7-software-deployment-evidence-for-sprint-review)
    - [6.2.X.8. Team Collaboration Insights during Sprint](#62x8-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)

### [Conclusiones](#conclusiones-1)

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

### [Bibliografía](#bibliografía-1)

### [Anexos](#anexos-1)

<br><br>

# Student Outcome

<b>ABET – EAC - Student Outcome 5:</b> La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

<table>
  <tr>
    <td><strong>Criterio Específico</strong></td>
    <td><strong>Acciones Realizadas</strong></td>
    <td><strong>Conclusiones</strong></td>
  </tr>
  <tr>
    <td>Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>
    <td>
      Erick Ruiz <br>
        TB1:<br> Lideré el desarrollo del primer capítulo para tener una visión clara del proyecto. Asimismo, desarollé en conjunto la primera versión de nuestras historias de usuario <br>
        TP1:<br>  <br>
        TB2:<br>  <br>
        TF1: <br>  <br>
      Jose Riegas<br>
        TB1:<br> Para el desarrollo del proyecto he participado de manera activa tanto en la toma de decisiones como en la división de responsabilidades, de la misma manera he ayudado en responsabilidades de mis compañeros con el afán de entregar un mejor producto.<br> 
        TP1:<br>  <br>  
        TB2:<br>  <br>
        TF1: <br>  <br>
      Anthony Loarte<br>
        TB1:<br> Durante el proyecto Bliss, mi enfoque ha sido mantener la cohesión del equipo, facilitando una comunicación fluida y asegurando que todas las voces fueran escuchadas. He trabajado mano a mano con mis compañeros para resolver conflictos y establecer un liderazgo compartido, lo que ha sido clave para el éxito del equipo.<br> 
        TP1: <br> <br>
        TB2: <br> <br>
        TF1: <br>  <br>
      Bruce Cipriano<br>
        TB1:<br> He contribuido activamente en el liderazgo compartido, facilitando la toma de decisiones y promoviendo la responsabilidad colectiva.<br> 
        TP1:<br>  <br> 
        TB2: <br>  <br>  
        TF1:<br>  <br>
      Godofredo Quispe<br>
        TB1: <br>Durante la entrega, completé las tareas asignadas de manera eficiente, asegurándome de reportar el progreso regularmente. Participé activamente en las reuniones del equipo, compartiendo sugerencias, atendiendo las opiniones de los demás y colaborando en la solución de los desafíos presentados.<br>
        TP1: <br><br>
        TB2: <br><br>
        TF1: <br><br>
</td>
    <td>
      TB1:<br> A lo largo del desarrollo del proyecto, hemos demostrado una fuerte capacidad de liderazgo compartido, destacando la importancia de la toma de decisiones conjunta y la distribución equitativa de responsabilidades. Cada miembro del equipo ha aportado activamente, promoviendo una comunicación abierta y colaborando para superar desafíos, lo cual ha fortalecido la cohesión y efectividad del grupo. La responsabilidad colectiva y el apoyo mutuo han sido pilares clave que nos han permitido dirigir el proyecto hacia el cumplimiento exitoso de nuestros objetivos. Este enfoque de liderazgo conjunto ha sido fundamental para crear un entorno de trabajo inclusivo y productivo.<br>
    </td>
  </tr>
  <tr>
    <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
    <td>
      Erick Ruiz<br>
        TB1:<br> Tomé la mayor parte de la responsabilidad del desarrollo del primer y segundo capítulo. <br> 
        TP1: <br>  <br> 
        TB2:<br>  <br> 
        TF1: <br>  <br>
      Jose Riegas<br>
        TB1:<br> Durante el proyecto fue de mi prioridad ayudar a mis compañeros en la realización de sus tareas, por este motivo he revisado todo el proyecto, corregido errores, como también aportado a la creación de ítems externos a mis responsabilidades asignadas.<br> 
        TP1:<br> <br> 
        TB2:<br>  <br>
        TF1: <br><br>
      Anthony Loarte<br>
        TB1:<br> A lo largo del proyecto Bliss, me he centrado en establecer un entorno de trabajo colaborativo e inclusivo, asegurándome de que cada miembro del equipo tuviera las herramientas y el apoyo necesarios para cumplir con sus tareas. Además, he liderado la planificación de actividades y el establecimiento de metas alcanzables para cumplir con los objetivos de manera eficiente.<br>
        TP1: <br> <br>
        TB2: <br> <br>
        TF1: <br>  <br>
      Bruce Cipriano<br>
        TB1:<br> He fomentado un entorno inclusivo, definiendo metas claras, planificando tareas, y asegurando el cumplimiento de los objetivos del proyecto.<br> 
        TP1:<br>  <br> 
        TB2: <br>. <br>  
        TF1: <br> <br>
      Godofredo Quispe<br>
         TB1: <br>Durante la entrega, fomenté un entorno colaborativo e inclusivo asegurándome de que todos los integrantes tuvieran la oportunidad de participar activamente. Establecí objetivos claros y prioricé una planificación efectiva, asegurando el cumplimiento de mis responsabilidades mediante una comunicación constante.<br>
         TP1: <br>.<br>
         TB2: <br>.<br>
         TF1: <br><br>
</td>
    <td>
       Durante el proyecto, hemos logrado crear un entorno inclusivo y colaborativo que ha facilitado la participación activa de todos los miembros del equipo. Hemos definido metas claras y planificado tareas detalladamente, lo que ha permitido un seguimiento efectivo del progreso y el cumplimiento de los objetivos. La colaboración y el apoyo mutuo han sido esenciales para asegurar que cada miembro del equipo se sintiera valorado y comprometido. Este enfoque ha contribuido significativamente a la eficiencia y éxito del proyecto.<br>
    </td>
  </tr>
</table>

<br><br>

# Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Descripción de la StartUp

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hyphotesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-Is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact mapping

## 3.4. Product Backlog

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2 Context mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context:

#### 4.2.X.1. Domain Layer

#### 4.2.X.2. Interface Context

#### 4.2.X.3. Application Context

#### 4.2.X.4. Infrastructure Context

#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.X.6.2. Bounded Context Database Design Diagram

# Capítulo V: Solutions UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Landing Page Wireframe

### 5.3.2. Landing Page Mock-up

## 5.4. Application UX/UI Design

### 5.4.1. Applications Wireframes

### 5.4.2. Applications Wireflow Diagrams

### 5.4.3. Applications Mock-ups

### 5.4.4. Applications User Flow Diagrams

## 5.5. Applications Prototyping

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Source Code Style Guide & Conventions

### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.X. Sprint n

#### 6.2.X.1. Sprint Planning n.

#### 6.2.X.2. Sprint Backlog n.

#### 6.2.X.3. Development Evidence for Sprint Review

#### 6.2.X.4. Testing Suite Evidence for Sprint Review.

#### 6.2.X.5. Execution Evidence for Sprint Review.

#### 6.2.X.6. Services Documentation Evidence for Sprint Review.

#### 6.2.X.7. Software Deployment Evidence for Sprint Review.

#### 6.2.X.8. Team Collaboration Insights during Sprint.

## 6.3. Validation Interviews.

### 6.3.1. Diseño de Entrevistas.

### 6.3.2. Registro de Entrevistas.

### 6.3.3. Evaluaciones según heurísticas.

## 6.4. Video About-the-Product.

# Conclusiones

## Conclusiones y recomendaciones

## Video About-the-Team

# Bibliografía

# Anexos
>>>>>>> 83d5a5c871cd524a9cc7c4546cc66b0da29bbc34
