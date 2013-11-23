City Weather - A spec for a front-end project using AngularJS
=============================================================
Create a single page web app that lets the user view the current weather and 5 day forecast for:

- A pre-defined list of U.S. cities
- Any location via Zip Code lookup

Requirements and Guidelines
===========================

* The weather information displayed should include the following:

  - Current weather conditions for the selected location or entered zip code
  - Weather forecast information for the selected location or entered zip code

* The app should let the user select from a pre-defined list of the following cities / zip codes:
```
  - Boston (02112)
  - New York (10001)
  - Philadelphia (19122)
  - Washington D.C. (20001)
  - Atlanta (30301)
  - Miami (33133)
  - Dallas (75201)
  - Chicacgo (60601)
  - St. Louis (63101)
  - Denver (80218)
  - Las Vegas (89101)
  - Phoenix (85001)
  - Los Angeles (90001)
  - San Francisco (94102)
  - Seattle (98101)
```

* The app should let the user enter any U.S. Zip code to see the weather for that location

* For both the selected city and location found for the user entered zip code, the following information should be displayed:

  - Current weather conditions
  - 5 day forecast

* The web page should be optimized for use, display and navigation for any device desktop, laptop, phone, tablet, etc.

* The app should be implemented as a static web page so that it can be deployed and run from anywhere, file system, Amazon S3, GitHub Pages, etc. There should be no dependency on any server side technology.

* The app should be developed using the following languages, tools, frameworks and libraries:

  - HTML/HTML5
  - CSS/CSS3
  - JavaScript
  - JSON
  - jQuery
  - Bootstrap
  - AngularJS

* The app should get its weather data in JSON representation from the Yahoo query API.

* An example call to get the weather data for New York City:

  - http://query.yahooapis.com/v1/public/yql?q=select%20item%20from%20weather.forecast%20where%20location%3D%2210001%22&format=json

* To use with AngularJS and JSONP:
  
  - http://query.yahooapis.com/v1/public/yql?q=select%20item%20from%20weather.forecast%20where%20location=10001&format=json&callback=JSON_CALLBACK

Feel free to ask any questions. Good Luck!

Milestones and Deliverables
===========================

1. Initial wireframe(s) to show and discuss your design, layout and concept.
   Can be static html, sketch, pdf, image, fiddle, etc.

2. Working and demonstration ready code.


Bonus and Bonii
===============
* Allow the user to bookmark and share the URL to display the weather for any location.
* Fork this repository and submit your deliveries using pull requests
* Feel free to ask any questions.

