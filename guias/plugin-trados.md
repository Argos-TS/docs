# Cómo utilizar los motores de Argos TS en SDL Trados Studio 2021

Desde [Argos TS](https://argos-ts.com/) ofrecemos motores de traducción a medida según el tipo de texto y combinación lingüística. Integrar este servicio en SDL Trados Studio es muy sencillo:

## Instalar el plugin

### Mediante la versión web de SDL AppStore

Para poder utilizar el servicio de `Traducción Automática` es necesario instalar el plugin de [Argos TS](https://argos-ts.com/) a través del siguiente enlace:

[Descargar Argos TS MT desde SDL AppStore](https://appstore.sdl.com/language/app/argos-ts-mt/1199/)

Una vez entremos debemos descargar el plugin haciendo click en el botón `Download` señalado en la siguiente imagen:

![SDL AppStore](../_media/sdl-appstore-online.png)

Una vez instalado procederemos a [Crear un nuevo proyecto](#crear-un-nuevo-proyecto).

### Mediante SDL AppStore integrado en SDL Trados

También tenemos la posibilidad de utilizar el servicio de `Traducción Automática` instalando el plugin de [Argos TS](https://argos-ts.com/) mediante el AppStore integrado en SDL Trados. Para instalarlo, debemos hacer lick en el botón `SDL AppStore` que está señalado y buscar el plugin `Argos TS`. Una vez lo encontremos, haremos click en `Instalar`.

![SDL AppStore](../_media/trados-appstore.png)

Una vez instalado procederemos a [Crear un nuevo proyecto](#crear-un-nuevo-proyecto).

## Crear un nuevo proyecto

Una vez está instalado el plugin, podemos proceder a crear un nuevo proyecto. A la hora de configurar las combinaciones lingüísticas, Trados nos permite seleccionar recursos para ayudar en el proceso de traducción. Escogeremos el motor [Argos TS](https://argos-ts.com/) tal y como se muestra en la siguiente imagen:

![Motor de traducción](../_media/nuevo-proyecto-trados.png)

## Selección del motor de traducción

Cuando seleccionemos el proveedor de `Traducción Automática`, nos mostrará el siguiente diálogo:

![Motor de traducción](../_media/plugin-trados.png)

En este cuadro debemos introducir la clave de API que se nos haya previsto previamente. Para conseguir una clave nueva, puede solicitarse mediante [este enlace](https://argos-ts.com/contacto/).
Al introducir la clave, se nos mostrarán los motores disponibles para la combinación lingüística seleccionada. Debemos seleccionar cuál es el idóneo para el tipo de texto que queramos traducir y hacemos click en `OK`.

## Traducción del documento

A partir de este punto ya podremos utilizar el motor seleccionado para la traducción en curso. Simplemente al hacer click en un segmento de destino vacío, éste cargará la `Traducción Automática`. De manera similar podemos cargar en lote la traducción de todos los segmentos mediante la función `Pretraducir documento` que ofrece SDL Trados Studio.
