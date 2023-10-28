Proyecto Integrador: Bases de datos
Estructura de la base de datos
La base de datos contendrá documentos que representan tareas pendientes. Cada documento tendrá los siguientes campos:
1.	ID: Un identificador único para cada tarea.
•	Tipo de dato: String o número.
2.	Título: El título de la tarea.
•	Tipo de dato: String.
3.	Descripción: Una descripción detallada de la tarea.
•	Tipo de dato: String.
4.	Fecha de Creación: La fecha en la que se creó la tarea.
•	Tipo de dato: Fecha (puede ser un timestamp o una cadena de fecha).
5.	Fecha de Vencimiento: La fecha límite para completar la tarea.
•	Tipo de dato: Fecha (puede ser un timestamp o una cadena de fecha).
6.	Estado: El estado actual de la tarea (pendiente, en progreso, completada, etc.).
•	Tipo de dato: String.
7.	Etiquetas: Etiquetas o categorías asociadas a la tarea.
•	Tipo de dato: Lista o array de strings.
8.	Prioridad: La prioridad de la tarea (alta, media, baja, etc.).
•	Tipo de dato: String o número.
9.	Responsable: El nombre de la persona responsable de completar la tarea.
•	Tipo de dato: String o ID de usuario.

Ejemplos de documentos en formato JSON:
Documento 1:
{
  "ID": "1",
  "Título": "Comprar víveres",
  "Descripción": "Ir al supermercado y comprar los víveres necesarios para la semana.",
  "Fecha de Creación": "2023-10-27",
  "Fecha de Vencimiento": "2023-10-30",
  "Estado": "Pendiente",
  "Etiquetas": ["Compras", "Supermercado"],
  "Prioridad": "Media",
  "Responsable": "Juan Pérez"
}

Documento 2:
{
  "ID": "2",
  "Título": "Preparar presentación",
  "Descripción": "Preparar una presentación para la reunión de proyecto de la próxima semana.",
  "Fecha de Creación": "2023-10-28",
  "Fecha de Vencimiento": "2023-11-03",
  "Estado": "En Progreso",
  "Etiquetas": ["Trabajo", "Proyecto"],
  "Prioridad": "Alta",
  "Responsable": "María Gómez"
}

Documento 3:
{
  "ID": "3",
  "Título": "Hacer ejercicio",
  "Descripción": "Realizar una rutina de ejercicios cardiovasculares en el gimnasio.",
  "Fecha de Creación": "2023-10-25",
  "Fecha de Vencimiento": "2023-10-29",
  "Estado": "Completada",
  "Etiquetas": ["Salud", "Ejercicio"],
  "Prioridad": "Baja",  
  "Responsable": "Ana López"
}


