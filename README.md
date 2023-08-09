# Petshop Web
## ES NECESARIO LA EJECUCION DE LA API LOCAL PARA EL CORRECTO FUNCIONAMIENTO DEL CÓDIGO
Este README proporciona una descripción general del código de la página web que consume una API para administrar clientes y productos de una tienda de mascotas. El código está escrito en C# y utiliza el framework ASP.NET Core.
## Descripción General
Este proyecto consiste en una aplicación web que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en clientes y productos de una tienda de mascotas. La aplicación consume una API RESTful para interactuar con el backend y realizar las operaciones necesarias.
## Estructura del Proyecto
El proyecto está organizado en varios archivos y carpetas:
* Models: Contiene las clases de modelo que representan los objetos Cliente, Producto, ErrorViewModel y ResultadoApi.
* Services: Contiene las interfaces y las implementaciones de los servicios para interactuar con la API de clientes y productos.
* Controllers: Contiene los controladores que manejan las rutas y las acciones de la aplicación.
* appsettings.json: Archivo de configuración que define las configuraciones de la aplicación.
## Controladores
### ClienteController
El controlador ClienteController maneja las operaciones relacionadas con los clientes:
* Index: Muestra la lista de clientes.
* Edit: Muestra el formulario de edición de un cliente.
* Edit1: Realiza la actualización de un cliente.
* Create: Muestra el formulario de creación de un cliente.
* Create1: Crea un nuevo cliente.
* Details: Muestra los detalles de un cliente.
* Delete: Muestra el formulario de confirmación de eliminación de un cliente.
* Delete1: Elimina un cliente.
### ProductoController
El controlador ProductoController maneja las operaciones relacionadas con los productos:
* Index: Muestra la lista de productos.
* Edit: Muestra el formulario de edición de un producto.
* Edit1: Realiza la actualización de un producto.
* Create: Muestra el formulario de creación de un producto.
* Create1: Crea un nuevo producto.
* Details: Muestra los detalles de un producto.
* Delete: Muestra el formulario de confirmación de eliminación de un producto.
* Delete1: Elimina un producto.
## Servicios
Los servicios IServicioApiCli e IServicioApiPro definen las operaciones que se pueden realizar en la API de clientes y productos, respectivamente. Las clases ServicioApiCli y ServicioApiPro implementan estas interfaces y manejan las llamadas a la API.
## Configuración
La configuración de la aplicación se encuentra en el archivo appsettings.json, donde se definen los niveles de registro de log y las configuraciones de los hosts permitidos.
## Ejecución
El archivo Program.cs define la ejecución de la aplicación. Se configuran los servicios, los controladores y las rutas. La aplicación se ejecuta en el puerto 5062.
## Requisitos
* ASP.NET Core SDK
* Visual Studio o Visual Studio Code (opcional)
## Instrucciones de Uso
1. Clonar el repositorio o descargar los archivos del proyecto.
2. Abrir el proyecto en un entorno de desarrollo compatible con ASP.NET Core.
3. Configurar la URL base de la API en las clases ServicioApiCli y ServicioApiPro.
4. Ejecutar la aplicación y acceder a través del navegador web.
5. Navegar por las diferentes páginas para realizar operaciones CRUD en clientes y productos.
## Nota
* Asegúrate de que la API de backend esté en funcionamiento y accesible desde la URL configurada en los servicios.
