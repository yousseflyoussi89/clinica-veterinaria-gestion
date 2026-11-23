 Sistema de gestión de una clínica veterinaria

Proyecto académico para practicar la coordinación, comunicación y colaboración en un proyecto software usando GitHub (Issues, Projects y Discussions).

## Alcance funcional

| Módulo | Descripción |
|---|---|
| Clientes | Alta, consulta, modificación y baja de los propietarios de las mascotas. |
| Mascotas | Registro de mascotas asociadas a un cliente (especie, raza, fecha de nacimiento, chip). |
| Citas | Agenda de citas por veterinario, con control de solapamientos y estados (programada, atendida, cancelada). |
| Historiales médicos | Registro de consultas, diagnósticos, tratamientos y vacunas de cada mascota. |
| Usuarios y permisos | Acceso para recepción, veterinarios y administración. |

## Organización del equipo

El equipo está formado por una sola persona, que asume todos los roles del proyecto:

| Rol | Responsabilidades |
|---|---|
| Jefe de proyecto | Planificación, tablero, seguimiento y documentación. |
| Analista / arquitecto | Requisitos, modelo de datos y decisiones técnicas. |
| Desarrollador backend | Lógica de negocio, API y base de datos. |
| Desarrollador frontend | Interfaz de usuario. |
| Tester | Plan y ejecución de pruebas. |

Cada Issue lleva una etiqueta `rol:` que indica qué rol la asume, y una etiqueta `prioridad:`.

## Cómo se trabaja

- **Tareas:** cada actividad es una Issue con descripción, prioridad, rol responsable y criterios de aceptación.
- **Tablero:** GitHub Projects con las columnas *Pendiente*, *En desarrollo* y *Finalizado*.
- **Dependencias y bloqueos:** se registran con las relaciones *blocked by* de GitHub, la etiqueta `bloqueado` y comentarios en la Issue.
- **Decisiones:** se debaten en GitHub Discussions, con alternativas y la justificación de la opción elegida.
