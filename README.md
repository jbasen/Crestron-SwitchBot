# Crestron-SwitchBot

Crestron Drivers for 3-Series and 4-Series processors that allows a Crestron system to control SwitchBots, the SwitchBot Curtain, and SwitchBot Scenes

V2 - Fixed a bug in the S# code that parses the device list

V3 - Updated to SwitchBot API v1.1 Security and added support for the SwitchBot Lock

V4 - Adds support for SwitchBot Meter and Meter Plus

V5 - Adds support for SwitchBot Blind Tilt.
IMPORTANT - THERE IS CURRENTLY A KNOWN BUG IN THE SWITCHBOT API AND THE SET_POSITION_DOWN
ANALOG INPUT DOESN'T WORK.  ONCE SWITCHBOT FIXES THE BUG THE ANALOG INPUT SHOULD START 
WORKING WITHOUT ANY CHANGE TO THIS DRIVER.  IF YOU NEED TO CLOSE THE BLIND IN THE DOWN
TILT POSITION THERE IS A DIGITAL INPUT TO ACCOMPLISH THIS.
