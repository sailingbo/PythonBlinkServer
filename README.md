# PythonBlinkServer
This is a simple Python script that accepts HTTP requests and lights up a blink(1) light depending on the request received.

## Example:
Send a request to [server]:8080/solid/red to light up the blink(1) red.
[server]:8080/clear will clear the blink(1).

## Current Supported Modes
* /solid/red
* /solid/green
* /solid/blue
* /flash/red
* /flash/green
* /flash/blue
* /clear

---
## Build into startup sequence:
I used this link to make it part of the bootup process. https://www.raspberrypi-spy.co.uk/2015/10/how-to-autorun-a-python-script-on-boot-using-systemd/
