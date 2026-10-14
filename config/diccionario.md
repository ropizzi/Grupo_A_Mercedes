BASE DE DATOS RELACIONAL
(estoy teniendo en cuenta que los clientes son únicamente de España.)
| entidades | claves primarias | atributos |
cliente         id_cliente     nombre,provincia, tipo_cliente, edad 
producto        id_producto    nombre_producto, id_cliente, fecha_compra, precio, stock
compra          id_compra      fecha_compra, banco, tipo_compra (online/presencial) -> interaccion_online

TABLA CLIENTE:

CLIENTE
|   campo    |  tipo   |   rango    |
id_cliente      entero   1 - 9.999.999
nombre          cadena
provincia       cadena
tipo_cliente    cadena    Empresa/particular
edad            entero     1 - 120
id_producto     entero   1 - 9.999.999
nombre_produto  cadena     vehículo, accesorios,...
fecha_compra    entero?     01/01/1926 - 01/01/27
precio          entero      1- 1.000.000.000
stock           entero      0 - 100.000
id_compra       entero      1 - 9.999.999
banco           cadena    (todos los bancos)
tipo_compra     cadena      online/concesionario
interaccion_online  entero  0- 10.000 clicks