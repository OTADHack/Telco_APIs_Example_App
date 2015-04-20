Telco APIs Example App
=========

Source code of an **Android application** providing forms and API calls to the Oracle Communications Services Gatekeeper environment created for the TADHack event.
It allows to test the following Telco APIs:
+ Payment API
+ Messaging API
+ Location API

Version
----

1.1

Usage
----

Follow this steps:

+ Request your credentials on the [Oracle's TADHack website](http://tadhack.optaresolutions.com).
+ Download the source code included in this repository using the `Download ZIP button` or using the clone option
```sh
git clone https://github.com/OTADHack/Telco_APIs_Example_App.git
cd Telco_APIs_Example_App
```
+ Import the project in [Eclipse + ADT plugin](http://developer.android.com/sdk/index.html): select `File -> New -> Project...`, and then `Android -> Android Project from Existing Code`. Select the OracleTADhack source code as Root Directory and click Finish. 
+ Using the Package Explorer view, expand the navigation tree in order to open the `OracleTADhack -> assets -> www -> index.html` file in a text editor. Update the values YOUR_LOGIN and YOUR_PASS (lines 180 and 181) with your credentials obtained in the first step.
+ Right-click the `OracleTADhack` project and select the `Run As -> Android Application`. 
+ The application is launched! Select the API you want to test (Payment, Messaging, or Location). You can choose to use the default parameters or replace them with your own ones. Enjoy!

Developer notes
----

This Android application is developed using [PhoneGap](http://phonegap.com). 

The main content is located in the `assets -> www -> index.html` file: 

+ HTML (lines 17 to 168): static pages including the required fields and buttons.
+ JavaScript general (lines 178 to 192): initial declarations. Here you can replace the url and credentials to test with your SDK instead of with the TADHack environment.
+ JavaScript Payment (lines 196 to 248): actions to execute when the Payment button is pressed. Includes the Payment API invocation.
+ JavaScript Messaging (lines 251 to 297): actions to execute when the Payment button is pressed. Includes the Payment API invocation.
+ JavaScript Location (lines 300 to 345): actions to execute when the Payment button is pressed. Includes the Payment API invocation.

Documentation
----

+ Payment Documentation can be found at [Oracle's TADHack Payment website](http://tadhack.optaresolutions.com/?page_id=102).
+ Messaging Documentation can be found at [Oracle's TADHack Messaging website](http://tadhack.optaresolutions.com/?page_id=87).
+ Location Documentation can be found at [Oracle's TADHack Location website](http://tadhack.optaresolutions.com/?page_id=94).

Support
----

If you have any doubt, ask it in [the Issues section](https://github.com/OTADHack/Telco_APIs_Example_App/issues).
