# CAN-PCBs
The goal of this project was to a create PCB for our CAN Bus using a star topology to increase resiliance. The board's holder was designed to fit on standard 1" pegboard and use screw terminals to connect devices, such as Talon SRXs, to the bus.

The files provided include the Eagle BRD, SCH, and EPF files, as well as STL files for the 3D printed holder. The DRU file used by our PCB manufacturer, [Silver Circuits](www.custompcb.com), is also provided. The holes on the holder are designed to accomodate these [heat-set inserts](https://www.mcmaster.com/#93365a132/=1b46wa6), installed using a standard soldering iron, to provide threaded insert holes. The board then uses at max 6 0.250" #6-32 bolts to be anchored down. 

The screw terminals are standard Wago 237-132 screw terminals obtained from [Amazon](https://www.amazon.com/gp/product/B00EZ3QPCU/). The terminating resistors are optional, but should those 120Ω resistors be added, the optional male headers **must** be added to enable or disable the resistor. The holes on the outer edge can be used to add zip ties to hold the wires and provide strain relief as well.

The images folder contains images of the board in Eagle, a render of the holder, and images of the PCB and holder on our robot.

If you have any questions, feel free to contact us at team5338@gmail.com.
