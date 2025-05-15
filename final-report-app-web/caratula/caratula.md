# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

## Carrera: Ingeniería de Software
## Aplicaciones Web - Presencial 
## PROFESOR: Alex Sanchez
## Sección: 1ASI0730
## NRC: 4388
## INFORME TB1
## START UP: Foodle
## PRODUCTO: GoodFood

### INTEGRANTES:
<table>
  <thead>
    <tr>
      <th style="background-color: #333; color: #fff;">Apellidos y Nombres</th>
      <th style="background-color: #333; color: #fff;">Código de Alumno</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Torres Flores, Paolo Alessandro</td>
      <td>U20221F613</td>
    </tr>
    <tr>
      <td>Aguirre Castillo, Sergio Cesar</td>
      <td>U202310425</td>
    </tr>
    <tr>
      <td>Rojas Piñero, Luis Miguel</td>
      <td>U202220864</td>
    </tr>
    <tr>
      <td>Muñoz Machuca, Maria Elena</td>
      <td>U202317442</td>
    </tr>
    <tr>
      <td>Montañez Moreno, Luis Angel</td>
      <td>U202223811</td>
    </tr>
  </tbody>
</table>

--- 

Ciclo 2025-01


# Registro de versiones del informe

| Versión | Fecha      | Autor | Descripción de modificación                                                                                                                                                                                                                          |
|---------|------------|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| TB1     | 25/04/2025 | Torres Flores, Paolo Alessandro<br/>Aguirre Castillo, Sergio Cesar<br/>Rojas Piñero, Luis Miguel<br/>Muñoz Machuca, Maria Elena<br/>Montañez Moreno, Luis Angel  | Se realizó la documentación de los capítulos I, II, III, IV y V así como la correcta diagramación de componentes, estados, clases y entidades. Además de realizó la creación de la landing page estática así como también el deployment de la misma. |


# Project Report Collaboration Insights

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
    - [2.4. Ubiquitous Language](#24-Ubiquitous-language)
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

# Student Outcome
| Criterio específico                                                                             | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Conclusiones |
|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta.                                | Rojas Piñero En el desarrollo de esta entrega me enfoque en trabajar de manera conntinua y siempre comunicando todo tipo de cambios o acciones por realizar a mis compañeros de equipo para mantener un flujo de trabajo optimo y llevadero durante el desarrollo de nuestro proyecto.<br> **Luis Angel Montañez Moreno**  En el desarrollo de esta primera entrega, se apoyó a cada miembro del equipo en las que presentaban un poco de dificultad y también se compartió información y recursos para fortalecer el trabajo del grupo.<br/>Torres Flores: En el proceso de este entregable pude poner en acción mis habilidades de trabajo en equipo y liderazgo mediante la organización de sesiones de trabajo conjunto y lideración de sprints que nos llevaron a culminar el desarrollo de este trabajo dentro del tiempo establecido y de manera organizada.<br/> Aguirre Castillo: En el desarrollo de esta entrega me enfoqué en trabajar de manera continua y siempre comunicando todo tipo de cambios o acciones por realizar a mis compañeros de equipo para mantener un flujo de trabajo óptimo y llevadero durante el desarrollo de nuestro proyecto.<br/>**María Muñoz** En el desarrollo del proyecto he tratado de comunicarme con mi grupo y participando activamente siempre de las reuniones previamente coordinadas. Asimismo, realizando las tareas asignadas comunicando a mis compañeros con anticipación para no tener complicaciones con la documentación                                                                                                                                                                                                                                                                                                      |Durante el desarrollo de las actividades, se demostró un liderazgo conjunto efectivo. Todos los miembros del equipo participaron activamente en la toma de decisiones, se promovió la escucha y el respeto mutuo, y se compartieron responsabilidades de manera equitativa. Esto permitió que el grupo se mantuviera enfocado, resolviera problemas de manera colaborativa y aprovechara al máximo las habilidades individuales para lograr resultados de alta calidad.           |
|Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | Rojas Piñero Para el desarrollo de esta primera entrega lo mas importante fue la comunicación y compatibilidad a nivel de equipo, comprendiendo las situaciones de cada uno y apoyandonos si era necesario para que el desarrollo del proyecto no se detuviera. Cumpliendo asi las metas predefinidas que teniamos y llevando a cabo los objetivos que nos propusimos.<br> **Luis Angel Montañez Moreno** En el desarrollo de esta primera entrega, se coordinaron reuniones grupales para asignar las responsabilidades que iba asumir cada integrante. Además, se fomentó la participación activa de cada uno para la toma de decisiones. <br/> Torres Flores: En el proceso de desarrollo de este entregable pude poner en práctica mis capacidades para planificar tareas en un entorno colaborativo, cumpliendo así todas y cada unas de las metas que se consignaron al inicio del trabajo. Esto lo pude lograr mediante las charlas de trabajo que se realizaron en la plataforma Discord y poniendo todo de mi parte para llegar a cumplir con lo establecido.<br/>Aguirre Castillo: Para el desarrollo de esta primera entrega, lo más importante fue la comunicación y la compatibilidad a nivel de equipo, comprendiendo las situaciones de cada integrante y apoyándonos cuando fue necesario para que el desarrollo del proyecto no se detuviera. De esta manera, logramos cumplir las metas predefinidas y llevar a cabo los objetivos que nos propusimos.<br/>**María Muñoz**, En el desarrollo del proyecto he desarrollado las tareas asignadas, comunicando cuando las he realizado y también corregir en caso hayan errores. Además, he participado en las reuniones para aclarar puntos del trabajo y cuál es el rol de cada uno, lo cual ha llevado al cumplimiento de las metas propuestas. |El equipo logró crear un ambiente de trabajo colaborativo e inclusivo, en el que cada integrante tuvo voz y participación activa. Se establecieron metas claras y alcanzables, se planificaron las tareas de manera organizada y se asignaron responsabilidades de forma justa. Gracias a una comunicación constante y al compromiso de todos, se cumplieron los objetivos en tiempo y forma, fortaleciendo la cohesión del grupo y demostrando una gestión eficaz del proyecto.|              
