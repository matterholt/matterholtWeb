---
layout: "../../../layouts/ArticleLayout.astro"
title: Saas background and user stories
publishDate: 2022/04/15
name: Matterholt
description: User stories for the application, and some background why I choose to build this product.
---

# Intro/Background

The application is specific to controlling the flow of data from the design group and validation 2 group. I worked on the validation side of development and help created the current system in place. The current system is a PPT created by a designer requesting change (countermeasure) for a product in development. The system is fairly similar to how software tracks bugs and other issues and I feel like this system can be adapted to replace the FEA request form.

The application will have groups and roles

1. Admin / Project Manager will get the project started and will be able to view the overall progress of the product.
2. Validation 1 group is more research and responsible for setting up the model and like a technical lead for setting up the analysis for the product. They would need a minimum involvement in the application and would be required to just view the progress.
3. The validation 2 group does the bulk of analysis and controls the flow of information. This group is what drives the application. They will spend the bulk of the time adding info and progressing the CM ticket.
4. The design group creates the cm request and initially would only be able to see where the cm request is at in the process and the results once the cm request has been published. Users in the group would also need to supply key dates for the product, letting everyone that is a part of the team know when things need to be completed

### Admin / Project manager / Validation 1 group, User Story

1. Once the company chooses to use the platform the design admin will create groups
2. Admin will send out a request to join the platform. (users will select which group they are a part of)
3. Admin will receive information about a new product build. They will be responsible for setting up the new product in the application. This entails basic info, assigning team leads, and key dates for the product development
4. Admin / Project manager would also be able to see the overall progress of the product

### Design User Story

1. Design Users will receive a notification that they have been added to a new development product.
2. The assigned user will be able to add any supporting teammates that are needed for the product development
3. The lead Design user would also create a schedule to allow everyone to know when things need to be completed.
4. Any design user assigned will be able to create an FEA request, upon approval from the Lead Designer request can be sent to the validation 2 group.
5. The FEA Request will need to contain information that would allow the validation to capture and complete the desired changes need for the countermeasure. Name, Base name, change list, weight. reason for changes.
6. Users would be able to view the status of requests. Once results get published, they should be able to view the judgment of the countermeasure request

### Validation 2 User Story

1. V2 User will receive a notification that they have been added to a new development product.
2. The assigned user will be able to add any supporting teammates that are needed for the product development
3. Users will be able to view a queue of cm requests,
4. Users would be allowed to assign cm requests to self or other validation members that are assigned to the new product.
5. Users will be able to click and view details about selected CM requests.
6. Users will be able to change the status of requests
7. Once the request is completed then the lead validation 2 would need to approve and publish judgment.

The stories are basic functions and would be enough to get the application built and be useful for the group. I’m sure I’ll come across issues or additions but going to table them for another time or another release.
