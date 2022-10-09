# Introduction
An extension for Chromium-based browsers to interact with non-HID USB devices to collect any data emitted by the device.

# Features
1. Connects to any USB device that communicates using DLL classes.
1. Activates only for certain URLs that subscribe/listen for device data.
1. Displays information in an integrated popup for user to review the incoming data.
1. Autofills the data into forms when the subscribing page URL is in context.

# Supported Platforms
* Microsoft Windows
* Chromium-based browsers (e.g., Google Chrome, Microsoft Edge, Brave)

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
Uses Chromium's [Native Messaging](https://developer.chrome.com/docs/apps/nativeMessaging) specifications as the basis for communicating with connected USB devices.

# License
COMING SOON

# Donations
COMING SOON
