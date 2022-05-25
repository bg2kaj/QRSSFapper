# QRSSFapper
A STM32 based QRSS CW beacon controller

This tool runs on STM32F103 but it should be okay with all STM32 series microcontroller.
Basically it is a beacon output proper CW/QRSS on-off state via a GPIO, you can drive other device with relay or anything.
On start up, It would check STM32 flash for setting and you can modify your own setting with serial port #1 menu.

There's 3 parameter you could modify: beacon info, CW dot speed in millisecond and CW sentence interval in millisecond.
Follow the start up menu to set those parameters.

	CW Format Specification
	CW: Dit:Dat 1:3
	Dit-Dat spacing 1 Dit
	Charactor spacing 3 Dit
	Words spacing 7 Dit

	Normal CW Dit: 120ms for 10WPM
	4 WPM CW Dit: 300ms
	1 sec Dit: 1000ms
	3 sec Dit: 3000ms
	10sec Dit: 10000ms
  
  73 and have fun!
  BG2KAJ
