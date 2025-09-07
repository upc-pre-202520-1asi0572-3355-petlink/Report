<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 7mo Ciclo</strong><br>
    <strong>Desarrollo de Soluciones IoT - 3355</strong><br>
    <strong>Profesor: David Carlos Vera Olivera</strong><br>
    <br>INFORME DE TRABAJO FINAL - TF
</p>

</p>

<p align="center">
    <strong>Startup: PetLink</strong><br>
    <strong>Producto: PetWatch </strong>
</p>

<div style="text-align:center;">
    <h3>Relación de integrantes:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Integrante</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Fernandez Alva, Maria Fernanda</td>
            <td>U20201C131</td>
        </tr>
        <tr>
            <td>Belleza Tello, Paolo Eduardo</td>
            <td>U20191A137</td>
        </tr>
        <tr>
            <td>Pilares Pocohuanca, Maria</td>
            <td>U202215528</td>
        </tr>
        <tr>
            <td>Chávarri Zarzosa, Daniel Jhared</td>
            <td>U202211108</td>
        </tr>
        <tr>
            <td>Góngora Sánchez, Marco Antonio</td>
            <td>U20211A085</td>
        </tr>
      <tr>
            <td>Rondon Añaños, Cristopher</td>
            <td>U20201A291</td>
        </tr>
      <tr>
            <td>Mayurí Armas, Jose Carlo</td>
            <td>U202011437</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Setiembre, 2025</strong>
</p>
<br>

<h1 align="center">Registro de versiones del Informe</h1>
</br>
<table>
        <thead>
            <tr>
                <th>Versión</th>
                <th>Fecha</th>
                <th>Autor</th>
                <th>Descripción de modificaciones</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>TB1</th>
                <td>20/09/2025</td>
                <td>
                    <ul>
          <li>Maria Fernanda Fernandez</li>
          <li>Paolo Belleza</li>
          <li>Maria Pilares</li>
          <li>Daniel Chávarri</li>
          <li>Marco Góngora</li>
          <li>Cristopher Rondon</li>
          <li>Jose Mayurí</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Capítulo I: Introducción</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Solution Software Design</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
</tbody>
</table>

# Project Report Collaboration Insights

**TB1:** Se han desarrollado las actividades correspondientes para la entrega TB1 en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: https://github.com/upc-pre-202520-1asi0572-3355-petlink/Report

# Contenido 
## Tabla de contenidos

## [Student Outcome](#student-outcome)
## [Capítulo I: Introducción](#capítulo-i-introducción)
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
## [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Journey Mapping](#233-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
## [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.2. Software Architecture Container Level](#4132-software-architecture-container-level)
      - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1. Bounded Context: IAM](#421-bounded-context-iam)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2. Bounded Context: Management](#422-bounded-context-management)
      - [4.2.2.1. Domain Layer](#4221-domain-layer)
      - [4.2.2.2. Interface Layer](#4222-interface-layer)
      - [4.2.2.3. Application Layer](#4223-application-layer)
      - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
      - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
        - [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3. Bounded Context: Records](#423-bounded-context-records)
      - [4.2.3.1. Domain Layer](#4231-domain-layer)
      - [4.2.3.2. Interface Layer](#4232-interface-layer)
      - [4.2.3.3. Application Layer](#4233-application-layer)
      - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
        - [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
## [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
- [5.1. Style Guidelines](#51-style-guidelines)
  - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
  - [5.1.2. Web, Mobile and IoT Devices Style Guidelines](#512-web-mobile-and-iot-devices-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
  - [5.2.1. Organization Systems](#521-organization-systems)
  - [5.2.2. Labeling Systems](#522-labeling-systems)
  - [5.2.3. Searching Systems](#523-searching-systems)
  - [5.2.4. SEO Tags and Meta Tags](#524-seo-tags-and-meta-tags)
  - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
  - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
  - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-applications-uxui-design)
  - [5.4.1. Applications Wireframes](#541-applications-wireframes)
  - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
  - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
  - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
- [5.5. Applications Prototyping](#55-applications-prototyping)

## [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
  - [6.1.2. Source Code Management](#612-source-code-management)
  - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
  - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
  - [6.2.1. Sprint 1](#621-sprint-1)
    - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
    - [6.2.1.2. Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
    - [6.2.1.3. Sprint Backlog 1](#6213-sprint-backlog-1)
    - [6.2.1.4. Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
    - [6.2.1.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.1.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.1.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.1.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.1.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
  - [6.2.2. Sprint 2](#622-sprint-2)
    - [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
    - [6.2.2.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
    - [6.2.2.3. Sprint Backlog 2](#6223-sprint-backlog-2)
    - [6.2.2.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
    - [6.2.2.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.2.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.2.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.2.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.2.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
  - [6.2.3. Sprint 3](#622-sprint-3)
    - [6.2.3.1. Sprint Planning 3](#6221-sprint-planning-3)
    - [6.2.3.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
    - [6.2.3.3. Sprint Backlog 3](#6223-sprint-backlog-3)
    - [6.2.3.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
    - [6.2.3.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.3.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.3.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.3.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.3.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)

## [Conclusiones](#conclusiones)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)

## [Video About-the-Team](#video-about-the-team)

## [Bibliografía](#bibliografía)

## [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 5

Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas                                                                                                      | Conclusiones |
| - |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| - |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta. | **TB1**<br>**Fernandez Alva, Maria Fernanda**<br>...<br><br>**Belleza Tello, Paolo Eduardo**<br>...<br><br>**Pilares Pocohuanca, Maria**<br>...<br><br>**Chávarri Zarzosa, Daniel Jhared**<br>...<br><br>**Góngora Sánchez, Marco Antonio**<br>...<br><br>**Rondon Añaños, Cristopher**<br>... <br><br>**Mayurí Armas, Jose Carlo**<br>...<br><br> | **TB1:** Como equipo, trabajamos de manera colaborativa para cubrir todas las etapas clave del desarrollo inicial de Chemtrack, desde la definición del problema y el análisis de mercado hasta la construcción de la solución tecnológica. Cada integrante asumió un rol fundamental en áreas como la elaboración de user stories, la identificación de eventos de dominio, el diseño de entrevistas, la creación de arquetipos, el mapeo de experiencias y el modelado de la arquitectura del sistema. Esta sinergia nos permitió integrar múltiples perspectivas y asegurar una base sólida, estratégica y centrada en el usuario para el desarrollo de nuestra solución. | Crea un entorno colaborativo einclusivo, establece metas, planifica tareas y cumple objetivos. | **TB1**<br>**Fernandez Alva, Maria Fernanda**<br>...<br><br>**Belleza Tello, Paolo Eduardo**<br>...<br><br>**Pilares Pocohuanca, Maria**<br>...<br><br>**Chávarri Zarzosa, Daniel Jhared**<br>...<br><br>**Góngora Sánchez, Marco Antonio**<br>...<br><br>**Rondon Añaños, Cristopher**<br>... <br><br>**Mayurí Armas, Jose Carlo**<br>...<br><br> | **TB1:** El equipo demostró una sólida capacidad para colaborar de forma inclusiva, planificando estratégicamente las tareas y cumpliendo los objetivos del proyecto. A través de reuniones constantes, el uso de metodologías ágiles y una distribución clara de responsabilidades, logramos mantener una comunicación efectiva, anticipar desafíos y avanzar de manera organizada. Esto nos permitió construir una base sólida para el desarrollo de PetLink, alineando tanto los aspectos técnicos como los objetivos del negocio. <br><br> |

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

PetLink es una startup tecnológica que busca transformar la forma en que se cuida y gestiona la salud de los animales domésticos, integrando soluciones IoT con plataformas digitales web y móviles. Nuestro objetivo es ofrecer una experiencia completa, tanto para veterinarios como para dueños de mascotas, permitiendo un seguimiento continuo, confiable y en tiempo real del estado de cada animal.

La solución está compuesta por una **pechera IoT inteligente**, equipada con sensores para medir variables críticas de salud y comportamiento (como el ritmo cardíaco y el nivel de actividad). A diferencia de los dispositivos convencionales, la pechera también incluye un **sistema de luz LED integrado**, que funciona como un indicador visual del estado de la mascota:

- **Verde:** Estado estable.

- **Amarillo:** Condición de alerta leve.

- **Rojo:** Signo crítico que requiere atención inmediata.

Los datos captados por la pechera son transmitidos en tiempo real hacia una **aplicación móvil** y una **plataforma web**, donde se procesan, almacenan y presentan en un formato claro y accesible tanto para veterinarios como para dueños.

Esta integración asegura una **supervisión continua** en internamientos veterinarios y una mayor **confianza y tranquilidad** para los dueños, eliminando la dependencia de observaciones manuales y favoreciendo un cuidado preventivo más eficiente.

La innovación de PetLink radica en la integración de tres componentes claves:

- **IoT para el monitoreo de salud animal:** Dispositivos inteligentes que recopilan información confiable de forma no invasiva.

- **Plataforma centralizada:** Una aplicación que conecta a veterinarios y dueños en un mismo entorno digital, eliminando barreras de comunicación.

- **Experiencia personalizada:** Cada mascota cuenta con un perfil único donde se centralizan datos médicos, tratamientos, historial y evolución.

A diferencia de los métodos tradicionales, PetLink no solo registra la información de forma pasiva, sino que permite accionar rápidamente con alertas, recomendaciones y reportes automáticos, lo que mejora la toma de decisiones en situaciones críticas.

### 1.1.2. Perfiles de integrantes del equipo

<table>
   <tr>
    <th>
      <img src="assets/Chapter-1/" width="800px">
    </th>
    <td valign="top">
      <p><b>Fernandez Alva, Maria Fernanda</b></p>
      <p>
       ...
      </p>
    </td>
  </tr>
     <tr>
    <th>
      <img src="assets/Chapter-1/foto-.png"  width="800px">
    </th>
    <td valign="top">
      <p><b>Belleza Tello, Paolo Eduardo</b></p>
      <p>
     ...
    </td>
  </tr>
     <tr>
    <th>
      <img src="assets/Chapter-1/Omar.jpeg" width="800px">
    </th>
    <td valign="top">
      <p><b>Pilares Pocohuanca, Maria</b></p>
      <p>
      ...
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/daniel.jpeg" width="800px">
    </th>
    <td valign="top">
      <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
      <p>
       Soy estudiante de la UPC, tengo 20 años. Estoy en la carrera de Ingeniería de Software, ya que, siempre me gustó la tecnología, los videojuegos, las páginas web, pero sobre todo 
       cómo crearlos. Estoy cursando el 6 ciclo de la carrera y mis habilidades son C++, Python, HTML y JavaScript. También soy bueno en ser responsable con cada curso y organizar mi 
       tiempo en ellos.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/marco.jpg" width="800px">
    </th>
    <td valign="top">
      <p><b>Góngora Sánchez, Marco Antonio</b></p>
      <p>
       Soy estudiante de la UPC. Estoy en la carrera de Ingeniería de Software ya que siempre me gustó el desarrollo y la comprensión de esta. Tengo conocimientos básicos en C++, Python, Vue y medio-avanzado en Java, SpringBoot y SQL. Con respecto a mis aptitudes es la cooperación en equipo, responsabilidad y creatividad tanto en diseño/estilos cómo en arquitectura de software.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/janiel.jpg" width="800px">
    </th>
    <td valign="top">
      <p><b>Rondon Añaños, Cristopher</b></p>
      <p>
      ...
      </p>
    </td>
  </tr>
   </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/janiel.jpg" width="800px">
    </th>
    <td valign="top">
      <p><b>Mayurí Armas, Jose Carlo</b></p>
      <p>
      ...
      </p>
    </td>
  </tr>
</table>

## 1.2. Solution Profile

**Product name**

El nombre elegido para nuestra solución es PetLink. Este nombre transmite la idea de un vínculo directo entre las mascotas, sus dueños y los veterinarios, garantizando un cuidado integral mediante el uso de dispositivos IoT y una plataforma digital.

**Product Description**

La solución IoT propuesta es innovadora porque ofrece un monitoreo inteligente de animales domésticos en tiempo real, integrando un collar IoT equipado con sensores y una aplicación móvil/web de gestión de salud.

El dispositivo IoT mide variables críticas como el ritmo cardíaco, el nivel de actividad y la ubicación de la mascota, transmitiendo los datos a la plataforma. Estos datos son analizados y convertidos en información útil tanto para veterinarios como para dueños, quienes podrán acceder a historiales clínicos, tratamientos y reportes de evolución.

La innovación principal radica en que el collar solo se activa durante internamientos veterinarios, asegurando un control preciso en situaciones críticas y evitando el uso innecesario del dispositivo en otros momentos. De esta forma, los veterinarios pueden gestionar pacientes de manera más eficiente y los dueños reciben información transparente sobre el estado de salud de sus animales.

Con PetLink, se mejora el control preventivo, se generan alertas oportunas y se refuerza la confianza entre veterinarios y dueños de mascotas.

**Monetización**

El modelo de negocio de PetLink se basa en un esquema de suscripción que cubre tanto el acceso a la plataforma como el uso de los dispositivos IoT.

- Los veterinarios podrán contratar planes que incluyan el monitoreo IoT y la gestión digital de historias clínicas.

- Los dueños de mascotas tendrán acceso a versiones básicas gratuitas (historia clínica digital y notificaciones) y versiones premium con características avanzadas como reportes detallados, seguimiento remoto y acceso a contenido educativo de cuidado animal.

- El hardware IoT (collar inteligente) se incluirá dentro de los planes premium o podrá adquirirse por separado, garantizando la sostenibilidad del modelo.

### 1.2.1. Antecedentes y problemática

En los últimos años, el cuidado de los animales domésticos ha adquirido gran relevancia debido al aumento de la tenencia responsable de mascotas y a la importancia que estas representan como miembros del hogar. Sin embargo, persisten diversos problemas relacionados con el seguimiento de la salud animal y la comunicación entre veterinarios y dueños.

Actualmente, muchos dueños de mascotas carecen de herramientas tecnológicas que les permitan monitorear en tiempo real variables críticas como el ritmo cardíaco, el nivel de actividad o la ubicación de sus animales. Esta falta de información limita la capacidad de detectar tempranamente signos de alerta, lo que puede retrasar la atención veterinaria en casos de emergencia.

Del lado de los veterinarios, el desafío radica en la **fragmentación de la información médica:** historiales clínicos dispersos, tratamientos gestionados manualmente y una falta de sistemas integrados que combinen datos médicos con métricas en tiempo real. Esto dificulta brindar un seguimiento preciso y continuo, especialmente cuando una mascota se encuentra internada.

Otro problema significativo es la **escasa participación activa de los dueños en el cuidado preventivo.** En la mayoría de los casos, los dueños solo acuden a los veterinarios cuando la mascota presenta síntomas graves, en lugar de contar con un acompañamiento constante que les permita prevenir complicaciones.

Por tanto, la ausencia de un sistema IoT centralizado y automatizado para el cuidado animal genera **brechas en la atención veterinaria, en la gestión de tratamientos y en la tranquilidad de los dueños**, lo cual repercute negativamente tanto en la salud de los animales como en la confianza hacia los profesionales del rubro.

**Herramienta 5W y 2H**

**¿Qué? (What)**
El problema central es la falta de un sistema de monitoreo integral y en tiempo real para animales domésticos. Los dueños no pueden supervisar constantemente variables críticas de salud y los veterinarios carecen de datos precisos que complementen la historia clínica. Esto genera retrasos en la detección de enfermedades o emergencias.

**¿Cuándo? (When)**

La problemática se presenta especialmente en dos contextos:

Durante la vida diaria de las mascotas en casa, donde los dueños no tienen visibilidad de su salud en tiempo real.

Cuando la mascota está internada, momento en el cual los veterinarios necesitan supervisión continua para tomar decisiones oportunas.

**¿Dónde? (Where)**

Este problema se observa en clínicas veterinarias, hospitales de animales y en los hogares de los dueños de mascotas. Afecta tanto al ámbito clínico (gestión profesional de la salud) como al doméstico (seguimiento por parte del dueño).

**¿Quién? (Who)**

Los principales afectados son:

Dueños de mascotas, quienes no cuentan con datos claros sobre la evolución de la salud de sus animales.

Veterinarios, que enfrentan limitaciones al momento de gestionar información médica y tomar decisiones en base a datos incompletos.

Mascotas, que son las más impactadas al no recibir un monitoreo preventivo que pueda anticipar complicaciones.

**¿Por qué? (Why)**

La falta de soluciones tecnológicas avanzadas en el sector veterinario es el principal factor. Actualmente, los sistemas de gestión clínica suelen ser manuales o digitales de forma parcial, pero no integran sensores IoT ni monitoreo en tiempo real. Esto genera brechas en la atención, falta de transparencia con los dueños y poca capacidad de acción preventiva.

**¿Cómo? (How)**

El problema se manifiesta a través de episodios críticos no detectados a tiempo, retrasos en el inicio de tratamientos y ausencia de un registro integral que vincule los datos de salud en tiempo real con la historia clínica de cada mascota.

**¿Cuánto? (How Much)**

De acuerdo con estimaciones de la industria veterinaria, más del 60% de los casos de emergencia animal podrían haberse detectado con un monitoreo preventivo y continuo. Además, la creciente inversión global en el mercado de tecnología para mascotas (que supera los 10 mil millones de dólares anuales) evidencia la urgencia y relevancia de soluciones innovadoras como PetLink.

**Conclusiones de las 5W + 2H**

El análisis revela que la problemática no solo radica en la falta de monitoreo en tiempo real, sino también en la fragmentación de información entre veterinarios y dueños. Esta situación afecta directamente la calidad del cuidado animal, incrementa la probabilidad de emergencias y reduce la confianza en el sistema de atención veterinaria.

Para abordar este desafío, se requiere una solución integral que combine sensores IoT con plataformas digitales, centralizando la información, generando alertas oportunas y promoviendo la participación activa de los dueños en la salud preventiva de sus mascotas.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Los servicios veterinarios actuales no cuentan con una solución integral que permita a los veterinarios y dueños de mascotas supervisar en tiempo real el estado de salud de los animales domésticos.

Las historias clínicas suelen estar fragmentadas o en papel, los dueños no reciben alertas oportunas sobre cambios en la salud de sus mascotas, y el monitoreo durante internamientos se limita a la observación manual, lo que retrasa la toma de decisiones.

Nuestra solución aborda esta brecha con un collar IoT inteligente que recopila variables como ritmo cardíaco, actividad y ubicación, transmitiendo la información a una plataforma digital donde veterinarios y dueños pueden acceder a reportes y alertas.

Nos enfocaremos inicialmente en clínicas veterinarias y dueños de mascotas en entornos urbanos, donde existe mayor acceso a tecnología y una creciente preocupación por la salud preventiva de los animales.

Sabremos que hemos tenido éxito cuando observemos una reducción en emergencias no previstas, un mejor control en internamientos y un aumento en la satisfacción de los dueños respecto al cuidado de sus mascotas.

#### 1.2.2.2. Lean UX Assumptions

*Bussiness Outcomes:*

- Reducción en un 40% de emergencias críticas no detectadas previamente.

- Incremento del 50% en la eficiencia de gestión clínica mediante historiales centralizados y monitoreo IoT.

- Aumento del 80% en la satisfacción de dueños gracias a reportes transparentes y alertas en tiempo real.

*Users:*

- **Veterinarios:** Que gestionan la salud de los animales y requieren herramientas tecnológicas de apoyo.

- **Dueños de mascotas:** Que desean información clara, preventiva y en tiempo real sobre sus animales.

*User Outcomes & Benefits:*

- **Veterinarios:** Historias clínicas digitales organizadas, acceso a métricas IoT en internamientos y soporte para decisiones médicas más rápidas.

- **Dueños:** Tranquilidad al recibir alertas inmediatas, acceso a la historia clínica digital y seguimiento del tratamiento actual de su mascota.

*Features Assumptions:*

- Monitoreo en tiempo real de variables de salud (ej. ritmo cardíaco, actividad, ubicación).
- Alertas inmediatas al veterinario y al dueño ante signos críticos.
- Historias clínicas digitales centralizadas con evolución y tratamientos.
- Reportes automatizados para dueños y profesionales.

*User Assumptions:*

- **¿Quién es el usuario?** Veterinarios y dueños de mascotas.
- **¿Dónde encaja nuestro** producto en su vida? En clínicas veterinarias (gestión clínica) y en hogares (cuidado preventivo).
- **¿Qué problemas evita?** Falta de datos en tiempo real, retraso en diagnósticos y desconocimiento del estado de salud animal.
- **¿Cuándo y cómo se usa?** En internamientos (IoT activo con supervisión continua) y en casa (historia clínica, tratamientos, alertas).
- **Características importantes:** precisión en sensores, interfaz sencilla, notificaciones claras, reportes automatizados.
- **Comportamiento esperado:** interfaz intuitiva, alertas visibles y sistema confiable.

*Business Assumptions:*

- Creemos que los veterinarios necesitan una forma más eficiente de monitorear pacientes y gestionar historias clínicas.
- Creemos que los dueños quieren información clara y actualizada sobre la salud de sus mascotas.
- Creemos que el valor principal es la tranquilidad y confianza generada por el monitoreo en tiempo real.
- Creemos que los ingresos provendrán de suscripciones a la plataforma y del uso de los collares IoT.
- Creemos que nuestra competencia serán apps de gestión veterinaria sin IoT o dispositivos de rastreo simples.
- Los superaremos ofreciendo una solución integrada, preventiva y fácil de usar.
- El mayor riesgo es que los veterinarios no adopten la solución por resistencia tecnológica; lo mitigaremos con capacitaciones y soporte continuo.

#### 1.2.2.3. Lean UX Hypothesis Statements

A continuación, se plantean las hipótesis que proponen una solución a la problemática dentro de las funcionalidades de la solución tecnológica. Cada una de estas hipótesis es específica y medible para sustentar el éxito de manera objetiva. Cabe resaltar que las métricas actuales son iguales a promedios generales de soluciones ya existentes.

### Hipótesis 1:
*Creemos que los veterinarios necesitan una herramienta para monitorear en tiempo real a las mascotas internadas.*
*Sabremos que hemos tenido éxito cuando el 80% de los internamientos en clínicas piloto utilicen el collar IoT para control.*

**Métricas:**
**Uso del IoT en internamientos:** Actual 0%, Meta 80%.

**Reducción de emergencias no previstas:** Actual 5/mes, Meta 1/mes.

---

### Hipótesis 2:
*Creemos que los dueños de mascotas necesitan recibir alertas oportunas para sentirse más tranquilos sobre la salud de sus animales.*
*Sabremos que hemos tenido éxito cuando el 90% de los dueños reporten mayor confianza en el cuidado de sus mascotas.*

**Métricas:**
**Nivel de satisfacción en encuestas:** Actual 60%, Meta 90%.

**Reportes consultados en la app:** Actual 20%, Meta 70%.

---

### Hipótesis 3:
*Creemos que la centralización de la historia clínica digital mejorará la eficiencia en el trabajo de los veterinarios.*
*Sabremos que hemos tenido éxito cuando el tiempo promedio de gestión clínica se reduzca en un 50%.*

**Métricas:**
**Tiempo en actualizar historias clínicas:** Actual 15 min/paciente, Meta 7 min/paciente.

**Uso de historias digitales:** Actual 10%, Meta 80%.

---

### Hipótesis 4:
*Creemos que el uso de sensores IoT precisos permitirá anticipar complicaciones médicas en mascotas.*
*Sabremos que hemos tenido éxito cuando los datos IoT permitan detectar signos críticos antes de que ocurran emergencias en el 70% de los casos.*

**Métricas:**
**Emergencias anticipadas:** Actual 0%, Meta 70%.

**Casos críticos no detectados:** Actual 100%, Meta 20%.

---

#### 1.2.2.4. Lean UX Canvas

<img src="assets/Capítulo 1/Canvas.jpg" width="800px">

## 1.3. Segmentos objetivo

**Segmento 1: Veterinarios**

Los veterinarios constituyen un actor clave dentro de PetLink, ya que son los responsables del cuidado clínico y del uso profesional de la información generada por el sistema.

**Funciones principales para este segmento:**

- Registro de **dueños y mascotas** en la plataforma, creando perfiles digitales únicos.

- Creación y actualización de la **historia clínica digital** de cada mascota, incluyendo antecedentes médicos, diagnósticos y vacunas.

- Gestión de **tratamientos en curso**, como recetas, recomendaciones y evolución del paciente.

- **Vinculación de un collar IoT** a la mascota durante su internamiento, para monitorear variables críticas en tiempo real (ej. ritmo cardíaco, actividad, alertas).

- Acceso a un **panel de control centralizado**, donde solo se muestran las mascotas internadas con IoT activo, optimizando la eficiencia en la supervisión.

Con estas herramientas, los veterinarios pueden mejorar la calidad del cuidado, reducir el tiempo en la gestión administrativa y ofrecer una atención más transparente y confiable a los dueños.

**Segmento 2: Dueños de Mascotas**

Los dueños representan el segundo pilar de PetLink, ya que son quienes buscan tranquilidad y confianza en el cuidado de sus animales.

**Funciones principales para este segmento:**

- Acceso a su cuenta personal para visualizar la información de una o varias mascotas.

- Consulta de la historia clínica digital resumida, con datos de vacunas, antecedentes y diagnósticos compartidos por el veterinario.

- Revisión del tratamiento actual, incluyendo recetas, evolución y recomendaciones activas.

- Recepción de alertas y notificaciones automáticas en caso de novedades en el tratamiento o cambios en la salud de su mascota.

- En internamientos, acceso a reportes básicos del monitoreo IoT, con información clara sobre la evolución, signos de alerta o estado estable de su mascota.

De esta manera, los dueños participan activamente en el cuidado preventivo, fortalecen su relación con el veterinario y se benefician de la tranquilidad que otorga contar con información confiable en tiempo real.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td>PetWatch <img src="Capitulo 2/Gemini_Generated_Image_47c82d47c82d47c8.png" width="80"></td>
    <td>Trackisafe <img src="Capitulo 2/TrackiSafe.png" width="80"></td>
    <td>Invoxia <img src="Capitulo 2/invoxia.png" width="80"></td>
    <td>Weenect <img src="Capitulo 2/Weenect.png" width="80"></td>
  </tr>
  <tr>
    <td rowspan="2" style="transform: rotate(180deg); writing-mode: vertical-lr; text-align: center;">Perfil</td>
    <td>Overview</td>
    <td>La pechera inteligente que permite monitorear en tiempo real el pulso y ritmo cardíaco del animal mientras está en observación veterinaria, brindando tranquilidad al dueño y apoyo al especialista.</td>
    <td>Un dispositivo GPS compacto que ofrece rastreo en tiempo real, geovallas, alertas y botón SOS.</td>
    <td>El dispositivo permite monitorear salud integral del perro: ritmo cardíaco, actividad, apetito, comportamiento, además de GPS</td>
    <td>Rastrea la ubicación mediante GPS, con actualizaciones cada 30 segundos. Ligero (43 g), resistente al agua, y permite geovallas y alertas de batería baja.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes? </td>
    <td>Monitorea la salud del animal (signos vitales) en tiempo real, ofreciendo seguridad y apoyo directo a veterinarios y tranquilidad a dueños.</td>
    <td>Rastreo en tiempo real con geovallas y botón SOS.</td>
    <td>Tecnología avanzada que combina GPS y monitoreo de salud con IA.</td>
    <td>Rastreo GPS en tiempo real con actualizaciones rápidas y app intuitiva.</td>
  </tr>
  <tr>
    <td rowspan="2" style="transform: rotate(180deg); writing-mode: vertical-lr; text-align: center;">Perfil de Marketing</td>
    <td >Mercado objetivo</td>
    <td>Clínicas veterinarias, hospitales de animales, dueños preocupados por la salud en consultas y hospitalización.</td>
    <td>Dueños de mascotas que temen que su animal se pierda.</td>
    <td>Dueños de perros, interesados en salud preventiva y seguridad.</td>
    <td>Dueños de perros y gatos que salen frecuentemente.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing </td>
    <td>Alianzas con veterinarias, demostraciones en ferias de mascotas, campañas en redes sociales dirigidas a dueños responsables.</td>
    <td>Venta online global, destacando seguridad y tranquilidad.</td>
    <td>Asociaciones con ferias de innovación, premios tecnológicos.</td>
    <td>Venta en tiendas online de mascotas y veterinarias.</td>
  </tr>
  <tr>
    <td rowspan="3" style="transform: rotate(180deg); writing-mode: vertical-lr; text-align: center;">Perfil de Producto</td>
    <td >Productos & Servicios </td>
    <td>Pechera con sensores + plataforma de monitoreo en tiempo real + alertas automáticas + aplicación.</td>
    <td>Dispositivo GPS + app de rastreo + plan de suscripción.</td>
    <td>Dispositivo con GPS + sensores de salud + app + servicios de IA.</td>
    <td>Localizador GPS con SIM integrada + aplicación.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Modelo de venta directa a veterinarias o alquiler por uso; costos moderados comparados con dispositivos importados.</td>
    <td>Dispositivo + suscripción mensual (~2 €/mes).</td>
    <td>Alto precio (gama premium) + suscripción incluida un tiempo.</td>
    <td>Precio medio + planes de recarga (6 o 12 meses).</td>
  </tr>
  <tr>
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td>Plataforma web y app móvil para acceso a datos en vivo.</td>
    <td>App móvil + Web.</td>
    <td>Web oficial y app móvil.</td>
    <td>App móvil + web de proveedores locales.</td>
  </tr>
  <tr>
    <td rowspan="5" style="transform: rotate(180deg); writing-mode: vertical-lr; text-align: center;">Análisis SWOT</td>
    <td colspan="5">
      Realice esto para su <b>startup</b> y sus competidores. 
      Sus fortalezas deberían apoyar sus oportunidades y contribuir 
      a lo que ustedes definen como su posible ventaja competitiva.
    </td>
  </tr>
  <tr>
    <td>Fortalezas</td>
    <td>Nicho poco explorado (veterinarias), enfoque en salud, bajo costo.</td>
    <td>Alta precisión, cobertura global.</td>
    <td>Innovación premiada, funciones completas.</td>
    <td>Disponible en Perú, buena integración con app.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Producto nuevo sin reputación en el mercado, requiere pruebas clínicas para ganar confianza.</td>
    <td>Batería de corta duración, depende de señal móvil.</td>
    <td>Costo elevado, puede ser inaccesible para mercados emergentes.</td>
    <td>Solo rastrea ubicación, sin datos de salud.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Creciente interés en IoT para mascotas, veterinarias buscando diferenciarse con tecnología.</td>
    <td>Expansión en países con problemas de mascotas perdidas.</td>
    <td>Creciente interés en wellness para mascotas.</td>
    <td>Mercado latinoamericano abierto a soluciones de rastreo.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Avance rápido de marcas internacionales, desconfianza inicial en un producto local.</td>
    <td>Competidores con mejor batería o sin costos de suscripción.</td>
    <td>Alternativas más baratas con funcionalidades similares.</td>
    <td>Competidores más completos (con salud incluida).</td>
  </tr>
</table>

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas.

A continuación, se diseñaron entrevistas dirigidas a los dos segmentos objetivos definidos para el proyecto. Las preguntas fueron elaboradas con el fin de generar respuestas abiertas y detalladas por parte de los entrevistados, permitiendo así obtener información valiosa que nos ayude a comprender mejor sus necesidades. Cabe mencionar que las preguntas de introducción no están incluidas en esta lista; sin embargo, se realizarán al inicio de cada entrevista.

### 2.2.2. Registro de entrevistas
  
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
En esta sección, se buscarán las necesidades implícitas y explícitas de las personas o segmentos para poder diseñar y adaptar el producto solución de manera apropiada.

### 2.3.1. User Personas

Se realiza las User Persona, personaje ficticio para reflejar al cliente ideal, estos user persona son creados en base a la investigación de capitulos previos para identificar a los diferentes tipos de clientes que podrían usar el producto solución. Se utilizó la herramienta UXPressia.

### 2.3.2. User Task Matrix

A continuación, se muestra el User Task Matrix para los siguientes segmentos objetivo:

### 2.3.3. Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

---

## 3.3. Impact Mapping

## 3.4. Product Backlog

A continuación, se mostrará la herramienta Product Backlog, lista de trabajo ordenado por la prioridad para el equipo de desarrollo de PetLink.

# Capítulo IV: Solution Software Design

## 4.1 Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
Durante la fase de *Event Storming*, el equipo de desarrollo llevó a cabo una sesión colaborativa en la que se compartieron ideas sobre funcionalidades y características que se deseaban incorporar en el proyecto. 

Para realizar esta dinámica se hizo uso de la plataforma *MIRO* como soporte visual y de organización. *Ver ANEXO A*

#### 4.1.1.1 Candidate Context Discovery

Para priorizar el desarrollo del núcleo funcional del sistema aplicamos la técnica *start-with value*, con el objetivo de tener una visión más clara y enfocada del producto desde sus bases.

#### 4.1.1.2 Domain Message Flows Modeling

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.2. Software Architecture Container Level 

#### 4.1.3.3. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: IAM

#### 4.2.1.2. Interface Layer

#### 4.2.1.3. Application Layer

#### 4.2.1.4. Infrastructure Layer

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.1.6.2. Bounded Context Database Design Diagram

### 4.2.2. Bounded Context: Management

#### 4.2.2.1. Domain Layer

#### 4.2.2.2. Interface Layer

#### 4.2.2.3. Application Layer

#### 4.2.2.4. Infrastructure Layer

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.2.6.2. Bounded Context Database Design Diagram

### 4.2.3. Bounded Context: Records

#### 4.2.3.1. Domain Layer

#### 4.2.3.2. Interface Layer

#### 4.2.3.3. Application Layer

#### 4.2.3.4. Infrastructure Layer

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.3.6.2. Bounded Context Database Design Diagram
