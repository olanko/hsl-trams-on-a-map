# HSL Trams on a map
HSL Trams on a map - Main project

Real time web app showing HSL trams on a map.

http://dev.hsl.fi/

Microservices talking via RabbitMQ:

* hsl:
  * hsl.js: fetch data from HSL MQTT

* hsl-middleman
  * cache position data for each vehicle
  * serve positional data when needed

* hsl-frontend
  * static AngularJS client app
  * server: parse and serve positional data for client app

olli.korhonen@iki.fi


