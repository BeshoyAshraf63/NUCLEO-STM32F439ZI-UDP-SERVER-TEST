# NUCLEO-STM32F439ZI-UDP-SERVER-LwIP-TEST
This is an application design to send data to UDP server (board itself) of address 192.168.1.7 and port number=7 by using LwIP stack.
.When data recieved = "OPEN" --> all 3 leds turns on.
.When data recieved = "CLOSE" --> all 3 leds turns on.
.Otherwise the reply comes in form of HELLO (recieved data) FROM UDP SERVER.
# How to use ?
1)Download STM32 Cube ide then flash the code on board.
2)Connect the board by ethernet cable directly to your laptop/pc.
3)Download hercules application then set the port number = 7 and module ip = 192.168.1.7.
4)Click listen then test it and enjoy ;) .
