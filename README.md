CavroRibbonInterfaceBoard
=========================
Electrical interface board for converting Cavro liquid handler into a high performance RepStrap 3D printer.
This board is for recycling the internal ribbon cable for better cable management inside the machine once
converted. The interface board packs the stepper motor signals and thermocouple SPI signal's as well as 
power and ground for the thermocouple ADCs into a connector that the original ribbon cable attaches to.
There will be two of these boards per arm on a given Cavro machine, one topside on the arm connecting
the thermocouples and motors and another in the electronics compartment for breaking out the signals in
the ribbon cable into individual connectors to connect to the RAMPS shield.
