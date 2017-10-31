# Farmasoft

# Informe

# Flujo de programa

Al acceder al sitio se visualiza la bienvenida, se requiere loguear para poder acceder al Sistema. Una vez Ingresado al Sistema se pueden acceder a las diferentes consultas mediante el menu superior.

# Estructura de archivos

El programa esta compuesto por el archivo principal (app.py), los módulos class_csv.py(genera una lista con objetos que contienen los datos de cada registro), form_py(contiene las clases de los formularios utilizados), func_listar (contiene todas las funciones de listado utilizadas por el sistema) y validar_csv (Valida que el CSV utilizado segun las consignas del TP) además estan los archivos usuarios_csv que contienen los usuarios que pueden entrar al sistema y farmacia.csv que contiene datos de las operaciones. Los archivos .html estan en la carpeta templates y el favicon dentro de la carpeta static.Los datos se muestran por tablas. Esta configurado para mostrar las 10 ultimas ventas, los 5 mejores clientes y los 5 productos mas vendidos(estos valores de cantidades se pueden modificar)
corre con python 3 y su uso como framework flask.

# Uso del programa

Al acceder al sitio se visualiza la bienvenida, debe clickear en "Ingresar" y se requiere loguear para poder acceder al Sistema(usuario admin, pass admin).
Una vez Ingresado al Sistema por defecto se ben las ultimas "n" ventas y se visualizan las siguientes Opciones en el menu superior.

FARMASOFT: muestra la pantalla de bienvenida con datos del desarrollador del sistema

salir: Se desloguea el Usuario logueado

Últimas Ventas: se visualizan las n ultimas ventas

Productos por Cliente:Se debe ingresar por lo menos 3 caracteres para la busqueda de clientes, luego se listan todos los registros hechos por el cliente buscado o un listado con todos los clientes que contienen los caracteres de la busqueda para que puedas seleccionar el que desees.

Clientes por Productos:Se debe ingresar por lo menos 3 caracteres para la busqueda de un producto, luego se listan todos los registros que contienen el producto buscado o un listado con todos los productos que contienen los caracteres de la busqueda para que puedas seleccionar el que desees.

Productos mas vendidos: Lista descendente los "n" productos mas vendidos

Méjores Clientes: Lista descendente los "n" clientes que mas gastaron

# Clases diseñadas

    archivo form.py contiene las siguientes clases:
Loginform se creo para el formulario del ingreso al sistema
Productoform se creo para el formulario de ingreso de palabra a buscar entre todos los producto
Clienteform se creo para el formulario del ingreso de palabra a buscar entre todos los clientes
    archivo class_csv.py
Contiene la clase Classificar donde los atributos del objeto se aloja el dato segun la colunna del csv
    archivo validar_csv.py
contien classes de errores para motrar en la validacion del csv




