SmartThings Edge Driver for Roku devices
Provides an essential element to create home automations to "Netflix and chill" !

This driver provides local LAN control and monitoring of Roku devices including sticks and TVs:

Automatic device discovery
Configurable device state refresh rate
Roku power on/off
This function is generally available for Roku TV devices only, but may partially work for some other non-TV Roku devices: it also depends on the HDMI interface support of your TV
Send specific Roku remote keypress commands
Control media playback
Go to a configured Roku channel (i.e. "favorites")
Invoke any of the above Roku commands through automations
Pre-requisites:
SmartThings Hub
Driver Installation
Install to SmartThings hub via channel link: https://bestow-regional.api.smartthings.com/invite/d429RZv8m9lo

Enroll your hub and then select "Roku Driver v1.0" to install from the list of available drivers.

Once installed to the hub, using the SmartThings mobile app, perform an Add device / Scan nearby devices and all Roku devices on the LAN will be discovered and added as SmartThings devices. (Roku devices must be present on the same sub-net as the SmartThings hub)

Device Settings can be used to set the device status refresh interval in seconds. Default is 20 seconds.

#Code of Conduct...
The code of conduct for SmartThingsEdgeDrivers can be found in CODE_OF_CONDUCT.md.

#How to Contribute
Pull requests to this repo are intended to be from OEMs submitting pull requests for devices seeking Works With SmartThings (WWST) Certification, for maintaining existing certification, and for bug fixes to existing drivers. For more info on WWST certification and the submission process, visit our certification documentation.

By submitting a pull request, you represent that you have the right to license your contribution to SmartThings and agree by submitting your patch that your contributions are licensed under the Apache 2.0 license. Before submitting your pull request, please make sure you have tested your changes and that they follow the project guidelines for contributing code.

Before contributions can be merged, all contributors must agree to the SmartThings Individual Contributor License Agreement.

License
SmartThingsEdgeDrivers is released under the Apache 2.0 License.
