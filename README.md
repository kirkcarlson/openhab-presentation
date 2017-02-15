# openhab-presentation
Presentation of openhab IoT information integrator

This is an OpenOffice presentation for OpenHAB, MQTT and One-Wire devices.
It outlines personal experience with the programs in implementing an
IoT network to drive a kiosk display.

The heart of the kiosk is a custom single page Web app. The HTML and basic
Javascript are discussed in the presentation. Physially the kiosk is a dedicated
Raspberry Pi driving a touch screen in the Smarti-Pi Enclosure. The Pi boots
up into the x-server which then loads the Chromium browser pointed to the
kiosk web page. The web page refetches data using AJAX and the OpenHAB RESTful
API.
