# cordova-plugin-fcm-config

> !! This Plugin is not necessary if [cordova-plugin-fcm](https://github.com/fechanique/cordova-plugin-fcm) > 2.0 is used !!

This plugin copies the required FCM configurations in the project root folders and Xcode project. 
It is used in combination with the great [cordova-plugin-fcm](https://github.com/fechanique/cordova-plugin-fcm) plugin.

> This project is just solving the integration of the FCM configurations to prevent the git checkin of all `platform/*` folders.

## Howto

1. Copy this repository as `cordova-plugin-fcm-config` folder into your cordova project root folder.
2. Replace the `google-services.json` and `GoogleService-Info.plist` files from Firebase console.
3. Add the plugin into your `config.xml` with 
  
```<plugin name="cordova-plugin-fcm-config" spec="cordova-plugin-fcm-config" />```
