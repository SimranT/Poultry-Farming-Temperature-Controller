# Elecronic-Chicken-Incubator
The hardware parts used: 
temperature and humidity sensor (DHT11)
weight sensor (HX711)
Wifi Module (ESP12E)

Description:
To automate the brooding place for newly born chicken in a poultry farm.
To maintain a sound condition for the growth of chicken by regulating
temperature.
To obtain real time data through internet.

“Intensive Electronic Chicken Brooding System over Wi-Fi” is mainly divided into five
Units Temperature and humidity sensing unit, ESP8266 Wi-Fi module, Weight sensing
unit, Temperature Controller and User Interface unit.
The Temperature sensor DHT11 senses the temperature in the Brooder surrounding and
sends the data to the ESP8266 Wi-Fi module then the data received is compared with the
standard required temperature for the chickens and as per the need of change in heat the
temperature controller unit comes into play. This data is also further used to display on
the user interface unit. Temperature controller unit consists of Relay circuit controlling
the cooling and heating element. If there is excess of heat in the area then the heating
element is adjourned in order to get the desired temperature maintained.
The weight sensing unit consists of the load cell and HX711 module. Weights on the load
cell holding the food and water containers are sensed by HX711 module and the data is
passed to ESP8266 Wi-Fi module. This data send to the server by the module is further
worked upon and used to view it on the user interface.
A web application has been generated using some software languages like Php &
Javascript to achieve a platform where the data being passed by the Wifi module is
generated with the help of the incoming data from different sensors installed in the
circuit. The Temperature Sensor, DHT11 proving with the atmospheric temperature and
humidity at that instant, while simultaneously we have a relay installed to get checked
every now and then to see if the temperature has been exceeded for that particular time
being and hence it gets updated automatically based on the data passed by the server for
the exact daily routines.
