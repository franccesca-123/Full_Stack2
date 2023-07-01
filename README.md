# Full_Stack2
Sistema de Gestión de Clínicas - Realizado usando C#, ASP.net

“Sistema de Gestión de Clínicas” con un esquema de base de datos, realizado como proyecto final para el curso Full Stack. El mismo está basado en la Arquitectura de 3 Capas.

Tecnologías Utilizadas:
Para el Frontend: HTML, CSS, Bootstrap, JavaScript

Para el Backend: C#, ASP.NET

Para la Base de Datos: SQL

Requisitos previos:
Microsoft Visual Studio
Microsoft SQL Server Express
Microsoft SQL Server Management Studio (SSMS)
Interfaz
Algunas capturas de pantalla de las páginas.

Página de Registro


Tomar una Cita


Citas Actuales


Buscar Personal


Funcionalidades Implementadas:
Nuestro proyecto gira en torno a tres clases principales de usuarios. Las características de cada clase se enumeran a continuación:

1. Paciente:
1. Inicio del Paciente: el paciente puede ver su perfil.
2. Cita Actual: el paciente puede ver si tiene alguna cita pendiente o aprobada con un médico.
3. Historial de Facturas: el paciente puede ver el historial de facturas de las citas que se han completado.
4. Historial de Tratamientos: el paciente puede ver el historial de tratamientos de las citas que se han completado.
5. Tomar Cita: el paciente puede ver todos los departamentos y luego seleccionar uno. A continuación, se muestran los médicos de ese departamento. Luego, el paciente selecciona un médico y se muestra el perfil del médico junto con un botón "tomar cita". Cuando se hace clic en el botón, se muestran los horarios disponibles de ese médico en particular. El paciente selecciona un horario libre de su elección y luego envía una solicitud para ese horario libre al médico. El médico luego lo aprueba/rechaza.
6. Notificaciones: en esta pestaña, se muestra una notificación cada vez que el médico acepta/rechaza la cita solicitada.
7. Comentarios: después de que se completa una cita, el paciente puede dar su opinión sobre esa cita calificándola del 1 al 5.
8. Un paciente puede solicitar solo una cita a la vez y no se le permitirá tomar más de una cita hasta que se haya completado la última cita.

2. Médico:
1. Perfil del Médico: el médico puede ver su propio perfil.
2. Citas Pendientes: el médico puede ver todas las citas pendientes asociadas a su ID de médico.
3. Citas de Hoy: se mostrarán las citas del día actual. El médico luego puede seleccionar/rechazar cualquier cita de ese día.
4. Actualización del Historial: puede actualizar la prescripción, enfermedad y progreso del paciente.
5. Generar Factura: luego generará la factura.
6. Historial del Paciente: el médico podrá ver el historial de tratamientos de todos sus pacientes tratados.

3. Administrador:
1. Inicio del Administrador: el administrador puede ver estadísticas de la clínica, que incluyen citas semanales, ingresos de la clinica
