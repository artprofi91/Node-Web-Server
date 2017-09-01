# Node-Web-Server
One of my short term goals is to be proficient in Node.js and to achieve this goal I subscribed to the ([Udemy course by Andrew Mead](https://www.udemy.com/the-complete-nodejs-developer-course-2/learn/v4/overview)).
The best way to learn Node is by building Node apps.

## What is a Web Server?

A Web Server is a software application which handles HTTP requests sent by the HTTP client, like web browsers, and returns web pages in response to the clients. Web servers usually deliver html documents along with images, style sheets, and scripts.

Most of the web servers support server-side scripts, using scripting languages or redirecting the task to an application server which retrieves data from a database and performs complex logic and then sends a result to the HTTP client through the Web server.

## Web Application Architecture

![image](https://user-images.githubusercontent.com/28790452/29979364-c42b331e-8f0a-11e7-9e6f-a27dbc8a33d0.png)

A Web application is usually divided into four layers:
* **Client** − This layer consists of web browsers, mobile browsers or applications which can make HTTP requests to the web server.
* **Server** − This layer has the Web server which can intercept the requests made by the clients and pass them the response.
* **Business** − This layer contains the application server which is utilized by the web server to do the required processing. This layer interacts with the data layer via the database or some external programs.
* **Data** − This layer contains the databases or any other source of data.

## Express framework

Express is a popular unopinionated web framework, written in JavaScript and hosted within the node.js runtime environment. It provides mechanisms to:
* Write handlers for requests with different HTTP verbs at different URL paths (routes).
* Integrate with "view" rendering engines in order to generate responses by inserting data into templates.
* Set common web application settings like the port to use for connecting, and the location of templates that are used for rendering the response.
* Add additional request processing "middleware" at any point within the request handling pipeline.

## Handlebars.js

Handlebars.js is a popular templating engine that is powerful, simple to use and has a large community. It is based on the Mustache template language, but improves it in several important ways. With Handlebars, you can separate the generation of HTML from the rest of your JavaScript and write cleaner code.
