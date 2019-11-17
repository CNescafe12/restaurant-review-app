## Overview: Restaurant Review App Stage 1
For the Restaurant Reviews projects, I have converted a static webpage to a mobile-ready web application. In Stage 1, The static design that lacks accessibility has been converted into the responsive design on different sized displays and accessible for screen reader use. I have added a service worker to begin the process of creating a seamless offline experience for the users.

## Getting Started
The started code is forked from Udacity for a restaurant reviews website. The project work has improved below three areas:

Responsive Design,
Accessibility and
Offline Use.

## How to launch the app locally?
To run this example you'll need to use a local server. The easiest way to do so is to use the chrome extension but you can launch the local http server using python as well. Please follow the steps mentioned below:

Using Python HTTP server In the project folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

1 -- Using Terminal enter into project directory

2 -- In a terminal, check the version of Python you have: python -V.

3.a If you have Python 2.x, spin up the server with python -m SimpleHTTPServer 3000 (or some other port, if port 8000 is already in use.)
3.b For Python 3.x, you can use python -m http.server 3000.
3 -- With your server running, visit the site: http://localhost:3000

## Running the page
Running Python server helps you test most of the page functions. Holding "Ctrl"+"F5" to refresh the page is a must! To test the service worker you will need to use "Web Server for Chrome", Python just did not work. With the code having no issues, you will have MIME type error if you use the Python Server to test the service worker.

## Leaflet.js and Mapbox:
This repository uses leafletjs with Mapbox. You need to replace mapboxToken: with a token from Mapbox-Access token in main.js and restaurant_info.js. Mapbox is free to use, and does not require any payment information.

## Note about ES6
Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code.

Acknowledgments
Special thanks to Udacity Team
