---
layout: project
type: project
image: images/URLookup_logo.png
title: URLookup
permalink: projects/urlookup
# All dates must be YYYY-MM-DD format!
date: 2020-10-06
labels:
  - Software
  - Web Application
  - JavaScript
  - Node.js
  - Security
  - AWS
summary: A web tool for checking a URL for threats.
---

<img class="ui image" src="../images/URLookup_landing.png">

## Introduction
URLookup is a small web application focused on the security of the web regarding URLs. Links can be dangerous, and most users don't know that they are until after they've already clicked on it. URLookup allows users to submit suspicious URLs to check for any possible threats and present easy-to-read results.

The point of URLookup is to use popular third-party scanning APIs, compile their often complicated results, and present the user with a concise decision whether the URL is safe. Currently, URLookup uses urlscan.io's API, but more API integration such as Google Safe Browsing, scanii, VirusTotal, annd Hybrid Analysis APIs are currently being planned. I solely created URLookup as a personal project because of my deep interest in cyber security and programming.

## Development
From conception, I chose the MERN stack (excluding MongoDB) for URLookup because I wanted to streamline the workflow by primarily using JavaScript for the front-end and back-end. I chose to use reactstrap (React + Boostrap) to simplify and speed-up development of the application's front-end. Furthermore, I combined the front-end and back-end by using Express.js to serve the front-end files to the client and handle API calls to the back-end simultaneously. This also meant I can simplify deployment later down the line. 

## Deployment to AWS
URLookup was initially deployed to Heroku; however, the project has since been migrated to AWS. (Link is at the bottom of the page)
The project is built and deployed using AWS Elastic Beanstalk so I can simplify management and focus on development. I established continouous delivery by creating a connection to the GitHub repo using AWS CodePipeline. Furthermore, I transferred my custom domain to AWS Route 53 where I configured the domain's A record to resolve to my Elastic Beanstalk instance.


## Technologies
Front-end:
- HTML, CSS, JavaScript
- React
- Bootstrap

Back-end:
- JavaScript
- Node.js
- Express.js

Other:
- AWS - Elastic Beanstalk, CodePipeline, Route 53
- Heroku
- Git/GitHub


Links:
- [URLookup Github Repo](https://github.com/jayryanj/URLookup)
- [Deployed on AWS](http://www.urlookup.com/)