# CHILECODES
## Información de la página
Esta página es una réplica de la página principal de CHILECODES, esta se dedica a la venta de codigos de videojuegos con una entrega automática de 24 horas del día, manteniendo los mejores precios del mercado Chileno.
## Requerimientos
Para la visualización de la página se necesita tener:
* Visual Studio Code
* Mysql
* Django
* python
* Microsoft Edge
## Contenido de la página
* HOME
* LOGIN
* Formulario
* Carro de compras
* Catálogo de productos
* Cambio de contraseña
## Usabilidad    
### Usuario
* Registrarse
* Loguearse en la página 
* Cambiar contraseña
* Ver productos 
* Comprar productos
### Administrador
* Agregar productos
* Modificar productos
* Eliminar producto
## Conexión con la base de datos
```javascript
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'chilestore',
        'USER': 'root',
        'PASSWORD': 'root',
        'HOST': 'localhost',
        'PORT': '3306'
    }
}
```
## Comandos
**Cargar página web**
```javascript
python manage.py runserver
```
**Crear tablas**
```javascript
python mange.py makemigration
```
**Migrar tablas creadas**
```javascript
python mange.py migrate
```
## Contribuyentes
@Alexis1218
@lumonsalvez023
@fernando1998andres
## Enlaces
https://chilecodes.cl/
