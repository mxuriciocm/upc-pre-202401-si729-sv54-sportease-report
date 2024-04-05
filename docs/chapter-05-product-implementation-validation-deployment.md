# Capítulo 5: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management.

Para la gestión de la configuración de software de nuestra aplicación nos enfocaremos en la Gestión de Código Fuente, donde controlaremos las versiones y estableceremos una estructura organizada para el código; la Configuración del Entorno de Desarrollo, aquí nos aseguramos que todos los miembros del equipo tengan herramientas consistentes y la Configuración de Despliegue, que aborda el despliegue en entornos de producción. Esta toma de decisiones garantiza la coherencia y eficiencia a lo largo del ciclo de vida de la aplicación, lo que es necesario para cumplir con nuestra misión de ofrecer a estudiantes, instructores y administradores optimizar sus actividades académicas deportivas.

### 5.1.1 Software Development Environment Configuration

En esta sección especificaremos, describiremos e indicaremos los nombres de productos, el propósito de uso en el proyecto, la ruta de referencia o ruta de descarga de cada uno de los productos de software que se utilizaron para colaborar en el ciclo de vida de nuestro producto digital.


* **Project Management**

Para las reuniones de equipo utilizamos aplicaciones como Google Meet y Discord. Ademas, para el control de versiones creamos un repositorio colaborativo en GitHub, para mantener y realizar cambios a nuestro proyecto de manera eficiente mediante commits.


* **Product UX/UI Design**

En los escenarios As-Is y To-Be, segmetno objetivo y impact mapping se utilizo la herramienta Miro. Con respecto a los wireframes, mock-ups y prototipo de la app web, usamos Figma.


* **Software Development**

Para el landing page se usaron las siguientes herramientas:

Visual Studio Code: Editor de código redefinido y optimizado para crear y depurar aplicaciones web y en la nube modernas.

HTML: Lenguaje para la creacion de la landing page

CSS: Lenguaje para los estilos y presentar los contenidos de una página de forma atractiva

JavaScript: Lenguaje de programación que los desarrolladores utilizan para hacer páginas web interactivas.

Git: Sistema de control de versiones distribuido y permite al equipo colaborar en el proyecto.


* **Software Testing**

Como usamos el editor de codigo Visual Studio Code podremos hacer uso de la extension Live Server. Con esta extensión, tenemos la capacidad de configurar un servidor local, lo que nos facilita la visualización inmediata de las modificaciones que realizamos en un navegador web como Microsoft Edge o Chrome. Tambien, para las pruebas de aceptacion, usaremos Gherkin para luego subirlos al repositorio.


* **Software Deployment**

Usaremos Github Pages para subir nuestro landing page, ya que es una pagina estatica no requiere muchos cambios y esto es bueno porque Github Pages nos deja actualizar el contenido gratis.


* **Software Document**

En la documentacion del software, haremos uso del HTML para la creacion de nuestro landig page.


### 5.1.2 Source Code Management.

En esta sección explicaremos de qué forma se implementará GitFlow. Como Workflow de control de versiones, es decir qué branches (ramas) creacion además de main branch (rama principal), por ejemplo, develop branch. Para GitFlow cada Feature requiere su propio branch, por ello se especificara qué convenciones se aplica para nombrar los feature branches.

| *Main: *Esta rama contendrá la versión estable del proyecto, lista para su despliegue.  |
|-----------------------------------------------------------------------------------------|

Develop: Aquí se agrupan todos los elementos en desarrollo. Una vez que el desarrollo está completo y se considera listo para avanzar al siguiente paso, se fusionará con la rama de lanzamiento (release).

Feature: Cada miembro del equipo trabajará en su propia rama individual, donde cargarán las secciones de código asignadas para una funcionalidad específica. Estas ramas de características se integrarán con la rama "develop".


Respecto a la convención para nombrar las ramas de características, se utilizará el formato siguiente:

| feature_<nombre -integrante>/<breve-descripción>    |
|-----------------------------------------------------|

Para nombrar las versiones de lanzamiento, se seguirá el versionado semántico 2.0.0, que consiste en la estructura 

| Mayor.Menor.Parche. |
|---------------------|

El último dígito (Parche) se refiere principalmente a corrección de errores compatibles con versiones anteriores..
El segundo dígito (Menor) aumenta cuando se añaden características compatibles con la versión anterior.
El primer dígito (Mayor) se incrementa para cambios significativos que podrían no ser compatibles con la versión anterior.

Por último, se adoptará el uso de Conventional Commits para los mensajes de texto en cada commit. La estructura de estos mensajes será <type>: <description> .


### 5.1.3 Source Code Style Guide & Conventions.

Se tiene la intención de seguir las directrices y normativas de codificación establecidas en una variedad de fuentes, tales como el HTML Style Guide and Coding Conventions, la Guía de Estilo de Codificación de Angular, la Guía de Estilo de Codificación para Java, las Convenciones Gherkin para Especificaciones Legibles, la Guía de Estilo de TypeScript, la Guía de Estilo de Codificación de Angular y las características específicas de Spring Boot.

### 5.1.4 Software Deployment Configuration.

## 5.2 Landing Page, Services & Applications Implementation.

### 5.2.1 Sprint 1
### 5.2.1.1 Sprint Planning 1

El objetivo principal de esta reunión es establecer un plan claro y realista para el sprint, identificando las tareas a realizar y comprometiéndose con un conjunto de entregables concretos que contribuyan al avance del proyecto. A continuación, se presenta el resumen del Sprint Planning Meeting, que proporcionará una visión general de los temas discutidos y las decisiones tomadas durante la reunión.

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
| Sum of Story Points                  | (Colocar la suma de los Story Points para los User Stories que se están incluyendo en este Sprint 1.) |


### 5.2.1.2 Sprint Backlog 1

IMAGEN EN DOCUMENTO DE LA TABLA

### 5.2.1.3 Development Evidence for Sprint Review.

| Repository                        | Branch              | Commit Id                          | Commit Message                   | Commit Message Body           |Commited on (Date) |
|-----------------------------------|---------------------|------------------------------------|----------------------------------|-------------------------------|-------------------|
| REPOSITORIO DEL LANDING(NOMBRE)   | feature/loremipsum  | 14ca4e3                            | feat: ...                        | MENSAJE DEL COMMIT            | FECHA DEL COMMIT  |

### 5.2.1.4 Testing Suite Evidence for Sprint Review. 

### 5.2.1.5 Execution Evidence for Sprint Review. 

### 5.2.1.6 Services Documentation Evidence for Sprint Review. 

### 5.2.1.7 Software Deployment Evidence for Sprint Review.

### 5.2.1.8 Team Collaboration Insights during Sprint.
