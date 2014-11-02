relaycontrol
============

USBrelay Controller

Allows you to turn on and off each individual (or all) relays on HID-compliant USBrelay modules. Currently supports vendor ID 0x16c0 and product ID 0x05df (DCT-Tech compliant).

Future releases will allow you to configure custom VID and PID as well as optional serial number for the device.

Aimed towards FreeBSD and Mac OS X users.

![usbrelay8](https://cloud.githubusercontent.com/assets/9513010/4875323/de82cc7a-6291-11e4-922b-5f5197c27a16.jpg)

<code>Usage: relaycontrol relay state</code>

<code> Where relay is either 0 (all relays) or an integer between 1 and 8</code>

<code> And state is either 1 (on) or 0 (off)</code>

Based on the works of Signal 11 Software's HIDAPI @ http://www.signal11.us/oss/hidapi/
