# Introduction
An extension for Chromium-based browsers to interact with non-HID USB devices for collecting any data emitted by the device.

# Screenshots & Demo
COMING SOON

# Features
1. Connects to any USB device that communicates using DLL classes.
1. Activates only for certain URLs that subscribe/listen for device data.
1. Displays information in an integrated popup for user to review the incoming data.
1. Autofills the data into forms when the subscribing page URL is in context.

# Supported Platforms
* Chromium-based browsers: Google Chrome, Microsoft Edge, Brave

Note: This extension will work in Microsoft Windows only because the native host executable for many devices are windows-based.
Note 2: If you need this extension to work for a non-Windows-based operating system, please contact me for a custom plugin.

# Installation
COMING SOON

# Configuration 
This extension is very flexible as you can configure both the source of and destination for the data. There are no limits on the number of source devices and no limits on then number of destination fields or pages. The mapping from source to destination is fully configurable. 
- Register source hardware device(s). 
- Register URL's that will activate the data listener. This can be a URL fragment too. 
- Select the input field for the desired page that will be consuming the data. 
- Configure the regex to parse and relay the data to the target input field. 
- Run a test to confirm that the hardware integration is working. 

# Technical Specifications
* Deployed as a Google [Browser Extensions](https://developer.chrome.com/docs/extensions/mv3/getstarted/extensions-101) to support web-based applications that are run using Chromium browsers.
* Uses Google [Native Messaging](https://developer.chrome.com/docs/apps/nativeMessaging) specifications for Chromium browsers as the basis for communicating with connected USB devices.

# License
COMING SOON

# Donations
COMING SOON
