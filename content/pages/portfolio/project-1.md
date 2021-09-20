---
title: Inspection Statistics (Under development)
date: '2021-09-02'
image_alt: 'White, black, and red shoe sole'
seo:
  title: Cooperative Marketing
  description: A project to assist the marketing efforts of a Cooperative Union in Uganda
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Project Title 1
      keyName: property
    - name: 'og:description'
      value: This is the project 1 description
      keyName: property
    - name: 'og:image'
      value: images/1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Project Title 1
    - name: 'twitter:description'
      value: This is the project 1 description
    - name: 'twitter:image'
      value: images/1.jpg
      relativeUrl: true
layout: project
subtitle: >-
  Applying statistics records to assist the marketing efforts of an inspection
  company in Uganda
---
# **Inspection Statistics.**

Inspection Statistics is a backend application built for the staff of an inspection company I worked for in Uganda. The application is built using an API, and Blazor for the front end, and it is built using clean architecture principles in ASP.NET.Core that enables the testing, maintaining, and scalability of the application.  The following layers are used; The domain entities and interfaces, application, infrastructure, and user interface layers. In this way, the code will be independent of the User Interface or the used frameworks and the database and the attention is focused on writing the business logicThe project is based on this tutorial from  [Pluralsight. ](https://app.pluralsight.com/library/courses/architecting-asp-dot-net-core-applications-best-practices/table-of-contents)

##### **STACK**

Blazor, ASP.NET.Core, API, EF Core, Database, .NET 5 SDK, Visual Studio 2019, Swagger, SQL Server

[**LIVE**](https://www.example.com)

#### **Project Purpose and Goal.**

Inspection Statistics is built with the goal of assisting the inspection company in its marketing efforts through statistical records.  The staff can register or log in to the application by authentication to perform API calls. In the main menu, there is the Inspections, departments, and the Invoices menu.  On the inspections page, are all the scheduled inspections. An inspection can be added, edited and its details are seen. One can also export the inspections to an excel file for further analysis. From the menu, one can also browse to the departments page which displays all the departments with their scheduled inspections. Past inspections can also be included. Finally, the staff can see all the invoices for a particular period.

#### **WebStack and Explanation.**

ASP.NET Core made the most sense of the application because it required creating an API combined with Blazor and exposing the API using Swagger and consumed from a client-side application.

#### **Problems and Thought Process.**

#### **Lessons Learnt.**
