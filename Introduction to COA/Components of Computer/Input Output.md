# Input/Output Components

I/O components facilitate communication b/w CPU and external devices for I/O
operations

## Ports

### Physical Ports

- `USB Ports`: to connect USB devices such as keyboards, USB drives, printers,
etc.

- `Ethernet Ports`: for connecting to LANs or Internet

- `Audio Ports`: for connecting speakers, headphones, microphones etc.

- `Video Ports`: for connecting monitors, displays, graphic cards etc.

### Digital Ports

- Digital ports are identified by numeric values ranging from $0$ to $65535$

- Ports $0$ to $1023$ are reserved for well-known services and protocols

- Ports $1024$ to $49151$ are registered ports assigned by IANA

- Ports $49152$ to $65535$ are dynamic or private ports for temporary connections
or testing purposes

## Expansion Slots

- Connectors on the motherboard for additional expansion cards

- Common options include RAM, SSD, GPU, NICs, sound cards and storage controllers

## Peripherals

- Input devices such as keyboards, mouse, track pads, joysticks etc.

- Output devices such as monitors, printers, speakers, projectors etc.

- Storage devices such as USBs, external HDDs, Optical drives (CD/DVD) and flash
drives

## Controllers & Interfaces

- They manage the communication b/w peripherals and the CPU

- `Storage Controllers` manage data transfer b/w CPU and storage devices such as
Hard drive, RAID and SATA/IDE controllers

- `NIC`: *Network Interface Controllers* facilitates comm b/w CPU and network devices

- `Sound Controllers` handles audio I/O operations such as processing and converting
analogue and digital audio signals

- `Graphic Controllers` manages video I/O like rendering and displaying graphical
content

## Device Drivers & Software

- Enables OS to communicate w/ and control external devices

- Includes device drivers and softwares provided by the manufacturers
