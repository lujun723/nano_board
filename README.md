#Nano Board for STM32F407VxT

##for who
- EE
- Students
- Electronic enthusiasts

##what inside
- two 2*25pins connectors lead out the cpu pins
- the core board is connected to a base board normally
- an USB cable for usb connect and power supply on the base board
- an onboard SWD debug jack via microUSB interface
- an onboard USART-USB debug lan via miniUSB interface
- all pins of cpu are lead out on two 2.54 wafer

##how it works
1. plug the usb cable into the base board since the other side connect to a PC USB jack.
2. the power led lighting up means it start working.
3. the heartbeat led would toggle at first time(it depends on the beaten thread works or not). 
4. you can use a microUSB cable to connect your SWD debugger.
5. you can use a miniUSB cable to print out the debug imformations.

##cape boards
- wifi board（not active now）
- DC motor board（not active now）
- step motor board（not active now）
- Bluetooth4.0 board（not active now）
- leds and button board（not active now）
- lcd board（not active now）
- to be continue...

##examples
1. before the beginning
2. hardware test(led and USART output)
3. rt-thread first touch via a terminal screen
4. heartbeat led toggle and command controls
5. rgb led controls via command line
6. to be added...
