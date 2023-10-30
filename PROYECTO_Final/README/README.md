Tienda en Línea con Flask y MySQL
Este es un proyecto de una tienda en línea desarrollada con Flask y MySQL, que te permite gestionar compras de ropa. Puedes agregar compras, editar información de compras existentes, eliminar compras y buscar compras por nombre.

Tabla de Contenidos
Descripción
Requisitos Previos
Instalación
Uso
Configuración de la Base de Datos
Rutas
Contribuciones
Licencia
Descripción
Esta aplicación Flask te permite llevar un registro de compras de ropa, con detalles como el nombre del cliente, número de teléfono, dirección de correo electrónico, prenda de ropa, cantidad y precio. La aplicación utiliza una base de datos MySQL para almacenar y gestionar estos registros.

Requisitos Previos
Antes de comenzar, asegúrate de tener las siguientes herramientas instaladas:

Python
Flask
Flask-MySQLdb (o el conector MySQL de tu elección)
Instalación
Sigue estos pasos para instalar y ejecutar la aplicación:

Clona el repositorio en tu máquina local:

bash
Copy code
git clone https://github.com/tunombredeusuario/tuproyecto.git
Instala las dependencias requeridas utilizando pip:

Copy code
pip install flask flask-mysqldb
Configura tu base de datos y ajusta la configuración en tu aplicación Flask:

Modifica la sección app.config en tu aplicación Flask para que coincida con la configuración de tu servidor MySQL.
Crea la base de datos y las tablas necesarias.
Ejecuta la aplicación Flask:

Copy code
python tuapp.py
Uso
Inicia la aplicación Flask.
Accede a la aplicación a través de un navegador web en http://localhost:5000 (o en la URL que hayas configurado).
Utiliza la interfaz web para llevar a cabo diversas acciones, como agregar una compra, listar todas las compras, editar información de compras, actualizar datos, eliminar compras y buscar compras por nombre.
Configuración de la Base de Datos
Si necesitas ajustar la configuración de la base de datos, puedes hacerlo en la sección de configuración de la aplicación Flask. Asegúrate de crear la base de datos y las tablas necesarias antes de ejecutar la aplicación.

Rutas
/: Página principal para realizar compras.
/add_contact: Agregar un nuevo registro de compra.
/list: Listar todos los registros de compra.
/edit/<id>: Editar un registro de compra específico.
/update/<id>: Actualizar información de compra.
/delete/<id>: Eliminar un registro de compra.
/search: Buscar compras por nombre.
Contribuciones
Si deseas contribuir a este proyecto, ¡te damos la bienvenida! Puedes enviar solicitudes de extracción o informar problemas en el repositorio.