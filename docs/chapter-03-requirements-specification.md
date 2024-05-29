# Capítulo 3: Requirements Specification

## 3.1 To-Be Scenario Mapping

Un "To-Be Scenario Mapping" es una técnica utilizada en el diseño de experiencia de usuario (UX) y el análisis de procesos para visualizar y diseñar cómo debería ser un proceso o experiencia en el futuro deseado. El término "to-be" significa "será", lo que indica que este tipo de mapeo se enfoca en representar cómo debería funcionar un proceso o experiencia una vez que se hayan realizado mejoras o cambios.

El To-Be Scenario Mapping implica la creación de un mapa visual que representa las etapas y acciones deseadas en un proceso o experiencia. Este mapa describe cómo deberían ser las interacciones, pasos, decisiones y puntos de contacto en el proceso futuro.

###### Figura 16. 
*To-be Scenario Mapping del primer User Persona.*

![To-be dueño](/assets/To-Be_Dueño.png)

###### Figura 17. 
*To-be Scenario Mapping del segundo User Persona.*

![To-be deportista](/assets/To-Be_Deportista.png)

## 3.2 User Stories

En esta sección, presentaremos un análisis detallado de cada una de las historias de usuario asignadas a lo largo de todo el ciclo de vida del proyecto. El objetivo primordial es asegurar la completa satisfacción de nuestros segmentos de mercado mediante la comprensión y la satisfacción de sus necesidades y expectativas. Para ello, vamos a especificar los requisitos definidos, así como el conjunto de User Stories y Epics que hemos identificado como fundamentales para el éxito del proyecto. Es importante destacar que cada User Story estará acompañada de sus criterios de aceptación, lo que garantizará una comprensión clara de lo que se espera lograr.

Para comenzar este proceso de presentación, vamos a comenzar con una comprensión clara de lo que representan los Epics en nuestro contexto. Los Epics actúan como contenedores de alto nivel que encapsulan conjuntos de funcionalidades o características más amplias del producto. Son los pilares sobre los cuales se construirá la experiencia del usuario y se alcanzarán los objetivos del proyecto según sus métricas ya establecidas de forma ordenada y controlada (Patton et al., 2014). 

Por lo tanto, presentaremos primero nuestro modelo de Epics, que servirá como guía y marco de referencia para comprender la naturaleza y el alcance de las historias de usuario que se presentarán a continuación. Este enfoque asegurará que se tenga una visión clara y completa de los diferentes tipos de historias de usuario, así como de sus divisiones y definiciones correspondientes, facilitando así una mejor comprensión y evaluación del proyecto en su conjunto.

###### Tabla 5.
*Tabla de épicas establecidas para las historias de usuarios.*

<table>
    <tr>
        <th>Epic ID</th>
        <th>Título</th>
        <th>Descripción</th>
    </tr>
    <tr>
        <td>EP01</td>
        <td>Administración de Horarios y Clases</td>
        <td>Como administrador de una academia deportiva, quiero tener herramientas para gestionar eficientemente los horarios de clases, pagos, asistencias, y eventos de mis estudiantes.</td>
    </tr>
    <tr>
        <td>EP02</td>
        <td>Gestión Financiera y de Recursos</td>
        <td>Como administrador, quiero poder gestionar todo el tema financiero de la academia, incluyendo ingresos, gastos, facturas, pagos a proveedores, control de presupuesto y generación de informes financieros.</td>
    </tr>
    <tr>
        <td>EP03</td>
        <td>Seguimiento del Desempeño de los Estudiantes</td>
        <td>Como instructor, quiero poder registrar y realizar un seguimiento del progreso de mis estudiantes, incluyendo rendimiento y logros.</td>
    </tr>
    <tr>
        <td>EP04</td>
        <td>Gestión de Usuarios y Roles en las Academias</td>
        <td>Como administrador, quiero poder gestionar los usuarios y asignar roles según sus funciones dentro de la academia deportiva a través de la plataforma, para garantizar un acceso adecuado a las funcionalidades y datos de la plataforma.</td>
    </tr>
    <tr>
        <td>EP05</td>
        <td>Seguridad y Privacidad de Datos de los Usuarios</td>
        <td>Como usuario, quiero que mis datos personales estén seguros y protegidos en la plataforma, y poder gestionar mi información personal de manera confiable, asegurándome de que se cumplan los estándares de seguridad y privacidad.</td>
    </tr>
	<tr>
        <td>EP06</td>
        <td>Technicals stories</td>
        <td>Como equipo de desarrollo, queremos implementar y manejar la plataforma mediante una API REST para controlar eficazmente los datos y el flujo de información en toda la solución, garantizando así un desarrollo y mantenimiento eficientes de la plataforma.</td>
    </tr>
	<tr>
        <td>EP07</td>
        <td>Diseño y Estructura de la Landing Page</td>
        <td>Como visitante, quiero encontrar una landing page diseñada y estructurada de manera atractiva y funcional, que me proporcione información detallada y precisa sobre lo que ofrece el sitio web, para tomar decisiones informadas sobre el uso de la plataforma.</td>
    </tr>
	<tr>
        <td>EP08</td>
        <td>Optimización de la Experiencia del Usuario</td>
        <td>Como visitante, quiero una experiencia de usuario optimizada en la landing page, que me brinde una navegación fluida y detallada, permitiéndome tomar decisiones conscientes sobre el uso de la plataforma.</td>
    </tr>
</table>

En esta próxima sección, presentaremos de forma detallada todas las historias de usuario establecidas en el proyecto de SportEase. Estas historias están meticulosamente diseñadas con el objetivo de alcanzar el máximo nivel de satisfacción por parte de nuestros clientes, al mismo tiempo que nos permiten cumplir con todos los objetivos delineados en el proceso de planificación. Es crucial destacar que cada historia de usuario se categorizará según la sección correspondiente de la arquitectura de software en la que se requieran.

Según Patton et al. (2014), una historia de usuario es una técnica utilizada en el desarrollo de software para describir una funcionalidad o característica desde la perspectiva del usuario final. En cada historia, se captura quién es el usuario, qué necesita hacer y por qué lo necesita. Esta descripción concisa y centrada en el usuario proporciona una guía clara para el equipo de desarrollo al diseñar y construir el producto, manteniendo siempre en mente las necesidades y expectativas del usuario final.

###### Tabla 6.
*Tabla de las historias de usuarios establecidas para la Landing Page de SportEase.*

<table>
    <tr>
        <th>Epic Id</th>
        <th>Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de aceptación</th>
    </tr>
    <!-- EPIC 7 -->
    <tr>
        <td rowspan="6">EP07</td>
        <td rowspan="2">US01</td>
        <td rowspan="2">Presentación de la Página de Inicio</td>
        <td rowspan="2">Como visitante, quiero encontrar una página de inicio diseñada de manera atractiva y funcional que me proporcione un resumen claro y conciso de las características principales y los beneficios para tener una idea rápida sobre lo que ofrece la plataforma.</td>
        <td>Visualización del Resumen en el Landing Page: Dado que el visitante accede al landing page del sitio web. Cuando el visitante visualiza la sección de resumen rápido. Entonces se presenta un resumen claro y conciso de las principales características y beneficios del sitio web, destacando los puntos más relevantes de manera atractiva y fácil de entender.</td>
    </tr>
    <tr>
        <td>Información Asertiva y Relevante: Dado que el visitante está leyendo el resumen en el landing page. Cuando el visitante revisa la información presentada. Entonces la información proporcionada se centra en los aspectos más importantes y distintivos del sitio web, ofreciendo una visión rápida y clara de lo que ofrece y cómo puede beneficiar al usuario.</td>
    </tr>
    <tr>
        <td rowspan="2">US02</td>
        <td rowspan="2">Resumen de precios</td>
        <td rowspan="2">Como visitante del segmento administrador quiero una vista detallada del plan ofrecido por el sitio web para tomar una desicion de compra a conciencia.</td>
        <td>Acceso a la Información del Plan: Dado que el visitante del segmento administrador está en el sitio web. Cuando el visitante busca información detallada sobre el plan ofrecido. Entonces se proporciona un acceso claro y visible a la página o sección que describe en detalle el plan ofrecido, ya sea a través del menú de navegación, enlaces destacados o botones de llamada a la acción.</td>
    </tr>
    <tr>
        <td>Descripción Completa y Clara del Plan: Dado que el visitante está en la página de información del plan. Cuando el visitante lee la descripción del plan. Entonces se presenta una descripción completa y clara del plan ofrecido, incluyendo características, beneficios, limitaciones, términos y condiciones, precio y cualquier otra información relevante que permita al visitante entender completamente lo que está incluido en el plan.</td>
    </tr>
    <tr>
        <td rowspan="2">US03</td>
        <td rowspan="2">Navegación Rápida y Fluida</td>
        <td rowspan="2">Como visitante, quiero una experiencia de usuario optimizada en la landing page, la cual me brinde una navegación fluida y detallada, lo que me permitirá tomar decisiones conscientes sobre el uso de la plataforma.</td>
        <td>Navegación Intuitiva y Fluida: Dado que el visitante navega por la landing page. Cuando el visitante interactúa con la página y busca acceder a diferentes secciones. Entonces la navegación es intuitiva y fluida, permitiendo al visitante acceder fácilmente a las diferentes secciones de la página y encontrar la información que busca sin dificultad.</td>
    </tr>
    <tr>
        <td>Experiencia de Usuario Optimizada: Dado que el visitante carga la landing page en su navegador. Cuando el visitante interactúa con los elementos de la página, como botones, menús y enlaces. Entonces la página responde de manera rápida y eficiente a las acciones del usuario, proporcionando una experiencia fluida y sin retrasos.</td>
    </tr>
    <!-- EPIC 07 -->
    <tr>
		<td rowspan="6">EP07</td>
        <td rowspan="2">US04</td>
        <td rowspan="2">Acceso Rápido a las Secciones Clave</td>
        <td rowspan="2">Como visitante, quiero encontrar un menú de navegación en el header de la landing page que me permita acceder rápidamente a las secciones clave de SportEase, como información sobre la plataforma, suscripciones, funcionalidades y contacto.</td>
        <td>Visibilidad del Menú de Navegación: Dado que el visitante carga la landing page en su navegador. Cuando el visitante visualiza la página. Entonces el menú de navegación está claramente visible en el header de la página, ubicado en una posición destacada y fácilmente identificable.</td>
    </tr>
    <tr>
        <td>Acceso Rápido a Secciones Clave: Dado que el visitante está en la landing page. Cuando el visitante hace clic en una opción del menú de navegación. Entonces el visitante es redirigido de manera rápida y directa a la sección correspondiente del sitio web, como información sobre la plataforma, suscripciones, funcionalidades o contacto, sin demoras ni tiempos de carga prolongados.</td>
    </tr>
    <tr>
        <td rowspan="2">US05</td>
        <td rowspan="2"> Descripción Detallada de Funcionalidades</td>
        <td rowspan="2">Como visitante, quiero encontrar una sección en la landing page que describa detalladamente las funcionalidades de SportEase para comprender cómo puedo beneficiarme con el uso de la plataforma.</td>
        <td>Contenido Detallado y Comprensible: Dado que el visitante carga la landing page en su navegador. Cuando el visitante accede a la sección de descripción de funcionalidades. Entonces se presenta contenido detallado que describe cada funcionalidad de SportEase de manera clara y comprensible, explicando su propósito, beneficios y cómo puede beneficiar al usuario.</td>
    </tr>
    <tr>
        <td>Organización y Estructura: Dado que el visitante está en la sección de descripción de funcionalidades. Cuando el visitante revisa el contenido. Entonces las funcionalidades se presentan de manera organizada y estructurada, facilitando la lectura y comprensión del visitante. Se utiliza un formato coherente y sección clara para cada funcionalidad.</td>
    </tr>
    <tr>
        <td rowspan="2">US06</td>
        <td rowspan="2">Formulario de Contacto</td>
        <td rowspan="2">Como visitante, quiero encontrar un formulario de contacto en la landing page para poder comunicarme fácilmente con el equipo de SportEase y obtener más información sobre la plataforma.</td>
        <td>Visibilidad del Formulario: Dado que el visitante carga la landing page en su navegador. Cuando el visitante accede a la sección donde se espera encontrar el formulario de contacto. Entonces el formulario de contacto está claramente visible en la landing page, ubicado en un lugar prominente y fácilmente identificable, como en el footer o una sección dedicada específicamente al contacto.</td>
    </tr>
    <tr>
        <td>Facilidad de Uso: Dado que el visitante está en la sección donde se encuentra el formulario de contacto. Cuando el visitante interactúa con el formulario. Entonces el formulario de contacto es fácil de usar, con campos claros y etiquetas descriptivas. Se proporcionan instrucciones claras sobre cómo completar el formulario y qué información se espera del visitante.</td>
    </tr>
    <!-- EPIC 8 -->
    <tr>
        <td rowspan="6">EP08</td>
        <td rowspan="2">US07</td>
        <td rowspan="2">Diseño Responsivo para Dispositivos Móviles</td>
        <td rowspan="2">Como visitante que accede desde un dispositivo móvil, quiero que la landing page de SportEase tenga un diseño responsivo que se adapte adecuadamente a mi pantalla, garantizando una experiencia de usuario óptima y fácil navegación.</td>
        <td>Adaptabilidad de la Interfaz: Dado que el visitante carga la landing page de SportEase desde un dispositivo móvil con diferentes tamaños de pantalla. Cuando el visitante accede a la página. Entonces la página se adapta automáticamente al tamaño de la pantalla del dispositivo móvil, asegurando que todos los elementos de la página se muestren correctamente y de manera legible sin necesidad de hacer zoom o desplazamiento horizontal.</td>
    </tr>
    <tr>
        <td>Legibilidad del Contenido: Dado que el visitante visualiza el contenido de la landing page desde un dispositivo móvil. Cuando el visitante lee el texto y los elementos de la página. Entonces el texto y otros elementos de la página son legibles y están correctamente formateados para dispositivos móviles, con tamaños de fuente adecuados, espaciado apropiado y disposición coherente.</td>
    </tr>
    <tr>
        <td rowspan="2">US08</td>
        <td rowspan="2">Call to Action Claro y Efectivo</td>
        <td rowspan="2">Como visitante de la landing page de SportEase, espero encontrar llamadas a la acción (CTA) claras y efectivas que me guíen hacia los pasos que debo seguir para interactuar con el sitio de manera óptima y lograr mis objetivos, como registrarme, suscribirme o explorar más información.</td>
        <td>Visibilidad Clara: Dado que el visitante carga la landing page de SportEase en su navegador. Cuando el visitante visualiza la página sin desplazarse. Entonces las llamadas a la acción están ubicadas en áreas prominentes de la página, como el encabezado, el cuerpo o el pie de página, y son fácilmente identificables sin la necesidad de desplazamiento.</td>
    </tr>
    <tr>
        <td>Llamadas a la Acción Atractivas: Dado que el visitante navega por la landing page de SportEase. Cuando el visitante visualiza las llamadas a la acción. Entonces las CTA están diseñadas de manera atractiva y destacan visualmente en la página, utilizando colores contrastantes, botones llamativos o elementos gráficos que invitan a la interacción.</td>
    </tr>
    <tr>
        <td rowspan="2">US09</td>
        <td rowspan="2">Mejora de la Interactividad</td>
        <td rowspan="2">Como visitante, quiero encontrar elementos interactivos en la landing page de SportEase, como animaciones sutiles, transiciones suaves y efectos visuales atractivos, que mejoren la experiencia de usuario y hagan que la navegación sea más agradable y entretenida.</td>
        <td>Transiciones Suaves y Naturales - Dado que el visitante navega por la página y realiza acciones como desplazarse o hacer clic en enlaces. Cuando se producen transiciones entre diferentes secciones o elementos de la página. Entonces las transiciones son suaves, naturales y fluidas, proporcionando una experiencia de navegación sin interrupciones ni saltos bruscos.</td>
    </tr>
    <tr>
        <td>Efectos Visuales Atractivos y Relevantes - Dado que el visitante observa efectos visuales en la página. Cuando el visitante interactúa con elementos que incluyen efectos visuales. Entonces los efectos visuales son atractivos, relevantes y añaden valor a la experiencia de usuario, contribuyendo a la comprensión del contenido o resaltando la importancia de ciertos elementos de la página.</td>
    </tr>
</table>

###### Tabla 7.
*Tabla de las historias de técnicas establecidas para todo el proyecto de SportEase.*

<table>
    <tr>
        <th>Epic Id</th>
        <th>Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de aceptación</th>
    </tr>
    <!-- EPIC 6 -->
    <tr>
        <td rowspan="5">EP06</td>
        <td rowspan="2">US10</td>
        <td rowspan="2">Configuración de la API REST</td>
        <td rowspan="2">Como miembro del equipo de desarrollo, quiero configurar correctamente la API REST para la plataforma SportEase, estableciendo rutas, métodos y parámetros necesarios para el intercambio de datos entre el cliente y el servidor.</td>
        <td>Configuración de Rutas - Dado que el equipo de desarrollo ha configurado la API REST para SportEase. Cuando se accede al endpoint principal de la API (/api/sportease).Entonces se muestran las rutas disponibles correctamente configuradas para los diferentes recursos y funcionalidades de la plataforma.</td>
    </tr>
    <tr>
        <td>Definición de Métodos HTTP - Dado que se han establecido los métodos HTTP adecuados para cada operación en la API. Cuando se realizan solicitudes utilizando los métodos HTTP especificados (GET, POST, PUT, DELETE). Entonces el servidor procesa las solicitudes según el método especificado y devuelve las respuestas correspondientes.</td>
    </tr>
    <tr>
        <td rowspan="2">US11</td>
        <td rowspan="2">Implementación de Funcionalidades Básicas</td>
        <td rowspan="2">Como miembro del equipo de desarrollo, quiero implementar las funcionalidades básicas de la API REST, como la creación, lectura, actualización y eliminación de recursos, para garantizar el acceso y la manipulación de datos de manera eficiente.</td>
        <td>Creación de Recursos - Dado que la API REST de SportEase ha sido implementada. Cuando se envían solicitudes POST a los endpoints correspondientes para crear nuevos recursos. Entonces se crean los recursos en la base de datos y se devuelve una respuesta con el código de estado 201 (Created) junto con los datos del nuevo recurso creado.</td>
    </tr>
    <tr>
        <td>Lectura de Recursos - Dado que la API REST de SportEase está en funcionamiento. Cuando se realizan solicitudes GET a los endpoints para obtener información sobre los recursos. Entonces se devuelven respuestas con el código de estado 200 (OK) junto con los datos solicitados en el formato especificado (por ejemplo, JSON).</td>
    </tr>
    <tr>
        <td rowspan="2">US12</td>
        <td rowspan="2">Gestión de Autenticación y Autorización</td>
        <td rowspan="2">Como miembro del equipo de desarrollo, quiero integrar un sistema de autenticación y autorización en la API REST, para garantizar la seguridad y la privacidad de los datos de los usuarios de SportEase.</td>
        <td>Registro de Usuarios - Dado que un usuario desea registrarse en SportEase. Cuando se envía una solicitud POST al endpoint de registro con los datos de usuario requeridos, como nombre de usuario, correo electrónico y contraseña. Entonces se crea una nueva cuenta de usuario en la base de datos y se devuelve una respuesta con el código de estado 201 (Created) junto con un token de acceso JWT (JSON Web Token) válido para la autenticación posterior.</td>
    </tr>
<table>

###### Tabla 8.
*Tabla de las historias de usuario establecidas para la aplicación web de SportEase.*

<table>
    <tr>
        <th>Epic Id</th>
        <th>Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de aceptación</th>
    </tr>
    <!-- EPIC 01 -->
    <tr>
        <td rowspan="6">EP01</td>
        <td rowspan="2">US13</td>
        <td rowspan="2">Registro de Asistencia de Estudiantes</td>
        <td rowspan="2">Como administrador de una academia deportiva, quiero poder marcar la asistencia de los estudiantes a mis clases y registrar las ausencias de manera eficiente.</td>
        <td>Dado que soy un administrador, cuando un estudiante tenga una mensualidad próxima a vencerse, debo recibir una notificación automática en la plataforma.</td>
    </tr>
    <tr>
        <td>Dado que quiero tomar medidas rápidas sobre la mensualidad pendiente, cuando recibo la notificación, debo poder acceder rápidamente a la página de gestión de pagos para comunicarme con el estudiante y recordarle sobre el pago pendiente.</td>
    </tr>
    <tr>
        <td rowspan="2">US14</td>
        <td rowspan="2">Registro de Asistencia y Puntualidad de Profesores</td>
        <td rowspan="2">Como administrador de una academia deportiva, necesito poder llevar un registro de la asistencia y la puntualidad de los profesores para garantizar la calidad y consistencia de las clases.</td>
        <td>Dado que accedo al sistema de gestión, cuando accedo al sistema de gestión, entonces debo poder registrar la asistencia de cada profesor a sus clases programadas.</td>
    </tr>
    <tr>
        <td>Dado que un profesor llega tarde a una clase, cuando un profesor llega tarde a una clase, entonces debo poder registrar su tardanza en el sistema y documentar la duración de la misma.</td>
    </tr>
    <tr>
        <td rowspan="2">US15</td>
        <td rowspan="2">Gestión de Eventos para Estudiantes</td>
        <td rowspan="2">Como administrador de una academia deportiva en SportEase, quiero poder crear y gestionar eventos (torneos) para mis estudiantes,para ofrecerles oportunidades adicionales de participación y enriquecimiento en la comunidad deportiva.</td>
        <td>Dado que soy administrador, cuando acceda al sistema de gestión, entonces debo tener la opción de crear un nuevo evento para los estudiantes.</td>
    </tr>
    <tr>
        <td>Dado que estoy creando un evento, cuando ingreso a la seccion de crear eventos, entonces debo poder ingresar detalles como el nombre del evento, la fecha y hora, la ubicación, una descripción y cualquier requisito o material necesario.</td>
    </tr>
    <!-- EPIC 02 -->
    <tr>
        <td rowspan="6">EP02</td>
        <td rowspan="2">US16</td>
        <td rowspan="2">Gestión de Pagos de Alquiler de Campos Deportivos</td>
        <td rowspan="2">Como administador de la academia deportiva, necesito tener un sistema para gestionar los pagos relacionados con el alquiler de campos deportivos, permitiéndome registrar los pagos adeudados a terceros por el uso de los campos y mantener un registro claro de las transacciones financieras asociadas.</td>
        <td>Dado que soy el propietario de la academia deportiva, cuando ingreso a la seccion de gestion de pagos de alquiler, entonces debo poder ingresar los detalles del contrato de alquiler de cada campo deportivo, incluyendo el monto del alquiler, la frecuencia de pago (por ejemplo, semanal, quincenal o mensual) y la fecha de vencimiento de cada pago.</td>
    </tr>
    <tr>
        <td>Dado que se ha ingresado un contrato de alquiler de campo deportivo, cuando un pago esté próximo a su fecha de vencimiento, entonces debo recibir notificaciones automáticas permitiéndome tomar medidas oportunas para realizar el pago a tiempo.</td>
    </tr>
    <tr>
        <td rowspan="2">US17</td>
        <td rowspan="2">Registro de Pagos y Asistencias a Profesores</td>
        <td rowspan="2">Como administrador de una academia deportiva, necesito poder registrar los pagos y llevar un control de las asistencias de los profesores para garantizar que reciban su compensación de manera oportuna y justa.</td>
        <td>Dado que soy administrador y es el momento de pagar a los profesores, cuando accedo al sistema de gestión, entonces debo poder registrar los pagos correspondientes a cada profesor de acuerdo con su contrato y la política de pagos de la academia.</td>
    </tr>
    <tr>
        <td>Dado que realizo un pago a un profesor, cuando ingreso los detalles del pago, como la fecha, el monto y el método de pago, entonces el sistema debe almacenar correctamente esta información y generar un registro de pago para referencia futura.</td>
    </tr>
    <tr>
        <td rowspan="2">US18</td>
        <td rowspan="2">Gestión de Descuentos por Tardanzas</td>
        <td rowspan="2">Como administrador de una academia deportiva, necesito poder aplicar descuentos por tardanzas a los pagos de los profesores para mantener la disciplina y la puntualidad en las clases.</td>
        <td>Dado que soy administrador y quiero aplicar descuentos por tardanzas, cuando accedo al sistema de gestión, entonces debo poder configurar los parámetros de los descuentos, como el monto a descontar por cada período de tardanza y las reglas para aplicarlos, como el umbral de minutos de tardanza.</td>
    </tr>
    <tr>
        <td>Dado que un profesor llega tarde a una clase, cuando registro su tardanza en el sistema de gestión, entonces el sistema debe calcular automáticamente el descuento correspondiente según las reglas configuradas y aplicarlo al próximo pago del profesor.</td>
    </tr>
    <!-- EPIC 03 -->
    <tr>
        <td rowspan="6">EP03</td>
        <td rowspan="2">US19</td>
        <td rowspan="2">Notificación de Vencimiento de Mensualidad</td>
        <td rowspan="2">Como administrador de una academia deportiva, necesito recibir notificaciones cuando la mensualidad de un estudiante esté próxima a vencerse para poder recordarle sobre el pago pendiente.</td>
        <td>Dado que soy un administrador, cuando un estudiante tenga una mensualidad próxima a vencerse, entonces debo recibir una notificación automática en la plataforma.</td>
    </tr>
    <tr>
        <td>Dado que recibo una notificación de vencimiento de mensualidad en la plataforma, cuando revise la noticicacion, entonces debe incluir el nombre del estudiante, el monto de la mensualidad y la fecha de vencimiento.</td>
    </tr>
    <tr>
        <td rowspan="2">US20</td>
        <td rowspan="2">Notificación por Faltas Consecutivas</td>
        <td rowspan="2">Como administrador de una academia deportiva, quiero recibir notificaciones cuando un alumno tenga un número excesivo de faltas consecutivas, para intervenir rápidamente y ofrecer apoyo al estudiante en caso de que haya problemas que afecten su asistencia regular.</td>
        <td>Dado que soy administrador de la academia, cuando el sistema detecte que un alumno ha acumulado un número predefinido de faltas consecutivas, entonces debe generar una notificación para mí.</td>
    </tr>
    <tr>
        <td>Dado que recibo una notificación por faltas consecutivas, cuando la revise, entonces la notificación debe incluir el nombre del alumno, el número de faltas consecutivas y un enlace directo a su perfil para tomar medidas.</td>
    </tr>
    <tr>
        <td rowspan="2">US21</td>
        <td rowspan="2">Recepción y Archivo de Justificaciones de Inasistencias y Tardanzas</td>
        <td rowspan="2">Como administrador de una academia deportiva en SportEase, quiero poder recibir y archivar justificaciones de inasistencias y tardanzas por parte de los estudiantes y profesores, para mantener un registro claro y organizado de las razones detrás de las ausencias y llegar a soluciones adecuadas según sea necesario.</td>
        <td>Dado que soy administrador de la academia, cuando un estudiante o profesor presente una justificación de inasistencia o tardanza, entonces debo poder recibirla a través de la plataforma.</td>
    </tr>
    <tr>
        <td>Dado que necesito recibir justificaciones, cuando un estudiante o profesor envíe una justificación, entonces debo recibir una notificación en mi panel de administrador.</td>
    </tr>
    <!-- EPIC 04 -->
    <tr>
        <td rowspan="6">EP04</td>
        <td rowspan="2">US22</td>
        <td rowspan="2">Gestión por Categorías o Edades</td>
        <td rowspan="2">Como administrador de una academia deportiva, necesito poder gestionar a los estudiantes organizándolos en categorías o grupos según su edad, nivel de habilidad u otros criterios relevantes.</td>
        <td>Dado que necesito asignar estudiantes a categorías o grupos en la plataforma, cuando ingrese a la seccion correspondiente, entonces debo poder agregar o quitar estudiantes de cada categoría según sea necesario.</td>
    </tr>
    <tr>
        <td>Dado que deseo visualizar y gestionar fácilmente los grupos en la plataforma, cuadno ingrese a la seccion correspondiente, entonces debo poder ver una lista de todas las categorías o grupos existentes, así como la lista de estudiantes asociados a cada grupo.</td>
    </tr>
    <tr>
        <td rowspan="2">US23</td>
        <td rowspan="2">Recordatorio de Cumpleaños de Estudiantes</td>
        <td rowspan="2">Como administrador de una academia deportiva, quiero recibir notificaciones para recordar los cumpleaños de los estudiantes, para poder felicitarlos y fortalecer la relación con ellos.</td>
        <td>Dado que soy un administrador, cuando un estudiante tenga su cumpleaños próximo, entonces debo recibir una notificación automática en la plataforma.</td>
    </tr>
    <tr>
        <td>Dado que recibo un recordatorio de cumpleaños, cuando la revise, entonces la notificación debe incluir el nombre del estudiante y la fecha de su cumpleaños.</td>
    </tr>
    <tr>
        <td rowspan="2">US24</td>
        <td rowspan="2">Asignación de Profesores por Categorías</td>
        <td rowspan="2">Como administrador de una academia deportiva, necesito poder asignar profesores a categorías específicas de clases o grupos de estudiantes para garantizar una distribución equitativa y eficiente de recursos humanos.</td>
        <td>Dado que accedo al sistema de gestión, cuando accedo al sistema de gestión, entonces debo poder ver una lista de todas las categorías de clases disponibles.</td>
    </tr>
    <tr>
        <td>Dado que deseo asignar profesores a una categoría de clase, para cada categoría de clase, cuando ingrese a la seccion correspondiente, entonces debo poder asignar uno o varios profesores responsables.</td>
    </tr>
    <!-- EPIC 05 -->
    <tr>
        <td rowspan="6">EP05</td>
        <td rowspan="2">US25</td>
        <td rowspan="2">Inicio de Sesión Seguro</td>
        <td rowspan="2">Como usuario de SportEase, quiero poder iniciar sesión de manera segura en la plataforma, para garantizar que mi cuenta esté protegida contra accesos no autorizados y mantener la privacidad de mis datos.</td>
        <td>Dado que ingreso mis credenciales de inicio de sesión (nombre de usuario o correo electrónico y contraseña), cuando presiono el botón de inicio de sesión después de ingresar mis credenciales, entonces el sistema debe validarlas de manera segura antes de permitirme el acceso.</td>
    </tr>
    <tr>
        <td>Dado que inicio sesión correctamente, cuando se validan mis credenciales correctamente, entonces debo ser redirigido a mi página de perfil o al tablero principal de la plataforma.</td>
    </tr>
    <tr>
        <td rowspan="2">US26</td>
        <td rowspan="2">Gestión de Perfil de Usuario</td>
        <td rowspan="2">Como usuario de SportEase, quiero poder gestionar mi perfil de usuario y la información personal asociada a él, para controlar qué datos se comparten y cómo se utilizan dentro de la plataforma.</td>
        <td>Dado que soy un usuario registrado y autenticado en la plataforma, cuando accedo a la sección de configuración de mi perfil desde el menú de usuario, entonces debo poder ver y editar la información de mi perfil, como nombre, correo electrónico, contraseña, foto de perfil, entre otros.</td>
    </tr>
    <tr>
        <td>Dado que deseo cambiar mi contraseña, cuando accedo a la opción de cambio de contraseña desde la configuración de mi perfil, entonces debo poder establecer una nueva contraseña siguiendo los requisitos de seguridad establecidos por la plataforma.</td>
    </tr>
    <tr>
        <td rowspan="2">US27</td>
        <td rowspan="2">Control de Privacidad de Datos</td>
        <td rowspan="2">Como usuario de SportEase, quiero tener control sobre la privacidad de mis datos personales y la visibilidad de mi información dentro de la plataforma,para asegurarme de que mis datos se utilicen y compartan según mis preferencias y necesidades de privacidad.</td>
        <td>Dado que accedo a la configuración de privacidad desde mi perfil de usuario, cuando navego a la sección de privacidad desde la configuración de mi perfil, entonces debo poder configurar mis preferencias de privacidad para controlar quién puede ver mi perfil y qué información se comparte públicamente.</td>
    </tr>
    <tr>
        <td>Dado que actualizo mis configuraciones de privacidad, cuando realizo cambios en las opciones de privacidad, entonces el sistema debe guardar mis preferencias de manera segura y aplicarlas a mi perfil y datos personales en la plataforma.</td>
    </tr>
</table>

## 3.3 Impact Mapping

El Impact Mapping es una técnica utilizada en el desarrollo de productos y la planificación estratégica para alinear los esfuerzos del equipo con los objetivos de negocio y los resultados deseados. Esta técnica se enfoca en identificar el impacto que un producto o proyecto puede tener en el negocio, los usuarios y otras partes interesadas.

Este pproporciona una vista holística y centrada en los resultados de cómo un producto o proyecto puede generar valor para el negocio y sus partes interesadas. Esto ayuda a los equipos a tomar decisiones más informadas sobre qué características desarrollar y cómo priorizar el trabajo para maximizar el impacto en el negocio y los usuarios (Lee, 2023).

###### Figura 18. 
*Impact Mapping completo de todos los segmentos objetivos de SportEase.*

![ImapctMapping](/assets/ImpactMapping.png)

## 3.4 Product Backlog

En esta sección del proyecto vamos a esquematizar y completar el Product Backlog, un elemento fundamental en la gestión ágil de proyectos de desarrollo de software. El Product Backlog actúa como una lista dinámica y priorizada de todas las funcionalidades, mejoras y requisitos que deben ser desarrollados para el producto. Su orden se basa en la priorización del valor para el negocio y es clave para guiar el trabajo del equipo de desarrollo a lo largo del proyecto.

El Product Backlog se compone de historias de usuario, tareas técnicas y otras actividades relacionadas con el desarrollo del producto. Este orden sigue una lógica clara, colocando en primer lugar aquellas historias relacionadas con la experiencia del usuario en la Landing Page, seguidas de las funcionalidades esenciales de la aplicación web, y finalmente, las historias técnicas necesarias para el desarrollo del sistema (Patton et al., 2014).

Como parte de nuestra iniciativa para esta sección, hemos integrado un modelo de guía de tareas y actividades señaladas para cada integrante dentro del Product Backlog mediante el uso de la aplicación Pivotal Tracker. Los lectores pueden acceder al planeamiento del Product Backlog completo a través del siguiente enlace: https://www.pivotaltracker.com/n/projects/2701202

###### Figura 19. 
*Modelo de trabajo realizado en la aplicación PivotalTracker para organizar todo el Product Backlog de SportEase.*

![PivotalTracker](/assets/pivotaltracker.png)

En la siguiente sección se presenta el Product Backlog ya finalizado del proyecto de SportEase. Cada elemento del Product Backlog ha sido cuidadosamente elaborado y priorizado según su valor para el negocio y su relevancia para los usuarios. Este enfoque garantiza que el equipo de desarrollo se enfoque en las características más importantes y valiosas para nuestros usuarios y para el éxito general del proyecto.

###### Tabla 9.
*Tabla del Product Backlog establecido para el proyecto de SportEase.*

| #Orden    | User Story Id  | Titulo                                                  | Descripcion               | Story Points (1/2/3/5/8)   |
|-----------|----------------|---------------------------------------------------------|---------------------------|----------------------------|
|     1     |      US01      | Visualización del Resumen en el Landing Page            | Como visitante, quiero encontrar una página de inicio diseñada de manera atractiva y funcional que me proporcione un resumen claro y conciso de las características principales y los beneficios para tener una idea rápida sobre lo que ofrece la plataforma.                          |   2                        |
|     2     |      US02      | Acceso a la Información del Plan                        | Como visitante del segmento administrador quiero una vista detallada del plan ofrecido por el sitio web para tomar una desicion de compra a conciencia.                          |   2                        |
|     3     |      US03      | Navegación Rápida y Fluida                              | Como visitante, quiero una experiencia de usuario optimizada en la landing page, que me brinde una navegación fluida y detallada, permitiéndome tomar decisiones conscientes sobre el uso de la plataforma.                          |   1                        |
|     4     |      US04      | Acceso Rápido a las Secciones Clave                     | Como visitante, quiero encontrar un menú de navegación en el header de la landing page que me permita acceder rápidamente a las secciones clave de SportEase, como información sobre la plataforma, suscripciones, funcionalidades y contacto.                          |   1                        |
|     5     |      US05      | Descripción Detallada de Funcionalidades                | Como visitante, quiero encontrar una sección en la landing page que describa detalladamente las funcionalidades de SportEase para comprender cómo puede beneficiarme el uso de la plataforma.                          |   1                        |
|     6     |      US06      | Formulario de Contacto                                  | Como visitante, quiero encontrar un formulario de contacto en la landing page para poder comunicarme fácilmente con el equipo de SportEase y obtener más información sobre la plataforma.                          |   1                        |
|     7     |      US07      | Adaptabilidad de la Interfaz                            | Como visitante que accede desde un dispositivo móvil, quiero que la landing page de SportEase tenga un diseño responsivo que se adapte adecuadamente a mi pantalla, garantizando una experiencia de usuario óptima y fácil navegación.                          |   2                        |
|     8     |      US08      | Call to Action Claro y Efectivo                         | Como visitante de la landing page de SportEase, espero encontrar llamadas a la acción (CTA) claras y efectivas que me guíen hacia los pasos que debo seguir para interactuar con el sitio de manera óptima y lograr mis objetivos, como registrarme, suscribirme o explorar más información.                          |   1                        |
|     9     |      US09      | Mejora de la Interactividad                             | Como visitante, quiero encontrar elementos interactivos en la landing page de SportEase, como animaciones sutiles, transiciones suaves y efectos visuales atractivos, que mejoren la experiencia de usuario y hagan que la navegación sea más agradable y entretenida.                          |   1                       |
|     10    |      US25      | Inicio de Sesión Seguro                                 | Como usuario de SportEase, quiero poder iniciar sesión de manera segura en la plataforma, para garantizar que mi cuenta esté protegida contra accesos no autorizados y mantener la privacidad de mis datos.                          |   8                        |
|     11    |      US26      | Gestión de Perfil de Usuario                            | Como usuario de SportEase, quiero poder gestionar mi perfil de usuario y la información personal asociada a él, para controlar qué datos se comparten y cómo se utilizan dentro de la plataforma.                          |   8                        |
|     12    |      US27      | Control de Privacidad de Datos                          | Como usuario de SportEase, quiero tener control sobre la privacidad de mis datos personales y la visibilidad de mi información dentro de la plataforma,para asegurarme de que mis datos se utilicen y compartan según mis preferencias y necesidades de privacidad.                          |   8                        |
|     13    |      US13      | Registro de Asistencia de Estudiantes                   | Como administrador de una academia deportiva, quiero poder marcar la asistencia de los estudiantes a mis clases y registrar las ausencias de manera eficiente.                          |   5                        |
|     14    |      US14      | Registro de Asistencia y Puntualidad de Profesores      | Como administrador de una academia deportiva, necesito poder llevar un registro de la asistencia y la puntualidad de los profesores para garantizar la calidad y consistencia de las clases.                          |   8                        |
|     15    |      US15      | Gestión de Eventos para Estudiantes                     | Como administrador de una academia deportiva en SportEase, quiero poder crear y gestionar eventos (torneos) para mis estudiantes,para ofrecerles oportunidades adicionales de participación y enriquecimiento en la comunidad deportiva.                          |   5                        |
|     16    |      US16      | Gestión de Pagos de Alquiler de Campos Deportivos       | Como administador de la academia deportiva, necesito tener un sistema para gestionar los pagos relacionados con el alquiler de campos deportivos, permitiéndome registrar los pagos adeudados a terceros por el uso de los campos y mantener un registro claro de las transacciones financieras asociadas.                          |   5                        |
|     17    |      US17      | Registro de Pagos y Asistencias a Profesores            | Como administrador de una academia deportiva, necesito poder registrar los pagos y llevar un control de las asistencias de los profesores para garantizar que reciban su compensación de manera oportuna y justa.                          |   8                        |
|     18    |      US18      | Gestión de Descuentos por Tardanzas                     | Como administrador de una academia deportiva, necesito poder aplicar descuentos por tardanzas a los pagos de los profesores para mantener la disciplina y la puntualidad en las clases.                          |   5                        |
|     19    |      US19      | Notificación de Vencimiento de Mensualidad              | Como administrador de una academia deportiva, necesito recibir notificaciones cuando la mensualidad de un estudiante esté próxima a vencerse para poder recordarle sobre el pago pendiente.                          |   3                        |
|     20    |      US20      | Notificación por Faltas Consecutivas                    | Como administrador de una academia deportiva, quiero recibir notificaciones cuando un alumno tenga un número excesivo de faltas consecutivas, para intervenir rápidamente y ofrecer apoyo al estudiante en caso de que haya problemas que afecten su asistencia regular.                          |   3                        |
|     21    |      US21      | Recepción y Archivo de Justificaciones de Inasistencias | Como administrador de una academia deportiva en SportEase, quiero poder recibir y archivar justificaciones de inasistencias y tardanzas por parte de los estudiantes y profesores, para mantener un registro claro y organizado de las razones detrás de las ausencias y llegar a soluciones adecuadas según sea necesario.                          |   5                        |
|     22    |      US22      | Gestión por Categorías o Edades                         | Como administrador de una academia deportiva, necesito poder gestionar a los estudiantes organizándolos en categorías o grupos según su edad, nivel de habilidad u otros criterios relevantes.                          |   8                        |
|     23    |      US23      | Recordatorio de Cumpleaños de Estudiantes               | Como administrador de una academia deportiva, quiero recibir notificaciones para recordar los cumpleaños de los estudiantes, para poder felicitarlos y fortalecer la relación con ellos.                          |   3                        |
|     24    |      US24      | Asignación de Profesores por Categorías                 | Como administrador de una academia deportiva, necesito poder asignar profesores a categorías específicas de clases o grupos de estudiantes para garantizar una distribución equitativa y eficiente de recursos humanos.                          |   5                        |
|     25    |      US10      | Configuración de la API REST                            | Como miembro del equipo de desarrollo, quiero configurar correctamente la API REST para la plataforma SportEase, estableciendo rutas, métodos y parámetros necesarios para el intercambio de datos entre el cliente y el servidor.                          |   8                        |
|     26    |      US11      | Implementación de Funcionalidades Básicas               | Como miembro del equipo de desarrollo, quiero implementar las funcionalidades básicas de la API REST, como la creación, lectura, actualización y eliminación de recursos, para garantizar el acceso y la manipulación de datos de manera eficiente.                          |   5                        |
|     27    |      US12      | Gestión de Autenticación y Autorización                 | Como miembro del equipo de desarrollo, quiero integrar un sistema de autenticación y autorización en la API REST, para garantizar la seguridad y la privacidad de los datos de los usuarios de SportEase.                          |   8                        |

---
