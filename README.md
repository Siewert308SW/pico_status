# pico_status
Python script to display status of the UPS PIco HV3.0A series.<br />
<br />
# Compatibility
UPS HV3.0A PIco Status is ment for firmware version 31 or up.<br />
Not compatible with firmware version 30 or earlier.<br />
<br />
# Sidenote
The info output depends on registers.<br />
If a register output isn't right in the script or not corresponding your board then the output could be false.<br />
Don't blame the board dev for false readings, just amend the script if necessary to suite your corresponding register values for your board. <br />
<br />
![alt text](pico_status.png "pico_status.py")
