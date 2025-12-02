<p align="center">
  <img src="/assets/UPC_logo_transparente.png"  style="width:200px; height:auto;">
</p>

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

## <div style="text-align: center;"> Ingeniería de Software </div>
## <div style="text-align: center;"> Periodo: 202520 </div>
## <div style="text-align: center;"> 1ACC0238 - Aplicaciones para Dispositivos Móviles </div>
## <div style="text-align: center;"> NRC: 1827 </div>
## <div style="text-align: center;"> David Gerardo Quevedo Velasco </div>
## <div style="text-align: center;"> Informe de Trabajo Final </div>
## <div style="text-align: center;"> Start up: Go7U </div>
## <div style="text-align: center;"> Product: PSYMED </div>

### <div style="text-align: center;"> INTEGRANTES:</div>
<p align="center">
U202213765 - Maita Falckenheiner, Romina Guadalupe <br>
U20221F613 - Torres Flores, Paolo Alessandro
</p>



<div style="text-align: center;"> Noviembre 2025 </div>

<div style="page-break-after: always;"></div>


## Registro de Versiones del Informe

## Historial de Versiones

| Versión |      Fecha | Responsable(s) | Descripción de cambios                                                                                                                                                                            |
|--------:|-----------:|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     1.0 | 04/11/2025 | Romina Maita | Creación de la estructura inicial del documento y capítulo I: Presentación (1.1 Startup Profile, 1.2 Solution Profile, 1.3 Segmentos objetivo)                                                    |
|     1.1 | 05/11/2025 | Paolo Torres | Desarrollo de Capítulo II secciones 2.1 Competidores, 2.2 Entrevistas (diseño, registro y análisis)                                                                                               |
|     1.2 | 06/11/2025 | Romina Maita | Elaboración de sección 2.3 Needfinding (User Personas, User Task Matrix, User Journey Mapping, Empathy Mapping, Ubiquitous Language)                                                              |
|     1.3 | 07/11/2025 | Paolo Torres | Documentación de sección 2.4 Requirements Specification (User Stories, Impact Mapping, Product Backlog)                                                                                           |
|     1.4 | 08/11/2025 | Romina Maita | Desarrollo de sección 2.5.1 EventStorming (Candidate Context Discovery, Domain Message Flows Modeling, Bounded Context Canvases)                                                                  |
|     1.5 | 09/11/2025 | Paolo Torres | Elaboración de secciones 2.5.2 Context Mapping y 2.5.3 Software Architecture (Context Level, Container Level, Deployment Diagrams)                                                                |
|     1.6 | 11/11/2025 | Romina Maita | Documentación de Bounded Context IAM (Domain Layer, Interface Layer, Application Layer, Infrastructure Layer, diagramas)                                                                          |
|     1.7 | 12/11/2025 | Paolo Torres | Elaboración de Bounded Context Profiles con todas sus capas y diagramas correspondientes                                                                                                          |
|     1.8 | 13/11/2025 | Romina Maita | Desarrollo de Bounded Context Appointment and Administration con documentación completa                                                                                                           |
|     1.9 | 14/11/2025 | Paolo Torres | Documentación de Bounded Context Medication y Patient Report con sus capas y diagramas                                                                                                            |
|     2.0 | 15/11/2025 | Romina Maita | Elaboración de Capítulo III: Solution UI/UX Design (3.1 Product Design, Style Guidelines, Information Architecture, Landing Page y Mobile Applications)                                           |
|     2.1 | 16/11/2025 | Paolo Torres | Desarrollo de Capítulo IV sección 4.1 Software Configuration Management (entorno de desarrollo, control de versiones, convenciones, configuración de despliegue)                                  |
|     2.2 | 18/11/2025 | Romina Maita | Documentación de sección 4.2 Landing Page & Mobile Application Implementation (Sprints con planning, backlog, evidencias de desarrollo, testing, ejecución, servicios, despliegue y colaboración) |
|     2.3 | 19/11/2025 | Paolo Torres | Elaboración de sección 4.3 Validation Interviews (diseño, registro y evaluaciones según heurísticas)                                                                                              |
|     2.4 | 20/11/2025 | Romina Maita | Desarrollo de Conclusiones y Recomendaciones, Glosario y Bibliografía                                                                                                                             |
|     2.5 | 21/11/2025 | Paolo Torres | Integración de videos de validación, producto y equipo, revisión final de anexos                                                                                                                  |
|     2.6 | 22/11/2025 | Romina Maita, Paolo Torres | Revisión completa del documento, corrección de formato, consistencia en referencias y verificación de contenido                                                                                   |
|     3.0 | 27/11/2025 | Romina Maita, Paolo Torres | Corrección de Sprints y documentación de avance y desplieque en Firebase                                                                                                                          |


<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

Durante la documentación del proyecto el grupo utilizó GitHub como controlador de versiones permitiendo ver el registro de cambios durante el ciclo académico.

A continuación se muestra una captura de los insights de los integrantes de acuerdo a las entregas:

TB2: 

![WhatsApp Image 2025-11-14 at 6 41 37 AM (1)](https://github.com/user-attachments/assets/9cd9eea0-000a-41cf-804a-8780244dd890)

TF:

<img width="902" height="221" alt="image" src="https://github.com/user-attachments/assets/0798ce9d-5c8b-4c29-8903-20a25a480022" />


# Contenido
## Tabla de Contenidos

### [Student Outcome](#student-outcome)
### [Objetivos SMART](#objetivos-smart)


### [Part I: As-Is Software Project](#part-i-as-is-software-project)

### [Capítulo I: Presentación](#capítulo-i-presentación)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)


### [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
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
  - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)
- [2.4. Requirements Specification](#24-requirements-specification)
  - [2.4.1. User Stories](#241-user-stories)
  - [2.4.2. Impact Mapping](#242-impact-mapping)
  - [2.4.3. Product Backlog](#243-product-backlog)
- [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
  - [2.5.1. EventStorming](#251-eventstorming)
    - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
    - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
    - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
  - [2.5.2. Context Mapping](#252-context-mapping)
  - [2.5.3. Software Architecture](#253-software-architecture)
    - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
    - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
    - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
- [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
  - [2.6.x. Bounded Context: \<Bounded Context Name\>](#26x-bounded-context-bounded-context-name)
    - [2.6.x.1. Domain Layer](#26x1-domain-layer)
    - [2.6.x.2. Interface Layer](#26x2-interface-layer)
    - [2.6.x.3. Application Layer](#26x3-application-layer)
    - [2.6.x.4. Infrastructure Layer](#26x4-infrastructure-layer)
    - [2.6.x.5. Bounded Context Software Architecture Component Level Diagrams](#26x5-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.x.6. Bounded Context Software Architecture Code Level Diagrams](#26x6-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.x.6.1. Bounded Context Domain Layer Class Diagrams](#26x61-bounded-context-domain-layer-class-diagrams)
      - [2.6.x.6.2. Bounded Context Database Design Diagram](#26x62-bounded-context-database-design-diagram)


### [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
- [3.1. Product Design](#31-product-design)
  - [3.1.1. Style Guidelines](#311-style-guidelines)
    - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
  - [3.1.2. Information Architecture](#312-information-architecture)
    - [3.1.2.1. Organization Systems](#3121-organization-systems)
    - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
    - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
    - [3.1.2.4. Searching Systems](#3124-searching-systems)
    - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
  - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
    - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
    - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
  - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
    - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
    - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
    - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
    - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
    - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)


### [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)
- [4.1. Software Configuration Management](#41-software-configuration-management)
  - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
  - [4.1.2. Source Code Management](#412-source-code-management)
  - [4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)
  - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
- [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
  - [4.2.1. Sprint n](#421-sprint-n)
    - [4.2.1.1. Sprint Planning n](#4211-sprint-planning-n)
    - [4.2.1.2. Sprint Backlog n](#4212-sprint-backlog-n)
    - [4.2.1.3. Development Evidence for Sprint Review](#4213-development-evidence-for-sprint-review)
    - [4.2.1.4. Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence-for-sprint-review)
    - [4.2.1.5. Execution Evidence for Sprint Review](#4215-execution-evidence-for-sprint-review)
    - [4.2.1.6. Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence-for-sprint-review)
    - [4.2.1.7. Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence-for-sprint-review)
    - [4.2.1.8. Team Collaboration Insights during Sprint](#4218-team-collaboration-insights-during-sprint)
- [4.3. Validation Interviews](#43-validation-interviews)
  - [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)
  - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)
  - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)

### [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
### [Video App Validation](#video-app-validation)
### [Video About the Product](#video-about-the-product)
### [Video About the Team](#video-about-the-team)
### [Glosario](#glosario)
### [Bibliografía](#bibliografía)
### [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome 

ABET - EAC - Student Outcome 7
Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea
necesario, utilizando estrategias deaprendizaje apropiadas.

| Criterio específico                                                                                                                     | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-----------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | TB2:<br>Romina Maita: Durante el desarrollo del proyecto PSYMED, fue sumamente enriquecedor explorar y aplicar conceptos nuevos de programación y arquitectura de software. Particularmente, resultó muy interesante aprender Domain-Driven Design (DDD), que permitió estructurar el dominio del problema de manera más efectiva y establecer límites claros entre contextos acotados. El aprendizaje de tecnologías multiplataforma como Flutter y Dart para desarrollo móvil, junto con Spring Boot para el backend, amplió significativamente mis capacidades técnicas. La implementación de arquitecturas limpias, principios SOLID y patrones de diseño mejoró la calidad del código y facilitó su mantenibilidad. Además, el uso de herramientas modernas como Docker para containerización, JWT para autenticación segura, y PostgreSQL para persistencia de datos, proporcionó una experiencia práctica valiosa en tecnologías ampliamente utilizadas en la industria.<br><br>Paolo Torres: El desarrollo del proyecto PSYMED representó una experiencia altamente formativa en términos de adquisición de nuevos conocimientos técnicos. Fue particularmente interesante explorar Domain-Driven Design (DDD) como metodología para modelar sistemas complejos, lo cual permitió identificar contextos acotados y establecer relaciones entre ellos mediante Context Mapping y EventStorming. El aprendizaje práctico de Flutter y Dart para desarrollo móvil multiplataforma, combinado con Spring Boot y Spring Security para el backend, me permitió trabajar con tecnologías de vanguardia utilizadas en el sector empresarial. La implementación de arquitecturas hexagonales, principios de diseño limpio y patrones de diseño como Command Query Responsibility Segregation (CQRS) mejoraron significativamente mi comprensión de cómo construir software escalable y mantenible. El uso de Docker para containerización, JWT para autenticación, y Swagger para documentación de APIs, proporcionó experiencia práctica en herramientas esenciales del ecosistema de desarrollo moderno. <br></br> TF: <br></br> Romina Maita:Durante este avance del proyecto, actualicé mis conocimientos sobre los procesos de distribución de aplicaciones móviles mediante la integración de Firebase App Distribution. Para lograrlo, revisé documentación técnica oficial y exploré conceptos relacionados con configuración de entornos, firmas de aplicaciones y despliegue continuo. Esta actualización de conocimientos me permitió aplicar un flujo de distribución más profesional y alineado con prácticas actuales del desarrollo móvil. <br></br> Paolo Torres: La incorporación de términos y condiciones en la aplicación implicó investigar lineamientos modernos de cumplimiento legal y su implementación adecuada en Flutter. Para ello, revisé guías de diseño, patrones para pantallas de consentimiento y el manejo de rutas en Flutter. Este proceso amplió mis conocimientos sobre la construcción de componentes legales dentro de una aplicación y fortaleció mi capacidad para integrar elementos esenciales en proyectos de software reales. | El trabajo desarrollado en PSYMED evidencia una actualización constante de conocimientos técnicos esenciales para el proyecto. La exploración de arquitecturas modernas, el uso de Flutter, Spring Boot y herramientas como Docker, JWT y PostgreSQL fortaleció la capacidad para construir soluciones de software robustas. Asimismo, la integración de Firebase App Distribution y la implementación de términos y condiciones en la aplicación permitieron aplicar prácticas actuales de despliegue, seguridad y cumplimiento. En conjunto, estas actividades reflejan un proceso sostenido de actualización y aplicación de conceptos necesarios para el desarrollo profesional.                                                                                         |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.  | TB2:<br>Romina Maita: Esta experiencia demostró claramente la importancia del aprendizaje continuo y la adaptabilidad en el desarrollo de software. El campo de la ingeniería de software evoluciona constantemente, introduciendo nuevas tecnologías, metodologías y mejores prácticas. La capacidad de aprender rápidamente conceptos como DDD, Flutter, arquitectura limpia y herramientas de DevOps es esencial para mantenerse competitivo en la industria. El desarrollo de PSYMED me permitió reconocer que cada proyecto es una oportunidad de aprendizaje, y que la disposición a explorar tecnologías nuevas, documentar el proceso y colaborar efectivamente en equipo son habilidades fundamentales para el crecimiento profesional continuo. Esta experiencia refuerza mi compromiso con el aprendizaje permanente y la actualización constante de conocimientos técnicos y metodológicos.<br><br>Paolo Torres: El desarrollo de PSYMED evidenció la necesidad crítica del aprendizaje permanente en el campo de la ingeniería de software. La industria tecnológica evoluciona rápidamente, y mantenerse actualizado con nuevas metodologías, frameworks y herramientas es esencial para el éxito profesional. A lo largo del proyecto, fue necesario aprender y aplicar conceptos nuevos constantemente, desde DDD y arquitecturas de software modernas hasta tecnologías específicas como Flutter y Spring Boot. Esta experiencia reforzó mi comprensión de que el aprendizaje permanente no es opcional, sino una responsabilidad profesional. La capacidad de adaptarse a nuevas tecnologías, comprender patrones de diseño complejos y aplicar mejores prácticas de ingeniería de software son habilidades que requieren desarrollo continuo. Esta experiencia fortaleció mi convicción de que el crecimiento profesional depende directamente de la disposición constante a aprender, experimentar y mejorar, y me motivó a establecer un compromiso activo con la educación continua y la actualización técnica permanente. <br><br> TF: <br></br> Romina Maita: El despliegue en Firebase evidenció la necesidad de un aprendizaje continuo para comprender nuevas herramientas y mantenerme actualizado con los servicios modernos de distribución. La revisión de documentación reciente y la adopción de buenas prácticas en Android Studio reforzaron la importancia de seguir aprendiendo para garantizar que el proyecto cumpla con estándares técnicos actuales y evolucione correctamente. <br></br> Paolo Torres: Las mejoras aplicadas al código en Flutter surgieron de la revisión constante de patrones recomendados, análisis de documentación oficial y estudio de optimizaciones sugeridas por la comunidad. Este ejercicio me permitió reconocer que el desarrollo profesional requiere una actualización permanente, especialmente en frameworks que evolucionan con rapidez. El aprendizaje continuo se vuelve esencial para mantener la calidad y sostenibilidad del proyecto.                                                                                                                                                                  | La experiencia en el desarrollo de PSYMED reafirmó la importancia del aprendizaje permanente como componente esencial del ejercicio profesional en ingeniería de software. La necesidad de incorporar continuamente nuevos conceptos evidenció que la evolución constante del sector exige una actualización técnica sostenida. La revisión de documentación, la adopción de buenas prácticas y la aplicación de patrones modernos demostraron que cada avance del proyecto requiere aprender, ajustar y mejorar. En conjunto, este proceso fortaleció la convicción de que el crecimiento profesional depende de la disposición continua a estudiar, experimentar y adaptarse a tecnologías emergentes para asegurar la calidad y vigencia de las soluciones desarrolladas. |

## Objetivos SMART

### Paolo Alessandro Torres Flores
Objetivo 1: Completar un máster en Gestión de Proyectos de Tecnología en un plazo máximo de tres años después de finalizar la carrera, con el propósito de adquirir competencias avanzadas en liderazgo y dirección de equipos de desarrollo de software.
Objetivo 2: Alcanzar un puesto de Project Manager en una organización de tecnología o consultoría antes de cinco años de egresado, liderando proyectos de transformación digital que generen impacto en el sector educativo o empresarial.

### Romina Guadalupe Maita Falckenheiner:

Objetivo 1: Obtener una certificación en Gestión de Productos Digitales (Product Management) en un plazo máximo de 18 meses tras egresar, con el fin de fortalecer sus capacidades de planificación, análisis de mercado y liderazgo de productos tecnológicos.
Objetivo 2: Desempeñarse como Product Owner en una startup tecnológica dentro de los primeros cuatro años de su carrera profesional, liderando equipos multidisciplinarios para el desarrollo de soluciones digitales orientadas a la educación y el bienestar social.

<div style="page-break-after: always;"></div>
