# <center>Informe de Trabajo Final</center>

<p align="center">
<strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"><br>
<strong>Carrera: </strong>Ingeniería de Software<br>
<strong>Curso: </strong>Diseño de Experimentos de Ingeniería de Software<br>
<strong>Sección: </strong>4446<br>
<strong>Profesor: </strong>Cenas Vasquez, Lennin Percy<br>
<strong>Startup: </strong>[NOMBRE_DEL_STARTUP]<br>
<strong>Producto: </strong>KitchenTech<br>
<strong>Integrantes del equipo:</strong><br>
- Johan Príncipe Godoy – u202014511<br>
- Nombre Apellido – Código<br>
- Nombre Apellido – Código<br>
- Nombre Apellido – Código<br>
<strong>2025 - 01</strong>
</p>

---

# Registro de Versiones del Informe

| Versión | Fecha      | Autor(es) | Descripción de modificación |
|---------|------------|-----------|-----------------------------|
| 1.0     | 2025-04-01 | [Nombre]  | Versión inicial             |

---

# Project Report Collaboration Insights

- **Repositorio GitHub:** [URL_REPOSITORIO]
- Evidencias de colaboración por miembro (commits, PRs, issues)
- Capturas de estadísticas de GitHub

---

# Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)

### Parte I: As-Is Software Project
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-Is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
  - [3.3 Product Backlog](#33-product-backlog)
  - [3.4 Impact Mapping](#34-impact-mapping)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
    - [4.1.3 Mobile Style Guidelines](#413-mobile-style-guidelines)
      - [4.1.3.1 iOS Style](#4131-ios-mobile-style-guidelines)
      - [4.1.3.2 Android Style](#4132-android-mobile-style-guidelines)
  - [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Wireframes](#431-landing-page-wireframes)
    - [4.3.2 Mock-ups](#432-landing-page-mock-ups)
  - [4.4 Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
    - [4.4.1 Wireframes](#441-mobile-applications-wireframes)
    - [4.4.2 Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3 Mock-ups](#443-mobile-applications-mock-ups)
    - [4.4.4 User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
  - [4.5 Mobile Applications Prototyping](#45-mobile-applications-prototyping)
    - [4.5.1 Android](#451-android-mobile-applications-prototyping)
    - [4.5.2 iOS](#452-ios-mobile-applications-prototyping)
  - [4.6 Web Applications UX/UI Design](#46-web-applications-uxui-design)
    - [4.6.1 Wireframes](#461-web-applications-wireframes)
    - [4.6.2 Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
    - [4.6.3 Mock-ups](#463-web-applications-mock-ups)
    - [4.6.4 User Flow Diagrams](#464-web-applications-user-flow-diagrams)
  - [4.7 Web Applications Prototyping](#47-web-applications-prototyping)
  - [4.8 Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1 Context Diagram](#481-software-architecture-context-diagram)
    - [4.8.2 Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3 Components Diagrams](#483-software-architecture-components-diagrams)
  - [4.9 Object-Oriented Software Design](#49-object-oriented-software-design)
    - [4.9.1 Class Diagrams](#491-class-diagrams)
    - [4.9.2 Class Dictionary](#492-class-dictionary)
  - [4.10 Database Design](#410-database-design)
    - [4.10.1 Relational/Non-Relational Diagram](#4101-relationalnon-relational-database-diagram)


- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1 Software Configuration Management](#51-software-configuration-management)
    - [5.1.1 Development Environment](#511-development-environment-configuration)
    - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.1.3 Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4 Deployment Configuration](#514-software-deployment-configuration)
  - [5.2 Implementation & Deployment](#52-product-implementation--deployment)
    - [5.2.1 Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2 Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3 Frontend-Web App](#523-implemented-frontend-web-application-evidence)
    - [5.2.4 Mobile App](#524-implemented-native-mobile-application-evidence)
    - [5.2.5 RESTful API](#525-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.6 API Docs](#526-restful-api-documentation)
    - [5.2.7 Team Collaboration](#527-team-collaboration-insights)
  - [5.3 Video About-the-Product](#53-video-about-the-product)

### Parte II: Verification, Validation & Pipeline

- [Capítulo VI: Product Verification & Validation](#capítulo-vi-product-verification--validation)
  - [6.1 Testing Suites](#61-testing-suites--validation)
    - [6.1.1 Unit Tests](#611-core-entities-unit-tests)
    - [6.1.2 Integration Tests](#612-core-integration-tests)
    - [6.1.3 BDD](#613-core-behavior-driven-development-bdd)
    - [6.1.4 System Tests](#614-core-system-tests)
  - [6.2 Static Testing & Verification](#62-static-testing--verification)
    - [6.2.1 Static Code Analysis](#621-static-code-analysis)
    - [6.2.2 Reviews](#622-reviews)
  - [6.3 Validation Interviews](#63-validation-interviews)
    - [6.3.1 Diseño](#631-diseño-de-entrevistas)
    - [6.3.2 Registro](#632-registro-de-entrevistas)
    - [6.3.3 Evaluación Heurística](#633-evaluación-según-heurísticas)
  - [6.4 Auditoría de UX](#64-auditoría-de-experiencias-de-usuario)
    - [6.4.1 Auditoría realizada](#641-auditoría-realizada)
      - [6.4.1.1 Información del grupo auditado](#6411-información-del-grupo-auditado)
      - [6.4.1.2 Cronograma de auditoría realizada](#6412-cronograma-de-auditoría-realizada)
      - [6.4.1.3 Contenido de la auditoría realizada](#6413-contenido-de-la-auditoría-realizada)
    - [6.4.2 Auditoría recibida](#642-auditoría-recibida)
      - [6.4.2.1 Información del grupo auditor](#6421-información-del-grupo-auditor)
      - [6.4.2.2 Cronograma de auditoría recibida](#6422-cronograma-de-auditoría-recibida)
      - [6.4.2.3 Contenido de la auditoría recibida](#6423-contenido-de-la-auditoría-recibida)
      - [6.4.2.4 Resumen de modificaciones](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)

- [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)
  - [7.1 Continuous Integration](#71-continuous-integration)
    - [7.1.1 Tools and Practices](#711-tools-and-practices)
    - [7.1.2 Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
  - [7.2 Continuous Delivery](#72-continuous-delivery)
    - [7.2.1 Tools and Practices](#721-tools-and-practices)
    - [7.2.2 Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
  - [7.3 Continuous Deployment](#73-continuous-deployment)
    - [7.3.1 Tools and Practices](#731-tools-and-practices)
    - [7.3.2 Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
  - [7.4 Continuous Monitoring](#74-continuous-monitoring)
    - [7.4.1 Monitoring Pipeline Components](#741-monitoring-pipeline-components)
    - [7.4.2 Alerting Pipeline Components](#742-alerting-pipeline-components)
    - [7.4.3 Notification Pipeline Components](#743-notification-pipeline-components)

### Parte III: Experiment-Driven Lifecycle

- [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
  - [8.1 Experiment Planning](#81-experiment-planning)
    - [8.1.1 As-Is Summary](#811-as-is-summary)
    - [8.1.2 Raw Material](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
    - [8.1.3 Experiment-Ready Questions](#813-experiment-ready-questions)
    - [8.1.4 Question Backlog](#814-question-backlog)
    - [8.1.5 Experiment Cards](#815-experiment-cards)
  - [8.2 Experiment Design](#82-experiment-design)
    - [8.2.1 Hypotheses](#821-hypotheses)
    - [8.2.2 Measures](#822-measures)
    - [8.2.3 Conditions](#823-conditions)
    - [8.2.4 Scale Calculations and Decisions](#824-scale-calculations-and-decisions)
    - [8.2.5 Methods Selection](#825-methods-selection)
    - [8.2.6 Data Analytics: Goals, KPIs and Metrics Selection](#826-data-analytics-goals-kpis-and-metrics-selection)
    - [8.2.7 Web and Mobile Tracking Plan](#827-web-and-mobile-tracking-plan)
  - [8.3 Experimentation](#83-experimentation)
    - [8.3.1 To-Be User Stories](#831-to-be-user-stories)
    - [8.3.2 To-Be Product Backlog](#832-to-be-product-backlog)
    - [8.3.3 Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
      - [8.3.3.1 To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)
      - [8.3.3.2 Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)
      - [8.3.3.3 Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)
      - [8.3.3.4 Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)
      - [8.3.3.5 Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
      - [8.3.3.6 Team Collaboration Insights](#8336-team-collaboration-insights)
    - [8.3.4 To-Be Validation Interviews](#834-to-be-validation-interviews)
      - [8.3.4.1 Diseño de Entrevistas](#8341-diseño-de-entrevistas)
      - [8.3.4.2 Registro de Entrevistas](#8342-registro-de-entrevistas)
  - [8.4 Aftermath & Analysis](#84-aftermath--analysis)
    - [8.4.1 Results Interpretation](#841-results-interpretation)
    - [8.4.2 Re-prioritized Backlog](#842-re-prioritized-backlog)
  - [8.5 Continuous Learning](#85-continuous-learning)
    - [8.5.1 Shareback Session Artifacts](#851-shareback-session-artifacts-learning-workflow)
  - [8.6 To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)
    - [8.6.1 About-the-Product Intro Video](#861-about-the-product-intro-video)

- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)


---

# Student Outcome

## Tabla de evidencias por participante:

| Participante | Entrega | Acciones realizadas | Conclusiones |
|--------------|---------|---------------------|--------------|
| Nombre       | TF1     | [Acciones]          | [Conclusión] |

---

# Parte I: As-Is Software Project

## Capítulo I: Introducción

### 1.1 Startup Profile
#### 1.1.1 Descripción de la Startup
#### 1.1.2 Perfiles de integrantes del equipo
<table border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="https://github.com/W3bW0rks/Project-Report/blob/1387b57f0bf4a86fc34d9d0a688142d5ad6aaf95/assets/Johan-Principe.png?raw=true" alt="" style="margin-bottom: 5px;" width="400"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Johan Principe Godoy
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
		   Soy un estudiante de Ingeniería de Software con conocimientos en lenguajes de programación como C#, Python, JavaScript, entre otros. Me apasiona la tecnología y el desarrollo de software, y estoy interesado en seguir aprendiendo más y desarrollar mis habilidades como programador. Además, soy responsable, proactivo y me gusta trabajar en equipo para lograr los objetivos propuestos.
        </td>
    </tr>
<tr align="center">
        <td rowspan="3">
            <img src="https://github.com/W3bW0rks/Project-Report/blob/1387b57f0bf4a86fc34d9d0a688142d5ad6aaf95/assets/Johan-Principe.png?raw=true" alt="" style="margin-bottom: 5px;" width="400"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Johan Principe Godoy
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
		   Soy un estudiante de Ingeniería de Software con conocimientos en lenguajes de programación como C#, Python, JavaScript, entre otros. Me apasiona la tecnología y el desarrollo de software, y estoy interesado en seguir aprendiendo más y desarrollar mis habilidades como programador. Además, soy responsable, proactivo y me gusta trabajar en equipo para lograr los objetivos propuestos.
        </td>
    </tr>
<tr align="center">
        <td rowspan="3">
            <img src="https://github.com/W3bW0rks/Project-Report/blob/1387b57f0bf4a86fc34d9d0a688142d5ad6aaf95/assets/Johan-Principe.png?raw=true" alt="" style="margin-bottom: 5px;" width="400"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Johan Principe Godoy
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
		   Soy un estudiante de Ingeniería de Software con conocimientos en lenguajes de programación como C#, Python, JavaScript, entre otros. Me apasiona la tecnología y el desarrollo de software, y estoy interesado en seguir aprendiendo más y desarrollar mis habilidades como programador. Además, soy responsable, proactivo y me gusta trabajar en equipo para lograr los objetivos propuestos.
        </td>
    </tr>
<tr align="center">
        <td rowspan="3">
            <img src="https://github.com/W3bW0rks/Project-Report/blob/1387b57f0bf4a86fc34d9d0a688142d5ad6aaf95/assets/Johan-Principe.png?raw=true" alt="" style="margin-bottom: 5px;" width="400"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Johan Principe Godoy
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
		   Soy un estudiante de Ingeniería de Software con conocimientos en lenguajes de programación como C#, Python, JavaScript, entre otros. Me apasiona la tecnología y el desarrollo de software, y estoy interesado en seguir aprendiendo más y desarrollar mis habilidades como programador. Además, soy responsable, proactivo y me gusta trabajar en equipo para lograr los objetivos propuestos.
        </td>
    </tr>
</table>

### 1.2 Solution Profile
#### 1.2.1 Antecedentes y problemática
##### 1.2.2 Lean UX Process
##### 1.2.2.1 Lean UX Problem Statements
##### 1.2.2.2 Lean UX Assumptions
##### 1.2.2.3 Lean UX Hypothesis Statements
##### 1.2.2.4 Lean UX Canvas

### 1.3 Segmentos objetivo

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1 Competidores
#### 2.1.1 Análisis competitivo
#### 2.1.2 Estrategias y tácticas frente a competidores

### 2.2 Entrevistas
#### 2.2.1 Diseño de entrevistas
#### 2.2.2 Registro de entrevistas
#### 2.2.3 Análisis de entrevistas

### 2.3 Needfinding
#### 2.3.1 User Personas
#### 2.3.2 User Task Matrix
#### 2.3.3 User Journey Mapping
#### 2.3.4 Empathy Mapping
#### 2.3.5 As-Is Scenario Mapping

### 2.4 Ubiquitous Language

---

## Capítulo III: Requirements Specification

### 3.1 To-Be Scenario Mapping
### 3.2 User Stories
### 3.3 Product Backlog
### 3.4 Impact Mapping

---

## Capítulo IV: Product Design

### 4.1 Style Guidelines
#### 4.1.1 General Style Guidelines
#### 4.1.2 Web Style Guidelines
#### 4.1.3 Mobile Style Guidelines
##### 4.1.3.1 iOS Mobile Style Guidelines
##### 4.1.3.2 Android Mobile Style Guidelines

### 4.2 Information Architecture
#### 4.2.1 Organization Systems
#### 4.2.2 Labeling Systems
#### 4.2.3 SEO Tags and Meta Tags
#### 4.2.4 Searching Systems
#### 4.2.5 Navigation Systems

### 4.3 Landing Page UI Design
#### 4.3.1 Landing Page Wireframes
#### 4.3.2 Landing Page Mock-ups

### 4.4 Mobile Applications UX/UI Design
#### 4.4.1 Mobile Applications Wireframes
#### 4.4.2 Mobile Applications Wireflow Diagrams
#### 4.4.3 Mobile Applications Mock-ups
#### 4.4.4 Mobile Applications User Flow Diagrams

### 4.5 Mobile Applications Prototyping
#### 4.5.1 Android Mobile Applications Prototyping
#### 4.5.2 iOS Mobile Applications Prototyping

### 4.6 Web Applications UX/UI Design
#### 4.6.1 Web Applications Wireframes
#### 4.6.2 Web Applications Wireflow Diagrams
#### 4.6.3 Web Applications Mock-ups
#### 4.6.4 Web Applications User Flow Diagrams

### 4.7 Web Applications Prototyping
### 4.8 Domain-Driven Software Architecture
#### 4.8.1 Software Architecture Context Diagram
#### 4.8.2 Software Architecture Container Diagrams
#### 4.8.3 Software Architecture Components Diagrams

### 4.9 Object-Oriented Software Design
#### 4.9.1 Class Diagrams
#### 4.9.2 Class Dictionary

### 4.10 Database Design
#### 4.10.1 Relational/Non-Relational Database Diagram.

## Capítulo V: Product Implementation

### 5.1 Software Configuration Management
#### 5.1.1 Development Environment Configuration
#### 5.1.2 Source Code Management
#### 5.1.3 Source Code Style Guide & Conventions
#### 5.1.4 Software Deployment Configuration

### 5.2 Product Implementation & Deployment
#### 5.2.1 Sprint Backlogs
#### 5.2.2 Implemented Landing Page Evidence
#### 5.2.3 Implemented Frontend-Web Application Evidence
#### 5.2.4 Implemented Native-Mobile Application Evidence
#### 5.2.5 Implemented RESTful API and/or Serverless Backend Evidence
#### 5.2.6 RESTful API Documentation
#### 5.2.7 Team Collaboration Insights

### 5.3 Video About-the-Product

---

# Parte II: Verification, Validation & Pipeline

## Capítulo VI: Product Verification & Validation

### 6.1 Testing Suites & Validation
#### 6.1.1 Core Entities Unit Tests
#### 6.1.2 Core Integration Tests
#### 6.1.3 Core Behavior-Driven Development (BDD)
#### 6.1.4 Core System Tests

### 6.2 Static Testing & Verification
#### 6.2.1 Static Code Analysis
##### 6.2.1.1 Coding standard & Code conventions.
##### 6.2.1.2 Code Quality & Code Security.
#### 6.2.2 Reviews

### 6.3 Validation Interviews
#### 6.3.1 Diseño de Entrevistas
#### 6.3.2 Registro de Entrevistas
#### 6.3.3 Evaluación según heurísticas

### 6.4 Auditoría de Experiencias de Usuario
#### 6.4.1 Auditoría realizada
##### 6.4.1.1 Información del grupo auditado.
##### 6.4.1.2 Cronograma de auditoría realizada.
##### 6.4.1.3 Contenido de la auditoría realizada.
#### 6.4.2 Auditoría recibida
##### 6.4.2.1 Información del grupo auditor.
##### 6.4.2.2 Cronograma de auditoría recibida.
##### 6.4.2.3 Contenido de la auditoría recibida.
##### 6.4.2.4 Resumen de modificaciones para subsanar hallazgos.

---

## Capítulo VII: DevOps Practices

### 7.1 Continuous Integration
#### 7.1.1 Tools and Practices
#### 7.1.2 Build & Test Suite Pipeline Components

### 7.2 Continuous Delivery
#### 7.2.1 Tools and Practices
#### 7.2.2 Stages Deployment Pipeline Components

### 7.3 Continuous Deployment
#### 7.3.1 Tools and Practices
#### 7.3.2 Production Deployment Pipeline Components

### 7.4 Continuous Monitoring
#### 7.4.1 Monitoring Pipeline Components
#### 7.4.2 Alerting Pipeline Components
#### 7.4.3 Notification Pipeline Components

---

# Parte III: Experiment-Driven Lifecycle

## Capítulo VIII: Experiment-Driven Development

### 8.1 Experiment Planning
#### 8.1.1 As-Is Summary
#### 8.1.2 Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims.
#### 8.1.3 Experiment-Ready Questions
#### 8.1.4 Question Backlog
#### 8.1.5 Experiment Cards

### 8.2 Experiment Design
#### 8.2.1 Hypotheses
#### 8.2.2 Measures
#### 8.2.3 Conditions
#### 8.2.4 Scale Calculations and Decisions.
#### 8.2.5 Methods Selection
#### 8.2.6 Data Analytics: Goals, KPIs and Metrics Selection.
#### 8.2.7 Web and Mobile Tracking Plan.

### 8.3 Experimentation
#### 8.3.1 To-Be User Stories
#### 8.3.2 To-Be Product Backlog
#### 8.3.3 Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle
##### 8.3.3.1 To-Be Sprint Backlogs
##### 8.3.3.2 Implemented To-Be Landing Page Evidence
##### 8.3.3.3 Implemented To-Be Frontend-Web Application Evidence
##### 8.3.3.4 Implemented To-Be Native-Mobile Application Evidence
##### 8.3.3.5 Implemented To-Be RESTful API and/or Serverless Backend Evidence
##### 8.3.3.6 Team Collaboration Insights
#### 8.3.4 To-Be Validation Interviews
##### 8.3.4.1 Diseño de Entrevistas
##### 8.3.4.2 Registro de Entrevistas

### 8.4 Aftermath & Analysis
#### 8.4.1 Results Interpretation
#### 8.4.2 Re-prioritized Backlog

### 8.5 Continuous Learning
#### 8.5.1 Shareback Session Artifacts: Learning Workflow

### 8.6 To-Be Software Platform Pre-launch
#### 8.6.1 About-the-Product Intro Video

---

# Conclusiones y Recomendaciones

## Conclusiones
## Recomendaciones
## Video About-the-Team

---

# Bibliografía

(Usar formato APA)

---

# Anexos

- Anexo A: Registro de Versiones
- Anexo B: Evidencias de entrevistas
- Anexo C: Mockups / Wireframes
- Anexo D: Resultados de pruebas  
