+++
title = "Tablas de Búsqueda"
description = "Managing Lookup tables"
date = 2021-05-01T08:20:00+00:00
updated = 2021-05-01T08:20:00+00:00
draft = false
weight = 50
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = ""
toc = true
top = false
+++

Los usuarios con permisos de Administrador pueden gestionar las tablas de búsqueda dentro del sistema.

Las tablas de búsqueda contienen datos que pueden ser referenciados por el formulario de solicitud, como una lista de ingredientes. 

Las opciones de configuración para las tablas de búsqueda se muestran a la derecha de cada tabla. Estos botones le permiten:
- Ver la tabla y los datos
- Actualizar la tabla
- Exportar los datos de la tabla

![conif buttons](/docs/about/demo/buttons1.png)


## Ver las Tablas de búsqueda

En la barra de menú, ve al menú de **Configuración**, luego haz clic **Tablas de búsqueda**

![Lookup table menu](/docs/about/demo/lookup1.png)


Para ver el contenido de una tabla de búsqueda, haz clic en el icono de ojo para la tabla de búsqueda que deseas ver.

![Lookup tables](/docs/about/demo/lookupgif.gif)


## Exportar una tabla de búsqueda

Haz clic en el botón naranja de exportación para descargar una copia de la tabla de búsqueda.

![Lookup tables](/docs/about/demo/Lookuptable.gif)


## Editar una tabña de búsqueda

Las tablas de búsqueda existentes se pueden actualizar ya sea:
- Editando una fila existente
- Agregando una nueva fila en la table

**Editar una fila existente**

1. Exporta una copia de la tabla de búsqueda. 

2. En el archivo CSV, realiza los cambios necesarios y guarda el archivo. No edites el valor de ID en el archivo CSV.

![Edit value](/docs/about/demo/editlook.png)

3. Desde la página de gestión de tablas de búsqueda, haz clic en el botón de carga que corresponde a la tabla correcta.

![export](/docs/about/demo/export.gif)

**Agrega una nueva fila**

1. Exporta una copia de la tabla de búsqueda. 

2. En la parte inferior del archivo CSV agrega una nueva fila sin completar la columna ID, el sistema generará el ID correcto. 

![add new row](/docs/about/demo/addnew.png)

3. Desde la página de gestión de la tabla de búsqueda, haz clic en el botón de carga que corresponda a la tabla correcta. 

4. Después de importar, los nuevos valores ahora pueden ser referenciados en la tabla de búsqueda. 










