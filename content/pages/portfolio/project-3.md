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
subtitle: Accessing JSON data through an API.
---
In this project, I  built a weather application where the current and forecast weather conditions are displayed for any ZIP Code.   I  get JSON data from the Weather Underground site API. I then parsed and used the weather information to populate my website. When one provides a zip code, the JSON data returned will then reveal the location, the current temperature, weather description, and details about the weather forecast.

I created JSON files within a JavaScript file and then I loaded the files from my localhost using XML HTTP request and finally loaded data from an API at the
