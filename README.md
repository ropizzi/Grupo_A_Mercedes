# P1 · Priorización de postventa Mercedes

**Asignatura:** Algoritmos y Estructuras de Datos.  
**Modalidad:** trabajo en equipo, con un máximo de tres integrantes.

Este repositorio es el espacio de trabajo del equipo durante todo el proyecto. La plantilla proporciona organización e instrucciones; los apartados pendientes deben completarse con vuestras decisiones, implementación y evidencias.

## Contexto y objetivo

El proyecto se inspira en el Reto 1 del ULab Mercedes-Benz, relacionado con la continuidad de clientes en talleres oficiales. Desarrollaréis un sistema de priorización de acciones de seguimiento y compararéis un montículo binario con una lista de Python.

Generaréis vuestros propios datos sintéticos, comprobaréis su calidad y analizaréis el rendimiento de ambas estructuras. Los datos y las reglas docentes no representan información real ni políticas oficiales de Mercedes-Benz.

## Materiales que debéis consultar

El profesorado facilitará el enunciado, el modelo de priorización y la guía de generación del dataset. Esos documentos definen los requisitos, los criterios de evaluación y el alcance del trabajo. Las fechas se comunicarán mediante Classroom 50 o el canal de la asignatura.

Leed los materiales antes de comenzar. Si una instrucción no queda clara, consultadla con el profesor y registrad el acuerdo correspondiente.

## Estructura del repositorio

```text
.
├── README.md
├── .gitignore
├── .github/
│   ├── ISSUE_TEMPLATE/       Formularios vacíos de tareas y entregas
│   └── pull_request_template.md
├── docs/                     Documentación que debe completar el equipo
│   ├── equipo.md
│   ├── plan_trabajo.md
│   ├── decisiones.md
│   ├── reproducibilidad.md
│   └── uso_ia.md
├── config/                   Configuración y diccionario elaborados por el equipo
├── src/                      Código que debe implementar el equipo
├── tests/                    Pruebas que debe diseñar el equipo
├── notebooks/                Notebook del proyecto
├── datos/
│   ├── muestras/             Archivos pequeños para revisión
│   └── generados/            Datasets grandes, excluidos del historial Git
├── resultados/
│   ├── figuras/              Visualizaciones seleccionadas
│   └── tablas/               Resúmenes de resultados y calidad
└── entregas/                 Información sobre las entregas y sus evidencias
```

Cada carpeta contiene un README que explica su propósito. Las instrucciones de organización no constituyen una arquitectura de implementación: el equipo debe decidir los módulos, las funciones, las dependencias y las pruebas.

## Primeros pasos

1. Confirmad el repositorio asignado en Classroom 50 y el acceso de todos los integrantes.
2. Completad [la identificación del equipo](docs/equipo.md).
3. Leed las guías y preparad [el plan de trabajo](docs/plan_trabajo.md).
4. Abrid Issues para las tareas iniciales, con responsables y criterios de aceptación propios.
5. Comenzad el diseño; registrad [las decisiones](docs/decisiones.md) antes de programar las partes correspondientes.

## Hitos de trabajo

| Hito | Evidencia que debe producir el equipo |
|---|---|
| H1 · Diseño | Esquema de datos, dependencias, decisiones de generación y planificación. |
| H2 · Datos | Generador, muestras, validación e informe de calidad de los datasets grandes. |
| H3 · Estructuras | Implementaciones, pruebas, trazas y comprobación de equivalencia. |
| H4 · Experimentación | Mediciones, tablas, gráficos, notebook ejecutado y conclusiones. |

El profesor concretará fechas y forma de entrega. Manteneos en el mismo repositorio durante todos los hitos para conservar la evolución del proyecto.

## Trabajo con GitHub

- Cada integrante utiliza su propia cuenta. Registrad el reparto y sus cambios.
- Usad Issues para describir tareas, dudas o problemas, con un responsable y una evidencia de finalización.
- Realizad commits cuando exista un avance coherente y describid qué ha cambiado. No se pide alcanzar una cuota de commits.
- Subid los avances al repositorio remoto durante el desarrollo; un commit que solo existe en vuestro equipo no puede revisarlo el profesor.
- Usad ramas y pull requests para proponer cambios. Siempre que sea posible, otro integrante debe revisarlos y explicar su revisión antes de integrarlos.
- Registrad correcciones y respuestas a los comentarios; no concentréis todo el trabajo en una subida final.
- Todos los integrantes deberán comprender el conjunto del proyecto y poder explicar sus contribuciones y las decisiones del equipo.

## Datos, resultados y entrega

Versionad código, documentación, configuración, muestras pequeñas y resúmenes seleccionados. Guardad los datasets grandes en `datos/generados/` durante el trabajo local; esta carpeta está excluida del historial Git.

Excluir un archivo de Git **no elimina la obligación de entregarlo**. El profesor indicará el canal de entrega de los datasets grandes. Registrad en [entregas](entregas/README.md) cómo acceder a ellos y cómo reproducirlos.

El notebook final se elaborará en `notebooks/`, con el nombre indicado en el enunciado. No debe sustituir los módulos, pruebas y documentación que correspondan al desarrollo del equipo.

## Estado inicial

Esta plantilla no incluye código, datos, resultados, pruebas implementadas, pseudocódigo ni soluciones. Un repositorio copiado de la plantilla sigue siendo un proyecto pendiente de realizar.
