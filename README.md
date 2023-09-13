# BLE Example

This is a very quick example of performing OTA updates via BLE using BTStack on the ESP.

It does not have BluePad32 integration.


## How to use example
This has been built using ESP-IDf v5.

This project has been setup using VSCode and its ESP extension.

It has been configured to expect the device to be on COM port 4 and the device is a basic ESP32, not the C2/3.

To change the command port or device run the command `ESO-IDF: Device Configuration`.

To build and flash run the command `ESP-IDF: Build, Flash and start a monitor on your device`.

Once running you should see the text `BTstack up and running at ...` in the monitor.

Now you use the Corresponding web app hosted here: https://ste2425.github.io/btstackota/

That web app allows you to connect to the esp and read a hard coded value from the characteristic.

It also allows you to perform an OTA update by writing to the same characteristic.
