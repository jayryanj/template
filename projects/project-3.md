---
layout: project
type: project
image: images/beach.jpeg
title: Hawaii Beach Conditions
permalink: projects/hawaii-beach-conditions
# All dates must be YYYY-MM-DD format!
date: 2019-07-26
labels:
  - Software
  - Python
summary: A simple program that displays the conditions of the various beaches in Hawaii.
---

<img src="../images/beach_gui.png">

<hr>

Have you ever thought about going to the beach, but you weren't sure if the conditions were right?

During my free time, I independently developed a small program called <em>Hawaii Beach Conditions</em>. The program simply allows the user to select various beaches on Oahu, Maui, Kauai, and the Big Island to see its current conditions. The user may select any of the provided islands, choose a beach, then a table will be shown displaying information about the beach. Some of the information include the beach's name, island, weather, wind , temperature, and surf.

The program was developed in Python 3. The code uses the Hawaii Beach Safety API which returns a JSON containing data on every major beach in Oahu, Maui, Kauai, and the Big Island. The other Hawaiian islands are not options because they are not included in the data returned by the API. Some features that I have planned for future development includes a graph that displays the wave height, replacing the table with a nicer design, in-depth weather forecast for the entire day, and images of each beach.

The code will be published to GitHub shortly.

From this project, I learned about using an API to receive data. I haven't used a lot of APIs in the past, but this side project allowed me to understand how useful they are. In addition, I learned a lot about GUI programming using Python. My experience with developing user interfaces have not been fun, but this side project allowed me to explore GUI programming more than I previously have.
