# Capítulo 5: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management.

Para la gestión de la configuración de software de nuestra aplicación nos enfocaremos en la Gestión de Código Fuente, donde controlaremos las versiones y estableceremos una estructura organizada para el código; la Configuración del Entorno de Desarrollo, aquí nos aseguramos que todos los miembros del equipo tengan herramientas consistentes y la Configuración de Despliegue, que aborda el despliegue en entornos de producción. Esta toma de decisiones garantiza la coherencia y eficiencia a lo largo del ciclo de vida de la aplicación, lo que es necesario para cumplir con nuestra misión de ofrecer a estudiantes, instructores y administradores optimizar sus actividades académicas deportivas.

### 5.1.1 Software Development Environment Configuration

En esta sección, detallaremos y explicaremos los productos utilizados en el proyecto digital, así como su propósito y cómo se accede a cada uno de ellos y siguiendo las restricciones establecidas.

1. Project Management:
Para gestionar el proyecto, se utilizaron herramientas de comunicación y control de versiones. Se estableció una organización en GitHub para gestionar el código y las versiones del proyecto. Además, para las reuniones de equipo y la comunicación interna, se utilizaron plataformas como Google Meet y Discord.
- Github: https://github.com/
- Google Meet: https://meet.google.com/
- Discord: https://discord.com/download

2. Requirements Management:
Para la gestión de requisitos se llevó a cabo mediante el uso de herramientas personalizadas que permitieron recopilar, organizar y priorizar los requisitos del proyecto de manera eficiente. Se utilizó Trello, una herramienta visual para la gestión de requisitos, permitiendo la creación tableros personalizados para organizar y priorizar las tareas del proyecto que permitió realizar los Task board y Pivotal Tracker, utilizado para gestionar y realizar un seguimiento del Product Backlog del proyecto.
- Trello: https://trello.com/es
- Pivotal Tracker: https://www.pivotaltracker.com/

3. Product UX/UI Design:
Para el diseño de la experiencia de usuario (UX) y diseño de interfaz de usuario (UI) del producto se utilizo la herramienta Figma, esta herrmienta permitio al equipo crear wireframes, mockups y prototipos interactivos para visualizar y validad el diseño del producto antes de la implementación.
Por otro lado, para la creación de User Personas, Empathy Maps, Journey Maps e Impact Maps se utilizó UXPressia y para la creación de As-Is y To-Be Scenario Maps se utilizó Miro.
- Figma: https://www.figma.com/downloads/
- UXPressia: https://uxpressia.com/
- Miro: https://miro.com/es/

4. Software Development:
Para el desarrollo de software se utilizó HTML5, CSS3 y JavaScript para el desarrollo de la Landing Page de la startup, por otro lado, para la creación del Web Application de la startup se utilizarán el framework de Vue por el lado del Frontend y en el Backend se utilizará ASP.NET Core Framework y C#.
Para trabajar con estas tecnologías, se emplearon los siguientes IDEs:
Visual Studio Code: Herramienta principal para el desarrollo Frontend y Backend, que ofrece una amplia gama de extensiones para mejorar la productividad del equipo. (En nuestro caso solo fue utilizado para la Landing Page).
JetBrains Toolbox: Proporciona un entorno integrado para el desarrollo web, con características avanzadas de edición y depuración que faciitan la creación de aplicaciones web robustas.
- Visual Studio Code: https://code.visualstudio.com/
- JetBrains Toolbox: https://www.jetbrains.com/toolbox-app/

5. Software Documentation:
La documentación del software se realizó utilizando GitHub, además de ser utilizado como plataforma de control de versiones, GitHub también se empleó para alojar la documentación técnica del proyecto. Se crearon repositorios específicos para almacenar toda la información. La documentación se gestionó mediante archivos Markdown para facilitar la creación y edición colaborativa.
- GitHub: https://github.com/


### 5.1.2 Source Code Management.

En este proyecto, utilizaremos GitHub como plataforma y sistema de control de versiones para gestionar el código fuente de nuestras diferentes partes del proyecto dentro de una organización.

**Repositorios en GitHub**
- Organización: https://github.com/upc-pre-202401-si729-sv54-sportease
- Landing Page: https://github.com/upc-pre-202401-si729-sv54-sportease/upc-pre-202401-si729-sv54-sportease-landing-page
- Report : https://github.com/upc-pre-202401-si729-sv54-sportease/upc-pre-202401-si729-sv54-sportease-report

**GitFlow Workflow**
Implementaremos el modelo GitFlow como Workflow de control de versiones, siguiendo las convenciones y prácticas establecidas para una gestión eficiente del desarrollo de software.
1. **Branches Principales:
- `main`: Rama principal del repositorio, contiene el código estable y liberado.
- `develop`: Rama de desarrollo deonde se integran las nuevas características y mejoras.

2. Branches de Funcionalidades (Feature Branches):
- Para cada nueva funcionalidad, se creará una rama de funcionalidad con el prefijo `feature/`, seguido del nombre descriptivo de la función o característica. En nuestro caso, creamos 5 branches de características correspondientes a los 5 capítulos de nuestro informe, donde se realizan los commits respectivos antes de fusionarlos con la rama develop cuando estén listos.

3. Branches de Lanzamiento (Release Branches) y Branches de Corrección (Hotfix Branches):
En nuestro caso, no hicimos uso de estas branches ya que no lo vimos necesario al ser solo documentacion del reporte.

**Versionado Semántico**
Seguimos la especificación Semantic Versioning 2.0.0 para nombrar nuestras versiones, siguiendo el formato: `MAJOR.MINOR.PATCH`.

**Conventional Commits**
Aplicamos el estándar de Conventional Commits para los mensajes de commit, siguiendo un formato estructurado que describe claramente los cambios realizados. Esto nos ayudó a automatizar la generación de notas de versión y facilitar la comprensión del historial de cambos del proyecto.

Con estas prácticas y convenciones adaptadas a una organización en GitHub, buscamos mantener un flujo de desarrollo ordenado, colaborativo y bien documentado.


### 5.1.3 Source Code Style Guide & Conventions.

En esta sección, estableceremos las convenciones y prácticas que seguiremos para nombrar elementos y programar en los lenguajes utilizados en la solución, que incluyen HTML, CSS, JavaScript, TypeScript, Angular, Java y Gherkin para los archivos `.feature`. Todas las convenciones seguirán la nomenclatura en inglés y adoptarán convenciones estándar de codificación.

1. **HTML y CSS**:
- Basado en las recomendaciones de W3C y otras fuentes de la comunidad, se establecerán convenciones para el nombramiento de elemntos hTML y estilo de la codificación CSS.
- Se seguirán las convenciones recomendadas por Google para HTML y CSS, que incluyen el uso de identaciones de 2 espacios, el uso de comillas dobles para atributos y el uso de comentarios descriptivos.
- Se utilizará la metodologìa BEM para organizar las clases CSS en bloques, elementos y modificadores, lo que facilitará la modularidad y la reutilización del código. 
- Se debe utilizar los elementos HTML de manera semántica para una correcta descripción del contenido del sitio web, incluyendo el uso adecuado de etiquetas.
- Para el desarrollo con Vue.js, se adoptarán las convenciones recomendadas por la comunidad de Vue, que incluyen el uso de PascalCase para los nombres y componentes y el uso de camelCase para las propiedades y métodos de los componentes.

2. **JavaScript**:
- Se tomarán en cuenta las directrices proporcionadas por MDN para la escritura de JavaScript, que incluyen el uso de nombres descriptivos para variables y funciones en camelCase, el uso de declaración de variavles con `let` o `const` en lugar de `var`, y el uso de punto y coma al final de cada declaración.
- Se seguirán las convenciones de codificación recomendadas por Google para JavaScript, que incluyen el uso de comillas simples para literales de cadena, el uso de comentarios descriptivos y el uso de funciones de flecha para expresiones de función.

3. **Typescript**:
- Se seguirán las convenciones de codificación recomendadas por Microsoft para TypeScript, que incluyen el uso de tipos estáticos, el uso de camelCase para nombres de variables y funciones, y el uso de interfaces y tipos personalizados para mejorar la legibilidad y el mantenimiento del código.
- Se utilizarán las características específicas de TypeScript, como los tipos de datos estáticos y la inferencia de tipos, para mejorar la robustez y la claridad del código.

4. **Angular**:
- Se adoptarán las convenciones de codificación recomendadas por la comunidad de Angular, que incluyen el uso de camelCase para los nombres de archivos y carpetas, así como para los nombres de componentes, directivas y servicios.
- Se seguirán las prácticas recomendadas por Angular para la organización de proyectos, que incluyen la separación clara de módulos, componentes y servicios, y el uso de la inyección de dependencias para la gestión de dependencias.

5. **Java**:
- Se seguirán las convenciones de codificación establecidas por Oracle para el lenguaje Java, que incluyen el uso de camelCase para los nombres de variables, métodos y parámetros, el uso de PascalCase para nombres de clases y el uso de comentarios Javadoc para documentar el código.
- Se promoverá el uso de la programación orientada a objetos (OOP) y el principio de diseño SOLID para escribir código modular y mantenible.

6. **Gherkin**:
- Se aplicarán las convenciones recomendadas para escribir especificaciones legibles en Gherkin, que incluyen el uso de palabras clave como Given, When y Then para describir el comportamiento del sistema, el uso de un lenguaje sencillo y claro, y la organización de los escenarios en contextos, acciones y resultados.
- Se seguirán las mejores prácticas recomendadas por Cucumber para escribir escenarios de prueba en Gherkin, que incluyen la reutilización de pasos de prueba, la modularización de escenarios y la escritura de pruebas autoexplicativas.

Además de estas referencias, se promoverá el uso de buenas prácticas y metodologías estándar en el desarrollo de software, como la modularidad, la reutilización de código, la legibilidad del código, la optimización del rendimiento y la seguridad. 
Con estas guías de estilo y convenciones de codificación, buscamos asegurar la coherencia, la calidad y la mantenibilidad del código a lo largo de todo el proyecto.

### 5.1.4 Software Deployment Configuration.

En esta sección, describiremos la configuración necesaria para desplegar satisfactoriamente cada uno de los productos digitales de nuestra solución, incluyendo Landing Page, los Web Services y las Frontend Web Applications.

1. Landing Page: Empezaremos por crear un repositorio en GitHub para almacenar los archivos HTML, CSS y JavaScript. Luego cada integrante del equipo trabajará en su propia rama "feature" para desarrollar nuestro landing page. Una vez completada una característica, se procederá a hacer el merge con la rama "develop" para que la landing page se encuentre actualizada. estableceremos la configuración en GitHub Pages para publicar la página de destino utilizando la rama "develop". A continuación, detallamos los pasos para llevar a cabo este despliegue en GitHub Pages:

- Comenzaremos creando un repositorio público en GitHub y poniendole un nombre.
- Configurar las ramas necesarias conforme al flujo de trabajo Gitflow estándar, que comprende main, release, develop, features y hotfix.
- Dirigirse a la sección de ajustes y elegir la pestaña Pages.
- Nos dirigimos al apartado de configuración para GitHub Pages.
- En el apartado de branch, seleccionamos el branch "develop" donde se realizará el despliegue del landing page, dejando las demás configuraciones con sus valores predeterminados.
- Al seleccionar la rama correspondiente, se generará un enlace que permitirá acceder al landing page. Cada modificación efectuada en el "develop" se actualiza automáticamente.
- Cada miembro del equipo trabajará en sus propias ramas.
- Se realizarán merges entre la develop y los feature para integrar los avances.
- Se observarán los cambios reflejados en el enlace provisto por GitHub Pages.
- Finalmente, el landing estará desplegada, lista para ser visualizada y utilizada.

2. Web Services (API):
- Preparar el código fuente del servicio web, asegurando que esté correctamente estructurado y documentado.
- Configurar un entorno de desarrolo o pruebas para realizar pruebas exhaustivas del servicio antes del desplieguee.
- Desplegar el código en un servidor adecuado para el entorno de producción.
- Configurar la seguridad y la autenticación según los requisitos del sistema.
- Documentar la API utilizando OpenAPI Specification para facilitar su integración y uso por parte de otros sistemas.

3. Frontend Web Applications:
- Clonaremos el repositorio desde GitHub.
- Compilaremos y empaquetaremos las aplicaciones frontend. En nuestro caso, utilizando Angular, ejecutaremos los comandos de construcción (npm run build) para generar los archivos estáticos.
- Una vez empaquetadas, las Aplicaciones Frontend Angular pueden ser servidas utilizando un servidor de aplicaciones compatible con archivos estáticos, como Nginx o GitHub Pages para proyectos estáticos más simples.
- Si es necesario, configuraremos las rutas en el servidor de aplicaciones para que coincidan con las rutas esperadas por las aplicaciones frontend.

## 5.2 Landing Page, Services & Applications Implementation.

En esta sección, describiremos el proceso de implementación, pruebas, documentación y despliegue de la Landing Page, los Web Services y las Frontend Web Applications. Abordaremos cada componente de manera individual a lo largo de los diferentes sprints, comenzando en este Sprint 1 con la implementación específica de la Landing Page. Una vez establecido nuestro Product Backlog, cada sprint se dividirá en secciones internas para abordar cada aspecto de la implementación y la colaboración del equipo.

### 5.2.1 Sprint 1

En esta sección, documentaremos y explicaremos el progreso tanto en el desarrollo del producto como en la colaboración del equipo durante el Sprint 1. Seguimos un proceso definido que abarca desde la planificación hasta la revisión y documentación del trabajo realizado. A lo largo de las siguientes secciones, detallaremos cómo se llevó a cabo la planificación del sprint, qué tareas se incluyeron en el Sprint Backlog, las pruebas y evidencia de desarrollo para la revisión del sprint, así como la documentación de los servicios y las percepciones clave sobre la colaboración del equipo durante este periodo.

### 5.2.1.1 Sprint Planning 1

En esta sección, se detallan los aspectos principales del Sprint Planning Meeting para el Sprint n. Este encuentro es crucial para establecer los objetivos del sprint, determinar las user stories que se abordarán y asignar tareas al equipo. A continuación, se presenta un resumen del Sprint Planning Meeting para este período.

| Sprint #                             | Sprint 1           |
|--------------------------------------|--------------------|
| Sprint Planning Background                                |
| Date                                 |  2024-04-01        |
| Time                                 |  04:06 PM          |
| Location                             |  Google Meet       |
| Prepared By                          |  Piero Tarazona    |
| Attendees (to planning meeting)      |  Piero Tarazona, Mauricio Chacon, Flavio Trigueros, Moises Donayre |
| Sprint 1 – 1 Review Summary          |  El Sprint 1 fue un éxito en términos de avance del producto de software y colaboración efectiva del equipo. Los logros alcanzados y la retroalimentación recopilada durante esta revisión proporcionan una base sólida para el siguiente sprint y refuerzan el compromiso del equipo con la calidad y la entrega oportuna del producto.  |
| Sprint 1 – 1 Retrospective Summary   |  Para la retrospectiva del Sprint 1 nos sirvio para reflexionar sobre el desempeño del equipo y identificar áreas de mejora. Esto nos servira como base para impulsar la mejora continua y optimizar el trabajo del equipo en los próximos sprints.  |
| Sprint Goal & User Stories                                |
| Sprint 1 Goal                        | Alcanzar una métrica de cumplimiento del 100%, lo que indicará que se ha logrado los objetivos del sprint 1              |
| Sprint 1 Velocity                    | Con el equipo para este sprint 1 decidimos aceptar 5 Story Points      |
| Sum of Story Points                  | La suma de los Story Points para los User Stories que se están incluyendo en este Sprint 1 es 32 |


### 5.2.1.2 Sprint Backlog 1

El Sprint 1 está centrado en la implementación de las funcionalidades clave de la landing page del sitio web, priorizando las historias de usuario identificadas. Nuestro objetivo principal es proporcionar a los visitantes una experiencia inicial sólida al presentar de manera clara y concisa las características y beneficios del sitio, junto con una navegación intuitiva y acceso rápido a la información relevante. Al completar las tareas asociadas a las historias de usuario definidas, sentaremos las bases para futuras iteraciones, asegurando que la página de inicio cumpla con las expectativas de los usuarios y contribuya al éxito del proyecto.

URL del Board en Trello: https://trello.com/invite/b/9fFNzPVl/ATTId6d62a99d06e758b547d220c4b08a09131B77500/appweb
![Board Trello](/assets/boardTrello.png)

<table>
        <tr>
            <td colspan="2">Sprint #</td>
            <td colspan="6">Sprint 1</td>
        </tr>
        <tr>
            <td colspan="2">User Story</td>
            <td colspan="6">Work-Item / Task</td>
        </tr>
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Descripcion</td>
            <td>Estimation (Hours)</td>
            <td>Assigned To</td>
            <td>Status (To-do / In / Process / ToReview / Done)</td>
        </tr>
        <tr>
            <td>US01</td>
            <td>Integración de Redes Sociales y Contenido Útil en el Footer</td>
            <td>T01</td>
            <td>Diseño del Footer</td>
            <td>Crear el diseño inicial del footer para integrar redes sociales y enlaces a contenido útil.</td>
            <td>40 minutos</td>
            <td>Mauricio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US02</td>
            <td>Navegación eficiente a través de enlaces internos con anclas</td>
            <td>T02</td>
            <td> Implementación de Enlaces Internos con Anclas</td>
            <td>Implementar enlaces internos con anclas para una navegación más eficiente a través de secciones específicas de la página web.</td>
            <td>1 hora</td>
            <td>Moises</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US03</td>
            <td>Informacion de los planes que ofrecemos</td>
            <td>T03</td>
            <td>Creación de Sección de Planes de Suscripción</td>
            <td>Crear una sección para mostrar información detallada sobre los planes de suscripción ofrecidos, facilitando la comparación y elección por parte de los usuarios.</td>
            <td>1 hora</td>
            <td>Flavio</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US04</td>
            <td>Implementación de Sección de Contacto</td>
            <td>T04</td>
            <td>Integración de Sección de Contacto</td>
            <td>Integrar una sección "Contáctanos" con formulario para correo electrónico y número de teléfono, facilitando la comunicación rápida y sencilla con los usuarios.</td>
            <td>1 hora</td>
            <td>Piero</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>US05</td>
            <td>Agregar la Sección "Sobre Nosotros"</td>
            <td>T05</td>
            <td>Agregacion de Sección "Sobre Nosotros"</td>
            <td>Agregar en el sitio web una sección "Sobre Nosotros" que proporcione información sobre nuestro objetivo, mejorando la comprensión de los usuarios sobre quiénes somos y qué hacemos.</td>
            <td>50 minutos</td>
            <td>Mauricio</td>
            <td>Done</td>
        </tr>
    </table>


### 5.2.1.3 Development Evidence for Sprint Review.

| Repository                        | Branch              | Commit Id                          | Commit Message                   | Commit Message Body           |Commited on (Date) |
|-----------------------------------|---------------------|------------------------------------|----------------------------------|-------------------------------|-------------------|
| REPOSITORIO DEL LANDING(NOMBRE)   | feature/loremipsum  | 14ca4e3                            | feat: ...                        | MENSAJE DEL COMMIT            | FECHA DEL COMMIT  |


### 5.2.1.4 Testing Suite Evidence for Sprint Review. 

| Repository                        | Branch              | Commit Id                          | Commit Message                   | Commit Message Body           |Commited on (Date) |
|-----------------------------------|---------------------|------------------------------------|----------------------------------|-------------------------------|-------------------|
| REPOSITORIO DEL LANDING(NOMBRE)   | feature/loremipsum  | 14ca4e3                            | feat: ...                        | MENSAJE DEL COMMIT            | FECHA DEL COMMIT  |

### 5.2.1.5 Execution Evidence for Sprint Review. 

Durante el Sprint 1, se logró un progreso significativo en la implementación de las características clave de la página de inicio del sitio web. El equipo completó con éxito todas las historias de usuario asignadas para este sprint, que incluyeron el desarrollo de un resumen claro de las características y beneficios del sitio web, la integración de acceso visible a información detallada de precios, la adición de un resumen conciso al final de la página de inicio, la inclusión de un llamado a la acción prominente para dirigir a los visitantes a la aplicación web principal, la presentación de contenido informativo claro y detallado, y la integración de información de contacto visible en la página de inicio. El equipo trabajó de manera colaborativa para garantizar que las características implementadas cumplan con los requisitos y contribuyan a una experiencia de usuario positiva.
Capturas de pantalla:

- Sección de Resumen:

![Resumen](/assets/resumen.png)

- Acceso a la Información de Precios:

![Precios](/assets/precios.png)

- Resumen al Final:

![Footer](/assets/footer.png)

- Contenido Informativo:

![Board Trello](/assets/servicios.png)

- Llamado a la acción

![Board Trello](/assets/calltoAction.png)

- Sección de Información de Contacto:

![Contacto](/assets/contacto.png)

Video: 

### 5.2.1.6 Services Documentation Evidence for Sprint Review. 

Durante este Sprint 1, nos enfocamos en desarrollar el landing page, sin implementación de cualquier servicio. Por lo tanto, este punto quedará sin actividad en este aspecto.

### 5.2.1.7 Software Deployment Evidence for Sprint Review.

Durante el Sprint 1, llevamos a cabo el despliegue de nuestra landing page en GitHub Pages. A continuación, detallamos los pasos realizados:

1. Primero creamos un repositorio en Github para el landing page

![Ramas](/assets/branches.png)

2. Las ramas necesarias se crean siguiendo el flujo de trabajo de GitFlow.

![Ramas](/assets/branches.png) 

3. En la configuración del repositorio, se accede a la sección "Pages".

![Ramas](/assets/branches.png)

4. Se ajusta la configuración para indicar la fuente de la landing page.

![Ramas](/assets/branches.png)

5. Después de guardar la configuración, se genera un enlace para acceder a la landing page.

![Ramas](/assets/branches.png)

6. Este enlace permite visualizar las actualizaciones realizadas en la rama "develop".

![Ramas](/assets/branches.png)

### 5.2.1.8 Team Collaboration Insights during Sprint.

Durante este primer Sprint, hemos completado el desarrollo del landing page y hemos colaborado estrechamente en su implementación. La colaboración entre los miembros del equipo se refleja en los diversos commits realizados en el repositorio de GitHub, los cuales han sido debidamente documentados en las capturas de pantalla adjuntas.
Para asegurar una colaboración efectiva, hemos implementado GitFlow como nuestra metodología de trabajo colaborativo en Git. Con GitFlow, hemos creado ramas para cada una de las secciones de nuestra landing page. Esto nos ha permitido trabajar de manera organizada y centrarnos en completar correctamente las historias de usuario designadas para cada sección.
En cuanto a la elaboración del código, hemos asignado a cada miembro del equipo una sección específica del landing page. Esta estrategia nos ha permitido avanzar de manera más eficiente y completar el trabajo antes de la fecha de entrega.
Además, hemos realizado reuniones adicionales para intercambiar ideas y resolver cualquier duda o problema que pudiera surgir durante el desarrollo del landing page. Estas sesiones han contribuido de manera positiva al éxito del proyecto.
A continuación, presentamos algunas capturas de pantalla que muestran los commits realizados por los miembros del equipo en GitHub:
![Ramas](/assets/branches.png)

![Mauricio](/assets/miguel.png)

![Piero](/assets/mauricio.png)

![Flavio](/assets/piero.png)

![Moises](/assets/elias.png)
