# Usuario

Muestra y permite modificar la configuración del usuario actual.

Para dar de alta un usuario, puede hacerlo un manager manualmente mediante `Nuevo usuario` o proporcionar una invitación para que el proveedor se registre mediante [Emails de registro](referencia/ajustes.md#emails-de-registro).

## General

Información general acerca del usuario actual. Es obligatiorio rellenar los campos `Nombre`, `Email` y [Rol](#rol).

### Rol

Capacidades que va a tener el usuario dentro de Argos TS. Existen los siguientes roles:

1. `Translator`: Únicamente puede recibr encargos y consultar el histórico de trabajos que ha realizado previamente.
2. `Manager`: Tiene habilitadas las funciones de gestión. Puede leer, crear, modificar o borrar cualquier contenido.
3. `Support`: Rol con las mismas capacidades que `Manager` creado para diferenciar al equipo de producción con el de soporte.

## Tasas

Lista de tarifas especificada por el propio traductor o por un manager para cada combinación ligüística y [Tipo de Trabajo](referencia/proyecto.md#tipo-de-trabajo).

Para añadir una nueva tasa, deben rellenarse los campos `Idioma Origen`, `Idioma Destino`, `Tipo de Trabajo` y `Tasa` y pulsar el botón `Añadir`.

Las tarifas que estén reflejadas en la tabla, se cargarán automáticamente en la [Nota de entrega](referencia/trabajo.md#nota-de-entrega) cuando se encargue un trabajo al proveedor actual.
