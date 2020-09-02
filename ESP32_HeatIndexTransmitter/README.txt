Device notifies phone of heat index every second.
DHT22 must be hooked up to pin 4 by default.
Use with nrfConnect app, must connect to device then look under "Unknown Service"
My DHT22 will often fail to read the value, currently the program just doesn't transmit if it fails to read, but this 
could lead to long delays between temperature reading.
Also need to implement sleep modes, might not be possible with Arduino IDE, may need to use ESP-IDF

