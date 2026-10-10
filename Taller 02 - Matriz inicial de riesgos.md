### Matriz inicial de riesgos
### Integrantes
- Sebastian Meneses Sierra

### Caso y contexto actualizado
La Biblioteca de la Institución Universitaria Pascual Bravo utiliza un sistema de gestión bibliotecaria para administrar préstamos de libros físicos, acceso a recursos digitales y datos de estudiantes y docentes. Además, dispone de equipos de cómputo para uso académico. El análisis se centra en el sistema de gestión bibliotecaria, los datos de los usuarios y los procesos de control de acceso a los recursos digitales y físicos.

### Supuestos
- No se tuvo acceso directo a la documentación interna de la universidad.
- Se asume que el sistema bibliotecario almacena información personal de estudiantes y docentes.
- Se asume que existen cuentas de usuario para personal administrativo y bibliotecarios.
- No se pudo verificar la existencia de controles formales de revisión de accesos o respaldos.
- Los controles actuales se describen como supuestos razonables basados en la información disponible.

### Activos y procesos identificados
- Base de datos de usuarios (estudiantes y docentes).
- Sistema de gestión bibliotecaria.
- Recursos digitales (libros electrónicos y bases de datos).
- Equipos de cómputo de la biblioteca.
- Proceso de gestión de cuentas y permisos.
- Respaldos de información del sistema.

### Riesgo R-01

Activo o proceso: Base de datos de usuarios

Amenaza: Acceso no autorizado por terceros.

Vulnerabilidad: Contraseñas débiles o ausencia de políticas de complejidad.

Riesgo: Un tercero podría acceder a datos personales de estudiantes y docentes utilizando credenciales vulnerables, provocando fuga de información y afectando la privacidad de los usuarios.

Probabilidad: 4 (Probable)

Impacto: 5 (Muy alto)

Nivel de riesgo: 20

Control actual o evidencia: No se encontró evidencia de una política formal de contraseñas.

Control propuesto: Implementar contraseñas seguras, autenticación multifactor para cuentas administrativas y revisión trimestral de usuarios.

Justificación: La información personal es uno de los activos más sensibles del sistema bibliotecario y su exposición puede generar consecuencias legales y reputacionales.

### Riesgo R-02

Activo o proceso: Gestión de cuentas y permisos.

Amenaza: Uso indebido de cuentas de excolaboradores.

Vulnerabilidad: No existe una revisión periódica de accesos cuando una persona cambia de cargo o termina su vínculo laboral.

Riesgo: Un exfuncionario podría ingresar al sistema bibliotecario porque su cuenta sigue activa, permitiendo consultas o modificaciones no autorizadas.

Probabilidad: 4 (Probable)

Impacto: 4 (Alto)

Nivel de riesgo: 16

Control actual o evidencia: No se dispone de evidencia de revisiones formales de accesos.

Control propuesto: Desactivar automáticamente las cuentas al finalizar contratos y realizar revisiones mensuales de usuarios activos.

Justificación: La permanencia de cuentas activas aumenta significativamente la posibilidad de accesos indebidos.

### Riesgo R-03

Activo o proceso: Sistema de gestión bibliotecaria.

Amenaza: Fallas técnicas o caída del servidor.

Vulnerabilidad: Ausencia de un plan documentado de continuidad y recuperación.

Riesgo: La indisponibilidad del sistema podría impedir la gestión de préstamos, devoluciones y consultas bibliográficas, afectando las actividades académicas.

Probabilidad: 3 (Posible)

Impacto: 5 (Muy alto)

Nivel de riesgo: 15

Control actual o evidencia: No se evidenció documentación sobre continuidad operativa.

Control propuesto: Implementar un plan de continuidad de negocio, realizar respaldos periódicos y ejecutar pruebas semestrales de recuperación.

Justificación: El sistema soporta procesos críticos para estudiantes y docentes.

### Riesgo R-04

Activo o proceso: Respaldos de información.

Amenaza: Acceso indebido a las copias de seguridad.

Vulnerabilidad: Los respaldos podrían almacenarse sin controles adecuados de acceso.

Riesgo: Información personal y registros de préstamos podrían quedar expuestos si una persona no autorizada accede a los respaldos.

Probabilidad: 3 (Posible)

Impacto: 5 (Muy alto)

Nivel de riesgo: 15

Control actual o evidencia: No se encontró evidencia sobre controles de acceso a respaldos.

Control propuesto: Limitar el acceso a los respaldos mediante roles autorizados y revisar los permisos cada trimestre.

Justificación: Los respaldos contienen información completa del sistema y representan un objetivo atractivo para accesos no autorizados.

### Riesgo R-05

Activo o proceso: Equipos de cómputo de la biblioteca.

Amenaza: Instalación de software malicioso por usuarios.

Vulnerabilidad: Falta de restricciones de instalación y monitoreo sobre los equipos.

Riesgo: Un usuario podría instalar malware en un equipo institucional, afectando la disponibilidad de los servicios y comprometiendo información de la biblioteca.

Probabilidad: 4 (Probable)

Impacto: 4 (Alto)

Nivel de riesgo: 16

Control actual o evidencia: En el contexto del caso se mencionan manipulaciones indebidas de equipos por parte de usuarios.

Control propuesto: Configurar cuentas de usuario restringidas, antivirus administrado centralmente y monitoreo de eventos en los equipos.

Justificación: Los equipos son utilizados por múltiples usuarios diariamente, aumentando la probabilidad de incidentes.

### Riesgo R-06

Activo o proceso: Recursos digitales y bases de datos electrónicas.

Amenaza: Robo o compartición de credenciales.

Vulnerabilidad: Ausencia de monitoreo de accesos y actividad sospechosa.

Riesgo: Usuarios no autorizados podrían acceder a recursos digitales mediante credenciales compartidas, generando incumplimientos de licenciamiento y pérdida de control del servicio.

Probabilidad: 3 (Posible)

Impacto: 4 (Alto)

Nivel de riesgo: 12

Control actual o evidencia: No se encontró evidencia de monitoreo de sesiones o accesos.

Control propuesto: Registrar accesos, generar alertas ante comportamientos anómalos y realizar campañas de concienciación sobre el uso de credenciales.

Justificación: Los recursos digitales son esenciales para las actividades académicas y deben utilizarse únicamente por usuarios autorizados.

### Priorización de riesgos
R-01: Acceso no autorizado a datos personales → Nivel 20.
R-02: Cuentas activas de excolaboradores → Nivel 16.
R-05: Malware en equipos de biblioteca → Nivel 16.
R-03: Indisponibilidad del sistema bibliotecario → Nivel 15.
R-04: Exposición de respaldos → Nivel 15.
R-06: Uso indebido de recursos digitales → Nivel 12
