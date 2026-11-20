# Informe Final de Auditoría y Plan de Acción
### 1. Identificación y resumen ejecutivo
### Integrante
- Sebastian Meneses Sierra

### Caso analizado
Biblioteca de la Institución Universitaria Pascual Bravo.

### Marcos de referencia utilizados
- ISO/IEC 27001
- COBIT
- ITIL

### Riesgo priorizado
### R-01: Acceso no autorizado a datos personales almacenados en la base de datos del sistema bibliotecario.
Durante la matriz inicial de riesgos, este riesgo fue clasificado como el más crítico debido a su alta probabilidad e impacto. Posteriormente se diseñó un plan de auditoría enfocado en evaluar los controles de autenticación y gestión de usuarios asociados a dicho riesgo. Como parte del presente ejercicio académico se documentó una prueba de auditoría utilizando información simulada, debido a que no se cuenta con acceso a información real de la organización.

# 2. Objetivo y alcance
### Objetivo de auditoría
Determinar si las cuentas con acceso al sistema de gestión bibliotecaria operan bajo controles adecuados de autenticación y gestión de credenciales para reducir el riesgo de acceso no autorizado a la información de estudiantes y docentes.

# Alcance
### Proceso evaluado
Gestión de usuarios y control de accesos al sistema bibliotecario.

### Sistema
Sistema de gestión bibliotecaria.

### Población
- Usuarios administrativos.
- Bibliotecarios.
- Registros de acceso.
- Solicitudes de creación y eliminación de cuentas.

### Período evaluado
Ejercicio académico con información simulada.

### Exclusiones
- Infraestructura de red.
- Otros sistemas institucionales.
- Rendimiento de servidores.
- Disponibilidad de aplicaciones externas.

# 3. Criterios y metodología
### Criterios de evaluación
### Criterio 1
Las cuentas de usuario deben administrarse siguiendo procedimientos formales de gestión de accesos.

### Criterio 2
Los permisos asignados deben corresponder a las funciones de cada usuario.

### Criterio 3
Las cuentas asociadas a usuarios retirados deben ser deshabilitadas oportunamente.

### Fuente:
Buenas prácticas de gestión de accesos alineadas con ISO/IEC 27001 y COBIT.

# Procedimiento seleccionado
Se eligió revisar el control relacionado con la desactivación de cuentas asociadas a usuarios retirados.

### ¿Qué control revisamos?
Control de gestión y revocación de accesos.

### ¿Qué debería ocurrir?
Las cuentas de usuarios retirados deben desactivarse inmediatamente después de finalizar su relación con la institución.

### ¿Qué revisamos?
Muestra simulada de cinco cuentas de usuario.

### ¿Cómo lo revisamos?
1. Identificación del estado laboral de cada usuario.
2. Comparación entre el estado laboral y el estado de la cuenta.
3. Identificación de cuentas activas pertenecientes a usuarios retirados.
4. Registro de excepciones encontradas.

### Condición considerada excepción
Una cuenta asociada a un usuario retirado continúa activa.

# 4. Evidencia y resultados de la prueba
### NOTA
Importante: Debido a que se trata de un ejercicio académico y no se dispone de acceso al sistema real de la Biblioteca de la Institución Universitaria Pascual Bravo, la muestra utilizada en esta prueba es completamente simulada y se construyó únicamente con fines educativos. Los resultados no representan el estado real de la organización.

### Muestra evaluada
| Usuario   | Estado laboral | Cuenta activa | Resultado |
|-----------|----------------|---------------|-----------|
| Usuario A | Activo         | Sí            | Conforme  |
| Usuario B | Activo         | Sí            | Conforme  |
| Usuario C | Retirado       | Sí            | Excepción |
| Usuario D | Activo         | Sí            | Conforme  |
| Usuario E | Activo         | Sí            | Conforme  |

### Resultado obtenido
En la muestra simulada de cinco cuentas se identificó una excepción correspondiente al Usuario C, cuya cuenta permanecía activa a pesar de encontrarse en estado de retiro.

Los demás registros evaluados se encontraron conformes con el criterio definido para la prueba.

### Limitaciones de la prueba
- La muestra utilizada es simulada y fue construida únicamente con fines académicos.
- No se tuvo acceso a información real de la organización.
- No fue posible verificar actividad real de las cuentas evaluadas.
- Los resultados obtenidos no permiten inferir el comportamiento de toda la población de usuarios.

Por lo anterior, las conclusiones se limitan exclusivamente a los elementos incluidos en la muestra presentada.

# 5. Hallazgo de auditoría
## Hallazgo H-01: Cuenta activa asociada a un usuario retirado

### Criterio
Las cuentas pertenecientes a usuarios retirados deben ser deshabilitadas oportunamente conforme a los procedimientos de gestión de accesos y las buenas prácticas de administración de identidades.

### Condición
En una muestra simulada de cinco cuentas evaluadas se identificó una cuenta activa correspondiente a un usuario retirado (Usuario C).

### Causa
No fue posible determinar la causa con la evidencia disponible dentro del ejercicio académico.

### Efecto o riesgo
La permanencia de cuentas activas asociadas a usuarios retirados podría permitir accesos no autorizados al sistema bibliotecario y a la información almacenada en él.

### Recomendación
Implementar revisiones periódicas de las cuentas activas y establecer mecanismos de validación que aseguren la desactivación oportuna de usuarios retirados.

### Nivel de prioridad
Alta, debido a que el hallazgo se relaciona con el riesgo R-01 identificado en la matriz de riesgos, referente al acceso no autorizado a datos personales.

# 6. Conclusión
La prueba realizada permitió evaluar parcialmente el control de gestión de accesos definido para mitigar el riesgo R-01 relacionado con el acceso no autorizado a datos personales.

Durante el ejercicio se identificó una excepción dentro de la muestra simulada analizada, correspondiente a una cuenta que permanecía activa después de la desvinculación del usuario.

Sin embargo, debido al tamaño de la muestra y a la naturaleza académica del ejercicio, no es posible afirmar que la situación observada represente el comportamiento de toda la población de usuarios. Las conclusiones se limitan exclusivamente a la evidencia evaluada.

# 7. Plan de acción
### Hallazgo asociado
H-01

### Acción propuesta
Realizar una revisión completa de las cuentas activas del sistema bibliotecario y deshabilitar aquellas asociadas a usuarios retirados.

### Responsable propuesto
Administrador del sistema bibliotecario.

### Prioridad
Alta.

### Plazo propuesto
30 días.

### Evidencia de cierre esperada
- Registro de revisión de cuentas.
- Evidencia de desactivación de usuarios retirados.
- Informe de verificación posterior del control.
- Actualización del procedimiento de gestión de accesos.

# 8. Anexos
## Entregables relacionados
- [Taller 01 - Sesión N°3](./Taller%2001%20-%20Sesion%20N%C2%B03.md)
- [Taller 02 - Matriz inicial de riesgos](./Taller%2002%20-%20Matriz%20inicial%20de%20riesgos.md)
- [Taller - Riesgo priorizado al plan de auditoría](./Taller%20-%20Riesgo%20priorizado%20al%20plan%20de%20auditor%C3%ADa.md)
- [Informe Final de Auditoría y Plan de Acción](./Informe%20Final%20de%20Auditor%C3%ADa%20y%20Plan%20de%20Acci%C3%B3n.md)

## Declaración
Este trabajo corresponde a un ejercicio académico. La evidencia utilizada en la prueba presentada es simulada y se encuentra claramente identificada como tal, siguiendo las instrucciones de la guía del curso. Los resultados obtenidos no representan el estado real de la organización analizada.

