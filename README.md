# Cheese People

Cheese People es una maqueta web responsiva para un emprendimiento de quesos artesanales. El proyecto incluye interfaces de autenticacion, registro, recuperacion de cuenta, panel de cliente y panel administrativo de tienda.

## Descripcion

La aplicacion esta desarrollada con HTML5 y Bootstrap. Su diseno usa una paleta azul oscuro tranquila, componentes responsivos, navegacion entre paginas y un logo de queso ubicado en `assets/img/queso.gif`.

## Paginas del Proyecto

* `app/login.html`: pantalla de inicio de sesion. Al enviar el formulario dirige al panel de cliente.
* `app/registro.html`: formulario para crear una cuenta nueva. Al registrarse dirige al inicio de sesion.
* `app/recuperar.html`: formulario para recuperar contrasena. Al enviar dirige al inicio de sesion.
* `app/cliente.html`: panel del cliente con informacion personal, pedidos activos e historial de pedidos.
* `app/admin.html`: panel de tienda con resumen, ventas, pedidos, clientes y modal para editar pedidos.

## Caracteristicas

* Diseno responsivo con Bootstrap.
* Navbar compartida entre las paginas principales.
* Logo y favicon relacionados con Cheese People.
* Formularios de login, registro y recuperacion.
* Panel de cliente con pestañas para pedidos activos e historial.
* Panel administrativo con tarjetas de resumen, tabla de pedidos y modal de edicion.
* Enlaces conectados entre las interfaces del proyecto.

## Tecnologias Utilizadas

* HTML5
* Bootstrap 5.3.8
* Bootstrap Icons 1.13.1
* CSS inline apoyado en clases de Bootstrap

## Estructura del Proyecto

```text
TALLER_4/
|-- README.md
|-- app/
|   |-- admin.html
|   |-- cliente.html
|   |-- login.html
|   |-- recuperar.html
|   |-- registro.html
|-- assets/
|   |-- css/
|   |-- img/
|   |   |-- queso.gif
|   |-- js/
```

## Navegacion

La pagina inicial recomendada es:

```text
app/login.html
```

Desde esa interfaz se puede acceder a registro, recuperacion de contrasena, panel de cliente y panel de tienda.

## Autor

Proyecto realizado como taller de maquetacion web con Bootstrap.
