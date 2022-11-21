# OP25mobilePi

The goal of this project is to create an i2c display interface for the OP25 Digital Trunked Radio Decoder Project running on a Raspberry Pi. This will effectively decode APCO P25 Scanner traffic such as Police, Fire, EMS, City, Municipalities, etc. The JSON data will be pulled from the OP25 web UI and displayed on the i2c screen in real time. The Raspberry Pi will be enclosed in a rugged aluminum case similar to a walkie talkie setup for mobile use. 

DISPLAY DATA:
- Current Talk Group
- Display Talk ID channel #
- Display Talk ID description
- Volume level

CONTROLS:
- push button rotary encoder to access main menu system and make selections
- push button 1 for safe shutdown 
- push button 2 customizable function

MENU SYSTEM:
- Volume control
- Channel control
- Scan frequencies
- Hold frequency
- Mute 

REMOTE ACCESS CONTROL:
- Host AP access point WiFi Hotspot allows users to connect to the Raspberry Pi and view the full sized web UI provided by OP25 to view spectrum details, channel info, make changes, etc.
- Bridged wlan0 to eth0 allow the outside WiFi connected user to directly access the OP25 web UI via port 8080 that is hosted on the eth0 subnet
