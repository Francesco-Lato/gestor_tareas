# Gestor de Tareas - Página Web

Este proyecto es una página web diseñada para gestionar tareas y organizar actividades diarias. La página incluye un calendario interactivo, una sección para insertar nuevas tareas y enlaces a diferentes asignaturas o categorías de tareas.

## Autor
- **Francesco Latorrata**

## Características Principales

1. **Calendario Interactivo**:
   - Muestra el mes actual (enero de 2024) con días seleccionables.
   - Los domingos están resaltados en color rojo.
   - Cada día es un enlace que permite acceder a detalles específicos de las tareas.

2. **Sección de Próxima Tarea**:
   - Muestra la tarea más próxima con su fecha y una breve descripción.
   - Ejemplo: "Despliegue de aplicaciones" para el lunes 15 de enero.

3. **Formulario para Insertar Tareas**:
   - Permite al usuario agregar nuevas tareas.
   - Campos incluidos:
     - **Asignatura**: Selección de una asignatura (Diseño, Empresa, Despliegue, Cliente, Servidor).
     - **Fecha**: Selección de fecha mediante un campo de tipo `date`.
     - **Descripción**: Área de texto para describir la tarea.

4. **Enlaces a Asignaturas**:
   - Enlaces a páginas específicas para cada asignatura:
     - Diseño de interfaces Web
     - Despliegue de aplicaciones
     - Empresa
     - Desarrollo entorno cliente
     - Desarrollo entorno servidor

5. **Diseño Responsivo y Estilos**:
   - Utiliza estilos personalizados (`estilos.css`) y normalización (`normalize.css`).
   - Iconos de FontAwesome y Google Fonts para mejorar la experiencia visual.

---

## Estructura del Código

### HTML
- **Cabecera (`<header>`)**:
  - Título del gestor de tareas.
  - Barra de búsqueda con un campo de texto y un botón.

- **Contenido Principal (`<main>`)**:
  - **Calendario**: Muestra los días del mes con enlaces a tareas específicas.
  - **Próxima Tarea**: Muestra la tarea más próxima con su descripción.
  - **Insertar Tarea**: Formulario para agregar nuevas tareas.
  - **Enlaces a Asignaturas**: Iconos y enlaces a páginas específicas de cada asignatura.

- **Pie de Página (`<footer>`)**:
  - Muestra el nombre del autor y el curso (2º DAW).

### CSS
- **`estilos.css`**: Contiene los estilos personalizados para la página.
- **`normalize.css`**: Normaliza los estilos para garantizar consistencia entre navegadores.

### Recursos Externos
- **FontAwesome**: Iconos utilizados en los enlaces de asignaturas.
- **Google Fonts**: Fuentes utilizadas en la página.

---

## Cómo Usar

1. **Clonar el Repositorio**:
   ```bash
   git clone <url-del-repositorio>
