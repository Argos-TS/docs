# Ajustes

Muestra la configuración interna de la plataforma. Los usuarios con rol `Translator` sólo podrán acceder al apartado [Perfil](#perfil), mientras que los que pertenezcan a los roles `Manager` y `Support` podrán acceder a todos los apartados.

## Perfil

### General

Información del usuario que está logeado. Los campos que se muestran son:

- `Nombre`
- `Apellidos`
- `Email`
- `Teléfono`
- `Imagen de Perfil`

### Tasas

`No editable`

Tarifas del usuario que está logeado.

## Empresa

Información general sobre la empresa que ha contratado la plataforma.

## Conjuntos de Archivos

Existen situaciones en las que se quiete adjuntar una serie de archivos a múltiples proyectos, como pueden ser guías de estilos o archivos de glosarios. Se pueden dar de alta conjuntos de archivos que pueden ser asociados a los proyectso mediante el campo [Proyecto > Adjuntar Conjunto de Archivos](referencia/proyecto.md#conjuntos-de-archivos).

En esta sección se muestra la lista de los conjuntos de archivos que se han dado de alta.

### Nuevo Conjunto de Archivos

Haciendo click en este botón, se abre un formulario con el que dar de alta un conjunto de archivos.

#### Nombre (Conjunto de archivos)

Nombre del conjunto de archivos actual

#### Archivos

Archivos que conforman el conjunto de archivos actual. Para añadir nuevos archivos, basta con arrastrarlos a la caja que lo indica o seleccionarlos en la ventana que aparece al hacer click en ella.

## Idiomas

Lista de idiomas que han sido dados de alta en la plataforma. Algunos de ellos no son editables para evitar perder la funcionalidad de traducción automática en ellos.

Al hacer click en `Nuevo` se inserta una fila vacía para añadir un nuevo idioma.

### Nombre (Idiomas)

Nombre del idioma que ha sido dado de alta.

### Abreviatura

Abreviatura que será utilizada en otros paneles para mostrar parejas de idiomas. Debe es posibe dar de alta dos registros que contengan una abreviatura igual.

## Tipos de Trabajo

Lista de tipos de trabajo que han sido dados de alta en la plataforma. Algunos de ellos no son editables para evitar perder la funcionalidad de traducción automática.

Al hacer click en `Nuevo` se inserta una fila vacía para añadir un tipo de trabajo.

Para más información sobre los tipos de trabajo, consultar [Proyecto > Trabajos > Tipo de Trabajo](referencia/proyecto.md#tipo-de-trabajo).

### Nombre (Tipos de Trabajo)

Nombre del tipo de trabajo que ha sido dado de alta.

### Unidad de Trabajo

Unidad en la que se mide el tipo de trabajo. Por ejemplo `Palabras` u `Horas`.

## Tipos de texto

Lista de tipos de texto que han sido dados de alta en la plataforma.

Al hacer click en `Nuevo` se inserta una fila vacía para añadir un nuevo tipo de texto.

### Nombre (Tipos de texto)

Nombre del tipo de texto que ha sido dado de alta.

## Sectores

Lista de sectores que han sido dados de alta en la plataforma.

Al hacer click en `Nuevo` se inserta una fila vacía para añadir un nuevo sector.

### Nombre (Sectores)

Nombre del sector que ha sido dado de alta.

## Otros Ajustes

### Tiempo de Espera

Tiempo que tiene que pasar hasta que se genere una notificación al manager avisando de que un proveedor no ha respondido aún a una oferta.

## Tasas por defecto

Lista de tarifas que serán aplicadas cuando no se haya dado de alta una tarifa para los clientes con la misma combinación de campos (`Tipo de Trabajo`, `Tipo de Texto`, `Sector`, `Idioma Origen`, `Idioma Destino`).

Para más información, consultar [Cliente > Tasas](referencia/cliente.md#tasas).

## Email de registro

Para dar de alta un proveedor, puede hacerlo el manager mediante el panel [Usuario](referencia/usuario.md#usuario) o puede mandarse un enlace de invitación para que sea el proveedor quien introduzca sus datos y tarifas.

Para mandar una invitación hay que escribir la dirección de email del proveedor a invitar en el campo `Email` y pulsar el botón `Enviar Email de Invitación`.
