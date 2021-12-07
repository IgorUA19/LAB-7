This code is what uploads the temperature sensor data to our ThingSpeak channel.

It takes the information that is being read from the temperature sensor. 
It get's this information by reading it off the COM3 port.
It the connects to our ThingSpeak channel using a specific channel ID provided.
It then begins the process of sending this information to ThingSpeak which gets 
displayed in our charts.
