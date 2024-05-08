+++
title = "Configuring Forms and Workflows"
description = "How to edit, create templates, fields, elements"
date = 2021-05-01T18:10:00+00:00
updated = 2023-08-01T18:10:00+00:00
draft = false
weight = 65
sort_by = "weight"
template = "docs/page.html"

[extra]
toc = true

+++

The template builder within Conforma is a simple way to configure and customise your system.

Users with Admin permissions are able to access the template builder and make changes to application forms, emails, and workflows. This section contains instructions for how to make some of the most common changes within template builder.

<div class="tip">
Due to the changes that can be made in the template builder, we recommend that users be very careful when editing forms. Please contact Conforma support for any assistance (support@conforma.nz).
</div> 

## Viewing your templates

To navigate to the template builder go to the Configuration drop-down menu, then click <b>Templates/Procedures</b>.

![Templates/Procedures](/docs/about/demo/templates1.png)

This displays a list of the templates (both active and inactive) in your system. Next to each template, there are three configuration icons that can be used to interact with the forms.

![Templates/Procedures](/docs/about/demo/templates2.png)

![Templates/Procedures](/docs/about/demo/openingaform.gif)

## Renaming a field
Here is an example of how you can edit an existing form field.

1. Click the <b>Edit</b> button to view your selected template in the template builder. Form templates must be in ‘DRAFT’ status before they can be edited

2. But first you must check to see if there are any applications associated with the template

![Templates/Procedures](/docs/about/demo/templates3.png)

- If there are no applications, click the <b>Make draft</b> button and jump to step 6

- If there are associated applications, continue through the following steps

3. Navigate back to the list of templates
 
![Templates/Procedures](/docs/about/demo/templates4.png)

4. Click the <b>Duplicate</b> button that corresponds to your template. This will create a new draft version of your template

5. Click onto your template to expand and view the different template versions. Find the new draft version and click the <b>Edit</b> button

![Templates/Procedures](/docs/about/demo/newdraft.gif)

6. Select the <b>Form</b> tab

![Templates/Procedures](/docs/about/demo/formtab.gif)

7. Under the Form tab, you can see the different sections of the Form Template. Select the one containing the element you wish to edit. For this example there is only one section: 'Pharmacy Details'

![Templates/Procedures](/docs/about/demo/templates5.png)

8. Next, select the page containing the element you wish to edit. In this example, it is in Page 1
  
![Templates/Procedures](/docs/about/demo/templates6.png)

9. You will now see a preview of the Form Template and its elements.
Click the <b>cog icon</b> next to the element you wish to edit

![Templates/Procedures](/docs/about/demo/templates7.png)

10. A new screen will appear. This is where you can edit all the parameters that govern the appearance and behaviour of the element. Once your changes have been made, click Save and then <b>Close</b>

![Templates/Procedures](/docs/about/demo/templates8.png)

11. To change the title, expand the ‘Plugin specific parameters’ box by clicking on the <b>down arrow</b>.

## Creating a new element
1. To add a new element to an application form, scroll to the bottom of the page and section of the form you are working on and select <b>New Element</b>

![Templates/Procedures](/docs/about/demo/templates9.png)

2. Begin editing the properties of the new element by clicking the <b>cog</b> icon

3. You can choose from a number of element types from the drop-down at the top

![Templates/Procedures](/docs/about/demo/templates10.png)

4. You can then create the element to add to your application form, before selecting <b>Save</b> and then <b>Close</b> 

5. For further information on creating new elements, check out our developer [docs](https://github.com/msupply-foundation/conforma-web-app/wiki/Template-Builder). 

## Changing permissions on a template
Permissions to allow users to apply, assign, view, or review applications can be managed under the <b>Permissions</b> tab.

1. An ‘apply’ permission will allow applications to create new applications

2. A ‘view’ permission allows supervisors of reviewers to view all submitted reviews

3. Both of these types of permissions can be easily added by selecting a pre-existing type from the dropdown

![Templates/Procedures](/docs/about/demo/templates11.png)

4. Assign and review permissions are more complex as there are a number of options  available, which allows for very customised form/application development. These can be added in the same way as apply and view permissions but using stages to create the desired workflow

5. For further information on adding or managing permissions, check out our developer [docs](https://github.com/msupply-foundation/conforma-web-app/wiki/Template-Builder). 

## Changing actions on a template
The Actions tab of the template builder allows users to create actions specific to the application type being configured.

1. To add a new action, select the type of trigger you want the action to occur as a result of using the drop-down selection

![Templates/Procedures](/docs/about/demo/templates12.png)

2. Select the <b>plus</b> icon to add that trigger

![Templates/Procedures](/docs/about/demo/templates13.png)

3. With the new trigger established, you can then add the desired action by selecting the <b>Add Action</b> button under next to the newly generated trigger

![Templates/Procedures](/docs/about/demo/templates14.png)

4. Use the <b>cog icon</b> to edit and configure the action in the pop up, before selecting <b>Save</b> and then <b>Close</b>. Actions can be independent or part of a sequential process in the application

![Templates/Procedures](/docs/about/demo/templates15.png)

5. For further information on adding or managing actions, check out our developer [docs](https://github.com/msupply-foundation/conforma-web-app/wiki/Template-Builder). 