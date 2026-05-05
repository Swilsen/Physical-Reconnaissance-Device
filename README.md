# Physical-Reconnaissance-Device
The project involved configuring a Raspberry Pi to regularly send a reverse shell request via ssh to a virtual machine in the Azure Cloud. This virtual machine could also be connected to via ssh from other devices over the internet, which would further allow interaction with the Raspberry Pi via the reverse shell connection. The goal was to create a scenario where the Raspberry Pi device was connected with an ethernet cable in a targeted physical penetration test, and it would be possible to conduct reconnaissance and exploits on the internal network in the scenario from a remote device.


[![Figure 1 – Project Setup Overview](PhysicalReconnaissanceDevice.png)](PhysicalReconnaissanceDevice.png)
