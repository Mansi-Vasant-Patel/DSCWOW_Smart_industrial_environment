# DSCWOW_Smart_industrial_environment
 In the period of COVID, health concerns have been increased and are going to remain for a longer period of time and as the technology is going IoT devices are coming into the picture faster than ever. So, here we propose a smart industrial environment which will take care of our health and will allow us to do things smartly.

#Air pollution prediction
 1. To use the code of prediction download data.csv file and prediction.ipynb
 2. Keep both the files in same location
 3. You can run the code on online jupyter notebook or its desktop app.
 
#Smart tiffin
 1. This is a IoT project so you will be requiring a BME280 sensor which should be soldered with its pin, a 5V fan, Raspberry pi model 3 b, transistor (2n2222a). 
 2. Now you have to configure the Raspberry pi and install flask using sudo pip install flask.
 3. Then you have to run the main.py through command prompt with the command python3 main.py.
 4. You will get an IP address where the website is hosted and through this website you can control the smart tiffin.
 
#Inventory and logistics management
 1. We will need MRFC522 RFID reader, Hx711 with 1kg loadcell, IR sensor and servo motor combined with arduino uno serially communicating with raspberry pi. These will denote         factory and customers end.
 2. We will need DHT11 and Ubon NEO6m GPS module combined with NodeMCU ESP8266 to provide geo location of the truck involved in logistics and, provide humidity and temperature         details for the inventory it is carrying.  
 3. We will need 13.56 MHz RFID cards for scanning purposes.
 4. We will need adafruit library to connect to adafruit cloud.
