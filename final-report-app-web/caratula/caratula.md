# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

## Carrera: Ingeniería de Software
## Aplicaciones Web - Presencial 
## PROFESOR: Alex Sanchez
## NRC: 4388
## INFORME TF
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

Ciclo 2025-10


# Registro de versiones del informe

| Versión | Fecha      | Autor | Descripción de modificación                                                                                                                                                                                                                           |
|---------|------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| TB1     | 25/04/2025 | Torres Flores, Paolo Alessandro<br/>Aguirre Castillo, Sergio Cesar<br/>Rojas Piñero, Luis Miguel<br/>Muñoz Machuca, Maria Elena<br/>Montañez Moreno, Luis Angel  | Se realizó la documentación de los capítulos I, II, III, IV y V así como la correcta diagramación de componentes, estados, clases y entidades. Además de realizó la creación de la landing page estática así como también el deployment de la misma.  |
| TP      | 15/05/2025 |Torres Flores, Paolo Alessandro<br/>Aguirre Castillo, Sergio Cesar<br/>Rojas Piñero, Luis Miguel<br/>Muñoz Machuca, Maria Elena<br/>Montañez Moreno, Luis Angel | Se realizaron las correcciones detalladas en las notas del la primera entrega así como también se agregaron los sprints correspondientes además de la creación y desarrollo de la capa de presentación de nuestra app web.                            |
| TB2     | 21/06/2025 | Torres Flores, Paolo Alessandro<br/>Aguirre Castillo, Sergio Cesar<br/>Muñoz Machuca, Maria Elena<br/>Montañez Moreno, Luis Angel | Se realizaron las correcciones detalladas en las notas del la segunda entrega así como también se agregaron los sprints correspondientes además de la creación y desarrollo de la capa de datos de nuestra app web.                                   |
| TF      | 07/07/2025 | Torres Flores, Paolo Alessandro<br/>Aguirre Castillo, Sergio Cesar<br/>Muñoz Machuca, Maria Elena<br/>Montañez Moreno, Luis Angel | Se realizaron las correcciones indicadas en la devolución de la segunda entrega. Se agregaron los sprints faltantes y se desarrolló la capa de datos de la aplicación web, asegurando su integración con el resto del sistema. También se mejoró el modelo de base de datos, eliminando relaciones uno a uno innecesarias para optimizar la estructura. En el análisis competitivo se incluyeron los precios y costos expresados en soles, tal como fue solicitado. Además, se completaron las Technical Stories, se vincularon los videos correspondientes a las secciones de Product y Team, y se corrigió el despliegue de los objetos restantes. Estas mejoras permitieron consolidar el proyecto y cumplir con los criterios establecidos para la entrega final.                                   |


# Project Report Collaboration Insights

**Insights del reporte**:

![insights reporte](https://github.com/user-attachments/assets/f8d1bc0d-9d0d-4d2d-8e83-9c47bd407046)

<br>

**Insights del frontend**:

![image](https://github.com/user-attachments/assets/d2d0bbaf-4a88-4280-b8ab-a8a70ca4dd17)

<br>

**Insights del backend**:

![image](https://github.com/user-attachments/assets/0f7f80a2-d629-42bf-9921-bf8b49efb46c)


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
| Criterio específico                                                                             | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Conclusiones |
|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta.                                | **TB1**<br>**Paolo Torres**: Durante el desarrollo del proyecto, organicé reuniones y lideré la planificación de tareas. Me aseguré de que cada integrante tuviera claridad sobre lo que debía hacer y fomenté un espacio de trabajo ordenado y enfocado. Supervisé el avance general para que trabajáramos de forma coordinada.<br>**Luis Moreno**: En esta entrega mantuve una comunicación fluida con mis compañeros, informando sobre cada avance y coordinando aspectos técnicos cuando era necesario. También colaboré en la resolución de dudas que surgían en el equipo.<br>**Sergio Aguirre**: Me aseguré de mantener informados a los demás sobre los avances y cambios que hacía en mi módulo. Participé activamente en las decisiones del grupo y me comprometí con la entrega de resultados dentro de los tiempos establecidos.<br>**María Muñoz**: Estuve presente en las reuniones acordadas y comuniqué oportunamente mis avances. Participé en las coordinaciones con el equipo y respondí con responsabilidad a mis tareas asignadas.<br><br>**TP**<br>**Paolo Torres**: Me encargué de revisar que las interfaces cumplan con los criterios de usabilidad, asegurándome de que se vea y funcione de forma coherente.<br>**Luis Moreno**: Aporté en la validación visual del módulo que trabajé, cuidando que los componentes estuvieran bien conectados con la lógica definida.<br>**Sergio Aguirre**: Realicé pruebas de navegación en mi parte del frontend para detectar errores y asegurarme de que la experiencia del usuario sea clara y fluida.<br>**María Muñoz**: Comprobé que todos los elementos de mi interfaz estuvieran bien alineados con el diseño general. Ajusté detalles para que sean intuitivos y accesibles.<br><br>**TB2**<br>**Paolo Torres**: Implementé los servicios necesarios en backend, siguiendo una estructura clara y manteniendo la lógica del dominio definida previamente.<br>**Luis Moreno**: Desarrollé los endpoints de mi módulo y verifiqué que cumplan con lo planificado. Me aseguré de mantener buena integración con las otras partes del sistema.<br>**Sergio Aguirre**: Organicé el código backend de forma ordenada, documentando los servicios y asegurando que las funciones se comporten correctamente.<br>**María Muñoz**: Finalicé la implementación del backend de mi módulo, verificando que las operaciones funcionen según lo esperado y estén alineadas con lo discutido en equipo.<br><br>**TF**<br>****Paolo Torres**: Lideré el trabajo final asegurándome de que todo el grupo se mantuviera enfocado en los objetivos. Coordiné la integración de los módulos, revisé el cumplimiento de los criterios de evaluación y participé activamente en la documentación y presentación.<br>
**Luis Moreno**: Apoyé en la integración de los diferentes componentes del sistema y verifiqué que el producto final se comportara de acuerdo con lo esperado. También contribuí en la revisión del informe y en la preparación del material de presentación.<br>
**Sergio Aguirre**: Me encargué de realizar ajustes finales tanto en frontend como en backend, asegurando el correcto funcionamiento del sistema. Además, contribuí en la redacción del informe final y en la preparación de la exposición.<br>
**María Muñoz**: Verifiqué que todos los módulos estuvieran correctamente integrados y colaboré en la revisión general del sistema. Apoyé en la elaboración de las conclusiones y recomendaciones del informe final.<br>
|**TB1**<br>Se demostró un liderazgo compartido y funcional. Cada integrante asumió un rol activo en el desarrollo del proyecto y en la toma de decisiones. La comunicación fue constante, lo que nos permitió mantenernos alineados, colaborar eficazmente y avanzar como un equipo unido.<br><br>**TP**<br>Durante el desarrollo del trabajo práctico, se evidenció una distribución equilibrada de tareas y un compromiso constante por parte de todos los integrantes. Cada miembro aportó activamente en la implementación técnica del proyecto, demostrando iniciativa y responsabilidad en su rol específico. La coordinación efectiva y el diálogo permanente fueron claves para resolver desafíos, optimizar tiempos y garantizar la calidad del resultado final. El trabajo en equipo no solo facilitó la integración de conocimientos, sino que también potenció nuestras habilidades colaborativas en un entorno práctico.<br><br>**TB2**<br>En esta segunda instancia del trabajo bibliográfico, se fortaleció aún más el liderazgo compartido y el compromiso colectivo. Cada integrante profundizó en los temas asignados, aportando con responsabilidad al análisis crítico de la información. La colaboración fue fluida y constante, lo que permitió integrar distintas perspectivas en una visión coherente y sólida. El trabajo en equipo se mantuvo como eje central del proceso, favoreciendo un aprendizaje significativo y una producción conjunta de calidad.<br><br>**TF**<br>El desarrollo del Trabajo Final representó una instancia de integración de conocimientos, colaboración efectiva y compromiso sostenido por parte de todo el equipo. Cada integrante asumió un rol clave en las distintas etapas del proyecto, desde la planificación hasta la ejecución, demostrando autonomía, responsabilidad y capacidad crítica. La coordinación y el diálogo constante fueron fundamentales para tomar decisiones acertadas, superar desafíos y lograr un resultado coherente y bien fundamentado. Este trabajo no solo consolidó lo aprendido a lo largo del proceso formativo, sino que también fortaleció nuestras competencias para el trabajo colaborativo y la resolución de problemas en contextos reales. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **TB1**<br>**Paolo Torres**: Me aseguré de que todos los miembros del equipo tuvieran claras las metas desde el inicio. Planifiqué los sprints con el equipo, distribuí tareas equitativamente y promoví un espacio de trabajo participativo y respetuoso.<br>**Luis Moreno**: Coordiné mi trabajo con el de los demás, respetando las fechas establecidas y comunicando cualquier inconveniente para solucionarlo juntos. Siempre estuve dispuesto a colaborar más allá de mi módulo cuando fue necesario.<br>**Sergio Aguirre**: Cumplí con las tareas asignadas de forma puntual, y en las reuniones siempre aporté ideas que pudieran mejorar el flujo de trabajo o la implementación de los módulos.<br>**María Muñoz**: Realicé mis entregas en los tiempos acordados. Participé activamente en la planificación del proyecto y mantuve una comunicación clara y constante para asegurar que todo esté alineado.<br><br>**TP**<br>**Paolo Torres**: Ayudé a integrar los componentes del frontend de forma que sigan una línea visual y funcional clara. Revisé estilos y jerarquías visuales para mantener coherencia en todo el sistema.<br>**Luis Moreno**: Validé que los componentes visuales cumplieran su función correctamente y colaboré para corregir errores menores detectados durante las pruebas.<br>**Sergio Aguirre**: Hice mejoras a nivel de interfaz en base al feedback recibido, trabajando en conjunto con los demás para unificar criterios visuales.<br>**María Muñoz**: Revisé mi módulo para asegurarme de que fuera accesible, fácil de usar y consistente con la experiencia que queríamos brindar en toda la app.<br><br>**TB2**<br>**Paolo Torres**: Establecí el esqueleto del backend para integrar correctamente cada módulo. Me aseguré de que la comunicación entre capas fuera clara y estable.<br>**Luis Moreno**: Validé el correcto funcionamiento de los servicios desde base de datos hasta los controladores. Documenté los endpoints y realicé pruebas locales.<br>**Sergio Aguirre**: Organicé mis servicios backend y verifiqué que los datos viajen correctamente entre las capas. Me aseguré de mantener coherencia con el diseño establecido.<br>**María Muñoz**: Ajusté funcionalidades del backend en base a los resultados de las pruebas. Trabajé para que las respuestas fueran claras y manejables desde el frontend. |**TB1**<br> El equipo logró crear un entorno donde la colaboración fue constante y cada miembro se sintió parte activa del proceso. Las metas fueron claras desde el inicio, las tareas fueron cumplidas en tiempo y forma, y se mantuvo un ambiente inclusivo, respetuoso y eficiente. Todo esto contribuyó al éxito del proyecto.<br><br>**TP**<br>Durante el desarrollo del trabajo práctico, se generó un entorno colaborativo e inclusivo, en el que todos los integrantes participaron activamente. Se establecieron metas claras desde el inicio, se planificaron las tareas de forma equitativa y se cumplió con los objetivos propuestos en los tiempos establecidos. La comunicación constante y el compromiso individual fortalecieron la dinámica grupal y permitieron una ejecución eficiente del trabajo.<br><br>**TB2**<br>En esta segunda entrega del trabajo bibliográfico, se mantuvo un ambiente de colaboración e inclusión que permitió el aporte equitativo de todos los integrantes. La planificación previa de tareas y la definición conjunta de metas facilitaron un análisis profundo de las fuentes, promoviendo el pensamiento crítico y el trabajo colectivo. La responsabilidad compartida contribuyó a alcanzar los objetivos del trabajo con solidez y cohesión.<br><br>**TF**<br>A lo largo del desarrollo del Trabajo Final, el equipo consolidó un entorno colaborativo e inclusivo, en el que se valoraron todas las voces y se respetaron las diferentes perspectivas. Se establecieron metas concretas, se organizaron tareas de manera estratégica y se cumplió con los objetivos mediante una planificación eficiente y un trabajo sostenido. Esta experiencia no solo reflejó el aprendizaje técnico y académico adquirido, sino también la capacidad del grupo para trabajar de forma cohesionada, autónoma y comprometida. |
