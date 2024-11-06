# Proyecto Biblioteca.
## Diagrama de caso de uso de la biblioteca.



<img src="Diagrama sin título.drawio copy.png">

## Especificación de caso de uso de la biblioteca.


### Actores.

#### Ususario.

|  Actor | Ususario |
|---|---|
| Descripción  | Usuario común de la biblioteca.  |
| Características  |  |
| Relaciones | - Registrar un préstamo  |
| Referencias |- Buscar libros <br> - Pedir préstamo |   
|  Notas |   |
| Autor  | Carlos Antonio Díaz Galán |
|Fecha | 29/10/2024 |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

#### Bibliotecario.


|  Actor | Bibliotecario |
|---|---|
| Descripción  | Bibliotecario de la biblioteca.  |
| Características  | El bibliotecario realiza las mismas acciones que el Usuario y las acciones específicas. |
| Relaciones | Registrar un préstamo. |
| Referencias | - Solicitar prestamo <br> - Buscar libro. |   
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
| Referencias | - Enviar notificación <br> - Recordatiorio de una devolución. |   
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
  | Descripción | Permite buscar libros en la biblioteca mediante el catálogo  |
  | Flujo básico |1. El usuario ingresa sus credenciales. <br>2. El usuario ingresa el título o autor.<br>3. El sistema muestra los resultados.<br>4. El usuario selecciona un libro.<br>5. El usuario solicita un libro. |
  | Pre-condiciones | El usuario tiene que estar dado de alta en el sistema.  |  
  | Post-condiciones  | Se muestran los resultados.  |  
  |  Requerimientos | Catálogo de libros.  |
  |  Notas |  _Notas adicionales_ |
  | Autor  | Carlos Antonio Díaz Galán |
  |Fecha | 29/10/2024 |

#### Registrar préstamo

| Caso de Uso CU.2 | Registrar préstamo               |
|------------------|----------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Usuario, bibliotecario           |
| Descripción      | Permite registrar un préstamo de libro solicitado por un usuario. |
| Flujo básico     | 1. El bibliotecario selecciona el libro solicitado por el usuario.<br>2. Se verifica la disponibilidad del libro.<br>3. Se registra el préstamo y se actualiza el estado del libro.<br>4. El sistema genera una fecha de devolución. |
| Pre-condiciones  | El usuario debe tener una cuenta activa y el libro debe estar disponible. |
| Post-condiciones | El libro queda registrado como prestado y la fecha de devolución se establece. |
| Requerimientos   | Sistema de registro de préstamos y disponibilidad del libro |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 29/10/2024               |

#### Enviar notificación

| Caso de Uso CU.3 | Enviar notificación               |
|------------------|-----------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Sistema de notificación           |
| Descripción      | Envía una notificación de recordatorio a los usuarios sobre la fecha de devolución de un libro. |
| Flujo básico     | 1. El sistema revisa los préstamos activos.<br>2. Se identifican los préstamos próximos a vencer.<br>3. Se envía una notificación de recordatorio al usuario. |
| Pre-condiciones  | Debe haber préstamos activos en el sistema. |
| Post-condiciones | El usuario recibe una notificación de recordatorio. |
| Requerimientos   | Sistema de notificación y contacto del usuario |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 29/10/2024               |

#### Recordar devolución

| Caso de Uso CU.4 | Recordar devolución               |
|------------------|-----------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Sistema de notificación           |
| Descripción      | El sistema envía un recordatorio de devolución al usuario cuando se aproxima la fecha de vencimiento. |
| Flujo básico     | 1. El sistema identifica los préstamos próximos a vencer.<br>2. Se genera una notificación de recordatorio.<br>3. El usuario recibe la notificación. |
| Pre-condiciones  | Debe haber una fecha de vencimiento próxima para el préstamo del libro. |
| Post-condiciones | El usuario es notificado del próximo vencimiento del préstamo. |
| Requerimientos   | Sistema de notificación y contacto del usuario |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 29/10/2024               |

---


# Proyecto ejercicio 2. Sistema de compras en Línea.

## Diagrama de caso de uso de la tienda en línea

<img src="Diagrama sistema de compras en linea.drawio.png">

## Especificación de caso de uso de la tienda en línea

### Actores

#### Cliente

|  Actor          | Cliente                  |
|-----------------|--------------------------|
| Descripción     | Usuario común de la tienda en línea. |
| Características | Cliente que puede navegar, comprar y pagar productos en la plataforma. |
| Relaciones      | Agregar productos al carrito, Realizar pedido, Realizar pago |
| Referencias     | Buscar productos, Añadir productos al carrito, Pagar el pedido |
| Notas           |                          |
| Autor           | Carlos Antonio Díaz Galán |
| Fecha           | 04/11/2024               |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

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

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

### Casos de uso

#### Buscar productos

| Caso de Uso CU.1 | Buscar productos                    |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
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
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
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
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
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
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
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
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Administrador                       |
| Descripción      | El administrador añade, modifica o elimina productos del catálogo de la tienda en línea. |
| Flujo básico     | 1. El administrador accede al catálogo de productos.<br>2. Añade, modifica o elimina un producto.<br>3. Guarda los cambios en el sistema. |
| Pre-condiciones  | El administrador debe estar autenticado en el sistema. |
| Post-condiciones | Los cambios en el catálogo se guardan y reflejan en la tienda en línea. |
| Requerimientos   | Acceso administrativo |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 04/11/2024               |

---

# Proyecto ejercicio 3. Sistema de Gestión de cursos en línea.

## Diagrama de caso de uso del sistema de gestión de cursos en línea.

<img src="Diagrama sistema de gestión de cursos en línea .drawio.png">

## Especificación de caso de uso de cursos en línea.

# Proyecto Sistema de Gestión de Cursos en Línea
## Diagrama de caso de uso del sistema de gestión de cursos en línea

<img src="Diagrama_Gestion_Cursos_En_Linea.drawio.png">

## Especificación de caso de uso del sistema de gestión de cursos en línea

### Actores

#### Estudiante

|  Actor          | Estudiante                |
|-----------------|---------------------------|
| Descripción     | Usuario que se inscribe en cursos, visualiza el contenido del curso y realiza evaluaciones. |
| Características | Puede navegar por los cursos disponibles, inscribirse en ellos, ver el material y completar evaluaciones. |
| Relaciones      | Inscribirse en curso, Ver material del curso, Realizar evaluaciones |
| Referencias     | Acceso a cursos y evaluaciones |
| Notas           |                          |
| Autor           | Carlos Antonio Díaz Galán |
| Fecha           | 06/11/2024               |

|  Atributo       |||
|-----------------|---------------------------|-------------------|
| _Nombre_        | _Descripción_             | _Tipo_           |
| | | |

#### Profesor

|  Actor          | Profesor                  |
|-----------------|---------------------------|
| Descripción     | Usuario responsable de crear y gestionar los cursos, así como de calificar las evaluaciones de los estudiantes. |
| Características | Puede crear, modificar y actualizar los cursos, además de gestionar las evaluaciones. |
| Relaciones      | Crear curso, Actualizar contenido del curso, Calificar evaluaciones |
| Referencias     | Administración de cursos y evaluaciones |
| Notas           |                          |
| Autor           | Carlos Antonio Díaz Galán |
| Fecha           | 06/11/2024               |

|  Atributo       |||
|-----------------|---------------------------|-------------------|
| _Nombre_        | _Descripción_             | _Tipo_           |
| | | |

### Casos de uso

#### Inscribirse en curso

| Caso de Uso CU.1 | Inscribirse en curso                |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Estudiante                          |
| Descripción      | El estudiante se inscribe en un curso disponible en la plataforma. |
| Flujo básico     | 1. El estudiante selecciona un curso.<br>2. La plataforma muestra el curso.<br>3. El estudiante se inscribe. |
| Pre-condiciones  | El estudiante debe estar registrado en la plataforma. |
| Post-condiciones | El estudiante queda inscrito y tiene acceso al contenido del curso. |
| Requerimientos   | Acceso a los cursos en la plataforma |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |

#### Ver material del curso

| Caso de Uso CU.2 | Ver material del curso              |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Estudiante                          |
| Descripción      | El estudiante accede al contenido del curso en el que está inscrito. |
| Flujo básico     | 1. El estudiante selecciona el curso.<br>2. El sistema despliega el material de estudio. |
| Pre-condiciones  | El estudiante debe estar inscrito en el curso. |
| Post-condiciones | El contenido se muestra al estudiante. |
| Requerimientos   | Conexión a internet, Contenido disponible en la base de datos |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |

#### Realizar evaluaciones

| Caso de Uso CU.3 | Realizar evaluaciones               |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Estudiante                          |
| Descripción      | El estudiante completa las evaluaciones del curso en el que está inscrito. |
| Flujo básico     | 1. El estudiante selecciona la evaluación.<br>2. El sistema presenta las preguntas.<br>3. El estudiante responde y envía la evaluación. |
| Pre-condiciones  | El estudiante debe estar inscrito en el curso y la evaluación debe estar disponible. |
| Post-condiciones | La evaluación queda registrada y lista para calificar. |
| Requerimientos   | Conexión a internet, Evaluación configurada |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |

#### Crear curso

| Caso de Uso CU.4 | Crear curso                         |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Profesor                            |
| Descripción      | El profesor crea un nuevo curso en la plataforma, definiendo el contenido y las evaluaciones. |
| Flujo básico     | 1. El profesor accede a la sección de administración de cursos.<br>2. Introduce el nombre y descripción del curso.<br>3. Añade el contenido y las evaluaciones. |
| Pre-condiciones  | El profesor debe estar autenticado en el sistema. |
| Post-condiciones | El curso queda disponible para inscripción. |
| Requerimientos   | Herramienta de edición de cursos |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |

#### Calificar evaluaciones

| Caso de Uso CU.5 | Calificar evaluaciones              |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Profesor                            |
| Descripción      | El profesor revisa y califica las evaluaciones completadas por los estudiantes. |
| Flujo básico     | 1. El profesor accede a las evaluaciones del curso.<br>2. Revisa las respuestas de los estudiantes.<br>3. Asigna una calificación. |
| Pre-condiciones  | La evaluación debe haber sido completada por el estudiante. |
| Post-condiciones | La calificación se registra en el sistema. |
| Requerimientos   | Conexión a internet |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |

#### Actualizar contenido del curso

| Caso de Uso CU.6 | Actualizar contenido del curso      |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta gracias al [documento]() |
| Actor            | Profesor                            |
| Descripción      | El profesor actualiza el contenido de un curso para mantenerlo al día. |
| Flujo básico     | 1. El profesor accede al curso.<br>2. Selecciona la opción de actualizar contenido.<br>3. Modifica o añade material. |
| Pre-condiciones  | El curso debe estar creado y el profesor autenticado. |
| Post-condiciones | El contenido actualizado se refleja en el curso. |
| Requerimientos   | Herramienta de edición de contenido |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |
