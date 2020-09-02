Device notifies phone of heat index every second.
DHT22 must be hooked up to pin 4 by default.
Use with nrfConnect app, must connect to device then look under "Unknown Service"
My DHT22 will often fail to read the value, currently the program just doesn't transmit if it fails to read, but this 
could lead to long delays between temperature reading.
Go to https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-sensor-arduino-ide/ to learn how to install DHT22 libraries
and hook up the DHT22 sensor.