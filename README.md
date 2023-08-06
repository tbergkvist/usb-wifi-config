# Enable wifi config on a preinstalled raspberry pi or ubuntu system using a usb drive.
Tired of connecting displays and keyboards when your system no longer has access to the wifi network it was configured to use?
This project is for people who hack on robots etc at different locations and need a quick way to add new wifi connections to ubuntu and rpi systems.

## Usage
- Put a file with wifi ssid and password on a usb drive.
- Insert the usb drive into your rpi or ubuntu system and start it up.
- The script should add the new network to the wpa_supplicant file and your wifi should be set up.
