# placesGiS
placesGiS is a Full Stack Application to show diffrent information about Rooms in my School.
It has a Arduino/ESP Code Part to collect Temperature, Humidity, Light and "Persons" with the Schematics in this Repository.
And a Web Part used to convert the Data and Display it to the Users.

## Hardware
I used an ESP12E on a Nodemcu Board for each room i wanted to add.
I added a DHT and a Light Sensor.
The Enclosure was 3D Printed and Power is given externally.

## Software
The Code consists of two Parts: Arduino and Web
Arduino: I scan through the Network with the esp8266 Promiscous Mode, capture Packets, get the Mac and add them to a List. Finaly i send them to my Web server
Web: Programmed in NodeJS, i recieve the Data through GET Parameters and Display them on a Website designed in Bootstrap.

## Links
Promiscous Mode: https://github.com/NoahBlaaa15/esp8266-promiscous-example
Arduino Code:https://github.com/NoahBlaaa15/placesGiS-Arduino
Web Code: https://github.com/NoahBlaaa15/placesGiS-Backend
Project Status: https://github.com/users/NoahBlaaa15/projects/1

## License
All Projects belonging to this Application are Licensed under the MIT License until furhter noticed.
