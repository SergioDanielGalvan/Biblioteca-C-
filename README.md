# TP1 - DSOO: Gestión de Biblioteca

## Descripción

Este es el repositorio del **1er TP obligatorio** de **Desarrollo de Software Orientado a Objetos (DSOO)**.

### Detalles de la Entrega

- **Tipo:** Trabajo práctico obligatorio  
- **Entrega en la semana 7**
- **Formato de Entrega:**  
  `TP1_ComX_GrupoX_Apellido1_Apellido2_Apellido3_Apellido4_Apellido5.zip` o `.rar`  
  *MUY IMPORTANTE* respetar el nombre de la entrega para su posterior organización y seguimiento.

- **Representante del equipo:**  
  La entrega debe ser realizada por un representante del equipo, quien debe haber sido registrado previamente en la planilla (corregirla de ser necesario).

- **Archivos a entregar:**  
  Todos los archivos correspondientes deben ser entregados **dentro de un archivo comprimido**, indicando la comisión, el número del grupo y los apellidos de los integrantes.

## Objetivo

El objetivo es implementar una **biblioteca** que gestione los préstamos de libros y los lectores registrados.

## Descripción del Proyecto

Se nos pide que, utilizando el ejemplo de la biblioteca visto durante la semana en clase, la misma tenga una colección de **lectores registrados**, de los cuales conocemos su **nombre** y **DNI**.

Cada lector puede tener hasta **tres préstamos vigentes**.

### Funcionalidad de los Préstamos:

Cuando se realiza un préstamo, el libro debe ser extraído de la biblioteca y entregado al lector (si es que puede retirarlo). Es decir, el libro se debe **quitar de la lista de libros** de la biblioteca y **asignarse** a la lista de libros en préstamo del lector.

## Tareas a Realizar

1. **Ampliar el UML** con los nuevos requerimientos.
2. **Desarrollar el método `altaLector`** que, pasándole los parámetros necesarios, dé de alta a un lector dentro de la lista de lectores si no estaba previamente registrado.
3. **Desarrollar el método `prestarLibro`** de la clase **Biblioteca**, el cual recibe el título de un libro y el DNI del lector que lo solicita. Este método debe retornar uno de los siguientes mensajes:
   - `"PRESTAMO EXITOSO"`: El libro fue prestado exitosamente, se lo quitó de la lista de la biblioteca y se lo adjudicó al lector.
   - `"LIBRO INEXISTENTE"`: El libro no está en la colección de la biblioteca.
   - `"TOPE DE PRESTAMO ALCANZADO"`: El lector ya tiene tres libros prestados.
   - `"LECTOR INEXISTENTE"`: El lector no está registrado en la biblioteca.

4. **Generar un video grupal** con cámaras activas, donde cada integrante explique su parte del desarrollo y funcionamiento del proyecto.

---
