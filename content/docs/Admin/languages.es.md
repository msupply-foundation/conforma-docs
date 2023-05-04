+++
title = "Idiomas"
description = "Languages"
date = 2021-05-01T08:20:00+00:00
updated = 2021-05-01T08:20:00+00:00
draft = false
weight = 51
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = ""
toc = true
top = false
+++


Todas las cadenas de localización que conforman el sistema, excepto los formularios que se gestionan de forma separada, se pueden localizar en diferentes idiomas.

En esta página de configuración, puedes exportar e importar el archivo que lista todas las palabras en cada idioma. También puedes habilitar o deshabilitar un idioma en la solicitud.

## Habilitar un idioma

En la barra de menú, ve al menú **Configuración**, y luego haz clic en **Localizaciones**

![Localisations table menu](/docs/about/demo/menu2.png)

Se mostrarán los idiomas disponibles. Marca la casilla de cualquier idioma que desees habilitar.

![Localisations menu](/docs/about/demo/localisationui.png)

Si se habilitan varios idiomas, los usuarios podrán seleccionar el idioma con el que desean trabajar 

![Localisations switch](/docs/about/demo/lsd.png)


## Ver cadenas de localización


Usa el botón Exportar para descargar y ver un archivo csv de las cadenas de localización configuradas y sus traducciones.

![Export strings](/docs/about/demo/importlang.png)


## Editar cadenas para una localización que ya existe

Exporte el archivo CSV de los idiomas configurados actualmente. 

Dentro del archivo CSV, edite las cadenas según sea necesario y guarde el archivo actualizado. 

Luego, haga clic en el botón **Importar** ay cargue el archivo CSV actualizado. Los cambios se implementarán a partir de entonces. 

![import button](/docs/about/demo/importl1.png)


## Agregar un nuevo idioma

Exporta el archivo CSV de idiomas configurados actualmente. 

Dentro del archivo CSV, agrega en una nueva columna los detalles básicos sobre el idioma que deseas incluir en el sistema, incluyendo el nombre, la descripción y si el idioma debe estar habilitado.

![language spreadsheet](/docs/about/demo/lglsht.png)

En la nueva columna, ingresa las cadenas traducidas. Si se deja una celda en blanco, se utilizará la cadena predeterminada del sistema. 

Una vez que hayas completado la entrada de las cadenas necesarias para el nuevo idioma de localización, guarda e importa el archivo. 

El nuevo idioma aparecerá en la página de configuración de idiomas y se puede habilitar para su uso.

![Updated language](/docs/about/demo/uplgl.png)


----------

Para obtener más información sobre cómo funciona la localización en Conforma, consulta nuestra página de desarrollo. [docs](https://github.com/openmsupply/conforma-web-app/wiki/Localisation). 






