# evrythng-webclient-polymer

Small mobile web app that interacts with EVRYTHNG. Built with Web Components + Polymer + Material Design.

All requests are done locally if there is an EVRYTHNG Hub in the network and its address is configured correctly in the application.

## Change Hub Address

Open up the application, logging in with any existing Facebook user.

Go to Menu > Settings and change the 'Local Hub Address' setting. This will be persisted locally,
so the next time you open the application it will use that address by default.

## Extras

### Device Properties Polling

By default the application is not polling for property updates. If you want to mimic a real-time scenario, change the
polling period in the application Settings (from 1 to 5 seconds).

### Standalone

For a more natural Android feeling, you can run the application in full screen:

* Open the application in Chrome for Android
* Select menu (three dots) and 'Add to Homescreen'
* Open the newly created icon on your device's homescreen

**Note: Facebook Login does not work correctly if the app is used as a Standalone. The popup will open, the user will
be logged in but it does not redirect back to the application. Reloading the application will authenticate you back and
running fine.**
