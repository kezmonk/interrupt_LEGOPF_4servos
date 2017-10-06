# interrupt_LEGOPF_4servos
interrupt_LEGOPF_4servos is a working code for reading out LEGO PF 8885 messages with an Arduino

this code was tested on UNO and Nano (ATMEGA328)

this version is set up to control up to four 180° servos, with the different channels controlling return-to-center or position-hold, but it can be easily chnaged to any other output.

this work was partially inspired by https://create.arduino.cc/projecthub/Arduino_Scuola/simple-arduino-based-lego-power-function-receiver-52fad9, and https://github.com/matthiaszimmermann/ArduinoLegoIrReceiver, http://brickostan.com/arduino-lpf/,
but was coded and values measuered all by me. I was not able to see the STOP command with my PF 8885 remote - but the GAP message was consistently there - I think this is the major change/difference compared to the others with respect to the PF message capture. 
 
note: the PF IR code was released as open source here: http://www.technicbricks.com/2008/01/power-functions-rc-protocol-released-as.html, and the orginal document http://storage.technicbricks.com/Media/2008/TBs_20080125_1/LEGO%20Power%20Functions%20RC%20v100.pdf,
 
LEGO is the trademark of The LEGO Group, as such copyright, trademarks and other proprietary rights concerning LEGO belong to the LEGO Company.
