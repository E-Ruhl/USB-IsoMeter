# USB-IsoMeter

The goal of this project is to develop a USB isolator that can power and transmit date through usb from one device to another while offering protection and power monitoring of the output port, displaying Voltage and Current as well as providing Power and energy metering. Basically the designe will be intended to protect a more expensive control/coding device from a potentially janky test device with the added benifit of providing some generic data read outs for said test device. 

This project was originally inspiered by the work of Oliver, who's work I will attempt to link here later. 

The original design has a male end USB plug which I will be removing in favor of the already attatched micro port. Perhaps in v2, I'll add in another female port to the transmitting side for use with a cellphone. I may also consider adding in a basic DC wire connection terminal for use with external power systems. 

Another design possibility I'd like to persue would be developing a USB Bus type of system where there are multiple outputs. The desing would then include write over usb capability to be controlled by a switch, although this design method seems impractical and expensive. The only useful application of the USB terminal bus would be for providing 5v power to multiple devices while metering the power consumption, although current provided from a USB port would be insufficient to run more than one device in practice, so the bus may end up simply being something that is connected to external power with a USB Bus connected through the female port. 


