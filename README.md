https://support.smartersvision.com/help-center/articles/3/11/14/introduction


Introduction
Mobile app developed using a flutter framework created by Google is open-source mobile application development. It is used to develop applications for Android and iOS, as well as being the primary method of creating applications

Requirements
To edit this project you must have Flutter and Dart installed and configured successfully on your device Install flutter
Set up your editor Install the Flutter and Dart plugins

Get Started
1- Download and unzip the Flutter App, use your preferred IDE (Android Studio / Visual Code / IntelliJ) to open the project.

2 - Open /assets/cfg/configurations.json and edit the remote link to connect your mobile app with your admin panel

{
  "api_base_url": "http://yourdomain.com/public/api/",
  "base_url": "http://yourdomain.com/public/"
}
Important:
These URLs must end with a slash  '/' 
If you have removed the public folder from your admin panel URL you must remove it from the URLs above 
3- Go to /assets/img/logo.png and replace it with your logo or app icon.

Note:
This logo used in the splash screen only, not in the app icon
4 - Create your own Google Maps API key at https://cloud.google.com/maps-platform/.

Note:
Follow the First 1 min to generate your own Google Maps API Key https://www.youtube.com/watch?v=9ImLCQBj9SE
5 - Google Maps API Checker

Please check your API before completing the installation http://yougapi.com/tools/google-api-key-checker.php

If you see the message “Geocoding service ok” and a Map of NY with 3 markers, it means the Google API key is ready to be used in our store locator apps
If you don’t see the image of the Map, make sure you have enabled the “static Maps” service from the “Enabled API” section