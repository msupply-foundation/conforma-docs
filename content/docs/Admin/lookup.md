+++
title = "Lookup Tables"
description = "Managing Lookup tables"
date = 2021-05-01T08:20:00+00:00
updated = 2021-05-01T08:20:00+00:00
draft = false
weight = 46
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = ""
toc = true
top = false
+++

Users with Admin permissions are able to manage Lookup tables within the system. 

Lookup tables contain data which may be referenced by the application form, such as a list of ingredients. 

The configuration options for the lookup tables are displayed to the right of each lookup table.

![conif buttons](/docs/about/demo/buttons1.png)

These buttons allow you to:
- View the table and data
- Update the table
- Export the table data

## Viewing lookup tables

In the menu bar, go to the **Configuration** menu, then click **Lookup tables**

![Lookup table menu](/docs/about/demo/lookup1.png)


To view the contents of a lookup table click on the eye icon for the lookup table you wish to view. 

![Lookup tables](/docs/about/demo/lookupgif.gif)


## Exporting a lookup table

Click the orange export button to download a copy of the lookup table. 

![Lookup tables](/docs/about/demo/Lookuptable.gif)


## Editing a lookup table

Existing Lookup tables can be updated by either:
- Editing an existing row
- Adding a new row into the table

**Editing an existing row**

1. Export a copy of the lookup table. 

2. Within the csv file make your changes and save the file. Do not edit the ID value in the csv.

![Edit value](/docs/about/demo/editlook.png)

3. From the lookup table management page, click the upload button that corresponds to the correct table. 

![export](/docs/about/demo/export.gif)

**Adding a new row**

1. Export a copy of the lookup table. 

2. At the bottom of the csv add your new row without populating the ID column, the system will generate the correct ID. 

![add new row](/docs/about/demo/addnew.png)

3. From the lookup table management page, click the upload button that corresponds to the correct table. 

4. After import the new values can now referenced in the Lookup table. 










