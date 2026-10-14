# Registro de decisiones

Documentad las decisiones relevantes cuando se tomen, no únicamente al terminar. Cada entrada debe contener una explicación propia del equipo.

## Decisión: Planificación

- **Fecha:** 14/10/26
- **Pregunta o problema:** Organización de tareas
- **Opciones consideradas:** Dividir el trabajo de cada hito entre tres
- **Decisión adoptada:** la opción considerada
- **Justificación:** es la manera más equitativa de dividir el trabajo entre las 3 componentes del grupo
- **Cómo se comprobará:** se encuentra la tabla en el apartado de planificación donde está organizado quien hará que
- **Limitaciones o aspectos pendientes:** planificar los próximos hitos (se hará despues de entregar el H1)
- **Issue, pull request o evidencia relacionada:** <img width="2052" height="598" alt="image" src="https://github.com/user-attachments/assets/1781c592-ba09-47d8-9fbc-c13bd6a12f7f" />

## Decisión: DEPENDENCIAS

- **Fecha:** 14/10/26
- **Pregunta o problema:** Dependencias
- **Opciones consideradas:** Uso de un archivo de texto estándar para listar las versiones y probar los entornos mediante un cuaderno de trabajo.
- **Decisión adoptada:** Verificar el funcionamiento de las librerías base a través de un entorno local de pruebas.
- **Justificación:** Permite comprobar inmediatamente que el entorno de desarrollo local es compatible y que las librerías se importan correctamente antes de que el resto del equipo las integre.
- **Cómo se comprobará:** Ejecutando el bloque de código de verificación para comprobar que se muestran las versiones de las librerías sin errores.
- **Limitaciones o aspectos pendientes:** Crear formalmente el archivo de texto en la raíz del repositorio y completar el flujo en GitHub mediante un pull request ya que lo estamos escribiendo desde Visual Studio.
- **Issue, pull request o evidencia relacionada:** Rama de trabajo dependencias y archivo de pruebas dependencias.ipynb.

## Decisión: ESQUEMA DE DATOS

- **Fecha:** 14/10/2026
- **Pregunta o problema:** Creación del esquema de datos y del diccionario
- **Opciones consideradas:**  A la hora de visualizar y de almacenar los datos, hemos considerado que una base de datos relacional, donde se han seleccionado intuitivamente los campos y atributos y se han descrito los datos por tipos y por rango a considerar. 
- **Decisión adoptada:** Base de datos relacional
- **Justificación:** La versatilidad a la hora de almacenar los datos, es un modelo muy intuitivo y a la hora de realizar consultas es muy eficiente
- **Cómo se comprobará:** A esta altura del proyecto no es posible comprobar la efectividad del diccionario.
- **Limitaciones o aspectos pendientes:** Cabe por evaluar si es el mejor modelo para el proyecto, además considerando que es una empresa popular, tendrá muchos registros.
- **Issue, pull request o evidencia relacionada:** Una rama de trabajo llamada diccionario y un archivo en markdown.
