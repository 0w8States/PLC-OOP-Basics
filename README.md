# OOP Basic projects for the IEC61131-3 PLC Environment

In this repo we have a few sample projects to get started with OOP in the IEC61131-3 environment. The **Tutorials** directory covers some of the basic concepts of OOP within the IEC61131-3 PLC language Structured Text.



### Tutorials

- **Flash Generator** - This example show the basic concept of overriding classes with inheritance. The base class implements a Flash method that pulses at a frequency based on the Cycletime property. The overriding GeneratorEx extends off the base, and adjusts the Flash method to be ON 1/3 of the time.

  

- **Light Control** - This example shows the basic concept behind interfaces. As long as the classes share and implement a common interface, you can call method for those classes through a single interface.

  

- **Abstract Drive** - This example shows the basic function of abstraction. You essentially have a base 'template' for the drive class, with no implementation. Every class extension from the base must implement the known abstract methods.



### Extended Samples

- **Lighting Controller** - This is an extended example of the Light Control sample above. It uses interfaces to control multiple lights in a room.

