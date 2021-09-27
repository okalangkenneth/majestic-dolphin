---
title: The Weather App.
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
subtitle: A 3 day weather application that sets weather data of a city .
---
In this project, I  built a hospitality page where data is dynamically loaded using AJAX . The weather application displays the current and forecast weather conditions for a city.

**STACK**

Javascript,  API, HTML, CSS, VS Code.

![](/images/Screenshot%20\(10\).png)

[**VIEW LIVE** **SITE**](https://okalangkenneth.github.io/weather_app/)

#### **Project Purpose and Goal.**

The purpose of the project will be to create an account with the Open Weather Map site, obtain the API key and learn about the documentation, and with a goal of building a simple application using JSON, AJAX, and data using a 3rd party API.

#### **WebStack and Explanation.**

The project folder consisted of the index.html, CSS, js, and images files. I opened the index file in Chrome and had the inspector open to watch the console before displaying the information on the app. By far the JSON file had the most code. It contained 2 XML HTTP requests. One for the current and the other for the forecast weather conditions. It also contained the GET methods which contained a value from the Open Weather Map site as well as my API key Id. The Index file has dynamic values referencing in the js file. By setting the city's name in the code, the data returned reveals the location, the current temperature, weather description, and a 3-day weather forecast.

#### **Problems and Thought Process.**

The bump that I ran into was converting the default kelvin units into celsius as it is the commonly used measure in Sweden. I solved this by visiting the StackOverflow website where I found the solution. I changed the units = metric in the GET request code.

#### **Lessons Learnt.**

The main lesson learned involved my understanding of JSON and 3rd party API integration. I also learnt that data loaded over HTTP doesn't work over HTTPS web hosts. However removing the HTTP , which is used to load images and for loading JSON data, it will work on both secure and nonsecure web hosting, but breaks when run locally.
