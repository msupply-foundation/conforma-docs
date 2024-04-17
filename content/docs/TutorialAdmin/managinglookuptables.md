+++
title = "Managing Lookup Tables"
description = "How to manage Lookup Tables"
date = 2021-05-01T18:10:00+00:00
updated = 2023-08-01T18:10:00+00:00
draft = false
weight = 64
sort_by = "weight"
template = "docs/page.html"

[extra]
toc = true

+++

Users with Admin permissions (or System Managers) are able to manage lookup tables within the Conforma system.

Lookup tables contain data which may be referenced by the application form, such as a list of ingredients to populate a drop-down list.

## Viewing lookup tables
1. Go to the Manage menu in the menu bar, then click <b>Lookup Tables</b>

![lookup tables](/docs/about/demo/lookup.png)

<div class="tip">
Note: if you are an admin user that does not have System Manager permissions, you will find Lookup Tables under the Configuration dropdown.
</div> 

The configuration options for the lookup tables are displayed to the right of each lookup table. These buttons allow you to:

a. View the lookup table and data

b. Update the lookup table

c. Export the lookup table data

![lookup tables](/docs/about/demo/lookup2.png)

To view the contents of a lookup table, click on the eye icon for the lookup table you wish to view.

![lookup tables](/docs/about/demo/lookupgif.gif)

## Exporting a lookup table

1. Click the orange <b>export</b> button to download a copy of the lookup table as a .csv file

## Editing a lookup table
Existing lookup tables can be updated by either:

a. <b>Editing</b> an existing row

b. <b>Adding</b> a new row into the table

c. <b>Deleting</b> a row from the table

### a. Editing an existing row:
1. Export a copy of the lookup table.

2. Within the .csv file, make your changes and save the file. <b>Note: Do not edit the ID column in the csv</b>

![lookup tables](/docs/about/demo/lookup3.png)

3. From the lookup table management page, click the <b>upload</b> icon that corresponds to the correct table.

![lookup tables](/docs/about/demo/export.gif)

### b. Adding a new row into the table
1. Export a copy of the lookup table

2. At the bottom of the .csv, add your new row without populating the ID column, the system will generate the correct ID automatically

![lookup tables](/docs/about/demo/lookup4.png)

3. From the lookup table management page, click the <b>upload</b> icon that corresponds to the correct table

4. After importing, the new values can now be referenced in the lookup table.

### c. Deleting a row from the table
1. Export a copy of the lookup table

2. Delete the rows that you wish to remove from the table

3. Save the .csv and reupload it using the <b>upload</b> icon that corresponds to the correct table. 
