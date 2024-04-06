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

**CONNVECIONES QUE USAREMOS**

HTML
- Usar nombres descriptivos para el archivo HTML
- Seguir una convención de nomenclatura consistente, como camelCase, para nombres de archivos y carpetas.
- Utiliza los elementos HTML de manera semántica para describir correctamente el contenido de tu sitio web. Esto incluye el uso apropiado de etiquetas.
- Mantener una estructura de código clara y legible mediante la indentación adecuada.
- Utilizar un estilo de formato consistente en todo el código para mejorar la mantenibilidad.

CSS
- Utiliza nombres de clases descriptivos y significativos para aplicar estilos a tus elementos HTML
- Prefiere nombres que reflejen la función o el propósito del elemento en lugar de su apariencia.
- Evita el uso de IDs para estilos, ya que pueden causar especificidad excesiva y dificultar la reutilización de estilos.

JavaScript:
- Para la nomenclatura se usara el camelCase para nombres de variables y funciones en JavaScript.
- Utiliza espacios o tabulaciones de manera consistente y asegúrate de mantener una línea de código por línea para mejorar la legibilidad.

TypeScript:
- Aprovecha las generics de TypeScript para crear funciones y clases que sean flexibles y reutilizables con diferentes tipos de datos.
- Usar el camelCase para nombres de variables y tipos, y el PascalCase para nombres de tipos de datos y clases.

Gherkin:
- Utiliza las palabras clave de Gherkin como Given, When, Then para estructurar tus escenarios de manera coherente y expresiva.

### 5.1.4 Software Deployment Configuration.

En esta sección especificaremos la configuración del despliegue de la solución, incluyendo los pasos necesarios para que, a partir de los repositorios de código fuente, se pueda lograr el despliegue de el Landing Page.

Empezaremos por crear un repositorio en GitHub para almacenar los archivos HTML, CSS y JavaScript. Luego cada integrante del equipo trabajará en su propia rama "feature" para desarrollar nuestro landing page. Una vez completada una característica, se procederá a hacer el merge con la rama "develop" para que la landing page se encuentre actualizada. estableceremos la configuración en GitHub Pages para publicar la página de destino utilizando la rama "develop". A continuación, detallamos los pasos para llevar a cabo este despliegue en GitHub Pages:


1. Comenzaremos creando un repositorio público en GitHub y poniendole un nombre.
2. Configurar las ramas necesarias conforme al flujo de trabajo Gitflow estándar, que comprende main, release, develop, features y hotfix.
3. Dirigirse a la sección de ajustes y elegir la pestaña Pages.
4. Nos dirigimos al apartado de configuración para GitHub Pages.
5. En el apartado de branch, seleccionamos el branch "develop" donde se realizará el despliegue del landing page, dejando las demás configuraciones con sus valores predeterminados.
6. Al seleccionar la rama correspondiente, se generará un enlace que permitirá acceder al landing page. Cada modificación efectuada en el "develop" se actualiza automáticamente.
7. Cada miembro del equipo trabajará en sus propias ramas.
8. Se realizarán merges entre la develop y los feature para integrar los avances.
9. Se observarán los cambios reflejados en el enlace provisto por GitHub Pages.
10. Finalmente, el landing estará desplegada, lista para ser visualizada y utilizada.

## 5.2 Landing Page, Services & Applications Implementation.

A continuacion explicaremos el enfoque que seguiremos para llevar a cabo la implementación, pruebas y lanzamiento de nuestro landing page, así como también de los servicios web y la interfaz de usuario de la aplicación web en cada ciclo de desarrollo. Con respecto al Sprint 1, nos centraremos únicamente en describir el proceso de implementación del landing page.

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

En este punto explicaremos los logros alcanzados para el Sprint 1

-Creacion de repositorios para el report y el landing page en GitHub.
-Realizacion del wireframe y mock-ups del landing page.
-Realizacion del wireframe y mock-ups de la aplicacion web.
-Implementación del landing page.
-Diseño del prototipo de la aplicación web.
-Subir en el GitHub Pages el landing pages.

### 5.2.1.6 Services Documentation Evidence for Sprint Review. 

En este Sprint 1, realizamos el landing page donde no se hizo implementacion de algun servicio, por ese motivo es el que quedara vacio este punto.

### 5.2.1.7 Software Deployment Evidence for Sprint Review.

Explicaremos las acciones que realizamos en el sprint 1, como la preparacion y despliegue de nuestro landing page

* Primero creamos un repositorio en Github para el landing page
* Las ramas necesarias se crean siguiendo el flujo de trabajo de GitFlow.
* En la configuración del repositorio, se accede a la sección "Pages".
* Se ajusta la configuración para indicar la fuente de la landing page.
* Después de guardar la configuración, se genera un enlace para acceder a la landing page.
* Este enlace permite visualizar las actualizaciones realizadas en la rama "develop".

### 5.2.1.8 Team Collaboration Insights during Sprint.

Para este Sprint 1, hemos hecho el desarrollo del landing page, colaborado en conjunto en la implementación. Esta colaboración se refleja en los distintos commits realizados en el repositorio, los cuales están documentados en las capturas de pantalla adjuntas.

Con respecto a la colaboracion del equipo, nos reunimos presencial como virtualmente para asignarnos tarea y discutir como elaborar el proyecto. Esto nos ha permitido comprender claramente nuestras responsabilidades individuales y tener un mejor desempeño. Para el desarrollo del código, hemos decidido que cada integrante se encarga de una sección específica del landing page. Esto para avanzar mas rapido y terminarlo antes de la entrega. Finalmente, tuvimos reuniones donde compartimos ideas y resolvemos algunas dudas o problemas que podriamos tener con respecto a la elaboracion del landing page, lo que nos dio resultados positivos en la elaboracion del trabajo.
