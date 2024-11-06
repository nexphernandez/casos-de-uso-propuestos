# Proyecto biblioteca.

## Diagrama de casos de uso Sistema de Biblioteca.

<img src="images\Casos-uso.drawio.png">

## Especificación de casos de uso de la biblioteca.

### Actores

  #### Usuario

|  Actor | Usuario |
|---|---|
| Descripción  | Usario común de la biblioteca. |
| Características  ||
| Relaciones |  |
| Referencias | Buscar libro,  pedir prestamo, devolver libro. |   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

  #### Bibliotecario

| Actor | Bibliotecario |
|---|---|
| Descripción | Bibliotecario de la bibloteca. |
| Características | El bibliotecario realiza las mimas acciones que el Usuario y las acciones especifícas. |
| Relaciones | Registrar prestamo, devolver libro. |
| Referencias | Buscar libro,  pedir prestamo, devolver libro, gestionar inventario, registrar prestamo. |   
| Notas ||
| Autor | Nicolás Expósito Hernandez |
| Fecha | 05/11/2024 |

### Casos de uso

  #### Buscar libro

  |	CU.1 | Buscar libro |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento](). |
  | Actor  |  Usuario y bibliotecario.|
  | Descripción | Buscar un libro en la biblioteca. |
  | Flujo básico | El actor busca un libro en la biblioteca |
  | Pre-condiciones | Que hayan libros que buscar |  
  | Post-condiciones ||  
  |  Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  | Fecha | 05/11/2024 |

  #### Pedir prestamo

  | CU.2 | Pedir prestamo  |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  |  Usuario, Bibliotecario. |
  | Descripción | Solicitar llevarse un libro de la biblioteca |
  | Flujo básico | El actor solicita llevarse un libro de la biblioteca |
  | Pre-condiciones | Que hayan libros que solicitar  |  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

  #### Devolver libro

  | CU.3 | Devolver ibro |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  |  Usuario, Bibliotecario. |
  | Descripción | El actor devuelve un libro a la biblioteca. |
  | Flujo básico | El actor devuelve un libro a la biblioteca. |
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

#### Gestinar inventario

  | CU.4 | Gestinar inventario |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Bibliotecario. |
  | Descripción | El actor gestiona el inventario |
  | Flujo básico | El actor gestiona el inventario |
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

#### Registrar prestamos

  | CU.5 | Registrar prestamos |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Bibliotecario. |
  | Descripción | El actor registra un prestamo |
  | Flujo básico | El actor registra un prestamo |
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

## Sistema de Compras en Línea.

<img src="images\sistema-de-compras-en-linea.drawio.png">

## Especificación de casos de uso de Sistema de Compras en Línea.

### Actores

  #### Cliente

|  Actor | Cliente |
|---|---|
| Descripción  | Cliente común del sistema de compras. |
| Características  ||
| Relaciones ||
| Referencias | Buscar productos, Añadir productos al carrito, Realizar pedido |   
|  Notas ||
| Autor  | Nicolás Expósito Hernández |
|Fecha | 05/11/2024 |

  #### Administrador

| Actor | Administrador |
|---|---|
| Descripción | Administrador del sistema de compras |
| Características | El Administrador realiza las mimas acciones que el Cliente y las acciones especifícas. |
| Relaciones | Buscar productos, Añadir productos al carrito, Realizar pedido |
| Referencias | Gestionar catálogo de productos |   
| Notas ||
| Autor | Nicolás Expósito Hernández |
| Fecha | 05/11/2024 |

### Casos de uso

  #### Buscar productos

  |	CU.1 | Buscar productos |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento](). |
  | Actor  | Cliente, Administrador |
  | Descripción | Buscar un producto en la pagina. |
  | Flujo básico | El autor busca un producto en la pagina.|
  | Pre-condiciones ||  
  | Post-condiciones ||  
  |  Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  | Fecha | 05/11/2024 |

  #### Añadir productos al carrito

  | CU.2 | Añadir productos al carrito  |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Cliente, Administrador |
  | Descripción | Añadir un producto a su carrito |
  | Flujo básico | El actor añade un producto a su carrito |
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

  #### Realizar pedido

  | CU.3 | Realizar pedido |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Cliente, Administrador |
  | Descripción | Realizar un pedido |
  | Flujo básico | El actor realiza un pedido |
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

#### Realizar pago

  | CU.4 | Realizar pago |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Cliente, Administrador |
  | Descripción | Realizar el pago |
  | Flujo básico | El actor realiza el pago |
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

#### Gestionar catálogo de productos

  | CU.5 | Gestionar catálogo de productos |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Administrador |
  | Descripción | Restionar los productos |
  | Flujo básico | El actor gestiona los productos |
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

## Sistema de Gestión de Cursos en Línea

<img src="images\sistema-de-gestion-de-cursos-en-linea.drawio.png">

### Actores

#### Estudiante

| Actor | Estudiante |
|---|---|
| Descripción | Estudiante común de cursos en linea |
| Características ||
| Relaciones ||
| Referencias |Inscribirse en cursos, visualizar el material y realizar evaluaciones. |   
| Notas ||
| Autor | Nicolás Expósito Hernández |
| Fecha | 05/11/2024 |

#### Profesor

| Actor | Profesor |
|---|---|
| Descripción | Profesor común de cursos en linea |
| Características ||
| Relaciones | Inscribirse en cursos, visualizar el material y realizar evaluaciones. |
| Referencias | Crear cursos, actualizar el contenido y calificar evaluaciones. |   
| Notas ||
| Autor | Nicolás Expósito Hernández |
| Fecha | 05/11/2024 |

### Casos de uso

#### Inscribirse en curso

  | CU.1 | Inscribirse en curso |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Estudiante, profesor |
  | Descripción | El actor se inscribe a un curso |
  | Flujo básico ||
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

  #### Ver material del curso

  | CU.2 | Ver material del curso |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Estudiante, profesor |
  | Descripción | El actor ve el material del curso |
  | Flujo básico ||
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

  #### Realizar evaluaciones

  | CU.3 | Realizar evaluaciones |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Estudiante, profesor |
  | Descripción | El actor realiza evaluaciones |
  | Flujo básico ||
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

  #### Crear curso

  | CU.4 | Crear curso |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Profesor |
  | Descripción | El actor crea cursos |
  | Flujo básico ||
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

  #### Calificar evaluaciones

  | CU.5 | Calificar evaluaciones |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Profesor |
  | Descripción | El actor califica evaluaciones |
  | Flujo básico ||
  | Pre-condiciones ||  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |

  #### Actualizar contenido del curso

  | CU.6 | Actualizar contenido del curso |
  |---|---|
  | Fuentes  | Este caso de uso se sustenta gracias al documento [documento]().  |
  | Actor  | Profesor |
  | Descripción | El actor actualiza contenido del curso |
  | Flujo básico ||
  | Pre-condiciones | Que el curso haya sido creado |  
  | Post-condiciones  ||  
  | Requerimientos ||
  |  Notas ||
  | Autor  | Nicolás Expósito Hernández |
  |Fecha | 05/11/2024 |