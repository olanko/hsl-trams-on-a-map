# HSL Trams on a map
HSL Trams on a map - Main project

Real time web app showing HSL trams on a map.

http://dev.hsl.fi/

Microservices:

* hsl, two totally separate microservices:
  * hsl.js: fetch data from HSL MQTT and push it to rabbitmq queue
  * httpserver: parse and serve positional data that clienapp needs

* hsl-middleman
  * cache position data for each vehicle
  * serve positional data when needed

* hsl-frontend
  * static AngularJS client app

olli.korhonen@iki.fi


