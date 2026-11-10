
# Prueba Técnica – Becario de Desarrollo de Software

## 1. Introducción

¡Bienvenido a nuestra prueba técnica!

El objetivo de esta actividad es conocer tus conocimientos fundamentales de programación, tu razonamiento lógico y tu capacidad para resolver problemas.

No buscamos una solución perfecta ni conocimientos avanzados. Nos interesa comprender cómo estructuras tu código y cómo abordas un problema.

## 2. Objetivo

Desarrollar un programa sencillo que permita administrar las tareas de un equipo de trabajo.

El programa deberá permitir registrar, consultar, buscar, completar y eliminar tareas.

## 3. Descripción del problema

Un equipo de desarrollo necesita un programa para llevar el control de sus actividades pendientes.

Cada tarea deberá contener la siguiente información:

```json
{
  "id": 1,
  "titulo": "Corregir error de inicio de sesión",
  "prioridad": "alta",
  "completada": false
}
```

### Descripción de los campos

| Campo | Descripción |
|---|---|
| id | Identificador único de la tarea |
| titulo | Nombre o descripción breve de la tarea |
| prioridad | Nivel de prioridad: alta, media o baja |
| completada | Indica si la tarea está terminada |

## 4. Requerimientos funcionales

El programa deberá implementar las siguientes funcionalidades:

### 4.1. Registrar una tarea

Permitir que el usuario agregue una nueva tarea con la información requerida.

**Consideraciones:**
- Cada tarea debe tener un ID único.
- El título no puede estar vacío.
- La prioridad debe ser alta, media o baja.
- Una tarea nueva debe registrarse como pendiente.

### 4.2. Consultar todas las tareas

Mostrar todas las tareas registradas con su información correspondiente.

### 4.3. Buscar una tarea

Permitir buscar una tarea utilizando su ID.

Si la tarea no existe, el programa deberá informar al usuario.

### 4.4. Completar una tarea

Permitir marcar una tarea pendiente como completada.

Si la tarea ya está completada, el programa deberá informar al usuario.

### 4.5. Eliminar una tarea

Permitir eliminar una tarea utilizando su ID.

Si la tarea no existe, el programa deberá informar al usuario.

## 5. Requerimientos técnicos

- Puedes utilizar el lenguaje de programación de tu preferencia.
- No es necesario utilizar frameworks.
- No es obligatorio utilizar una base de datos.
- Los datos pueden almacenarse en memoria.
- No es necesario desarrollar una interfaz gráfica.
- El programa puede ejecutarse desde la consola.
- Puedes utilizar las bibliotecas estándar del lenguaje seleccionado.

La organización y estructura del código quedan a tu criterio.

## 6. Ejemplo de funcionamiento

El siguiente ejemplo es únicamente una referencia de cómo podría interactuar un usuario con el programa.

```text
===== GESTOR DE TAREAS =====

1. Agregar tarea
2. Mostrar tareas
3. Buscar tarea
4. Completar tarea
5. Eliminar tarea
6. Salir

Selecciona una opción: 1

ID: 1
Título: Corregir login
Prioridad: alta

Tarea registrada correctamente.
```

No es obligatorio utilizar exactamente este menú. Puedes implementar otra forma de interacción que permita ejecutar las funcionalidades solicitadas.

## 7. Criterios de evaluación

Se evaluarán los siguientes aspectos:

### Funcionamiento
- Cumplimiento de los requerimientos.
- Validación de datos.
- Manejo de casos donde una tarea no existe.
- Funcionamiento correcto de las operaciones.

### Calidad del código
- Claridad y legibilidad.
- Uso adecuado de variables y funciones.
- Organización del programa.
- Evitar código repetitivo cuando sea posible.

### Razonamiento
- Capacidad para explicar la solución.
- Comprensión del código desarrollado.
- Justificación de las decisiones tomadas.

No es necesario utilizar técnicas avanzadas de programación.

## 8. Entregables

Deberás entregar:

1. El código fuente de tu solución.
2. Un archivo README.md que explique:
   - Qué lenguaje utilizaste.
   - Cómo ejecutar el programa.
   - Qué funcionalidades implementaste.
   - Si existe alguna funcionalidad pendiente.
   - Qué recursos o herramientas de apoyo utilizaste.

Puedes entregar tu solución mediante:

- Un repositorio de GitHub.
- Un archivo ZIP con el proyecto.

## 9. Tiempo estimado

El tiempo estimado para completar la prueba es de **60 a 90 minutos**.

La fecha límite de entrega será comunicada por el equipo de reclutamiento.

## 10. Uso de herramientas de apoyo

Puedes consultar documentación oficial, tutoriales y otros recursos de aprendizaje.

También se permite utilizar herramientas de inteligencia artificial como apoyo.

En caso de utilizarlas, indica brevemente para qué las empleaste.

Durante la entrevista técnica podríamos solicitarte que expliques algunas partes de tu código o realices una modificación sencilla.

## 11. Recomendaciones finales

- Lee todos los requerimientos antes de comenzar.
- Prioriza que el programa funcione correctamente.
- Organiza tu código de forma clara.
- Prueba las funcionalidades implementadas.
- Si no logras completar alguna funcionalidad, indícalo en tu entrega.

**¡Mucho éxito en tu prueba técnica!**
