# screenshot-and-email-web-content
Using Javascript ,take screenshot of contents in a html5 container and email it, in iOS and Android devices.

# Usage

* Create a cordova project, clone the above code and replace the 'www' folder in cordova project with 'www' folder from the git
* Create iOS and Andriod platforms in the project folder.
```
cordova platform add ios --save
cordova platform add android --save
```
* Install cordova email composer plugin in our project.
```
# ~~ stable version ~~
cordova plugin add cordova-plugin-email-composer@0.8.3
```
* Now deploy the project in the device and run.