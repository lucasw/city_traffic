city_traffic
============

Visualization of traffic moving through a randomly generated city

Generate a network of roads  
===========================

Initially make a square network.

Initally roads would only be of one type, but then later have them support different kinds of traffic.

Generate blocks and buildings in spaces between roads
=====================================================

Initially square footprint buildings of a fixed size, random number of floors, and fixed number of buildings to a block.

Buildings will spawn traffic on nearby roads, and each unit will have a destination in another building on the map.  The very simple and wrong model is that all other buildings on the map are equally likely destinations, but later this should be corrected so that is true only some percent of the time.  Most of the trips will go to the nearest nearby building that has a destination of the right type (with some randomization).

Building can be of multiple types, housing, commercial, retail, with subtypes fleshed out later.

Graphics
========

Could be 2d using easeljs, but would like to do 3D using three.js.  Each building would be simple polygons, and traffic would be points of illumination.  Later lights could be added in windows of buildings, or textures generated ahead of time with a variety of patterns of on and off lights.






