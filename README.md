# bulb on off using ESP board HOTSPOT
 very easy to follow 
copy paste code 
on line 88 you can set your own password and ssid by default it will be 
ssid=name
password=password
led pin are D7 and D1 on ESP12E board 
you can set your static IP on line 87 by default it is :192.168.0.17
if you connect to this device and go on the IP which you designated you can either turn on the pin D7 and D1 or turn them off.
For the connections you can use either 3v relay(preferred) or 5v Relay. In this led/bulb pin is D7 on ESP board.
Also in the latest release (v1) ESP board does save the state: When electricity goes or power outage occurs.
