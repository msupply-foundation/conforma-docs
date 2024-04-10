+++
title = "Configuring Languages"
description = "How to Edit languages"
date = 2021-05-01T18:10:00+00:00
updated = 2023-08-01T18:10:00+00:00
draft = false
weight = 66
sort_by = "weight"
template = "docs/page.html"

[extra]
toc = true

+++

All the strings that make up the Conforma system (except for the forms, which are managed separately), can be localised into different languages.

In the Conforma localisations configuration page, you can export and import the file that lists all the words in each language for use in the system. You can also manage languages by enabling/disabling them within the application.

## Enabling a language
1. In the menu bar, go to the Configuration drop-down menu, then click <b>Localisations</b>

![Configuring languages](/docs/about/demo/lang1.png)

2. The available languages will be displayed. Check the box of any languages you wish to enable.

![Configuring languages](/docs/about/demo/lang2.png)

If multiple languages are enabled, users will be able to select the language they wish to operate with from the homepage:

1. In the top right corner of the screen click the drop-down menu next to your user details.

2. Click <b>Change Language</b>

![Configuring languages](/docs/about/demo/lang3.png)

3. Once you select your preferred language, it will update automatically. You can always change it back using the same method.

## Viewing the localisation strings
Under localisations, you can use the Export button to download and view a .csv of the configured language strings and translations.

![Configuring languages](/docs/about/demo/lang4.png)

## Editing strings for an existing localisation
1. Under localisations, export the currently configured languages .csv file

2. Within the .csv, edit the strings as required and save the updated file (we recommend doing this in Google Sheets or Microsoft Excel)

3. Then click the <b>Import</b> button and upload the updated .csv file. Your changes will now be implemented.

![Configuring languages](/docs/about/demo/lang5.png)

## Adding a new language
1. Under localisations, export the currently configured languages .csv file

2. Within the .csv, fill out a new column to include the basics about the language you wish to include in the system including the name, description and whether the language is to be enabled

![Configuring languages](/docs/about/demo/lang6.png)

3. Within the new column, enter in the translated strings. If a cell is left blank, it will default to the default system string

4. Once you have completed entering the required strings for your new localisation language, save and import the file. <b>Be sure to save the file with the exact same name as when you downloaded it</b>

5. The new language will appear within the languages configuration page and can then be enabled for use.

![Configuring languages](/docs/about/demo/lang7.png)

To learn more about how localisation works in Conforma, check out our developer [docs](https://github.com/msupply-foundation/conforma-web-app/wiki/Localisation). 