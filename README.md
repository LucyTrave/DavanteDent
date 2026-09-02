# DavanteDent

Aplicación web front-end para gestionar las citas de una clínica dental. Permite registrar los datos de cada cita y del paciente, consultar las citas guardadas, modificar sus datos y eliminar registros desde el navegador.

## Funcionalidades

- Acceso desde una pantalla principal a las opciones de creación y gestión de citas.
- Registro de la fecha y hora de la cita.
- Introducción de observaciones sobre el tratamiento o motivo de la consulta.
- Registro del nombre y apellidos, DNI, teléfono y fecha de nacimiento del paciente.
- Validación de los datos introducidos antes de guardar una cita.
- Visualización de las citas registradas en un listado.
- Modificación de citas existentes.
- Eliminación de citas.
- Persistencia de los datos en el navegador mediante `localStorage`.

## Tecnologías utilizadas

- HTML5 para la estructura de la aplicación.
- CSS3 para el diseño y la presentación visual.
- JavaScript para la lógica, las validaciones y la gestión de las citas.
- Web Storage (`localStorage`) para conservar los datos en el navegador.

## Capturas de pantalla

### Pantalla de inicio

Desde la pantalla principal se puede acceder a la creación de una cita o a la gestión de las citas existentes.

![Pantalla principal de DavanteDent](docs/images/01-inicio-davantedent.png)

### Gestión de citas

El formulario permite introducir los datos de la cita y del paciente. En la parte inferior se muestra el listado de citas registradas, con las acciones disponibles para modificar o eliminar cada registro.

![Formulario y listado de citas de DavanteDent](docs/images/02-gestion-citas.png)

### Registro de una cita

La aplicación permite seleccionar la fecha y la hora, añadir observaciones y guardar los datos del paciente. La nueva cita se incorpora al listado de citas registradas.

![Registro de una nueva cita en DavanteDent](docs/images/03-registro-cita.png)

## Ejecución del proyecto

No requiere instalación de dependencias ni configuración de una base de datos.

1. Descarga o clona el repositorio.
2. Abre la carpeta del proyecto.
3. Abre `índice.html` en el navegador o ejecuta el proyecto con Live Server desde Visual Studio Code.

Los datos se almacenan localmente en el navegador. Si se eliminan los datos del sitio o el almacenamiento local, también se borrarán las citas guardadas.

## Objetivo del proyecto

Este proyecto forma parte de mi portfolio como Desarrolladora Web Junior. Su objetivo es aplicar JavaScript a un caso práctico de gestión, trabajando con formularios, validación de datos, operaciones de creación, consulta, modificación y eliminación, y persistencia local.

## Autora

**Lucía Jiménez Travé**

- GitHub: [github.com/LucyTrave](https://github.com/LucyTrave)
- LinkedIn: [linkedin.com/in/lucíajtravé](https://www.linkedin.com/in/luc%C3%ADajtrav%C3%A9)
