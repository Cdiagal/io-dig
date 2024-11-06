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

|  Atributo       |||
|-----------------|--------------------------|-------------------|
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
| Nombre          | Nombre del estudiante     | Texto            |
| Correo electrónico | Email de contacto       | Texto            |
| Progreso        | Avance en el curso        | Porcentaje       |

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
| ID de empleado  | Identificación del profesor | Numérico      |
| Asignatura      | Curso asignado            | Texto            |
| Calificaciones  | Calificaciones de los estudiantes | Registro |

### Casos de uso

#### Inscribirse en curso

| Caso de Uso CU.1 | Inscribirse en curso                |
|------------------|-------------------------------------|
| Fuentes          | Este caso de uso se sustenta en los requisitos de inscripción para estudiantes |
| Actor            | Estudiante                          |
| Descripción      | El estudiante se inscribe en un curso disponible en la plataforma. |
| Flujo básico     | 1. El estudiante selecciona un curso.<br>2. La plataforma muestra los detalles del curso.<br>3. El estudiante confirma su inscripción. |
| Pre-condiciones  | El estudiante debe estar registrado en la plataforma. |
| Post-condiciones | El estudiante queda inscrito y tiene acceso al contenido del curso. |
| Requerimientos   | Acceso a los cursos en la plataforma |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |

#### Ver material del curso

| Caso de Uso CU.2 | Ver material del curso              |
|------------------|-------------------------------------|
| Fuentes          | Basado en la funcionalidad de visualización de contenidos del curso |
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
| Fuentes          | Basado en los requisitos de evaluación de los cursos |
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
| Fuentes          | Este caso de uso se sustenta en la funcionalidad de gestión de cursos |
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
| Fuentes          | Basado en la funcionalidad de calificación |
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
| Fuentes          | Basado en la necesidad de edición de contenidos |
| Actor            | Profesor                            |
| Descripción      | El profesor actualiza el contenido de un curso para mantenerlo al día. |
| Flujo básico     | 1. El profesor accede al curso.<br>2. Selecciona la opción de actualizar contenido.<br>3. Modifica o añade material. |
| Pre-condiciones  | El curso debe estar creado y el profesor autenticado. |
| Post-condiciones | El contenido actualizado se refleja en el curso. |
| Requerimientos   | Herramienta de edición de contenido |
| Notas            |                          |
| Autor            | Carlos Antonio Díaz Galán |
| Fecha            | 06/11/2024               |
