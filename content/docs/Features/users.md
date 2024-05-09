+++
title = "Configurable Permissions for Users"
description = "An overview of the different types of users in Conforma"
date = 2021-05-01T08:20:00+00:00
updated = 2023-08-01T08:20:00+00:00
draft = false
weight = 23
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = ""
toc = true
top = false
+++

Conforma allows for highly granular permissions for different users, as we know not all users need to see everything at once (nor should they be able to). Let's go over a couple of the common user types and how they can interact with the system.

![users](/docs/about/demo/users.png)

Any user can access Conforma from anywhere simply by using their own login details. As Conforma is a web-based application, so long as users have access to the internet, they can access the system through a desktop or tablet browser.

![login](/docs/about/demo/1.png)

## External users

External users are typically users outside of the organisation using Conforma, but one that interacts with Conforma by submitting applications or notifications of important information to the key organisation.

Key examples of what external users would normally be set up to do in Conforma include: 

* Establishing their own user profile and setting up a company profile (which can have multiple external users assigned to it)
* Submitting applications to an organisation (for example, submitting a product registration application to a regulatory agency for review)
* Responding to queries and communications (for example, responding to requests for information from a regulatory agency reviewing their application)
* Receiving system generated correspondence related to submitted applications
* Tracking and managing applications within Conforma. The intention is to ensure external users have a transparent oversight of their applications to reduce the number of enquiries the organisation using Conforma might receive
* Viewing and managing any outcomes of their applications, such as 'Registered Products' or 'Licences'.

Below is an example of an external applicants view of a medicine application form:

![externaluser](/docs/about/demo/exuser1.png)

Basic guidance on how to use Conforma as an external user is available in the [Guidance](https://docs.conforma.nz/docs/TutorialExternal/creatingextuser/) section.

## Internal user

An internal user is typically a staff member of the organisation using Conforma to manage their processes, such as a regulatory authority.

Key examples of what internal users would normally be setup to do in Conforma include: 

* Reviewing and determining outcomes for submitted applications (for example, an internal user could be an evaluator who assesses medicine applications from pharmaceutical suppliers)
* Managing complex work processes or 'workflows' in the system, which can require multiple steps and several users involved
* Generating correspondence, for example approval certificates or amendment requests to an external user in response to their application
* Storing notes and documents related to a workflow, such as meeting minutes, lab results or evaluation reports uploaded from outside Conforma
* Tracking and managing the lifecycle of applications and products in the system, relevant for tasks such as renewals of licences as a regulator
* Managing workloads for team members, tracking upcoming or overdue tasks, and managing databases of application by-products
* Viewing data and customised reports from a centralised location.

Below is an example of an internal user's view of the status of applications received:

![Internal User view](/docs/about/demo/IntUser.png)

Basic guidance on how to use Conforma as an internal user is available in the [Guidance](https://docs.conforma.nz/docs/TutorialInternal/loginintuser/) section.

## Admin user

Admin users are able to perform higher level administrative and configuration functions, such as:

* Managing users and their permissions
* Editing existing workflows or forms, or even creating new ones
* Turning different modules or workflows on or off as needed
* Editing the wording of emails or updating generated documents
* Updating and managing local data lists and look-up tables.

What’s great and unique about Conforma is that it can be easily configured within the system interface using the template builder tool. This means that a non-developer user can be trained on how to manage and configure their own setup, in turn providing countries and organisations with governance over their own systems.

Below is an example of the look-up table management:

![Admin User View](/docs/about/demo/lts.png)

Basic guidance on how to use Conforma as an admin user is available in the [Guidance](https://docs.conforma.nz/docs/Tutorialadmin/accessingdconforma/) section.
