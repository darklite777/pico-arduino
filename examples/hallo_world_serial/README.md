
We just print the test Hallo World every second to the USB console and to Serial1 and Serial2

By default we use the following pins: 

- Serial1: UART0 tx (GP0) / rx (GP1)  
- Serial2: UART1 tx (GP4) / rx (GP5) 

In the example we show how to redefine the pins to use GP12 and GP13.

To test the functionality I am using a YP-05 FTDI 

## Connections for the YP-05

Before making any connectins, make sure that the jumper is set to 3.3V !

 YP-05   | Pico              
---------|-------------------
 RX      | TX (GPIO 12) 
 TX      | RX (GPIO 13) 
 GND     | GND               

<img src="https://www.pschatzmann.ch/wp-content/uploads/2021/03/ftdi.jpg" alt="FTDI">

You can connect with any Termial Emulation using the following settings

- Speed: 115200
- Data Bits: 8
- Parity: None
- Stop Bits: 1
- No Hardware flow control


