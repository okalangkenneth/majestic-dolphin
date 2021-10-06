---
title: RESTful API.
date: '2019-04-30'
thumb_image_alt: An orange on a blue background
image_alt: An orange on a blue background
seo:
  title: Project Title 2
  description: This is the project 2 description
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Project Title 2
      keyName: property
    - name: 'og:description'
      value: This is the project 2 description
      keyName: property
    - name: 'og:image'
      value: images/2.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Project Title 2
    - name: 'twitter:description'
      value: This is the project 2 description
    - name: 'twitter:image'
      value: images/2.jpg
      relativeUrl: true
layout: project
subtitle: >-
  Creating a RESTful API using node.js,express and Mongodb.(MERN) for server and
  CRUD application
---
REST API  application where the user will interact with the backend by making orders from the database.

#### **STACK**

MongoDB, Javascript, API, HTML, CSS, VS Code.

[**VIEW LIVE** **SITE**](https://okalangkenneth.github.io/weather_app/)

#### **Project Purpose and Goal.**

The purpose of the project will be to;

*   Create REST API using MongoDB, Express, and Node

*   Create CRUD operations to interact with the backend database

*   Create Authentication for the user.

#### **WebStack and Explanation.**

I preferred using VS Code because of its easy-to-use interface and syntax highlighting. Node is used to install all the dependency files for the project.

#### **Problems and Thought Process.**

The bump that I ran into was converting the default kelvin units into celsius as it is the commonly used measure in Sweden. I solved this by visiting the StackOverflow website where I found the solution. I changed the units = metric in the GET request code.

#### **Lessons Learnt.**

The main lesson learned involved my understanding of JSON and 3rd party API integration. I also learned that data loaded over HTTP doesn't work over HTTPS web hosts. However removing the HTTP, which is used to load images and to load JSON data, will work on both secure and nonsecure web hosting, but breaks when run locally.
