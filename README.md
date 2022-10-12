# Cordova Zoom Plugin

This project contains the sources for the Cordova Zoom plugin originally released by Zoom Video Communications, Inc.

Since Zoom decided to drop official support for the Cordova/Ionic SDK, I made some efforts keep it working with more recent versions of the Zoom SDK.

Links for more information
* Zoom Software Quarterly Lifecycle Policy https://support.zoom.us/hc/en-us/articles/360059429231-9-month-release-window-
* Original Github project https://github.com/zoom/zoom-sdk-ionic
* Thread in Zoom dev forum https://devforum.zoom.us/t/unable-to-join-meeting-ionic-app/74211

Current supported Zoom SDK version: 5.12 

## Usage
To use this plugin, you need to download the iOS and Android SDKs from the Zoom Marketplace.

### Android

* Unzip the SDK
* mkdir libs/android
* find the files mobilertc.aar and commonlib.aar and copy them to libs/android/

### iOS

* Unzip the SDK
* mkdir libs/ios
* copy lib/MobileRTCResources.bundle to libs/ios/
* copy lib/MobileRTC.xcframework/ios-arm64/MobileRTC.framework to libs/ios

## Disclaimer

This project is provided as-is. There are features that are not working (e.g. login with username/password) or even tested. Use at your own risk. I cannot provide any support for this plugin, but I am happy to accept pull-requests/merge-requests.
