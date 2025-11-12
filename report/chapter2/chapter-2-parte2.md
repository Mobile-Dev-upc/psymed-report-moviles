
## 2.4. Requirements specification
### 2.4.1 User Stories.

US01 - Registrar como profesional de la salud mental
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US01</td> <td>Profesional de la salud mental</td> <td>8</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Registrar como profesional de la salud mental</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero registrarme con mis credenciales para poder acceder a las funcionalidades específicas y gestionar la información de mis pacientes. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el profesional de la salud mental proporciona la información requerida para su registro,<br> Cuando el sistema valida la información ingresada,<br> Entonces el sistema debe registrar los datos del profesional de forma segura,<br> Y asignarle el rol correspondiente de profesional de la salud mental.</li> <li><b>Escenario 2: Información incompleta</b><br> Dado que el profesional de la salud mental no proporciona toda la información requerida,<br> Cuando el sistema valida los datos,<br> Entonces el sistema debe rechazar el registro,<br> Y notificar qué información falta para completarlo.</li> <li><b>Escenario 3: Credenciales duplicadas</b><br> Dado que el profesional intenta registrarse con credenciales ya existentes,<br> Cuando el sistema valida la información,<br> Entonces el sistema debe impedir el registro,<br> Y notificar que las credenciales ya están registradas, sugiriendo la recuperación de acceso.</li> </ul> </td> </tr> </table>

US02 - Iniciar de sesión como paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US02</td> <td>Paciente</td> <td>8</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Iniciar sesión como paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como paciente, quiero iniciar sesión en la plataforma para acceder a mi información personal y seguimiento de tratamiento. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Inicio exitoso</b><br> Dado que el paciente proporciona credenciales válidas,<br> Cuando el sistema las valida,<br> Entonces el sistema debe permitir el acceso al entorno del paciente,<br> Y habilitar las funciones asociadas a su rol.</li> <li><b>Escenario 2: Credenciales incorrectas</b><br> Dado que el paciente ingresa credenciales incorrectas,<br> Cuando el sistema valida la información,<br> Entonces el sistema debe denegar el acceso,<br> Y notificar que las credenciales no son válidas, ofreciendo una opción de recuperación.</li> <li><b>Escenario 3: Recuperación de acceso</b><br> Dado que el paciente solicita recuperar su acceso,<br> Cuando el sistema procesa la solicitud,<br> Entonces debe enviar un enlace de restablecimiento al correo electrónico registrado.</li> </ul> </td> </tr> </table>

US03 - Iniciar de sesión como profesional de la salud mental
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US03</td> <td>Profesional de la salud mental</td> <td>8</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Iniciar de sesión como profesional de la salud mental</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero iniciar sesión en la plataforma para gestionar la información de mis pacientes y acceder a herramientas de seguimiento. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Inicio exitoso</b><br> Dado que el profesional de la salud mental proporciona credenciales válidas,<br> Cuando el sistema las valida,<br> Entonces el sistema debe permitir el acceso,<br> Y habilitar las funciones de gestión de pacientes correspondientes a su rol.</li> <li><b>Escenario 2: Credenciales inválidas</b><br> Dado que el profesional proporciona credenciales incorrectas,<br> Cuando el sistema las valida,<br> Entonces el sistema debe denegar el acceso,<br> Y notificar el error, ofreciendo la opción de restablecer el acceso.</li> <li><b>Escenario 3: Recuperación de acceso</b><br> Dado que el profesional solicita recuperar su contraseña,<br> Cuando el sistema procesa la solicitud,<br> Entonces debe enviar un enlace de restablecimiento al correo asociado.</li> </ul> </td> </tr> </table>

US04 - Registrar de información personal del paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US04</td> <td>Profesional de la salud mental</td> <td>5</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Registrar información personal del paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero registrar la información personal del paciente para tener una referencia detallada y precisa de sus datos básicos en cada consulta. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el profesional proporciona toda la información personal requerida del paciente,<br> Cuando el sistema valida los datos,<br> Entonces debe almacenar la información de manera segura y asociarla al perfil del paciente.</li> <li><b>Escenario 2: Datos incompletos</b><br> Dado que el profesional no completa toda la información requerida,<br> Cuando el sistema valida los datos,<br> Entonces debe impedir el registro,<br> Y notificar qué información falta para completarlo.</li> </ul> </td> </tr> </table>

US05 - Visualizar del estado actual de ánimo del paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US05</td> <td>Profesional de la salud mental</td> <td>3</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Visualizar el estado actual de ánimo del paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero visualizar el estado de ánimo actual del paciente para evaluar su condición emocional. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Estado disponible</b><br> Dado que existe un registro de estado de ánimo del paciente,<br> Cuando el sistema consulta el perfil del paciente,<br> Entonces debe mostrar el estado de ánimo más reciente registrado.</li> <li><b>Escenario 2: Sin registros previos</b><br> Dado que no existen registros de estado de ánimo del paciente,<br> Cuando el sistema realiza la consulta,<br> Entonces debe indicar la ausencia de registros disponibles.</li> </ul> </td> </tr> </table>

US06 - Registrar de estado de ánimo
<table> <tr> <th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th> </tr> <tr><td>US06</td><td>Paciente</td><td>5</td><td>EP02</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar estado de ánimo</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero comunicarle a mi profesional mi estado de ánimo para ver mi estado actual. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el paciente proporciona su estado emocional actual,<br> Cuando el sistema recibe y valida la información,<br> Entonces el sistema debe almacenar el registro de estado de ánimo y asociarlo al perfil del paciente.</li> <li><b>Escenario 2: Visualización del historial</b><br> Dado que el paciente cuenta con registros previos de estados de ánimo,<br> Cuando el sistema consulta el historial,<br> Entonces debe mostrar los registros anteriores organizados cronológicamente.</li> </ul> </td></tr> </table>

US07 - Registrar de funciones biológicas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US07</td><td>Paciente</td><td>5</td><td>EP02</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar funciones biológicas</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero registrar la calidad de mis funciones biológicas para que mi profesional conozca mi estado actual de salud. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro de funciones biológicas</b><br> Dado que el paciente proporciona información sobre sus niveles de sueño, hambre, energía e hidratación,<br> Cuando el sistema valida y procesa los datos,<br> Entonces debe almacenar las respuestas en el perfil del paciente,<br> Y permitir su posterior consulta por el profesional.</li> </ul> </td></tr> </table>

US08 - Registrar de medicamentos del paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US08</td><td>Profesional de la salud mental</td><td>3</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar medicamentos del paciente</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como profesional de la salud mental, quiero registrar los medicamentos del paciente para seguir adecuadamente su tratamiento farmacológico. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el profesional proporciona toda la información requerida sobre el medicamento,<br> Cuando el sistema valida los datos,<br> Entonces debe registrar la información del medicamento y asociarla al paciente correspondiente.</li> <li><b>Escenario 2: Información incompleta</b><br> Dado que la información ingresada es incompleta o incorrecta,<br> Cuando el sistema valida los datos,<br> Entonces debe rechazar el registro,<br> Y notificar los campos que necesitan corrección.</li> </ul> </td></tr> </table>

US09 - Ver medicamentos
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US09</td><td>Paciente</td><td>3</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Ver medicamentos</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero poder ver los medicamentos que mi profesional de salud mental ha asignado para poder estar pendiente de cuáles consumir. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de medicamentos</b><br> Dado que existen medicamentos registrados por el profesional,<br> Cuando el sistema consulta la información del paciente,<br> Entonces debe mostrar la lista completa de medicamentos asociados y sus detalles.</li> <li><b>Escenario 2: Sin medicamentos registrados</b><br> Dado que no hay medicamentos asignados al paciente,<br> Cuando el sistema realiza la consulta,<br> Entonces debe mostrar un mensaje indicando la ausencia de registros.</li> </ul> </td></tr> </table>

US10 - Crear citas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US10</td><td>Profesional de la salud</td><td>2</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Crear citas</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como profesional de la salud, quiero agendar las citas de mis pacientes. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Creación de cita</b><br> Dado que el profesional proporciona la información necesaria (fecha, hora, duración, paciente),<br> Cuando el sistema valida y registra la información,<br> Entonces debe crear la cita y asociarla al paciente correspondiente.</li> </ul> </td></tr> </table>

US11 - Ver citas médicas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US11</td><td>Paciente</td><td>2</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Ver citas médicas</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero poder ver las citas médicas programadas para poder saber qué días asistir al consultorio del profesional de salud mental. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de citas</b><br> Dado que existen citas médicas registradas,<br> Cuando el sistema consulta las citas asociadas al paciente,<br> Entonces debe mostrar la lista con fecha, hora y profesional asignado.</li> <li><b>Escenario 2: Sin citas registradas</b><br> Dado que no existen citas programadas,<br> Cuando el sistema realiza la consulta,<br> Entonces debe indicar que no hay citas próximas.</li> </ul> </td></tr> </table>

## Historias de usuario para la aplicación Móvil

US12 - Iniciar sesión como paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US12</td><td>Paciente</td><td>8</td><td>EP01</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Iniciar Sesión como Paciente en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero iniciar sesión con mi usuario y contraseña para acceder a mi información personal y de salud dentro de la aplicación. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Inicio exitoso</b><br> Dado que el paciente proporciona credenciales válidas,<br> Cuando el sistema las valida,<br> Entonces debe permitir el acceso al entorno móvil del paciente y cargar su información personal.</li> <li><b>Escenario 2: Credenciales inválidas</b><br> Dado que el paciente proporciona credenciales incorrectas,<br> Cuando el sistema valida la información,<br> Entonces debe rechazar el acceso e informar el error.</li> <li><b>Escenario 3: Campos vacíos</b><br> Dado que faltan datos de autenticación,<br> Cuando el sistema valida la solicitud,<br> Entonces debe impedir el acceso e indicar la ausencia de datos requeridos.</li> </ul> </td></tr> </table>

US13 - Visualizar información de perfil
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US13</td><td>Paciente</td><td>3</td><td>EP01</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Visualizar Información de Perfil en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero ver mi información personal para confirmar que mis datos sean correctos. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización del perfil</b><br> Dado que el paciente accede a su perfil,<br> Cuando el sistema recupera su información,<br> Entonces debe mostrar nombre, correo, dirección, ID de paciente y profesional asociado.</li> </ul> </td></tr> </table>

US14 - Cerrar sesión
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US14</td><td>Paciente</td><td>2</td><td>EP01</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Cerrar Sesión en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero cerrar mi sesión de forma segura para proteger mi privacidad. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Cierre exitoso</b><br> Dado que el paciente ha iniciado sesión,<br> Cuando solicita cerrar sesión,<br> Entonces el sistema debe finalizar la sesión activa y eliminar los datos temporales de autenticación.</li> </ul> </td></tr> </table>

US15 - Registrar mi estado de salud diario
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US15</td><td>Paciente</td><td>5</td><td>EP02</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar Mi Estado de Salud Diario en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero registrar mi estado de salud diario para llevar un seguimiento de mi bienestar. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el paciente proporciona su estado diario en todas las categorías requeridas,<br> Cuando el sistema valida y guarda la información,<br> Entonces debe registrar los datos de ese día y confirmar la acción.</li> <li><b>Escenario 2: Registro duplicado</b><br> Dado que el paciente ya registró su estado diario,<br> Cuando intenta volver a hacerlo,<br> Entonces el sistema debe impedir el registro duplicado y notificar que ya existe uno.</li> </ul> </td></tr> </table>

US16 - Consultar mi lista de medicamentos
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US16</td><td>Paciente</td><td>5</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Consultar Mi Lista de Medicamentos en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero ver mi lista de medicamentos asignados con detalles de motivo, frecuencia e intervalo. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de medicamentos</b><br> Dado que existen medicamentos registrados,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar cada medicamento con su motivo, intervalo y cantidad.</li> </ul> </td></tr> </table>

US17 - Ver próximas citas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US17</td><td>Paciente</td><td>3</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Ver Próximas Citas en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero ver mis próximas citas médicas con sus detalles para planificar mi asistencia. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de citas</b><br> Dado que existen citas futuras,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar la lista con fecha, hora, duración y profesional asignado.</li> <li><b>Escenario 2: Cita actual</b><br> Dado que existe una cita para la fecha actual,<br> Entonces el sistema debe marcarla con una etiqueta distintiva.</li> </ul> </td></tr> </table>

## Historias de Usuario de la Landing Page (US18 - US20)

US18 - Encontrar información del propósito de la aplicación
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US18</td><td>Visitante de la Landing Page</td><td>1</td><td>EP05</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Encontrar información del propósito de la aplicación</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como visitante de la Landing Page, quiero entender claramente el propósito de la aplicación para saber cómo puede ayudarme. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Propósito visible</b><br> Dado que el visitante accede a la página principal,<br> Cuando el sistema carga el contenido,<br> Entonces debe mostrar información clara y concisa sobre el propósito de la aplicación.</li> </ul> </td></tr> </table>

US19 - Visualizar de imágenes y gráficos relevantes
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US19</td><td>Visitante de la Landing Page</td><td>1</td><td>EP05</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Visualizar imágenes y gráficos relevantes</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como visitante de la Landing Page, quiero ver imágenes y gráficos claros que complementen la información y despierten mi interés. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Imágenes relevantes</b><br> Dado que el visitante navega por la página,<br> Cuando el sistema presenta contenido visual,<br> Entonces las imágenes deben ser de alta calidad y coherentes con el mensaje del sitio.</li> <li><b>Escenario 2: Gráficos informativos</b><br> Dado que el visitante visualiza secciones con gráficos,<br> Cuando el sistema muestra estos elementos,<br> Entonces deben facilitar la comprensión del contenido textual.</li> </ul> </td></tr> </table>

US20 - Visualizar tipografía cómoda y agradable estéticamente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US20</td> <td>Visitante de la Landing Page</td> <td>1</td> <td>EP05</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Visualizar tipografía cómoda y agradable estéticamente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como visitante de la Landing Page, quiero que la tipografía sea legible y visualmente coherente para facilitar la lectura y mantener una experiencia estética agradable. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Legibilidad de la tipografía</b><br> Dado que el visitante accede a la Landing Page,<br> Cuando el sistema muestra el contenido textual,<br> Entonces debe utilizar una tipografía clara, con un tamaño adecuado y contraste suficiente para facilitar la lectura.</li>
  <li><b>Escenario 2: Consistencia tipográfica</b><br>
  Dado que el visitante navega entre diferentes secciones de la Landing Page,<br>
  Cuando el sistema renderiza los textos,<br>
  Entonces debe mantener una coherencia visual en los estilos tipográficos (fuente, tamaño y color) en toda la página.</li>
</ul>

</td> </tr> </table>

**Spike Stories**

| Story ID | User      | Priority | Epic                           | Title                                                                                                | Description                                                                                                                                                                                                             | Acceptance Criteria                                                                                                                                                                                                                                                                         |
|----------|-----------|----------|--------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SP-01    | Developer | Alta     | Autenticación                  | Investigar bibliotecas de autenticación y manejo de roles                                            | Como desarrollador quiero investigar bibliotecas y frameworks de autenticación (JWT) para determinar cuál es más adecuada para integrar autenticación segura y diferenciación de roles entre pacientes y profesionales. | Dado que se realiza la investigación de bibliotecas de autenticación<br>Cuando se evalúan criterios de compatibilidad, seguridad, persistencia de sesión y soporte multiplataforma<br>Entonces se entrega un documento técnico con la librería recomendada y un prototipo mínimo funcional. |
| SP-02    | Developer | Alta     | Sincronización móvil–backend   | Analizar mecanismos de sincronización de datos entre aplicación móvil y backend                      | Como desarrollador quiero investigar las opciones de sincronización de datos (online/offline) entre la aplicación móvil y el backend para garantizar consistencia de la información clínica y del paciente.             | Dado que se analizan distintas estrategias de sincronización (REST, local)<br>Cuando se evalúan la latencia, seguridad y manejo de errores<br>Entonces se presenta un documento técnico y un prototipo que demuestra la sincronización correcta de datos básicos del usuario.               |
| SP-03    | Developer | Media    | Gestión de información clínica | Definir modelo de datos y herramientas para visualización de estado emocional y funciones biológicas | Como desarrollador quiero definir la estructura de base de datos y las herramientas de visualización adecuadas para representar los estados de ánimo, funciones biológicas y medicamentos del paciente.                 | Dado que se analizan bases de datos SQL<br>Cuando se evalúan criterios de rendimiento, escalabilidad y compatibilidad con el backend<br>Entonces se entrega un esquema de datos propuesto y un prototipo visual básico de los registros del paciente.                                       |
| SP-04    | Developer | Media    | Sistema de citas               | Investigar opciones para la gestión y visualización de citas médicas                                 | Como desarrollador quiero investigar librerías y APIs que faciliten la creación, visualización y sincronización de citas médicas entre paciente y profesional.                                                          | Dado que se prueban distintas herramientas de calendarización<br>Cuando se evalúan sus capacidades de integración, manejo de conflictos y notificaciones<br>Entonces se documenta la opción más viable y se crea un prototipo que demuestre la creación de una cita básica.                 |
| SP-05    | Developer | Baja     | Web App                        | Investigar diseño visual, tipografía y accesibilidad para la Web App                                 | Como desarrollador quiero investigar lineamientos de diseño visual, tipografía y frameworks front-end para crear una Web App atractiva, legible y accesible.                                                            | Dado que se analizan frameworks como Angular Material y TailwindCSS<br>Cuando se evalúan los criterios de legibilidad, contraste, accesibilidad y consistencia visual<br>Entonces se entrega un prototipo de la Web App y una guía de estilos inicial para su implementación.               |

### 2.4.2 Impact Mapping.

### Segmento profesionales:
![Professionals_](/assets/professionals_IM.jpeg)

### Segmento pacientes:
![Patients_impactmapping](/assets/patients_IM.jpeg)

## 2.4.3 Product Backlog.

| Order User Story | Título                                                     | Descripción                                                                                                                                                                                       | Story Points (Priority) |
|------------------|------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| 1                | Registrar como profesional de la salud mental              | Como profesional de la salud mental quiero registrarme con mis credenciales para poder acceder a las funcionalidades específicas y gestionar la información de mis pacientes.                     | 8                       |
| 2                | Iniciar sesión como paciente                               | Como paciente, quiero iniciar sesión en la plataforma para acceder a mi información personal y seguimiento de tratamiento.                                                                        | 8                       |
| 3                | Iniciar sesión como profesional de la salud mental         | Como profesional de la salud mental, quiero iniciar sesión en la plataforma para gestionar la información de mis pacientes y acceder a herramientas de seguimiento.                               | 8                       |
| 4                | Iniciar sesión como Paciente en la aplicación móvil        | Como Paciente, quiero poder iniciar sesión con mi usuario y contraseña para acceder a mi información personal y de salud dentro de la aplicación.                                                 | 8                       |
| 5                | Registrar información personal del paciente                | Como profesional de la salud mental, quiero registrar la información personal del paciente para tener una referencia detallada y precisa de sus datos básicos en cada consulta.                   | 5                       |
| 6                | Registrar estado de ánimo                                  | Como paciente, quiero comunicarle a mi profesional mi estado de ánimo para ver mi estado actual.                                                                                                  | 5                       |
| 7                | Registrar funciones biológicas                             | Como paciente, quiero registrar la calidad de mis funciones biológicas para que mi profesional conozca mi estado actual de salud.                                                                 | 5                       |
| 8                | Registrar mi estado de salud diario en la aplicación móvil | Como Paciente, quiero poder registrar mi estado de salud diario (Mood, Hunger, Hydration, Sleep Quality, Energy Level) para llevar un seguimiento de mi bienestar.                                | 5                       |
| 9                | Consultar Mi Lista de Medicamentos en la aplicación móvil  | Como Paciente, quiero poder ver la lista de medicamentos que tengo asignados para conocer el nombre, el motivo, la frecuencia (Intervalo) y la Cantidad de cada uno.                              | 5                       |
| 10               | Visualizar el estado actual de ánimo del paciente          | Como profesional de la salud mental, quiero visualizar el estado de ánimo actual del paciente para evaluar su condición emocional.                                                                | 3                       |
| 11               | Registrar de medicamentos del paciente                     | Como profesional de la salud mental, quiero registrar los medicamentos del paciente para seguir adecuadamente su tratamiento farmacológico.                                                       | 3                       |
| 12               | Ver medicamentos                                           | Como paciente quiero poder ver los medicamentos que mi profesional de salud mental ha asignado para poder estar pendiente de cuales consumir.                                                     | 3                       |
| 13               | Visualizar información de perfil en la aplicación móvil    | Como Paciente, quiero poder ver mi información personal (Correo Electrónico, Dirección, ID de Paciente y ID de Profesional) en la sección "Mi Perfil" para confirmar que mis datos son correctos. | 3                       |
| 14               | Ver próximas citas en la aplicación móvil                  | Como Paciente, quiero poder ver una lista de mis citas médicas próximas con sus detalles (fecha, hora, duración y profesional ID) para estar informado y planificar mi asistencia.                | 3                       |
| 15               | Crear citas                                                | Como profesional de la salud quiero agendar las citas de mis pacientes.                                                                                                                           | 2                       |
| 16               | Ver citas médicas                                          | Como paciente quiero poder ver las citas médicas programadas para poder saber que días ir al consultorio del profesional de salud mental.                                                         | 2                       |
| 17               | Cerrar sesión en la aplicación móvil                       | Como Paciente, quiero poder cerrar mi sesión de forma segura desde la pantalla de Mi Perfil para proteger mi privacidad.                                                                          | 2                       |
| 18               | Encontrar información del propósito de la aplicación       | Como visitante de la Landing Page, quiero encontrar fácilmente la información que explique el propósito de la aplicación para comprender cómo puede ser útil para mí.                             | 1                       |
| 19               | Visualizar imágenes y gráficos relevantes                  | Como visitante de la Landing Page, quiero que las imágenes y gráficos sean claros y visualmente atractivos para captar mi interés y comprender mejor el contenido.                                | 1                       |
| 20               | Visualizar tipografía cómoda y agradable estéticamente     | Como visitante de la Landing Page, quiero que la tipografía de la misma sea legible y estéticamente agradable para facilitar la lectura y la navegación.                                          | 1                       |

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams

En esta sección se puede apreciar el diagrama de contexto C4 que muestra el panorama general de trabajo del proyecto.

<img width="1529" height="2700" alt="image" src="https://github.com/user-attachments/assets/cdd027df-31c8-4496-9320-dfe72cff0676" />


#### 2.5.3.2. Software Architecture Container Level Diagrams

Aquí podemos apreciar el diagrama de contenedores del producto realizado

<img width="2709" height="3891" alt="image" src="https://github.com/user-attachments/assets/610a59b9-70d0-4352-9536-57c00714d5c7" />


#### 2.5.3.3. Software Architecture Deployment Diagrams


## 2.6. Tactical-Level Domain-Driven Design

### 2.6.1. Bounded Context: iam
#### 2.6.1.1. Domain Layer
- Aggregate: Account
    - Propósito: Representar la cuenta de usuario del sistema (credenciales y rol) y su asociación a un perfil.
    - Atributos relevantes: userName (String, único), password (String), role (Roles enum), profileId (ProfileId embedded).
    - Comportamientos principales: constructores a partir de SignUpCommand, validación de roles, getRoleInString(), getAllRoles().
- Value Objects / Enums:
    - Roles: enum que define roles del sistema (ej. ROLE_PROFESSIONAL, ROLE_PATIENT).
    - ProfileId: identificador embebido que referencia un perfil asociado.
- Commands y Queries relevantes:
    - SignUpCommand, SignInCommand, SeedRolesCommand.
    - GetAccountByIdQuery.
- Domain Services / Interfaces:
    - AccountCommandService: interfaz para operaciones de comando sobre cuentas (registro, autenticación delegada a infra/app).
    - AccountQueryService: interfaz para consultas de cuenta.

#### 2.6.1.2. Interface Layer
- Controllers / REST:
    - AuthenticationController: expone endpoints de autenticación (signin, signup).
    - AccountsController: endpoints para operaciones CRUD/consulta de cuentas.
- Resources / DTOs:
    - SignUpResource, SignInResource, AuthenticatedAccountResource, AccountResource.
- Transform/Assembler:
    - SignUpCommandFromResourceAssembler, SignInCommandFromResourceAssembler, AuthenticatedAccountResourceFromEntityAssembler, AccountResourceFromEntityAssembler.
- ACL / Facade:
    - IamContextFacade: fachada de alto nivel para integraciones con el contexto IAM.

#### 2.6.1.3. Application Layer
- Implementaciones de servicios de aplicación:
    - AccountCommandServiceImpl: implementa la lógica de comandos (registro, manejo de contraseñas delegando a servicios de hashing, creación de entidades).
    - AccountQueryServiceImpl: implementa consultas y transformación a resources/DTOs.
- Outbound services (interfaces usadas por la capa de aplicación):
    - TokenService: abstracción para generación/validación de tokens.
    - HashingService: abstracción para hashing de contraseñas.

#### 2.6.1.4. Infrastructure Layer
- Persistencia:
    - AccountRepository (JPA): implementación de repositorio para la entidad Account.
- Tokens / Hashing:
    - TokenServiceImpl, BearerTokenService: implementación de generación y manejo de tokens JWT.
    - BCryptHashingService, HashingServiceImpl: implementación de hashing de contraseñas usando bcrypt.
- Seguridad / Authorization pipeline:
    - UserDetailsServiceImpl: integración con Spring Security para cargar detalles del usuario.
    - UserDetailsImpl, UsernamePasswordAuthenticationTokenBuilder: modelado de la información de seguridad para autenticación.
    - BearerAuthorizationRequestFilter: filtro que extrae/valida tokens en requests.
    - UnauthorizedRequestHandlerEntryPoint: manejador para peticiones no autorizadas.
    - WebSecurityConfiguration: configuración de seguridad HTTP y filtros.

---

### 2.6.2. Bounded Context: profiles
#### 2.6.2.1. Domain Layer
- Aggregates:
    - ProfessionalProfile
        - Propósito: Representar el perfil profesional (datos identificadores, contacto, datos profesionales relevantes).
        - Atributos típicos: identificador propio, datos de contacto (PersonName, Email), dirección (StreetAddress), referencia a cuenta (AccountId).
    - PatientProfile
        - Propósito: Representar el perfil de paciente con sus datos personales y de contacto.
        - Atributos típicos: identificador, PersonName, Email, StreetAddress, referencia a cuenta (AccountId).
- Value Objects:
    - PersonName: nombre y apellidos como VO.
    - StreetAddress: dirección compuesta como VO.
    - Email: VO para dirección de correo.
    - AccountId: VO que referencia la cuenta asociada.
- Commands y Queries relevantes (evitando referencias a historial clínico):
    - CreateProfessionalProfileCommand, CreatePatientProfileCommand.
    - CheckProfessionalProfileByIdCommand, CheckPatientProfileByIdCommand.
    - GetProfessionalProfileByIdQuery, GetProfessionalProfileByAccountIdQuery, GetPatientProfileByIdQuery, GetPatientProfileByAccountIdQuery, GetPatientProfileByProfessionalIdQuery, GetAllPatientProfilesQuery.
- Domain Services / Interfaces:
    - ProfessionalProfileCommandService / ProfessionalProfileQueryService.
    - PatientProfileCommandService / PatientProfileQueryService.

#### 2.6.2.2. Interface Layer
- Controllers / REST:
    - ProfessionalProfileController: endpoints para creación y consulta de perfiles profesionales.
    - PatientProfileController: endpoints para creación y consulta de perfiles de pacientes.
- Resources / DTOs:
    - ProfileResource, CreateProfessionalProfileResource, CreatePatientProfileResource.
- Transform / Assembler:
    - ProfileResourceFromEntityAssembler, CreateProfessionalProfileCommandFromResourceAssembler, CreatePatientProfileCommandFromResourceAssembler.
- ACL / Facade:
    - ProfilesContextFacade (y su implementación ProfilesContextFacadeImpl): fachada para exposiciones del contexto profiles hacia otras zonas de la aplicación.

#### 2.6.2.3. Application Layer
- Implementaciones de servicios de aplicación:
    - ProfessionalProfileCommandServiceImpl, ProfessionalProfileQueryServiceImpl.
    - PatientProfileCommandServiceImpl, PatientProfileQueryServiceImpl.
- Outbound services (interfaces usadas por la capa de aplicación):
    - ExternalAccountService: integración con el contexto de cuentas (IAM) para validar o recuperar información de cuenta cuando se crea o consulta un perfil.

#### 2.6.2.4. Infrastructure Layer
- Persistencia:
    - ProfessionalProfileRepository (JPA): repositorio para persistir perfiles profesionales.
    - PatientProfileRepository (JPA): repositorio para persistir perfiles de pacientes.
- Otras implementaciones de infraestructura:
    - Implementaciones de los servicios outbound (por ejemplo, adaptadores que consumen APIs de otros contextos como ExternalAccountService).

---

### 2.6.3. Bounded Context: appointment and administration
#### 2.6.3.1. Domain Layer
- Aggregates / Entities:
    - Appointment
        - Propósito: Representar una cita programada entre un profesional y un paciente (fecha, hora, estado, referencias a perfiles).
        - Atributos típicos: appointmentId, professionalId (referencia a perfil profesional), patientId (referencia a perfil de paciente), scheduledAt (fecha/hora), status (pendiente, confirmado, cancelado), notes (opcional).
    - AdministrationRecord (si aplica)
        - Propósito: Representar registros administrativos asociados a citas o a la gestión de la agenda (facturación básica, estado de atención, metadata administrativa).
        - Atributos típicos: id, appointmentId, type, metadata.
- Value Objects:
    - AppointmentId, TimeSlot, Status (enum) y otros VO para encapsular reglas de validación de fechas y estados.
- Commands y Queries relevantes:
    - Commands: CreateAppointmentCommand, UpdateAppointmentCommand, CancelAppointmentCommand, ConfirmAppointmentCommand.
    - Queries: GetAppointmentByIdQuery, GetAppointmentsByProfessionalQuery, GetAppointmentsByPatientQuery, GetAvailableTimeSlotsQuery.
- Domain Services / Policies:
    - AppointmentSchedulingService (reglas para validar solapamientos, disponibilidad de profesionales, ventanas de tiempo).
    - NotificationsHelper (lógica de alto nivel para determinar notificaciones a enviar; la entrega se delega a infra).

#### 2.6.3.2. Interface Layer
- Controllers / REST:
    - AppointmentsController: endpoints para crear, actualizar, cancelar, confirmar y listar citas.
    - AdministrationController: endpoints administrativos relacionados con gestión de agendas y registros administrativos.
- Resources / DTOs:
    - AppointmentResource, CreateAppointmentResource, UpdateAppointmentResource, TimeSlotResource.
- Transform / Assembler:
    - Assemblers que convierten entre recursos HTTP y comandos/queries de aplicación.
- ACL / Facade:
    - AppointmentContextFacade: fachada para exponer capacidades de citas a otros bounded contexts.

#### 2.6.3.3. Application Layer
- Command / Query Handlers:
    - Implementaciones que gestionan CreateAppointmentCommand, UpdateAppointmentCommand, CancelAppointmentCommand y consultas para recuperar agendas y citas.
- Application Services / Use Cases:
    - AppointmentCommandServiceImpl: orquesta creación/actualización/cancelación, valida mediante AppointmentSchedulingService y delega persistencia.
    - AppointmentQueryServiceImpl: implementa consultas y construye resources/DTOs.
- Outbound services (interfaces):
    - ExternalNotificationService: interfaz para envío de notificaciones (email, SMS, push) usada por la capa de aplicación.
    - ExternalCalendarService: interfaz opcional para sincronizar con calendarios externos.

#### 2.6.3.4. Infrastructure Layer
- Persistencia:
    - AppointmentRepository (JPA): repositorio para persistir citas y registros administrativos.
- Integraciones:
    - Implementación de ExternalNotificationService (adaptadores a sistemas de mensajería o SMTP).
    - Implementación de ExternalCalendarService (adaptador para sincronización con calendarios externos si aplica).
- Infra de soporte:
    - Jobs / Scheduled Tasks: procesos para limpiar citas antiguas, enviar recordatorios, y reconciliar estados.
    - Mecanismos de locking o coordinación para evitar solapamientos en la programación (p. ej. transacciones, filas optimistas/pesimistas según necesidad).

---

### 2.6.4. Bounded Context: medication
#### 2.6.4.1. Domain Layer
- Aggregates / Entities:
    - Medication
        - Propósito: Representar un medicamento del catálogo (identificación, nombre comercial y genérico, presentaciones y concentraciones).
        - Atributos típicos: medicationId, name, genericName, forms (tabletas, jarabe, inyección), strength, manufacturer.
    - Prescription
        - Propósito: Representar una prescripción asociada a un paciente y a un profesional, con instrucciones de dosificación y estado.
        - Atributos típicos: prescriptionId, medicationId, patientId, professionalId, dosage (VO), frequency (VO), duration, instructions, status.
    - AdministrationRecord
        - Propósito: Representar registros de administración de dosis (fecha, dosis, quien administró), útil para seguimiento operativo.
- Value Objects:
    - Dosage: cantidad y unidad.
    - Frequency: periodicidad (ej. 3 veces al día) y reglas asociadas.
    - MedicationId, PrescriptionId.
- Commands y Queries relevantes:
    - Commands: CreateMedicationCommand, UpdateMedicationCommand, CreatePrescriptionCommand, UpdatePrescriptionCommand, DiscontinuePrescriptionCommand, RecordAdministrationCommand.
    - Queries: GetMedicationByIdQuery, SearchMedicationsQuery, GetPrescriptionsByPatientQuery, GetPrescriptionByIdQuery.
- Domain Services / Policies:
    - PrescriptionValidationService (reglas de interacción, comprobaciones de contraindicaciones delegadas a servicios externos).
    - DoseSchedulingService (calcula horarios y ventanas de administración según frequency/dosage).

#### 2.6.4.2. Interface Layer
- Controllers / REST:
    - MedicationController: endpoints para gestión de catálogo de medicamentos.
    - PrescriptionController: endpoints para crear/actualizar/cancelar prescripciones y listar prescripciones por paciente o profesional.
- Resources / DTOs:
    - MedicationResource, CreateMedicationResource, PrescriptionResource, CreatePrescriptionResource, AdministrationRecordResource.
- Transform / Assembler:
    - Assemblers que convierten entre recursos HTTP y comandos/queries de aplicación.
- ACL / Facade:
    - MedicationContextFacade: fachada para exponer servicios del contexto medication a otros bounded contexts.

#### 2.6.4.3. Application Layer
- Command / Query Handlers:
    - Implementaciones para CreateMedicationCommand, CreatePrescriptionCommand, RecordAdministrationCommand y consultas relacionadas.
- Application Services / Use Cases:
    - MedicationCommandServiceImpl, MedicationQueryServiceImpl.
    - PrescriptionCommandServiceImpl: orquesta validaciones, llamadas a servicios de interacción y persistencia.
- Outbound services (interfaces):
    - ExternalMedicationInteractionService: consulta interacciones/contraindicaciones en bases externas.
    - ExternalPharmacyService: integración para envío o verificación de stock en farmacias.

#### 2.6.4.4. Infrastructure Layer
- Persistencia:
    - MedicationRepository, PrescriptionRepository, AdministrationRecordRepository (JPA): persistencia de catálogo, prescripciones y registros.
- Integraciones:
    - Adaptadores para ExternalMedicationInteractionService y ExternalPharmacyService.
- Soporte operativo:
    - Tareas programadas para reconciliar stock, caducidades y para enviar recordatorios de cumplimiento de dosis si aplica.

---

### 2.6.5. Bounded Context: patientreport
#### 2.6.5.1. Domain Layer
- Aggregates / Entities:
    - PatientReport
        - Propósito: Representar informes generados para un paciente (contenido estructurado, metadatos, estado de revisión y publicación).
        - Atributos típicos: reportId, patientId, authorProfessionalId, title, content (estructura o blob), createdAt, status (draft, reviewed, published).
    - ReportTemplate
        - Propósito: Plantillas reutilizables para generación de informes con campos estructurados.
        - Atributos típicos: templateId, name, structureDefinition.
- Value Objects:
    - ReportId, ReportStatus, Metadata (fecha, tags, confidencialidad).
- Commands y Queries relevantes:
    - Commands: CreateReportCommand, UpdateReportCommand, ReviewReportCommand, PublishReportCommand.
    - Queries: GetReportByIdQuery, GetReportsByPatientQuery, GetReportsByAuthorQuery.
- Domain Services / Policies:
    - ReportGenerationService (lógica para ensamblar contenido desde templates y datos aportados).
    - ReportAccessControlService (políticas de visibilidad y acceso según roles y permisos).

#### 2.6.5.2. Interface Layer
- Controllers / REST:
    - PatientReportController: endpoints para crear, editar, revisar, publicar y listar informes.
- Resources / DTOs:
    - PatientReportResource, CreateReportResource, ReportTemplateResource.
- Transform / Assembler:
    - Assemblers para convertir entre entidades/domain commands y recursos HTTP.
- ACL / Facade:
    - PatientReportContextFacade: fachada para exponer operaciones de informes a otros contextos.

#### 2.6.5.3. Application Layer
- Command / Query Handlers:
    - Handlers que procesan CreateReportCommand, ReviewReportCommand, PublishReportCommand y consultas para recuperación de informes.
- Application Services / Use Cases:
    - PatientReportCommandServiceImpl, PatientReportQueryServiceImpl.
- Outbound services (interfaces):
    - ExternalStorageService: interfaz para almacenar blobs (PDFs, anexos) en almacenamiento externo.
    - ExternalNotificationService: notificar publicación o cambios de estado a interesados.

#### 2.6.5.4. Infrastructure Layer
- Persistencia:
    - PatientReportRepository (JPA): persistencia de metadatos de informes.
- Integraciones:
    - Adaptadores para ExternalStorageService (S3, Filesystem) y para servicios de notificaciones.
- Soporte operativo:
    - Jobs para generación batch de reportes, exportación y limpieza de archivos temporales.

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se ve el diagrama de componentes del Bounded Context IAM, en este caso, llamado Identity and Access.

<img width="1210" height="3100" alt="image" src="https://github.com/user-attachments/assets/ac193c02-7dff-4f9a-bdcd-6fb8a780eb09" />

#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
#### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
#### 2.6.1.6.2. Bounded Context Database Design Diagram

#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se ve el diagrama de componentes del Bounded Context Profiles, en este llamado, User Management

<img width="1640" height="3700" alt="image" src="https://github.com/user-attachments/assets/b6b708c1-4120-4d00-b3f4-54fbfef39a82" />


#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se muestra el diagrama de clases a nivel de Profiles

<img width="900" height="655" alt="image" src="https://github.com/user-attachments/assets/91797e6a-8aa0-4d70-ae64-b6a85b93018d" />


#### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams
#### 2.6.2.6.2. Bounded Context Database Design Diagram

#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se ve el diagrama de componentes del Bounded Context Appointment and Administration

<img width="2278" height="4991" alt="image" src="https://github.com/user-attachments/assets/319932db-c794-42dd-8191-fb5e5d526dba" />


#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams
#### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams
#### 2.6.3.6.2. Bounded Context Database Design Diagram

#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se ve el diagrama de componentes del Bounded Context Medication

<img width="1640" height="3700" alt="image" src="https://github.com/user-attachments/assets/d9615687-461d-46e1-8d7b-14a3d90fa84b" />


#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagram

En esta sección se muestra el diagrama de clases a nivel de Medication

<img width="588" height="730" alt="image" src="https://github.com/user-attachments/assets/60e672cb-a146-4409-8d36-c15688998ece" />

#### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams
#### 2.6.4.6.2. Bounded Context Database Design Diagram

#### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se ve el diagrama de componentes del Bounded Context Patient Report, en este caso llamado Tracking

<img width="994" height="3700" alt="image" src="https://github.com/user-attachments/assets/e848ebc1-ebad-4801-b920-7f528a9e0cdf" />

#### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams
#### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams
#### 2.6.5.6.2. Bounded Context Database Design Diagram
