# PebblePark

PebblePark is a smartwatch application that assists users find nearest parking spots based on their current location ans various filters.
We are using Google Places API to get the parking data, and since the Google Maps API provides only proximity based data, we have mocked up starting price of the parking spots. 
Potentially, there are other APIs which provide us in depth details such as number of parking spoits available (which also we have mocked up), parking based on vehicle type, and other features.
What really makes this application one of it's kind is the fact that we provide a built in navigator system as well. So you don't really need any other companion app along with Pebble Park.
The application can also potentially let the user book his / her parking ticket on the app itself.

1. PebblePark - Server code that provides several REST services.
2. pebblejs - Pebble SDK project used to create the native Pebble application.
