# Flutter Taxi App [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


A Flutter starter taxi app built with BLOC pattern. It has following features

  - Taxi markers showing on different position on map (Based on static position)
  - Different animations across different part of screen 
  - Polyline showing on map (Hardcoded data from Google Maps API)
  - Runs on both Android & IOS.
  -  It helps in managing state and make access to data from a central place in your project.
  - Its a state management system for Flutter recommended by Google developers.

### Screenshots

![makephotogallery.net_1580238239.jpg](https://www.dropbox.com/s/dgd40s5752y2jsl/makephotogallery.net_1580238239.jpg?dl=0&raw=1)

### Dependencies

This project is built with various awesome open sourced libraries

* [google_maps_flutter](https://pub.dev/packages/google_maps_flutter) -  to show map on screen (Still in beta version)
* [flutter_bloc](https://pub.dev/packages/flutter_bloc) - to mantain state and make every widget independent using blocs 
* [bloc](https://pub.dev/packages/bloc) - to listen events on taps by user and dispatch new state to other widgets
* [equatable](https://pub.dev/packages/equatable) - to make models comparable (Nice Library) 
* [shimmer](https://pub.dev/packages/shimmer) - to show nice loading effect
* [location](https://pub.dev/packages/location) - to get current location of user (Feature to be developed)
