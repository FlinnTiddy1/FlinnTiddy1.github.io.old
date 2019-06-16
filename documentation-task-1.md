---
layout: page
title: Documentation Task#1
---

Adon tasked me with documenting the comparsion between **React-Native-Maps** and **Leaflet Maps** in react native.

**Leaflet Maps -**

Firstly I will start with explaining Leaflet Maps, its pros and cons and my experience.

![](/assets/leaflet.JPG)

Leaflet is a widely used JavaScript library (Open Source) used to build applications that wish to integrate maps. Leaflet prides itself with having simplicity, performance and usability in mind when developed. They encourage people to read and contribute to the source code to further the project as a whole.

Example of a Leaflet map -
![](/assets/leafletexample.JPG)

Leaflet requires a secondary third party component to function as leaflet themself doesn't offer any of the physical map data just the framework to load other services into. These other third parties are Mapbox, OpenStreetMaps.org and more. This function is called a tileLayer. Setting up a tilerlayer object is relatively simple with the basic requriements being a URL link to the API you wished you pull data from and the access token / API key.

Example of Tile Layer object -
![](/assets/tilelayer.JPG)


**Pro's of using Leaflet Maps -**
* Light weight
* Free (Some API's)
* Large amount of plugins
* Strong community
* Open source
* Choice of map providers

**Con's of using Leaflet Maps --**
* Slight learning curve
* Extermely lacking API documentation for React Native

**My Experience with Leaflet -**

My experience with implementing leaflet into Taking Steps was a interesting one. I started with trying to find some resources that involved the use of react native as we are developing our app in this platform. I quickly realized there was a huge shortage of any documentation of people using leaflet in react native and this was going to be a issue. Every slack post I found people recommended avoiding Leaflet in react native as there wasn't any official support resulting leaflet having to be used in a WebView component. After a week and abit of trying my best to get this working in Taking Steps I decided to switch to React-Native-Maps as this includes integration from Google Maps which will easily allow me to provide a reliable map system with user tracking that the client has requested.<br><br><br>

**React-Native-Maps -**


Lastly I will start with explaining React-Native-Maps, its pros and cons and my experience.

![](/assets/reactmaps.JPG)


React-Native-Maps is a react native component designed to be compbatiable with iOS and android. MapView is the main component and is built so features on the map such as markers, polygons, lines for tracking etc are specified as children of the MapView itself. This gives a react-like API for declaring controlling features on the map. This way of design allows new users to pick up the component and start coding straight away without confusion. React-Native-Maps can be used with multiple different map sources such as Google Maps (Most popular), OpenStreetMaps.org and more.

Example of a React-Native-Map using Google -
![](/assets/react-native-maps-example.JPG)


**Pro's of using React-Native-Maps -**
* Free (Some API's)
* Open source
* Android
* iOS
* Heaps of documentation
* Choice of map providers
* Google avaiable
* Easy to customize (Markers, Animations and more)

**Con's of using React-Native-Maps --**
* None?

**My Experience with React-Native-Maps -**

My experience with react native maps was very straight forward and easy. I was tasked with implementing maps for Taking Steps and I first thought of using Google Maps for their reliability and good design. I found a few resources online explaining how to use React native maps and the Google maps API. I obtained a API key and placed inside my android manifest while at the same time enabling Internet permissions and Location permissions to allow communication between the phone and API. I implemented the rest of the tutorial on our Walking.JS page by adding a MapView and a Component Mounted method to find the Phones current location and set the map to it. I imported the "Marker" component to allow for exact location testing on my physical testing device and the android inbuilt emulator. All this was relatively straight forward due to well documented tutorials online. My next job with react-native-maps is to add route tracking for the user to display the path they take during their walks using Taking Steps.<br><br>

**Overall-**

Overall React Maps is a lot more developer friendly due to the well documented resources online compared to the minimal amount Leaflet has. Given some time and development Leaflet for react native could become a more viable option in the future in my opinion.