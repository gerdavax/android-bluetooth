# android-bluetooth
Dump of my Android Bluetooth library for Android 1.x, published on Google Code in July 2009. As far as I knew at that time, it was the world first open source library to access Android Bluetooth stack.

[ORIGINAL DESCRIPTION ON GOOGLE CODE]

Experimental unofficial Bluetooth API for Android

# Important News
Now (2009/10/27) that Android 2.0 supports Bluetooth, we will redesign our (unofficial) Bluetooth API for Android to be as much similar as possible to the official API. This way: applications running on Android 1.1, 1.5 and 1.6 based on Bluetooth API will be easily ported to Android 2.0 devices not upgraded to latest firmware version will be able to run Bluetooth features. Redesigned API will be published as "Bluetooth API 1.0" and it is expected to be available the first week of November.

# Description
This project aims to provide a simple API to access Android's Bluetooth stack. This library does not to require a rooted device: it is intended to work with standard firmware provided by phone manufacturers.

Currently only remote device scanning, remote device pairing, (partial) service discovery (SDP) and client RFCOMM serial connections are supported. Support for other profiles (e.g. audio) than RFCOMM is not available. RFCOMM server connections are still not supported.

This library is to be considered as experimental, it has not been designed nor tested for production environments. Any future change to the Bluetooth stack on Android releases could make this library totally useless. Although it has been successfully tested on firmware 1.1, 1.5 "cupcake" and 1.6 "donut", do not expect to get it work on future releases (even minor updates). Use it at your own risk.

Check the sample application "Bluetooth Samples" on the Android Market.

Don't forget to add following permissions to your application:

The (unofficial) Bluetooth API for Android has been tested on:

- HTC Dream (aka T-Mobile G1, firmware 1.1, 1.5 and 1.6)
- HTC Magic (firmware 1.5 and 1.6)
- HTC Tattoo (firmware 1.6)
- Huawei U8220 (aka T-Mobile Pulse, firmware 1.5)
 - (partially tested) Samsung Galaxy (firmware 1.5)
It has been reported as NOT working on HTC Hero (I have not this handset, therefore I could not do any investigation to date). Still not tested on Archos 5 Internet Tablet and Zii EGG (which still does not support Bluetooth on its Android porting).
