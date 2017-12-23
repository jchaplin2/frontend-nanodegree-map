# World Travel Map Project

## Description
A map application I built that shows places I've travelled in the world.

## Installation
1. Clone repo here : https://github.com/jchaplin2/frontend-nanodegree-map
1. Run a web server, I used python3.6 http.server
1. Add pyton to your PATH.
1. cd to the project directory.
1. type the following at the command line python -m http.server 8000
1. Open http://localhost:8000 in a web browser.

## How to Use
* Enter a name of a place to see it selected on the map.
* Clicking Reset un-selects all markers for that location.
* Clicking a map marker displays a detailed view with a street view of location.
* If on a mobile device move the phone around to toggle the pitch on streetview.
* Toggling country selects a new set of places on the map.
* There are also three styles available to toggle from: Default, Neon, Night mode

## Demo
[Demo](https://jchaplin2.github.io/frontend-nanodegree-map/)

## Known Issues
1. Requesting flag image over https doesn't work on the demo. Github uses https and I don't have a paid account for geonames (http://www.geonames.org/commercial-webservices.html). If you want to use this feature clone the repo and run it over a local web server.

## Resources:
* Google Maps API: https://developers.google.com/maps/
* Knockout: http://knockoutjs.com/
* JQuery: https://jquery.com/

## Inspiration
https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001