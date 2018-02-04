# Quick Overview
The goal of this project was to create a Printed Circuit Board (PCB) for our Controller Area Network (CAN) Bus using a star topology for increased resilience compared to our previous bus topology.
You can learn more CAN and various topologies [here](www.mindsensors.com/content/86-can-and-its-topology).
Each board was designed to accommodate up to **10** CAN devices to interconnect, i.e., 8 Victor SPXs or Talon SRXs along with a Power Distribution Panel and roboRIO.
Easy expansion is possible by linking multiple boards to each other directly to increase the total number of connections, i.e., 2 boards allows for 18 total connections.
When combined with code that is fault-tolerant, it can be possible to recover from the loss or disconnection of a device on the bus which would otherwise be catrostrophic.

# PCB Specifics
The PCB uses screw terminals to connect devices to the bus.
They, such as the ones we use from [Amazon](https://www.amazon.com/gp/product/B00EZ3QPCU/), are standard Wago 237-132 screw terminals.
It is ideal when the CAN wires are placed in Weidmuller ferrules, such as the ones we use from [Automation Direct](https://www.automationdirect.com/adc/Shopping/Catalog/Wiring_Solutions/BM_Group_-_Wire_End_Connectors/Insulated_Ferrules/DIN_Color_Single_Wire/BM-00601), but that is not required.
The terminating 120Ω resistors are optional in almost every use case and are for optional future funcionality.
However, should one or two 120Ω resistors be added, the corresponding optional male headers **must** be added to enable or disable the resistors.
The holes on the outer edge of the PCB can be used to add small zip ties to hold the pairs of Yellow and Green CAN wires to provide strain relief.

# Holder and Mounting Info
The PCB's holder was also designed to fit on standard 1" pegboard via zip ties or bolts.
The holes on the holder was designed to accommodate heat-set inserts, such as the ones we use from [McMaster-Carr](https://www.mcmaster.com/#93365a132/=1b46wa6), to provide threaded holes.
The board then uses at max 6 0.250" #6-32 bolts, such as the ones we use from [McMaster-Carr](https://www.mcmaster.com/#91251a144/=1bf0myv), to be anchored down.
Particularly, the spacing around the center holes allows for the use of thumb screws, such as the ones we use from [Amazon](https://www.amazon.com/Anodized-Aluminum-Computer-Thumbscrews-Thread/dp/B00BGZ1OFI/), to allow for easier removal early on.

# Files Provided
The files provided include the Eagle BRD, SCH, and EPF files, as well as STL files for the 3D printed holder.
The files are compatible with [Eagle](https://www.autodesk.com/products/eagle/free-download) 8.0 and up.
The DRU file used by our PCB manufacturer, [Silver Circuits](http://www.custompcb.com), is also provided.

# Additional Info
The images folder contains images of the board and schematic in Eagle, a image of the render of the holder, and images of the actual PCB in the 3D-printed holder.
If you have any questions, feel reach out and contact us at team5338@gmail.com or on Chief Delphi.
Please share with us your experiences of using them and any feedback you have!
