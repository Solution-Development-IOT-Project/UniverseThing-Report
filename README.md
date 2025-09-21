<hr>

# <center>Informe de Trabajo Final</center>

<h3 align="center"> Universidad Peruana de Ciencias Aplicadas </h3>

<h3 align="center"> Ingeniería de Software </h3>

<h3 align="center">Ciclo 2025 - 2</h3>

<div align="center">
  <img width=250 src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"/>
</div>

<h1 align="center"> TB1 Report </h1>

<h3 align="center"> Docente: Leon Baca, Marco Antonio </h3>

<h3 align="center"> 1ASI0572 - Desarrollo de Soluciones IoT </h3>

<h4 align="center"> NRC: 3414 </h4>

<h3> Startup: UniverseThing </h3>

<h3> Product: AgroPre </h3>

<h3> Team Members: </h3>

<div align="center">

| Member                |    Code    |
| :-------------------- | :--------: |
| ##                    |     ##     |
| Quispe Tipo Godofredo | U202120772 |
| ##                    |     ##     |
| ##                    |     ##     |
| ##                    |     ##     |

</div>

<h3 align="center">Septiembre, 2025</h3>

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

**UniverseThing** es una startup de agrotech que desarrolla soluciones de IoT para la agricultura de precisión. Nuestro producto principal, **AgroPre**, es un sistema integral de monitoreo y automatización diseñado para optimizar el manejo de cultivos, con enfoque en la protección contra heladas y el control inteligente de plagas. **AgroPre** combina hardware robusto, visión artificial y análisis de datos en tiempo real para ofrecer a los agricultores una herramienta capaz de transformar la gestión de riesgos climáticos y biológicos en sus cultivos.

**Misión:**
Empoderar a los agricultores con tecnología accesible y automatizada que maximice el rendimiento de sus cultivos, reduzca pérdidas por factores ambientales y promueva prácticas agrícolas sostenibles mediante el uso eficiente de recursos.

**Visión:**
Ser la plataforma líder en soluciones de IoT para la agricultura de precisión en América Latina, reconocida por su innovación, confiabilidad y impacto positivo en la seguridad alimentaria y la economía rural.

**Problema Identificado:**
La agricultura enfrenta desafíos críticos debido a la imprevisibilidad climática y la creciente incidencia de plagas. Las heladas, por ejemplo, pueden destruir cosechas enteras en horas, mientras que las plagas como Áfidos generan pérdidas silenciosas pero igualmente devastadoras. Los métodos tradicionales de protección (como coberturas manuales o fumigaciones calendarizadas) son ineficientes, costosos y reactivos. Además, la falta de datos en tiempo real y la dependencia de la mano de obra limitan la capacidad de los agricultores para responder a tiempo ante estas amenazas.

**Solución Propuesta:**
**AgroPre** ofrece un sistema modular y escalable que incluye:

- **Monitoreo en tiempo real:** Sensores de temperatura ambiental, sensor de luz y cámaras con visión artificial para detectar riesgos de heladas y plagas.
- **Automatización inteligente:** Activación automática de mecanismos de protección (como cubiertas térmicas motorizadas y fumigación localizada) basada en umbrales predefinidos o detección de plagas.
- **Plataforma digital:** Una interfaz web y móvil que permite a los agricultores visualizar datos, recibir alertas y controlar el sistema de forma remota.
- **Sostenibilidad:** Reducción del uso de agua, insecticidas y mano de obra mediante intervenciones precisas y basadas en datos.

### 1.1.2. Perfiles de integrantes del equipo

|                  Foto                  |                                                                                                                                                                                                                                                                   Descripción                                                                                                                                                                                                                                                                   |
|:--------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ![Foto1](imagenes/cap-1/Godofredo.jpg) | **Nombre:** i nombre es Godofredo y actualmente me encuentro cursando la carrera de Ingeniería de Software, un campo que me apasiona profundamente. Mi interés por las nuevas tecnologías es constante, y estoy siempre al tanto de las últimas innovaciones que están redefiniendo el panorama tecnológico. Me considero un entusiasta de la programación, área en la que he adquirido un dominio en diversos lenguajes, tales como Python, C++ y Assembler, lo que me ha permitido abordar una amplia gama de proyectos y desafíos técnicos . |

## 1.2. Solution Profile

**Problema identificado:** Los agricultores de papa, especialmente aquellos con cultivos medianos y grandes, enfrentan pérdidas significativas debido a dos factores principales: las heladas impredecibles que queman los cultivos y las plagas (Áfidos) que dañan las plantas y reducen el rendimiento. Los métodos tradicionales de protección (como quema de heno o fumigar de forma preventiva) son intensivos en mano de obra, poco precisos, costosos y a menudo reactivos en lugar de preventivos. La falta de monitoreo en tiempo real y automatización conduce a la toma de decisiones tardía, resultan en daños económicos sustanciales.

**Solución propuesta:**
**AgroPre** es un sistema integral de IoT que automatiza la protección de cultivos contra heladas y plagas, permitiendo a los agricultores monitorear y actuar de forma remota.

- **Desde el rol del agricultor o administrador:** Puede visualizar en tiempo real la temperatura ambiental y alertas de plagas en su finca a través de una app web y móvil. Recibe notificaciones automáticas cuando se detecta una helada inminente o una plaga. Tiene el control para activar manualmente los sistemas de protección (telas, fumigación) o confiar en la automatización total.
- **Desde el rol del sistema (automatizado):** El sistema monitorea constantemente las condiciones ambientales. Para heladas: Activa automáticamente motores que deslizan una cubierta térmica sobre los cultivos cuando la temperatura cae por debajo de un umbral predefinido. Para plagas: Utiliza cámaras con visión artificial para detectar insectos en las plantas. Al confirmar una plaga, activa un mecanismo de sacudida para derribar las plagas a una plataforma y luego fumiga el área.
- Gracias a la automatización, el monitoreo en tiempo real y la respuesta precisa, **AgroPre** convierte al agricultor en un gestor de datos, reduce pérdidas, optimiza recursos (insecticida, mano de obra) y promueve una agricultura más sostenible y precisa.

### 1.2.1. Antecedentes y problemática

**What (Qué)**

- **¿Cuál es el problema?** Pérdida de cultivos y reducción de la rentabilidad debido a heladas y plagas, combinado con métodos de control manuales, ineficientes y que no escalan.
- **¿Cuál es la relación con la persona en cuestión?** **AgroPre** empodera al agricultor con tecnología accesible que automatiza las tareas más críticas y estresantes, permitiéndole proteger su inversión de forma proactiva y desde cualquier lugar.

**When (Cuándo)**

- **¿Cuándo sucede el problema?** Las heladas son más frecuentes en las madrugadas durante el invierno. Las plagas pueden aparecer en cualquier momento, especialmente en temporadas cálidas, y su detección temprana es crucial.
- **¿Cuándo utiliza el cliente el producto?** El cliente utiliza el dashboard de **AgroPre** diariamente para monitorear el estado de su cultivo. El sistema actúa de forma autónoma durante eventos críticos (noches frías, detección de plagas), pero el cliente recibe alertas inmediatas en esos momentos.

**Where (Dónde)**

- **¿Dónde está el cliente cuando usa el producto?** En cualquier lugar con conexión a internet: su oficina, su casa, o incluso mientras viaja, a través de su teléfono móvil o computador.
- **¿Dónde surge el problema?** Directamente en el campo, en las parcelas de cultivo de papa.

**Who (Quién)**

- **¿Quiénes se ven involucrados en el problema?**

1. **Agricultores Tecnificados (Medianos/Grandes):** Pierden dinero e inversión. Su dolor es económico y de gestión.
2. **Cooperativas:** Ven afectada la productividad y calidad consistente de sus socios, impactando su competitividad en el mercado.
3. **Ingenieros Agrónomos:** Necesitan herramientas mejores para asesorar a sus clientes de manera efectiva y basada en datos.

**Why (Por qué)**

- **¿Cuáles son las causas del problema?**

- **Clima impredecible:** El cambio climático aumenta la frecuencia de eventos extremos como heladas.
- **Métodos reactivos:** Los agricultores a menudo actúan cuando el daño ya está hecho.
- **Altos costos de mano de obra:** Estar las 24 horas vigilando el campo es inviable y caro.
- **Fumigación indiscriminada:** Aumenta costos, daña el medio ambiente y puede generar resistencia en las plagas.

**How (Cómo)**

- **¿En qué condiciones los clientes usan nuestro producto?** Lo usan como parte de su rutina diaria de gestión agrícola y confían en que funcione de forma autónoma en condiciones climáticas adversas o de detección de plagas, often mientras ellos se dedican a otras actividades.

**How Much (Cuánto)**

- **¿Cuál es la magnitud del problema?** Las pérdidas pueden ser devastadoras. Una sola helada fuerte puede destruir el 100% de una cosecha. Según la FAO, las plagas y enfermedades de las plantas causan pérdidas de hasta el 40% de la producción agrícola mundial anualmente. Para un agricultor mediano, esto puede representar la diferencia entre la rentabilidad y la quiebra.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

En el sector agrícola actual, los productores de papa se enfrentan a pérdidas económicas recurrentes y significativas debido a la incapacidad de responder a tiempo ante amenazas ambientales como heladas y plagas. Las soluciones existentes (monitoreo manual, fumigación preventiva) son ineficientes, costosas y no escalables. Esto crea una necesidad crítica de un sistema integrado, automatizado y basado en datos que permita una protección preventiva y precisa, transformando la gestión del riesgo climático y sanitario de un arte reactivo a una ciencia predecible.

#### 1.2.2.2. Lean UX Assumptions

**User Assumptions (Suposiciones de Usuario)**

- **¿Quién es el usuario?** Un agricultor mediano/grande o representante de una cooperativa, con cierto nivel de tecnificación y acceso a un smartphone.
- **¿Dónde encaja nuestro producto en su trabajo o vida?** Encaja como una herramienta de gestión crítica para proteger su principal activo que es **su cultivo**. Es una extensión de su toma de decisiones.
- **¿Qué problemas resuelve nuestro producto?** **Resuelve** la ansiedad por las **heladas**, la detección tardía de **plagas**, el gasto excesivo en insecticidas y la dependencia de la mano de obra para vigilancia.
- **¿Cuándo y cómo se usa nuestro producto?** Se usa **diariamente** para monitoreo y de forma automática **durante la noche** o en **alertas.** La interfaz debe ser simple para usarse en el campo.
- **¿Qué características son importantes?** **Alertas en tiempo real**, dashboard claro con datos históricos, **control manual remoto** y confiabilidad absoluta del **sistema automático**.
- **¿Cómo debe verse y comportarse nuestro producto?** Debe verse robusto y profesional, pero simple. Debe inspirar confianza. La app debe funcionar offline en modo básico.

**Business Assumptions (Suposiciones de Negocio)**

- **Necesidades y problemas:** Creemos que los agricultores pagarán por una solución que reduzca tangiblemente el riesgo de perder su cosecha.
- **Plataforma:** La necesidad se resuelve con un sistema físico (hardware) + una plataforma digital (software/App).
- **Segmentación:** Nuestros usuarios son agricultores tecnificados y cooperativas.
- **Comportamientos:** El valor principal es la paz mental y la reducción de pérdidas.
- **Beneficios:** Los usuarios obtendrán mayores rendimientos, ahorro en insumos y mano de obra, y datos valiosos para tomar mejores decisiones.
- **Captación de clientes:** A través de ingenieros agrónomos influyentes, ferias agrícolas y demostraciones en campo.
- **Modelo de ingresos:** Venta del hardware (kit) + suscripción anual por software, datos y soporte.
- **Competencia:** Soluciones fragmentadas (estaciones meteorológicas simples, apps de monitoreo, servicios de fumigación manual).
- **Ventaja competitiva:** La integración total automatización + visión artificial + fumigación precisa en un solo sistema.

**Technical Assumptions (Suposiciones Técnicas)**

- **Tecnología utilizada:** Podemos usar microcontroladores (ESP32), Raspberry Pi para visión artificial, sensores industriales, y desarrollar una Web en Angular y una app Mobil en Flutter.
- **Escalabilidad:** El sistema debe ser escalable para fincas de diferentes tamaños.

**Market Assumptions (Suposiciones de Mercado)**

- **Tamaño del mercado:** El mercado de agricultura de precisión y IoT agrícola está creciendo rápidamente a nivel global y en Latinoamérica.
- **Competencia:** Existen empresas grandes (como John Deere, Bosch) pero con soluciones mucho más caras y complejas. Nuestra competencia directa son soluciones locales menos integradas.
- **Tendencias:** La agricultura de precisión es una tendencia imparable impulsada por la necesidad de eficiencia y sostenibilidad.

**Design Assumptions (Suposiciones de Diseño)**

- **Interacción del usuario:** La interacción debe ser mínima. El agricultor quiere "configurar y olvidar". Las alertas deben ser muy claras (notificaciones push, SMS).
- **Experiencia del usuario:** Debe ser simple, confiable y visible en condiciones de luz solar intensa.
- **Colores y la tipografía:** Colores que transmitan confianza (verdes, azules), tipografía grande y legible.
- **Preferencias visuales:** Mapas de calor de la finca, gráficos simples de tendencias de temperatura, fotos de las detecciones de plagas.
- **Prototipos y pruebas:** Es crucial probar el hardware en condiciones reales extremas (lluvia, polvo, calor) y la app con los usuarios reales en el campo.

#### 1.2.2.3. Lean UX Hyphotesis Statements

- **Hipótesis 01:** Creemos que los agricultores tecnificados necesitan automatizar la protección contra heladas. Sabremos que es correcto cuando el 70% de los agricultores probadores diga que la activación automática de la tela es la funcionalidad más valiosa.
- **Hipótesis 02:** Creemos que la detección automática de plagas con IA reducirá el uso de insecticidas en al menos un 30%. Sabremos que es correcto midiendo el volumen de insecticida usado antes y después de instalar el sistema en una parcela de prueba.
- **Hipótesis 03:** Creemos que los agricultores pagarán una suscripción anual por el software y los datos. Sabremos que es correcto si al menos el 60% de los que compran el hardware se suscriben al segundo año.
- **Hipótesis 04:** Creemos que la app móvil es el canal principal de interacción. Sabremos que es correcto si el 90% de las alertas son visualizadas primero en el móvil frente a la web.
- **Hipótesis 05:** Creemos que la confiabilidad del sistema es más importante que el precio. Sabremos que es correcto si las entrevistas revelan que el "que no falle" es la principal preocupación, por encima del costo.
- **Hipótesis 06:** Creemos que las cooperativas son el canal de venta más efectivo. Sabremos que es correcto si el 50% de nuestras ventas del primer año provienen de este segmento.

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

**Segmento Objetivo #1: Agricultores Tecnificados (Los Decisores y Beneficiarios Directos)**

Este grupo está compuesto por productores agrícolas medianos y grandes, propietarios o administradores de fundos, que tienen la capacidad de inversión y la mentalidad para adoptar tecnología que mejore la productividad y reduzca riesgos. Son pragmáticos y buscan soluciones con un retorno de la inversión claro y tangible. Características clave:

- **Edad:** 20 a 65 años
- **Género:** Predominantemente masculino, aunque con una creciente participación femenina.
- **Contexto:** Agricultura comercial de medianas a grandes escalas (de 5 a 500+ hectáreas). Su operación ya cuenta con cierto nivel de tecnificación (riego por goteo, uso de fertilizantes con precision, talvez drones para monitoreo).
- **Ocupación:** Propietario de fundo, administrador agrícola, gerente de campo.
- **Uso de tecnología:** Usuarios intermedios de smartphones; utilizan apps del banco, WhatsApp para negocios, y pueden estar familiarizados con software básico de gestión agrícola o estaciones meteorológicas simples. Valoran la funcionalidad por sobre la complejidad.
- **Necesidades y Puntos de Dolor:**

  - **Reducir el riesgo económico:** Evitar pérdidas catastróficas por heladas o plagas.
  - **Optimizar costos:** Reducir el gasto en mano de obra para vigilancia nocturna y en aplicaciones preventivas de insecticidas.
  - **Tomar decisiones basadas en datos:** Tener información en tiempo real para actuar de manera proactiva, no reactiva.
  - **Escalabilidad:** Gestionar múltiples campos o parcelas de manera eficiente.
  - **Paz mental:** Poder monitorear sus cultivos de forma remota y confiar en que el sistema responderá automáticamente a las amenazas.

**Segmento Objetivo #2: Cooperativas Agrícolas (Los Multiplicadores, Facilitadores y Comunidades)**

Corresponde a las juntas directivas y gerentes técnicos de asociaciones o cooperativas de productores de papa. Su objetivo es mejorar la productividad, calidad y rentabilidad de todos sus socios para fortalecer la posición competitiva del grupo en el mercado. Actúan como un canal de distribución y validación masiva. Características clave:

- **Edad:** 20 a 65 años (integrantes de la junta directiva y gerencia).
- **Género:** Ambos.
- **Contexto:** Organizaciones que agrupan a decenas o cientos de pequeños y medianos agricultores para conseguir mejores precios, comprar insumos al por mayor y acceder a tecnología y financiamiento.
- **Ocupación:** Presidente, gerente, ingeniero agrónomo jefe de la cooperativa.
- **Uso de tecnología:** Buscan soluciones tecnológicas que puedan implementarse a escala en las parcelas de sus socios. Están abiertos a modelos de negocio B2B (empresa a empresa) y suelen tener acceso a programas de subsidio o crédito gubernamental.
- **Necesidades y Puntos de Dolor:**

  - **Beneficio colectivo:** Implementar soluciones que mejoren los resultados de todos sus asociados de manera homogénea.
  - **Control de calidad y estandarización:** Asegurar que la producción de todos los socios cumpla con ciertos estándares (ej: libres de plagas, uso racional de agroquímicos) para acceder a mercados más exigentes.
  - **Trazabilidad:** Generar data y historiales que certifiquen las buenas prácticas agrícolas del grupo.
  - **Sostenibilidad del modelo:** Atraer y retener socios ofreciendo tecnología de punta como un beneficio tangible de pertenecer a la cooperativa.
  - **Negociación:** Adquirir tecnología a un mejor precio mediante compras agrupadas.

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
