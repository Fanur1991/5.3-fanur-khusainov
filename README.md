# Estructura de datos MongoDB

Desarrollo de estructuras de bases de datos MongoDB para la gestión de una óptica, una tienda de comida a domicilio y una versión reducida de YouTube.

### Nivel 1 - Optica

El proyecto se centra en la gestión de una óptica llamada. Aquí se detallan los puntos clave:

| **Colecciones** | **Atributos**                                                                                                           |
| --------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Proveedores     | Nombre, dirección (calle, número, piso, puerta, ciudad, código postal, país), teléfono, fax, NIF.                       |
| Gafas           | Marca, graduación de vidrios, tipo de montura (flotante, pasta o metálica), color de montura, color de vidrios, precio. |
| Clientes        | Nombre, dirección postal, teléfono, correo electrónico, fecha de registro, clienteRecomendador.                         |
| Ventas          | Empleado que realizó la venta, fecha y hora de la venta.                                                                |

#### Modelaje:

1. **Diseño de la base de datos según la vista del cliente de la óptica.**

- El ejercicio pide que se considere la información necesaria para mostrar la interfaz gráfica proporcionada.
<p align="center">
    <img src="./01-level-1/01-exercise-1/taskView/view1.jpg">
</p>

2. **Diseño de la base de datos según la vista de las gafas.**

- El ejercicio pide que se considere la información necesaria para mostrar la interfaz de las gafas.
<p align="center">
    <img src="./01-level-1/02-exercise-2/taskView/view2.jpg">
</p>

### Nivel 2 - Tienda de comida a domicilio

Este nivel se enfoca en el diseño de una web para pedidos de una tienda de pedidos de comida a domicilio. Puntos destacados:

| **Colecciones**      | **Atributos**                                                            |
| -------------------- | ------------------------------------------------------------------------ |
| Clientes             | Identificador único, nombre, dirección, código postal, teléfono.         |
| Pedidos              | Fecha/hora, tipo de entrega, productos (cantidad y tipos), precio total. |
| Productos            | Identificador único, nombre, descripción, imagen, precio.                |
| Categorías de Pizzas | Identificador único, nombre.                                             |
| Empleados            | Identificador único, nombre, apellidos, NIF, teléfono, rol.              |

### Modelaje:

1. **Diseño de la base de datos para la gestión de pedidos online.**

- El ejercicio pide que se considere la información necesaria para manejar pedidos, clientes y productos.
<p align="center">
  <img src="./02-level-2/taskView/view.jpg">
</p>

2. **Diseño de la base de datos desde la perspectiva de las pizzas.**
   - El ejercicio pide que se considere la información necesaria para manejar las distintas categorías y productos de pizzas.

### Nivel 3 - YouTube

Este nivel representa una versión reducida de YouTube con las siguientes características:

| **Colecciones**        | **Atributos**                                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Usuarios               | id, email, contraseña, nombre de usuario, fecha de nacimiento, sexo, país, código postal.                           |
| Videos                 | id, título, descripción, tamaño, nombre del archivo de vídeo, duración, thumbnail, reproducciones, likes, dislikes. |
| Canales                | id, nombre, descripción, fecha de creación.                                                                         |
| Listas de Reproducción | id, nombre, fecha de creación, estado (pública o privada).                                                          |

#### Modelaje:

1. **Diseño de la base de datos para una versión reducida de YouTube.**
   - El ejercicio pide que se considere la información necesaria para manejar usuarios, videos, canales y listas de reproducción.
   <p align="center">
     <img src="./03-level-3/taskView/view.jpg">
   </p>

## Licencia

This project is distributed under the Apache 2.0 license.

---

Developed by [Fanur Khusainov](https://www.linkedin.com/in/fanur-khusainov-ab86b2102/) with ❤️ and ☕.
