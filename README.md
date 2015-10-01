# Workshop “Cross-Plattform HTML5 – in Action!”
All the resources for the BASTA! 2015 workshop “Cross-Plattform HTML5 – in Action!” can be found in this repository.

## Setup
* Download and install the platform SDKs and/or emulators for the platform you want to develop for (this might take quite a while… so do this first!)
  * [Xcode](https://developer.apple.com/xcode/download/)
  * [Android SDK](https://developer.android.com/sdk/index.html)
  * [Windows 10 SDK](https://dev.windows.com/en-us/downloads/windows-10-sdk)
  * [Windows Phone 8.1 SDK](https://dev.windows.com/en-us/develop/download-phone-sdk)
* Download and install [node.js](https://nodejs.org/)
* Download and install [Atom](https://atom.io/) or another editor of your choice (free: `notepad`, [Visual Studio Code](https://code.visualstudio.com/); commercial: [Sublime Text](https://www.sublimetext.com/), [WebStorm](https://www.jetbrains.com/webstorm/))

## Supported platforms
* Any modern web browser (Chrome, Firefox, Edge, Safari) by simply hosting it
* Mobile platforms (iOS, Android, Windows) by packaging the app using Cordova
* Desktop platforms (Windows, Mac OS X, Linux) by packaging the app using NW.js

## Third-Party Libraries
### JavaScript, CSS
* [AngularJS](https://angularjs.org/), JavaScript framework — HTML enhanced for web apps!
  * [Angular Translate](https://github.com/angular-translate/angular-translate), i18n for AngularJS apps, made easy
  * [Angular Translate Static File Loader](https://github.com/angular-translate/bower-angular-translate-loader-static-files), loading translation from static json files
  * [UI Router](https://github.com/angular-ui/ui-router), AngularJS routing framework
  * [ngSanitize](https://docs.angularjs.org/api/ngSanitize), Service for sanitation
* [Bootstrap](http://getbootstrap.com/), responsive layout framework
* [AdminLTE](https://almsaeedstudio.com/preview), free responsive dashboard template
  * [Font Awesome](https://fortawesome.github.io/Font-Awesome/), free icon font
  * [jQuery](https://jquery.com/), JavaScript library required for AdminLTE
  * [winstore-jscompat](https://github.com/MSOpenTech/winstore-jscompat), fixes jQuery issues with Windows (Phone) 8 and 8.1 platforms
* [FastClick](https://github.com/ftlabs/fastclick), eliminates the [infamous 300 ms lag on touch devices](http://developer.telerik.com/featured/300-ms-click-delay-ios-8/)
* [three.js](http://threejs.org/), JavaScript library for WebGL and 3D content
  * [Touch Polyfill](https://github.com/CamHenlin/TouchPolyfill), adds touch event support to Internet Explorer 11/Windows (Phone) 8.1
* [Leaflet](http://leafletjs.com/), an open-source JavaScript library for mobile-friendly interactive maps

### Native Wrappers
* [Cordova](https://cordova.apache.org/)
  * [Camera Plugin](https://github.com/apache/cordova-plugin-camera), allows native camera access
  * [Geolocation Plugin](https://github.com/apache/cordova-plugin-geolocation), allows access to geolocation
  * [Statusbar Plugin](https://github.com/apache/cordova-plugin-statusbar), allows modifying the statusbar
* [NW.js](http://nwjs.io/)

## Additional Resources
* [Cross-platform 2D and 3D visualizations](https://github.com/thinktecture/basta-herbst-2015-2d-3d)
* [Offline-first architecture for HTML5 apps](https://speakerdeck.com/christianweyer/auch-ohne-netz-offline-first-architekturen-fur-html5-apps)
* [Leightweight architecture with ASP.NET and SignalR](https://speakerdeck.com/christianweyer/fur-alle-leichtgewichtige-architekturen-mit-asp-dot-net-web-api-and-signalr)
* [AngularJS/Cordova: Fixing the Windows Phone back button](http://weblogs.thinktecture.com/christian_liebel/2015/07/angularjs-cordova-and-the-windows-phone-back-button.html)
