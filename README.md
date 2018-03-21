# Quick Overview
The goal of this project was to create a Printed Circuit Board (PCB) for our Controller Area Network (CAN) Bus using a star topology for our robot.
You can learn more CAN and various topologies [here](http://www.mindsensors.com/content/86-can-and-its-topology).
Each board was designed to accommodate up to **10** CAN devices, i.e., 8 Victor SPXs or Talon SRXs along with a Power Distribution Panel and RoboRIO.
Easy expansion is possible by linking multiple boards to each other directly to increase the total number of connections, i.e., 2 boards allows for 18 total connections.
When combined with code that is fault-tolerant, it can be possible to recover from the loss or disconnection of a device on the bus, which would be catastrophic on a daisy-chained network.
This project contains two folders, one for the PCB that our team currently uses on our competition robot, as well as one for the PCB that we plan to handout at the Chesapeake District Championships.
We have used these boards for two districts events, and are satisfied with their excellent performance and ease of wiring.

# PCB Specifics
The PCB uses screw terminals to connect devices to the bus.
They, such as the ones we use from [Amazon](https://www.amazon.com/gp/product/B00EZ3QPCU/), are standard Wago 237-132 screw terminals.
We have found it ideal when the CAN wires are placed in ferrules, such as the ones we use from [Automation Direct](https://www.automationdirect.com/adc/Shopping/Catalog/Wiring_Solutions/BM_Group_-_Wire_End_Connectors/Insulated_Ferrules/DIN_Color_Single_Wire/BM-00601), but that is not required.
The terminating 120Ω resistors are optional in almost every use case and are for extra future functionality to not require the use of two devices with built in termination.
However, should a 120Ω resistors be added, its corresponding optional male headers **must** be added to enable or disable the resistors.

# Holder and Mounting Info
The PCBs' holders were also designed to fit on standard 1" pegboard via zip ties or bolts.
The holes on each holder was designed to accommodate heat-set inserts, such as the ones we use from [McMaster-Carr](https://www.mcmaster.com/#93365a132/=1b46wa6), to provide threaded holes.
The board then uses at up to 6 0.1875" #6-32 bolts depending on the PCB, such as the ones we use from [McMaster-Carr](https://www.mcmaster.com/#91864a085/), to be anchored down.
Particularly, the spacing around the center holes allows for the use of thumb screws, such as the ones we use from [Amazon](https://www.amazon.com/Anodized-Aluminum-Computer-Thumbscrews-Thread/dp/B00BGZ1OFI/), to allow for easier insertion and removal before final mounting.

# Files
For each board, the files provided include the Eagle BRD, SCH, and EPF files, as well as STL files for the 3D printed holder.
The files are compatible with [Eagle](https://www.autodesk.com/products/eagle/free-download) 8.0 and up.
The DRU file used by our PCB fab, [Silver Circuits](http://www.custompcb.com), is also provided. However, the Eagles files can be used to manufacture the board with the PCB fab of your choice
For each board, there are also images of the board layout and schematic in Eagle, a render of the holder, and images of the actual PCB in the 3D-printed holder.

# Final Notes
If you have any questions, feel reach out and contact us at team5338@gmail.com or on [Chief Delphi]().
Please share with us your experiences if you use them and any feedback you have!
