# Proyecto Biblioteca.
## Diagrama de caso de uso de la biblioteca.



<img src="Diagrama sin título.drawio.png">

## Especificación de caso de uso de la biblioteca.


### Actores.

#### Ususario.

|  Actor | Ususario |
|---|---|
| Descripción  | Usuario común de la biblioteca.  |
| Características  |  |
| Relaciones | Registrar un préstamo  |
| Referencias | Buscar libros , pedir préstamo |   
|  Notas |   |
| Autor  | Carlos Antonio Díaz Galán |
|Fecha | 29/10/2024 |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

#### Bibliotecario.
|---|---|


|  Actor | Bibliotecario |
|---|---|
| Descripción  | Bibliotecario de la biblioteca.  |
| Características  | El bibliotecario realiza las mismas acciones que el Usuario y las acciones específicas. |
| Relaciones | Registrar un préstamo. |
| Referencias | solicitar prestamo, Buscar libro. |   
|  Notas |   |
| Autor  | Carlos Antonio Díaz Galán |
|Fecha | 29/10/2024 |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

#### Sistema de notificación.


|  Actor | Bibliotecario |
|---|---|
| Descripción  | Notificación de la biblioteca.  |
| Características  |  |
| Relaciones |  |
| Referencias | Enviar notificación, Recordatiorio de una devolución. |   
|  Notas |   |
| Autor  | Carlos Antonio Díaz Galán |
|Fecha | 29/10/2024 |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |



### Casos de uso.

#### Buscar libro.

|  Caso de Uso	CU.1 | Buscar libro.  |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al [documento]()  |
  | Actor  |  Usuario, bibliotecario. |
  | Descripción | _Descripción del caso de uso_  |
  | Flujo básico | _Descripción paso a paso de la ejecución. (1->2->3.)_ |
  | Pre-condiciones | _Que debe ocurrir con anterioridad_  |  
  | Post-condiciones  | _Que debe ocurrir con posterioridad_  |  
  |  Requerimientos | _Que debe de exister para que el caso de uso se ejecute. Ej: Tarjeta de crédito_  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | _Quien desarrolla la especificación del actor_ |
  |Fecha | _Fecha de la especificación_ |



# Proyecto ejercicio 2. Sistema de compras en Línea.

## Diagrama de caso de uso de la tienda en línea



## Especificación de caso de uso de la tienda en línea

### Actores

#### Cliente

|  Actor          | Cliente                  |
|-----------------|--------------------------|
| Descripción     | Usuario común de la tienda en línea. |
| Características | Cliente que puede navegar, comprar y pagar productos en la plataforma. |
| Relaciones      | Agregar productos al carrito, Realizar pedido, Realizar pago |
| Referencias     | Buscar productos, Añadir productos al carrito |
| Notas           |                          |
| Autor           | Carlos Antonio Díaz Galán |
| Fecha           | 04/11/2024               |

|  Atributo       |||
|-----------------|--------------------------|-------------------|
| _Nombre_        | _Descripción_            | _Tipo_           |
| Nombre          | Nombre del cliente       | Texto            |
| Correo electrónico | Email de contacto     | Texto            |
| Método de pago  | Forma de pago preferida  | Selección        |

#### Administrador

|  Actor          | Administrador            |
|-----------------|--------------------------|
| Descripción     | Administrador de la tienda en línea. |
| Características | Puede gestionar el catálogo de productos y precios. |
| Relaciones      | Gestionar catálogo de productos |
| Referencias     | Agregar, modificar y eliminar productos |
| Notas           |                          |
| Autor           | Carlos Antonio Díaz Galán |
| Fecha           | 04/11/2024               |

|  Atributo       |||
|-----------------|--------------------------|-------------------|
| _Nombre_        | _Descripción_            | _Tipo_           |
| ID de empleado  | Identificación del administrador | Numérico  |
| Nivel de acceso | Nivel de privilegios     | Selección        |

### Casos de uso

#### Buscar productos

| Caso de Uso CU.1 | Buscar productos                    |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta en el análisis de requerimientos del sistema de compras en línea |
| Actor            | Cliente                             |
| Descripción      | El cliente busca productos mediante palabras clave o categorías. |
| Flujo básico     | 1. El cliente ingresa palabras clave en el buscador.<br>2. El sistema muestra los resultados de productos relevantes.<br>3. El cliente selecciona un producto para ver sus detalles. |
| Pre-condiciones  | El cliente debe estar en la página principal del sitio web de la tienda. |
| Post-condiciones | El cliente visualiza los resultados de la búsqueda. |
| Requerimientos   | Conexión a internet, Base de datos de productos |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 04/11/2024               |

#### Añadir productos al carrito

| Caso de Uso CU.2 | Añadir productos al carrito         |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta en el análisis de requerimientos del sistema de compras en línea |
| Actor            | Cliente                             |
| Descripción      | El cliente añade productos al carrito de compras para realizar una compra. |
| Flujo básico     | 1. El cliente selecciona un producto.<br>2. El sistema muestra los detalles del producto.<br>3. El cliente selecciona la cantidad y añade al carrito. |
| Pre-condiciones  | El cliente debe haber encontrado un producto en la tienda. |
| Post-condiciones | El producto se añade al carrito con la cantidad seleccionada. |
| Requerimientos   | Producto disponible en inventario |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 04/11/2024               |

#### Realizar pedido

| Caso de Uso CU.3 | Realizar pedido                     |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta en el análisis de requerimientos del sistema de compras en línea |
| Actor            | Cliente                             |
| Descripción      | El cliente revisa su carrito y confirma la compra de los productos. |
| Flujo básico     | 1. El cliente revisa los productos en su carrito.<br>2. El cliente confirma su dirección de envío.<br>3. El sistema calcula el total de la compra.<br>4. El cliente confirma el pedido. |
| Pre-condiciones  | El carrito debe contener productos. |
| Post-condiciones | El pedido queda registrado en el sistema. |
| Requerimientos   | Información de envío válida |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 04/11/2024               |

#### Realizar pago

| Caso de Uso CU.4 | Realizar pago                       |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta en el análisis de requerimientos del sistema de compras en línea |
| Actor            | Cliente                             |
| Descripción      | El cliente selecciona el método de pago y completa la compra. |
| Flujo básico     | 1. El cliente selecciona su método de pago.<br>2. El sistema procesa el pago.<br>3. Se confirma la compra al cliente. |
| Pre-condiciones  | Pedido registrado en el sistema y métodos de pago disponibles. |
| Post-condiciones | Pago confirmado y recibo enviado al cliente. |
| Requerimientos   | Método de pago activo |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 04/11/2024               |

#### Gestionar catálogo de productos (Administrador)

| Caso de Uso CU.5 | Gestionar catálogo de productos     |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta en el análisis de requerimientos del sistema de compras en línea |
| Actor            | Administrador                       |
| Descripción      | El administrador añade, modifica o elimina productos del catálogo de la tienda en línea. |
| Flujo básico     | 1. El administrador accede al catálogo de productos.<br>2. Añade, modifica o elimina un producto.<br>3. Guarda los cambios en el sistema. |
| Pre-condiciones  | El administrador debe estar autenticado en el sistema. |
| Post-condiciones | Los cambios en el catálogo se guardan y reflejan en la tienda en línea. |
| Requerimientos   | Acceso administrativo |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 04/11/2024               |

