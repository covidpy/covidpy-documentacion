# COVID-19 PY App/Plataforma
Lista de deseos (wishlist), cosas por hacer (todo), ideas, oportunidades y desafíos relacionados con la plataforma para el acompañamiento de pacientes Covid-19.



### Mejorar la documentación
Verificar, mejorar, actualizar y redactar la documentación de cada proyecto en el repositorio.

### Creación de ayuda para los usuarios finales
Crear contenido que ayude al entendimiento en el uso de la App para pacientes y personal de blanco.

### Creación de contenido para uso interno y externo
Contenidos para el personal de blanco, tales como publicidad de la plataforma.
Contenidos para social media.
Crear artículos en inglés del caso de éxito de Paraguay.
Creación y/o traducción de contenido ya hecho. Por ejemplo gráficos en guaraní y/o en inglés.
Crear nuevos diseños y textos sobre el Covid-19. Animaciones, infografías para social media, etc.
Crear preguntas frecuentes de la plataforma.
Crear documentaciones y ayudas.
Crear nuevos blog post sobre las novedades de la plataforma.

### Notificaciones Push
Recordatorio automático a los usuarios para que reporten periódicamente su estado de salud y localización mediante notificaciones push disparadas desde el backend.

### Contact tracing para ciudadanos
Investigar y ver la factibilidad de incluir dentro del proyecto.

### Autoreporte de salud abierto
Actualmente la App está orientada exclusivamente a las personas que están siendo acompañadas por el MSPBS, por ejemplo las que tienen caso positivo, sospechoso, etc. Considerar la posibilidad de abrir la App para que cualquier usuario pueda completar su reporte de salud de manera voluntaria y además recibir notificaciones e información personalizada.

### Registro de visitas a lugares (check-in)
Los locales comerciales registran en cuadernos de forma manual las visitas. Analizar incluir en el proyecto la posibilidad de tener esos registros de manera digital, segura y anónima (relacionado con contact tracing).

### Incluir funciones o modos cuando el paciente ya está internado
Si el paciente ya está internado, ¿hará igual el autoreporte? ¿agregar una opción para especificar? ¿la App sería contextual?

### Agregar botón de comunidad en la instancia de Discourse del MSPBS
En caso de que se quiera tener un lugar donde las personas puedan compartir conocimientos, tener respuestas a dudas y tener participación e inteligencia colectiva.

### Enviar por email a los usuarios su resumen de estado de salud y un recordatorio de que reporten
Agregar la funcionalidad en el backend para que automáticamente los usuarios reciban un resumen de su evolución de su estado de salud, recibiendo además información que podría ser de su interés con base en su estado y fomentando a la vez el reporte constante de cada paciente.

### Enviar por email al personal de blanco
Agregar la funcionalidad en el backend para que automáticamente el personal de blanco reciba un email y/o notificación sobre un nuevo caso positivo, sospechoso o un reporte de estado de salud delicado nuevo.

### Mejoras en la UX/UI & feedback
Realizar pruebas A/B, propuestas y experimentos sobre la experiencia de usuario e interfaz gráfica de la App para que sea más accesible, cómoda y fácil de usar. Incluir nuevos mecanismos de recolección de datos de uso para recolectar feedback y una sección en la App para que las personas puedan reportar cada tanto sugerencias, mejoras, etc.
Capacidad para más idiomas.

### Testing de ciberseguridad y estrés
Realizar pruebas de vulnerabilidades que pueda tener la plataforma y reportar errores que puedan suceder debido a estrés (datos masivos, límites, etc).

### Incluir videollamadas con el equipo del 154 directamente
Permitir que el usuario pueda tener un contacto visual y auditivo con el equipo del 154, además de enviar su ubicación en tiempo real.
Probar integrar con la plataforma para video conferencia, Jitsi, etc.
Permitir que cuando una persona llama al 154, esta pueda recibir un link que le habilite una video llamada con un operador o médico.
Integrar con la plataforma para poder tener cruzamiento de la ubicación de la persona (pedir mediante el browser) y un form para completar mientras el operador o médico habla con la persona.
Tablero y analítica de llamadas, tales como mapa de ubicaciones, estados completados de los forms, etc.

### Creación de nuevas API’s
Permitir el uso de servicios y accesos a datos que podrían ser de utilidad para otros desarrolladores, sistemas y servicios.

### Dashboard público
Desarrollar Dashboard web público de información sobre el uso de la plataforma con datos anonimizados de la plataforma Covid-19.

### Dashboard para el personal de blanco
Mejoras en el Back office para visualización y administración de datos en tiempo real.

### Revisión del código y mejoras
Inspección del código para hacer mejoras en el proyecto, tales como mejorando la eficiencia, legibilidad y siguiendo las buenas prácticas establecidas de desarrollo de software.

### Mejoras en el reporte de salud
Feature para que el usuario de la App pueda subir una foto (selfie) cada vez que envía un reporte.

### Histórico de la evolución del estado de pacientes
Mantener histórico de cambio de estado de los pacientes, crear reportes y mejorar la visualización.

### Mejorar el envío de mensajes personalizados a cada paciente
Verificar el feature y la UX/UI para mejorar la capacidad de que el personal de blanco envíe mensajes por SMS y/o email y/o push a cada paciente y/o grupos de pacientes mediante filtros tales como por estado de salud, fechas, ubicación, etc.
Envío de Mensajes Por Grupo y Personalizado
Envío de Notificaciones de Alerta SMS, Push y Buzón de Mensajes
Integración envio SMS local con failover. 
Actualización del estado de mensajes SMS Enviados. 
Módulo que permite la configuración y envío de mensajes segmentados de acuerdo con el grupo/tipo paciente o individuales.	

### Reporte y gestión de Contactos del Paciente
Mejorar la visualización del grafo de contactos de los pacientes. Visualizar Contactos del Paciente y ABM Nuevos Contactos Cercanos.

### Resultados de Laboratorio
Agregar apartado donde el paciente pueda visualizar su código de vigilancia y Disponibilidad de Resultado de Examen Laboratorial, esto requiere conexión con sistema de
vigilancia, por número de CI, se busca en una vista el código y si hay resultados disponibles, los resultados no serán desplegados en la app ni se almacenarán en la base de datos de la app), si hay resultados disponibles se podría agregar el botón del link de la web del ministerio donde realizar la consulta del resultado.

### Gestión de localización del paciente
Visualizar Último Reporte de Ubicación del Paciente 
Visualizar Histórico de Ubicación del Paciente 
Operador Actualizar la Ubicación del Paciente 
Personas que se movieron de su ubicación 
Lista de Personas que no reportan su ubicación
Marcar Una posición Reportada como “Inválida”

### Gestión de Paciente
Reenviar SMS de Activación de Cuenta
Modificar Número y envio SMS
Modificar Datos Personales Básicos
Registro de pacientes por lotes disponiendo solo ci y teléfono
Registrar ID dado por la base digital de VENOC

### Gestión de alta de Pacientes
Visualizar Pacientes que deben Darse de Alta en X Dia 
Envío de Mensajes al darse de Alta (cambiar diagnóstico a Alta) 
Ajuste de Banner en la APP cuando paciente se da de alta

### Gestión Personal de Salud
ABM de Personal de Salud
Distribuir Pacientes a Operadores de Salud  (solo podrán ver los que tienen asignado) 

### Gestión de exámenes laboratoriales
Registrar Local toma muestra laboratorial (WEB, SMS) 
Actualizar Resultado Examen Laboratorial
Notificación Automática de Disponibilidad Resultado Examen 
Consultar Resultado y  Código Vigilancia 

### Registrar pacientes/casos
Envío de Mensajes y Notificaciones de Acuerdo con el tipo de Ingreso. (Desarrollado)
Registro Automático a partir de la base de Migraciones. (Suspenso)
Registro Automático a partir de Agendamiento al 154. (Desarrollado)
Nuevo Registro – Ingreso Hospitalario (Urgente)

### Reportes gerenciales
Listado General de Usuarios 
Personas que Entraron al País y no se Registraron
Mapa de Calor

### Notificación y mensajes
Ajustes para incorporación de HTML básico en los mensajes.
Agregar campo “Asunto” a los mensajes. 
Botón Navegación entre mensajes.

### Menú General
Inclusión de Analytics, heat maps.

### Notificaciones al usuario
Notificar Existencia Resultado Laboratorial.

### Ingreso hospitalario
Registrar  Ingreso de Paciente a Hospital (Fecha, Hospital)
Registrar Salida de Paciente de Hospital (Fecha)

### Auditoría y seguridad
Visualizar Auditoría de operaciones
Nuevo tipo permiso “Visualizar Datos Clínico Paciente”

### Formulario de ingreso al país
El ciudadano que ingresa al país podrá ingresar a un link específicamente preparado para los viajeros donde podrán completar un formulario de pre-registro para que al momento de hacer su proceso migratorio el personal de migraciones haga efectivo su registro en la app para iniciar su proceso de aislamiento

### Actualización de datos básicos
Utilizar Live Search para Selección Ciudad y Departamento

### Twitter bot (Integración)
Cantidad de personas que usan la plataforma, tales como cantidades de casos por tipo.
Gráficos automáticos de tendencias, etc.
Generar mapas de calor actualizados automáticamente cada cierto tiempo y enviar tweets.

### Integraciones con MailChimp o similares
Crear integraciones con MailChimp y envíe automáticamente un resumen del día a las personas que se suscriban a un newsletter.
Enviar mail automático o notificación en Telegram a un grupo o canal cuando luego de un tiempo ciertos pacientes no reportaron su ubicación y/o estado de salud. Incluir a las autoridades, MSPBS, Policía, etc.
Cada mail ingresado en la App de paciente agregar automáticamente a una BD (lista de contactos) para tener listo en caso de enviar mail de notificaciones. Esa BD de contactos debe estar discriminada por estados de pacientes y actualizada en todo momento.

### Integraciones con Telegram
Crear un Telegram Bot para que automáticamente ponga en la comunidad un resumen al final del día.
Crear un grupo de personal de blanco y/o canal para hacer post automáticos desde la plataforma, incluyendo actualización de datos, protocolos, resúmenes, fechas de tomas de muestra, etc.

### Vista web para pantalla completa en un navegador (Social Wall)
Lo que genera la plataforma y publica en Twitter se puede ver en tiempo real en pantallas.

### Integraciones con Google Spreadsheets
Agregar filas cada vez que hay una actualización de datos en la plataforma, hacer un servicio para conectar.
De esa planilla tomar esos datos e integrar con otros servicios. Por ejemplo, al final del día o de la semana enviar un resumen por mail, integrando con MailChimp por ejemplo. O cada vez que se agrega una nueva línea, actualizar un gráfico (automáticamente) y enviar un Tweet, un mensaje en Telegram, etc.

### Integración con Google Calendar
Mostrar en un calendario en una TV (Pantalla + PC) compartido con el equipo de Vigilancia y los médicos las fechas de tomas de muestras, duración de cuarentena de los pacientes, etc.
Cuando se cambia el estado de un paciente, agregar al calendario compartido.

### Integración con Trello
Tener en un tablero (puede estar en una TV también) una vista sobre los agendamientos. Por ejemplo poner en una columna por defecto los pendientes (to-do) y en otra los realizados.
También en otro tablero o en el mismo poner los pacientes en columnas por estado, los positivos, sospechosos, en cuarentena, etc. A cada tarjeta se le puede además asociar fechas y descripciones.

### Analítica de datos y uso
Google Analytics, Fathom y/o similares sobre el portal y la plataforma.
Deploy y/o desarrollo de mapas de calor de la interacción del usuario.
Heat map de uso en la App.

### Integración con Identidad Electrónica y el Portal Único de Gobierno
Colocar una opción en la plataforma para que los pacientes y/o personal de blanco pueda darse de alta o vincular con su Identidad Electrónica.
Mostrar los beneficios, trámites y servicios que puede acceder la persona con su Identidad Electrónica (carpeta ciudadana) sin salir de su casa.

### Mapa de calor
Feature o App o web que en base a tu ubicación te dice si estás en una zona de mayor peligro. Si es una App puede tener acceso a la ubicación y en caso de que el usuario se mueva, puede enviar notificaciones Push.

### Newsletter y suscripción para ciudadanos
Base de datos de suscriptores
En la App (si es abierta), para permitir que los ciudadanos se puedan suscribir a un boletín de información, tales como actualizaciones de la App, informaciones sobre el Covid-19 oficiales del MSPBS, procedimientos, nuevas líneas de atención, etc.

### Newsletter y suscripción para personal de blanco
Base de datos de médicos interesados
Para permitir que el personal de blanco se pueda suscribir a un boletín de información, tales como procedimientos para el personal sanitario, protocolos nuevos, etc.

### Newsletter y suscripción para voluntarios y colaboradores
Base de datos para gente que quiera ayudar
Para permitir que las personas que quieran colaborar se enteren de las oportunidades, road map, etc.

### Incluir secciones en la plataformas de preguntas frecuentes
Sobre:
El portal
La App de seguimiento
La App y/o módulos de operador

### Incluir link y secciones de información y resultados de investigaciones
Lugar donde se expondrán los resultados hechos por los distintos equipos y comunidades en relación con la plataforma y los datos del MSPBS.
