# Internet of Four Things

Converting a serial port into three digital outputs and one digital inputs.

## First get your serial port

Below shows a DE9 serial port that was common on older systems. If you have one of these you are done. 

![Serial port DB9](images/serial-port.jpg)

More modern ports may look like this.

![Modern serial port](images/440px-Serial_port-from-wikipedia.jpg)

Modern systems may not have a serial port. In this case you will need to use a USB-Serial converter can be used. 

![Usb to RS232 converter](images/usb-rs232-large.jpg)

## A short discussion on RS232 signals

[RS232](https://en.wikipedia.org/wiki/RS-232#Data_and_control_signals) specifies how data terminating equipment (DTE) communicates to the data communication equipment (DCE). In this discussion, the computer/laptop is the DTE. 

![RS232 DE9 pinouts](images/modemstraightdb9.gif)

Thanks to [wilbo6666](http://wilbo666.pbworks.com/w/page/49320712/RS232) for this fine image of the DE9<sup>[1](#de9Footnote1)</sup> pinouts.

From the computers (DTE) point of view, there are three output pins and five input pins and one ground pin. 

One pair of pins (RD and TD) are used for data which are not suitable for signalling. 

One pair of pins (DTR and DSR) are used to power the input pins and to simulate an active DCE ready for communication. 

This leaves one output pin and three input pins. 

## Schematic



## Usage

The output pins can power a small LED but not much more. 
Format: ![Alt Text](images/led-red.jpg)

---

<a name="de9Footnote1">1</a>: The DE9 is often incorrectly called DB9. 

![D sub miniature connectors](images/DSubminiatures.svg)
