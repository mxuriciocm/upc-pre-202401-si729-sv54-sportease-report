# Capítulo 3: Requirements Specification
## 3.1 To-Be Scenario Mapping

Dueño de academia

![To-Be_Dueño](/assets/To-Be_Dueño.png)

Deportistas

![To-Be_Dueño](/assets/To-Be_Deportista.png)

## 3.2 User Stories
EPICS
<table>
    <tr>
        <th>Epic ID</th>
        <th>Título</th>
        <th>Descripción</th>
    </tr>
    <tr>
        <td>EP01</td>
        <td>Administración de Horarios y Clases</td>
        <td>Como administrador de una academia deportiva, quiero tener herramientas para gestionar eficientemente los horarios de clases, pagos, asisencias, eventos de mis estudiantes.</td>
    </tr>
    <tr>
        <td>EP02</td>
        <td>Seguimiento del Desempeño de los Estudiantes</td>
        <td>Como instructor, quiero poder registrar y realizar un seguimiento del progreso de mis estudiantes, incluyendo rendimiento y logros.</td>
    </tr>
    <tr>
        <td>EP03</td>
        <td>Gestión de Usuarios y Roles en las Academias</td>
        <td>Como administrador, quiero poder gestionar los usuarios y asignar roles según sus funciones dentro de la academia deportiva a través de SportEase.</td>
    </tr>
    <tr>
        <td>EP04</td>
        <td>Seguridad y Privacidad de Datos de los Usuarios</td>
        <td>Como usuario, quiero que mis datos personales estén seguros y protegidos en la plataforma SportEase, y poder gestionar mi información personal de manera confiable.</td>
    </tr>
	<tr>
        <td>EP05</td>
        <td>Technicals stories</td>
        <td>Como equipo de desarrollo, queremos implementar y manejar la plataforma mediante una API REST para controlar eficazmente los datos y el flujo de información en toda la solución, garantizando así un desarrollo y mantenimiento eficientes de la plataforma.</td>
    </tr>
	<tr>
        <td>EP06</td>
        <td>Diseño y Estructura de la Landing Page</td>
        <td>Como visitante, quiero encontrar una landing page diseñada y estructurada de manera atractiva y funcional, que me proporcione información detallada y precisa sobre lo que ofrece el sitio web, para tomar decisiones informadas sobre el uso de la plataforma.</td>
    </tr>
	<tr>
        <td>EP07</td>
        <td>Optimización de la Experiencia del Usuario</td>
        <td>Como visitante, quiero una experiencia de usuario optimizada en la landing page, que me brinde una navegación fluida y detallada, permitiéndome tomar decisiones conscientes sobre el uso de la plataforma.</td>
    </tr>
</table>

USER STORIES FOR LANDING PAGE
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
        <td rowspan="6">EP06</td>
        <td rowspan="2">US01</td>
        <td rowspan="2">Presentación de la Página de Inicio</td>
        <td rowspan="2">Como visitante, quiero encontrar una página de inicio diseñada de manera atractiva y funcional que me proporcione un resumen claro y conciso de las características principales y los beneficios para tener una idea rápida sobre lo que ofrece la plataforma.</td>
        <td>Visualización del Resumen en el Landing Page - Dado el visitante accede al landing page del sitio web. Cuando el visitante visualiza la sección de resumen rápido. Entonces se presenta un resumen claro y conciso de las principales características y beneficios del sitio web, destacando los puntos más relevantes de manera atractiva y fácil de entender.</td>
    </tr>
    <tr>
        <td>Información Asertiva y Relevante - Dado el visitante está leyendo el resumen en el landing page. Cuando el visitante revisa la información presentada. Entonces la información proporcionada se centra en los aspectos más importantes y distintivos del sitio web, ofreciendo una visión rápida y clara de lo que ofrece y cómo puede beneficiar al usuario.</td>
    </tr>
    <tr>
        <td rowspan="2">US02</td>
        <td rowspan="2">Resumen de precios</td>
        <td rowspan="2">Como visitante del segmento administrador quiero una vista detallada del plan ofrecido por el sitio web para tomar una desicion de compra a conciencia.</td>
        <td>Acceso a la Información del Plan - Dado el visitante del segmento administrador está en el sitio web. Cuando el visitante busca información detallada sobre el plan ofrecido. Entonces se proporciona un acceso claro y visible a la página o sección que describe en detalle el plan ofrecido, ya sea a través del menú de navegación, enlaces destacados o botones de llamada a la acción.</td>
    </tr>
    <tr>
        <td>Descripción Completa y Clara del Plan - Dado el visitante está en la página de información del plan. Cuando el visitante lee la descripción del plan. Entonces se presenta una descripción completa y clara del plan ofrecido, incluyendo características, beneficios, limitaciones, términos y condiciones, precio y cualquier otra información relevante que permita al visitante entender completamente lo que está incluido en el plan.</td>
    </tr>
    <tr>
        <td rowspan="2">US03</td>
        <td rowspan="2">Navegación Rápida y Fluida</td>
        <td rowspan="2">Como visitante, quiero una experiencia de usuario optimizada en la landing page, que me brinde una navegación fluida y detallada, permitiéndome tomar decisiones conscientes sobre el uso de la plataforma.</td>
        <td>Navegación Intuitiva y Fluida - Dado el visitante navega por la landing page. Cuando el visitante interactúa con la página y busca acceder a diferentes secciones. Entonces la navegación es intuitiva y fluida, permitiendo al visitante acceder fácilmente a las diferentes secciones de la página y encontrar la información que busca sin dificultad.</td>
    </tr>
    <tr>
        <td>Experiencia de Usuario Optimizada -Dado el visitante carga la landing page en su navegador. Cuando el visitante interactúa con los elementos de la página, como botones, menús y enlaces. Entonces la página responde de manera rápida y eficiente a las acciones del usuario, proporcionando una experiencia fluida y sin retrasos.</td>
    </tr>
    <tr>
		<td rowspan="6">EP06</td>
        <td rowspan="2">US04</td>
        <td rowspan="2">Acceso Rápido a las Secciones Clave</td>
        <td rowspan="2">Como visitante, quiero encontrar un menú de navegación en el header de la landing page que me permita acceder rápidamente a las secciones clave de SportEase, como información sobre la plataforma, suscripciones, funcionalidades y contacto.</td>
        <td>Visibilidad del Menú de Navegación - Dado que el visitante carga la landing page en su navegador. Cuando el visitante visualiza la página. Entonces el menú de navegación está claramente visible en el header de la página, ubicado en una posición destacada y fácilmente identificable.</td>
    </tr>
    <tr>
        <td>Acceso Rápido a Secciones Clave - Dado que el visitante está en la landing page. Cuando el visitante hace clic en una opción del menú de navegación. Entonces el visitante es redirigido de manera rápida y directa a la sección correspondiente del sitio web, como información sobre la plataforma, suscripciones, funcionalidades o contacto, sin demoras ni tiempos de carga prolongados.</td>
    </tr>
    <tr>
        <td rowspan="2">US05</td>
        <td rowspan="2"> Descripción Detallada de Funcionalidades</td>
        <td rowspan="2">Como visitante, quiero encontrar una sección en la landing page que describa detalladamente las funcionalidades de SportEase para comprender cómo puede beneficiarme el uso de la plataforma.</td>
        <td>Contenido Detallado y Comprensible - Dado que el visitante carga la landing page en su navegador. Cuando el visitante accede a la sección de descripción de funcionalidades. Entonces se presenta contenido detallado que describe cada funcionalidad de SportEase de manera clara y comprensible, explicando su propósito, beneficios y cómo puede beneficiar al usuario.</td>
    </tr>
    <tr>
        <td>Organización y Estructura - Dado que el visitante está en la sección de descripción de funcionalidades. Cuando el visitante revisa el contenido. Entonces las funcionalidades se presentan de manera organizada y estructurada, facilitando la lectura y comprensión del visitante. Se utiliza un formato coherente y sección clara para cada funcionalidad.</td>
    </tr>
    <tr>
        <td rowspan="2">US06</td>
        <td rowspan="2">Formulario de Contacto</td>
        <td rowspan="2">Como visitante, quiero encontrar un formulario de contacto en la landing page para poder comunicarme fácilmente con el equipo de SportEase y obtener más información sobre la plataforma.</td>
        <td>Visibilidad del Formulario - Dado que el visitante carga la landing page en su navegador. Cuando el visitante accede a la sección donde se espera encontrar el formulario de contacto. Entonces el formulario de contacto está claramente visible en la landing page, ubicado en un lugar prominente y fácilmente identificable, como en el footer o una sección dedicada específicamente al contacto.</td>
    </tr>
    <tr>
        <td>Facilidad de Uso - Dado que el visitante está en la sección donde se encuentra el formulario de contacto. Cuando el visitante interactúa con el formulario. Entonces el formulario de contacto es fácil de usar, con campos claros y etiquetas descriptivas. Se proporcionan instrucciones claras sobre cómo completar el formulario y qué información se espera del visitante.</td>
    </tr>
    <!-- EPIC 7 -->
    <tr>
        <td rowspan="6">EP07</td>
        <td rowspan="2">US07</td>
        <td rowspan="2">Diseño Responsivo para Dispositivos Móviles:</td>
        <td rowspan="2">Como visitante que accede desde un dispositivo móvil, quiero que la landing page de SportEase tenga un diseño responsivo que se adapte adecuadamente a mi pantalla, garantizando una experiencia de usuario óptima y fácil navegación.</td>
        <td>Adaptabilidad de la Interfaz - Dado que el visitante carga la landing page de SportEase desde un dispositivo móvil con diferentes tamaños de pantalla. Cuando el visitante accede a la página. Entonces la página se adapta automáticamente al tamaño de la pantalla del dispositivo móvil, asegurando que todos los elementos de la página se muestren correctamente y de manera legible sin necesidad de hacer zoom o desplazamiento horizontal.</td>
    </tr>
    <tr>
        <td>Legibilidad del Contenido - Dado que el visitante visualiza el contenido de la landing page desde un dispositivo móvil. Cuando el visitante lee el texto y los elementos de la página. Entonces el texto y otros elementos de la página son legibles y están correctamente formateados para dispositivos móviles, con tamaños de fuente adecuados, espaciado apropiado y disposición coherente.</td>
    </tr>
    <tr>
        <td rowspan="2">US08</td>
        <td rowspan="2">Call to Action Claro y Efectivo</td>
        <td rowspan="2">Como visitante de la landing page de SportEase, espero encontrar llamadas a la acción (CTA) claras y efectivas que me guíen hacia los pasos que debo seguir para interactuar con el sitio de manera óptima y lograr mis objetivos, como registrarme, suscribirme o explorar más información.</td>
        <td>Visibilidad Clara - Dado que el visitante carga la landing page de SportEase en su navegador. Cuando el visitante visualiza la página sin desplazarse. Entonces las llamadas a la acción están ubicadas en áreas prominentes de la página, como el encabezado, el cuerpo o el pie de página, y son fácilmente identificables sin la necesidad de desplazamiento.</td>
    </tr>
    <tr>
        <td>Llamadas a la Acción Atractivas - Dado que el visitante navega por la landing page de SportEase. Cuando el visitante visualiza las llamadas a la acción. Entonces las CTA están diseñadas de manera atractiva y destacan visualmente en la página, utilizando colores contrastantes, botones llamativos o elementos gráficos que inviten a la interacción.</td>
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

TECHNICAL STORIES
<table>
    <tr>
        <th>Epic Id</th>
        <th>Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de aceptación</th>
    </tr>
    <!-- EPIC 5 -->
    <tr>
        <td rowspan="5">EP05</td>
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
        <td rowspan="2">Gestión de Autenticación y Autorización:</td>
        <td rowspan="2">Como miembro del equipo de desarrollo, quiero integrar un sistema de autenticación y autorización en la API REST, para garantizar la seguridad y la privacidad de los datos de los usuarios de SportEase.</td>
        <td>Registro de Usuarios - Dado que un usuario desea registrarse en SportEase. Cuando se envía una solicitud POST al endpoint de registro con los datos de usuario requeridos, como nombre de usuario, correo electrónico y contraseña. Entonces se crea una nueva cuenta de usuario en la base de datos y se devuelve una respuesta con el código de estado 201 (Created) junto con un token de acceso JWT (JSON Web Token) válido para la autenticación posterior.</td>
    </tr>
</table>

## 3.3 Impact Mapping

![ImapctMapping](/assets/ImpactMapping.png)

## 3.4 Product Backlog

| #Orden  | User Story Id  | Titulo                                                       | Descripcion               | Story Points (1/2/3/5/8)   |
|---------|----------------|--------------------------------------------------------------|---------------------------|----------------------------|
| 1       | US01           | Integración de Redes Sociales y Contenido Útil en el Footer  | Como usuario, deseo que en el footer del sitio se encuentren enlaces a las redes sociales de la empresa y acceso rápido a contenido útil para facilitar mi interacción con la empresa y encontrar información relevante de manera conveniente.  |   5  |
| 2       | US02           | Navegación eficiente a través de enlaces internos con anclas | Como usuario, quiero poder acceder directamente a secciones específicas de la página web mediante enlaces internos con anclas, para mejorar la navegación y encontrar la información deseada de manera eficiente. |   5   |
| 3       | US03           | Informacion de los planes que ofrecemos                      | Como usuario interesado en conocer las opciones disponibles, quiero acceder fácilmente a una sección en el sitio web que presente información detallada sobre los planes de suscripción ofrecidos, para poder comparar y tomar una decisión informada sobre cuál plan se adapta mejor a mis necesidades.   |  5   |
| 4       | US04           | Implementación de Sección de Contacto                        | Como developer, quiero integrar una sección "Contactanos" que incluya un numero y se puede ingresar el correo, para brindar a los usuarios la posibilidad de comunicarse con nosotros de manera fácil y rápida.   |   3   |
| 5       | US05           | Agregar la Sección "Sobre Nosotros"                          | Como developer, quiero integrar seccion de "Sobre nosotros" que incluya informacion sobre nuestro objetivo, para brindar a los usuarios una comprensión clara de quiénes somos, qué hacemos y por qué lo hacemos   |   3   |
