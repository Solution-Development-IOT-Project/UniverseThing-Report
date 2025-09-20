<hr>

# <center>Informe de Trabajo Final</center>

<h3 align="center"> Universidad Peruana de Ciencias Aplicadas </h3>

<h3 align="center"> Ingeniería de Software </h3>

<h3 align="center">Ciclo 2025 - 2</h3>

<div align="center">
  <img width=250 src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"/>
</div>

<h1 align="center"> TB1 Report </h1>

<h3 align="center"> Docente: Vera Olivera, David Carlos </h3>

<h3 align="center"> 1ASI0572 - Desarrollo de Soluciones IoT </h3>

<h4 align="center"> NRC: 3355 </h4>

<h3> Startup: ------ </h3>

<h3> Product: ------ </h3>

<h3> Team Members: </h3>

<div align="center">

| Member                              |    Code    |
| :---------------------------------- | :--------: |
| ##                                  |     ##     |
| Del Carmen Zorrilla, Ray Alessandro | U202124061 |
| ##                                  |     ##     |
| ##                                  |     ##     |
| ##                                  |     ##     |

</div>

<h3 align="center">Agosto, 2025</h3>

<br><br>

# Registro de Versiones del Informe

<br><br>

# Project Report Collaboration Insights

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

A continuación, se presenta un análisis competitivo que examina a las principales empresas que rivalizan con nuestra startup. Hemos identificado tanto competidores directos, aquellos que ofrecen una solución de software centralizada en la monitoreo del clima para toma de deciciones, como indirectos que, si bien no son idénticos, compiten en áreas prevencion y medidas contra plagas. Este análisis se centra en aquellos que ofrecen soluciones que se superponen con las de **AgroPre**.

1. **Sencrop**  
   ![Logo de Sencrop](/images/cap-2/sencrop.png)  
   **Descripción:**  
   Una red de estaciones meteorológicas conectadas que proporciona datos hiperlocales y alertas para la gestión climática de cultivos.

   **Características principales**

   - Red de estaciones meteorológicas modulares (viento, lluvia, temperatura).
   - Plataforma y app con datos en tiempo real y alertas personalizadas (heladas, lluvia).
   - Modelo de suscripción claro y precios transparentes.
   - Enfoque en la comunidad y el intercambio de datos entre agricultores.

---

2. **Semios**  
   ![Logo de Semios](/images/cap-2/semios.png)  
   **Descripción:**  
   Una plataforma integral de gestión de riesgos que utiliza una extensa red de sensores IoT para el monitoreo de clima, plagas y agua.

   **Características principales**

   - Plataforma todo-en-uno (monitoreo de heladas, plagas, agua y nutrientes).
   - Red de sensores propios y trampas de feromonas inteligentes para control de plagas.
   - Modelos predictivos de enfermedades y alertas de riesgo.
   - Enfoque enterprise para grandes productores y agroindustria.

---

3. **Trapview**  
   ![Logo de Trapview](/images/cap-2/trapview.png)  
   **Descripción:**  
   Un sistema automatizado de monitoreo de plagas que utiliza trampas con visión artificial e IA para identificar y predecir infestaciones.

   **Características principales**

   - Trampas inteligentes con cámara e IA para identificación automática de insectos.
   - Plataforma con alertas en tiempo real y mapas de calor de infestaciones.
   - Especialización best-in-class en el monitoreo de plagas para cultivos de alto valor.
   - Modelo de venta B2B con precios bajo consulta.

### 2.1.1 Análisis competitivo

<table> 
  <tr>
    <th colspan="6"> Competitive Analysis Landscape </th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar acabo este análisis? </td>
    <td colspan="4"> Pregunta </td>
  </tr>
  <tr>
    <td colspan="4"> Deberíamos llevar a cabo este análisis para conocer el entorno, la competencia, tomar decisiones de desarrollo y construir nuestra propuesta de valor. </td>
  </tr>
  <tr>
    <td colspan="2"> Productos </td>
    <td> AgroPre </td>
    <td> Sencrop </td>
    <td> Semios </td>
    <td> Trapview </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td> Sistema integral de IoT asequible que combina el monitoreo de temperatura y la vision artificial para automatizar la protecciòn contra heladas y el control inteligente de plagas. </td>
    <td> Red de estaciones meteorológicas conectadas para monitoreo hiperlocal del clima. </td>
    <td> Plataforma integral de IoT para la gestión de riesgos climáticos, de plagas y recursos. </td>
    <td> Trampas inteligentes con IA para el monitoreo automático y predicción de plagas. </td>
  </tr>
  <tr>
    <td>Ventaja
    competitiva
    ¿Qué valor
    ofrece a los
    clientes?</td>
    <td> <b>Solución integral y accesible.</b> Ofrece una plataforma todo-en-uno (temperatura + plagas) con automatización, dirigida a un mercado medio tradicionalmente desatendido por soluciones premium, con un fuerte enfoque en la sostenibilidad y el ahorro de recursos.   </td>
    <td> <b>Simplicidad y comunidad.</b> Ofrece datos accesibles, precios transparentes y una red colaborativa de agricultores que comparten datos.	</td>
    <td> <b>Integración total.</b> Solución todo-en-uno (clima, plagas, agua) con modelos predictivos propios para grandes extensiones. </td>
    <td> <b>Precisión y automatización.</b> Tecnología best-in-class en identificación de plagas con IA, que elimina el monitoreo manual. </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td> Mercado Objetivo </td>
    <td> <b>Agricultores medianos y cooperativas en Latinoamérica</b>, que cultivan tuberculo(papa), que buscan tecnología efectiva pero no pueden pagar soluciones empresariales.  </td>
    <td> Agricultores medianos y cooperativas en Europa (cereales, viñedos, frutales). </td>
    <td> Grandes empresas agroindustriales y productores de alto valor a nivel global. </td>
    <td> Productores de cultivos de alto valor (vid, cítricos, hortalizas) con problemas graves de plagas. </td>
  </tr>
  <tr>
    <td> Estrategias de Marketing </td>
    <td> Marketing digital localizado (redes sociales, seminarios), alianzas con asociaciones agrícolas y cooperativas, demostraciones en field days (días de campo), y un modelo de precios claro publicado en la web. </td>
    <td> Marketing de contenidos, demostraciones online, precios transparentes en la web y alianzas con distribuidores locales. </td>
    <td> Ventas directas B2B, asistencia a ferias globales, "request a demo" y casos de estudio de ROI para grandes clientes. </td>
    <td> Marketing de precisión, ventas directas especializadas, presencia en ferias técnicas y demostraciones en el sitio. </td>
  </tr>
  <tr>

  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td> Productos & Servicios </td>
    <td> <b>Sistema modular:</b><ul><li><b>Módulo Clima:</b> Sensores de temperatura ambiental y luz.</li>   <li><b>Módulo Plagas:</b> Cámaras con IA para detección de áfidos/plagas.</li> <li><b>Actuadores:</b> Sistema de fumigación localizada. </li> <li><b>Suscripción</b> a la plataforma con alertas, dashboard y control remoto.</li></ul> </td>
    <td> Venta de sensores modulares (Raincrop, Windcrop) + suscripción a plataforma web/app con alertas. </td>
    <td> Venta/leasing de una red de sensores (clima, suelo, trampas) + plataforma SaaS de gestión y analytics. </td>
    <td> Venta de trampas inteligentes autónomas (Trapview) + suscripción a la plataforma de monitoreo y alertas. </td>
  </tr>
  <tr>
    <td> Precios & Costos </td>
    <td> <b>Modelo de negocio escalable y transparente:</b><ul> <li>Costo inicial por kit de hardware (módulo base + sensores).</li> <li>Suscripción mensual/anual asequible por plataforma y servicios de alertas. Precios públicos para generar confianza.</li> </ul></td>
    <td> <b>Modelo claro:</b> Costo inicial del hardware + suscripción anual/mensual. Precios públicos en la web. </td>
    <td> <b>Modelo enterprise:</b> Precios altos y personalizados. Requiere contacto con ventas. Costo significativo por hectárea. </td>
    <td> <b>Modelo premium:</b> Precios altos no publicados. Orientado a cultivos donde el ROI por evitar pérdidas es claro. </td>
  </tr>
  <tr> 
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td> Venta directa online, red de distribuidores técnicos agropecuarios locales y alianzas con cooperativas para llegar directamente al agricultor. </td>
    <td> Venta online directa y a través de una red de distribuidores y partners locales. </td>
    <td> Fuerza de ventas directa propia y canales enterprise. </td>
    <td> Venta directa y a través de partners especializados en protección de cultivos. </td>
  </tr>
  <tr>
    <td rowspan="4"> Análisis SWOT </td>
    <td> Fortalezas </td>
    <td>  <ul><li>Solución dual única (clima + plagas) en su segmento de precio.</li><li>Fácil instalación y usabilidad.</li><li>Modelo de precios transparente.</li><li>Enfoque en problemas específicos de la región (heladas, áfidos).</li> </ul></td>
    <td> Simplicidad, precio transparente, fácil instalación, fuerte comunidad de usuarios. </td>
    <td> Plataforma más completa del mercado, robusta tecnología, datos predictivos, escalable. </td>
    <td> Tecnología líder en IA para plagas, ahorro de mano de obra, datos extremadamente precisos. </td>
  </tr>
  <tr>
    <td> Debilidades </td>
    <td> <ul>    <li>Marca nueva y desconocida frente a competidores establecidos.</li>    <li>Capacidad limitada de Investigació y Desarrollo e inversión inicial comparado con grandes empresas del sector.</li>    <li>La necesidad de educación del mercado sobre los beneficios del IoT.</li></ul> </td>
    <td> Solución limitada solo al clima, no aborda plagas ni riego. Depende de la densidad de su red. </td>
    <td> Muy costosa para el agricultor medio. Compleja de implementar e integrar. </td>
    <td> Enfoque muy niche (solo plagas). No es una solución integral. Alto costo inicial. </td>
  </tr>
  <tr>
    <td> Oportunidades </td>
    <td> <ul><li>Gran mercado no atendido de agricultores medianos en Latam.</li> <li>Tendencia global hacia la agricultura sostenible y de precisión.</li> <li>Posibilidad de integración con financieras o aseguradoras para ofrecer descuentos por uso.</li>  </ul> </td>
    <td> Expandirse a nuevos mercados (ej. Latinoamérica) y agregar más tipos de sensores. </td>
    <td> Vender módulos por separado a mercados medianos y asociarse con grandes fabricantes. </td>
    <td> Integrarse como módulo especializado en plataformas más grandes. </td>
  </tr>
  <tr>
    <td> Amenazas </td>
    <td> Competencia de soluciones gratuitas y  la desconfianza inicial del agricultor hacia la tecnología nueva. </td>
    <td> La llegada de competidores con precios más agresivos o funcionalidades integradas. </td>
    <td> La aparición de soluciones más baratas y simples que capturen el mercado medio. </td>
    <td> Avance de la visión artificial en smartphones que podría simplificar el monitoreo. </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

1. **Estrategia de Diferenciación por Especialización Local y Sostenibilidad**

**Objetivo:**Posicionar a AgroPre como la solución especializada en los problemas específicos del agricultor latinoamericano (heladas y plagas como áfidos en papa), con un fuerte enfoque en la sostenibilidad y el ahorro de recursos.

**Tacticas:**

- Desarrollar y promocionar algoritmos de IA entrenados específicamente con imágenes de plagas y datos climáticos de la región andina.
- Enfocar el mensaje de marketing en el ahorro de agua y pesticidas gracias a la fumigación localizada automatizada, un beneficio tangible y de alto valor.
- En comparación con Semios (muy genérico y costoso) y Sencrop (solo clima), enfatizar: **"Protección hecha a la medida de tu cultivo y tu bolsillo"**.

2. **Estrategia de Enfoque en el Agricultor Mediano y Cooperativas**

**Objetivo:**Dominar el segmento de agricultores medianos y cooperativas de papa en Latinoamérica, un mercado masivo históricamente ignorado por las soluciones empresariales.
**Tacticas:**

- Crear **kits modulares preempaquetados** asequibles: "Kit Básico Heladas", "Kit Completo Papa" (clima + plagas), para simplificar la decisión de compra.
- Establecer alianzas estratégicas con **gremios agrícolas, cooperativas y ministerios de agricultura** para llegar directamente al cliente final con demostraciones y financiamiento.
- Desarrollar funcionalidades colaborativas donde una cooperativa pueda monitorear múltiples parcelas de sus asociados en un solo dashboard.

3. **Estrategia de Humanización, Confianza y Educación**

**Objetivo:**Romper la barrera de desconfianza hacia la tecnología nueva mediante educación, soporte cercano y un lenguaje claro.
**Tacticas:**

- Ofrecer soporte técnico local en español y quechua/aymara (según la región), con agronomos que entiendan el negocio del cliente, no solo la tecnología.
- Crear contenido educativo masivo y accesible: tutoriales en video desde el campo, podcasts con expertos agronómicos locales y guías prácticas para el manejo del cultivo.
- Utilizar un lenguaje claro y evita tecnicismos complejos. A diferencia de Semios, AgroPre debe sentirse como "**un vecino que sabe de tecnología**" y no como una corporación fría.

4. **Estrategia de Precio Ultra-Transparente y de Bajo Costo de Entrada**

**Objetivo:**Eliminar la fricción financiera y generar confianza con un modelo de precios claro y accesible que no requiera contactar a ventas.
**Tacticas:**

- Publicar todos los precios directamente en la web: costo de cada sensor, kit y el precio de la suscripción mensual. Esto contrasta fuertemente con la opacidad de Semios y Trapview.
- Ofrecer un plan de financiamiento o renting para el hardware, permitiendo pagos bajos mensuales que incluyan tanto el dispositivo como la suscripción.
- Diseñar un plan gratuito que permita monitorizar una pequeña parcela de forma básica, para que el agricultor experimente el valor del dato antes de comprometerse financieramente.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

1. **Entrevista para el Agricultor Tecnificado** (Dueño o Encargado de Finca)
   Preguntas principales:

   1. ¿Podría contarme un poco sobre usted y su finca? (edad, tipo de cultivo principal, extensión de tierra, ubicación).
   2. ¿Cómo describiría su enfoque hacia la tecnología en su trabajo diario? ¿Se considera innovador, tradicional, o un poco de ambos?
   3. ¿Cuál es el mayor desafío que enfrenta actualmente en la producción? (Espontáneo, luego profundizar en heladas/plagas)
      Preguntas:
   4. Para el control de heladas/plagas, ¿qué métodos utiliza actualmente? ¿Podría describirme el proceso paso a paso?
   5. ¿Ha probado alguna vez alguna tecnología o herramienta digital para ayudarse con estos problemas? (ej. una app del clima, algún sensor). ¿Cómo le fue?
   6. Imagine un sistema que le avise al celular en tiempo real cuando ocurre una helada y active automáticamente su sistema de proteccion. ¿Qué le parecería?
   7. ¿Qué tan importante es para usted el ahorro de agua y pesticidas? ¿Lleva un registro de estos costos?
   8. A la hora de invertir en su finca, ¿qué pesa más: el precio inicial de una herramienta o el retorno de la inversión a largo plazo?
   9. ¿Quién decide si usted se involucra en la decisión de comprar una tecnología nueva o un equipo costoso?
   10. ¿Qué es lo primero que mira o pregunta cuando un proveedor le ofrece una nueva tecnología para su cultivo?

2. **Entrevista para el Representante de una Cooperativa Agrícola** (Gerente, Director Técnico, Líder de Proyectos u otro participante directo)

Preguntas principales:

1.  ¿Podría contarme sobre el rol de la cooperativa y su participación en ella? (número de socios, cultivos principales, zona de influencia).
2.  Desde su perspectiva, ¿cuáles son los dos problemas técnicos más recurrentes que afectan la productividad de sus socios?
3.  ¿Qué tipo de programas o servicios ofrece actualmente la cooperativa para ayudar a sus socios a mitigar estos problemas? (ej. asistencia técnica, compra conjunta de insumos).
    Preguntas complementarias:

4.  ¿Cómo es el proceso típico para evaluar y adoptar una nueva tecnología que beneficie a los socios? ¿Quiénes están involucrados en esa decisión?
5.  El costo de la tecnología, ¿suele ser una barrera infranqueable para sus socios? ¿Han explorado modelos de financiamiento o subsidios para ello?
6.  ¿Qué tan valuable sería para la cooperativa tener datos agregados y en tiempo real sobre las alertas de heladas o plagas en las parcelas de sus socios? ¿Cómo usarían esa información?
7.  Además del precio, ¿qué otros factores son críticos para que la cooperativa confíe en un proveedor? (soporte técnico, garantías, capacitación, etc.).
8.  ¿Ven más viable un modelo de negocio donde los socios paguen una suscripción mensual baja en lugar de una gran inversión inicial?
9.  ¿Qué tipo de alianza o colaboración le resultaría más atractiva con una empresa como la nuestra? (ej. ser un punto de demostración, un canal de distribución, etc.).
10. Si pudiéramos implementar un piloto gratuito con 5 de sus socios, ¿estaría interesado en colaborar? ¿Qué necesitaría para que esto suceda?

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
