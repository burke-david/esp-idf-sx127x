# Example of Arduino environment   
I use [this](https://github.com/sandeepmistry/arduino-LoRa).   

# Wirering

|SX127x||ATmega||
|:-:|:-:|:-:|:-:
|RST|--|D9|*1|
|NSS|--|D10|*1|
|MOSI|--|D11|*1|
|MISO|--|D12||
|SCK|--|D13|*1|
|VCC|--|3.3V||
|GND|--|GND||

(*1)    
SX127x is not 5V tolerant.   
You need level shift from 5V to 3.3V.   
