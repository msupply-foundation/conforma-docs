+++
title = "Languages"
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


All the strings that make up the system, except the forms which are managed seperately, can be localised into different languages. 

On this configuration page you can export and import the file that lists all the words in each language. And also enable/disable a language in the application.

## Enabling a language

In the menu bar, go to the **Configuration** menu, then click **Localisations**

![Localisations table menu](/docs/about/demo/menu2.png)

The available languages will be displayed. Check the box of any languages you wish to enable. 

![Localisations menu](/docs/about/demo/localisationui.png)

If multiple languages are enabled, users will be able to select the language they wish to operate with. 

![Localisations switch](/docs/about/demo/lsd.png)


## Viewing the localisation strings

Use the Export button to download and view a csv of the configured language strings and translations. 

![Export strings](/docs/about/demo/importlang.png)


## Editing strings for an existing localisation

Export the current configured languages csv file. 

Within the csv edit the strings as required and save the updated file. 

Then click **Import button** and upload the updated csv file. Your changes will now be implemented. 

![import button](/docs/about/demo/importl1.png)


## Adding a new language 

Export the current configured languages csv file. 

Within the csv fill out in a new column the basics about the language you wish to include in the system including the name, description and whether the language is to be enabled. 

![language spreadsheet](/docs/about/demo/lglsht.png)

Within the new column enter in the translated strings, if a cell is left blank it will default to the system default string. 

Once you have completed entering the required strings for your new localisation language save and import the file. 

The new language will appear within the languages configuration page and can be enabled for use. 

![Updated language](/docs/about/demo/uplgl.png)


----------

To learn more about how localisation works in Conforma, check out our developer [docs](https://github.com/openmsupply/conforma-web-app/wiki/Localisation). 






