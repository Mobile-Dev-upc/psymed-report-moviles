<p align="center">
  <img src="/assets/UPC_logo_transparente.png"  style="width:200px; height:auto;">
</p>

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

## <div style="text-align: center;"> Ingeniería de Software </div>
## <div style="text-align: center;"> Ciclo 2025-02 </div>
## <div style="text-align: center;"> 1ACC0238 - Aplicaciones para Dispositivos Móviles </div>
## <div style="text-align: center;"> Nrc: 1827 </div>
## <div style="text-align: center;"> David Gerardo Quevedo Velasco </div>
## <div style="text-align: center;"> Informe de TB2 </div>
## <div style="text-align: center;"> Start up: Go6U </div>
## <div style="text-align: center;"> Product: PSYMED </div>

### <div style="text-align: center;"> INTEGRANTES:</div>
<div style="display: flex; justify-content: center;">
    <table>
      <thead>
        <tr>
          <th style="background-color: #333; color: #fff;">Código de Alumno</th>
          <th style="background-color: #333; color: #fff;">Nombre y Apellido</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>U20221F613</td>
          <td>Torres Flores, Paolo Alessandro</td>
        </tr>
        <tr>
          <td>U202213765</td>
          <td>Maita Falckenheiner, Romina Guadalupe</td>
        </tr>
      </tbody>
    </table> 
</div>

<div style="text-align: center;"> Noviembre 2025 </div>

<div style="page-break-after: always;"></div>


## Registro de Versiones del Informe

## Historial de Versiones

| Versión |      Fecha | Responsable(s) | Descripción de cambios                                                                                                                                                          |
|--------:|-----------:|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     0.1 | 04/09/2025 | Marco          | Creación de estructura inicial del documento y carátula. Agregado el índice general y capítulos preliminares.                                                                   |
|     0.2 | 05/09/2025 | Marco, Paolo   | Redacción de **Capítulo I: Introducción**, secciones 1.1 y 1.2. Incorporación de perfiles de la startup y proceso Lean UX.                                                      |
|     0.3 | 06/09/2025 | Marco          | Avance en 1.3 (Segmentos objetivo) y elaboración inicial del **Capítulo II: Requirements Elicitation & Analysis**.                                                              |
|     0.4 | 07/09/2025 | Marco, Paolo   | Inclusión de entrevistas: diseño y registro. Creación de User Personas, Task Matrix y Journey Mapping.                                                                          |
|     0.5 | 08/09/2025 | Paolo          | Desarrollo de Empathy Mapping, As-Is Scenario Mapping y Ubiquitous Language. Revisión general de redacción.                                                                     |
|     0.6 | 09/09/2025 | Romina, Fatima | Redacción de **Capítulo III: Requirements Specification**, incluyendo To-Be Scenarios, User Stories y Product Backlog.                                                          |
|     0.7 | 10/09/2025 | Paolo          | Avance de Impact Mapping. Inicio de **Capítulo IV: Product Design**, con Style Guidelines y Information Architecture.                                                           |
|     0.8 | 11/09/2025 | Paolo, Fatima  | Elaboración de Landing Page Wireframe y Mock-up. Desarrollo de Mobile Applications Wireframes y Wireflows.                                                                      |
|     0.9 | 12/09/2025 | Fatima, Romina | Creación de Web Applications Wireframes, Wireflows y Mock-ups. Adición de Domain-Driven Software Architecture (contexto y contenedores).                                        |
|     1.0 | 13/09/2025 | Romina         | Diseño de Class Diagrams, Class Dictionary y Database Diagram. Inicio de Capítulo V con Software Configuration Management.                                                      |
|     1.1 | 14/09/2025 | Todo el equipo | Revisión final, corrección de estilo y ortografía. Inclusión de evidencia de implementación (Landing, Frontend, Backend, API), bibliografía y anexos. Preparación para entrega. |



<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

Durante la documentación del proyecto el grupo utilizó GitHub como controlador de versiones permitiendo ver el registro de cambios durante el ciclo académico.

A continuación se muestra una captura de los insights de los integrantes de acuerdo a las entregas:

TB2: 
<img width="928" height="482" alt="inisss" src="https://github.com/user-attachments/assets/7234530d-4d15-47d8-bf5f-943253430be7" />

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


## Objetivos SMART