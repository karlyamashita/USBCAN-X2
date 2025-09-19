USBCAN-X2 dual CAN bus analyzer using a STM32G491CE.

The schematic and gerber files are open source.

### Description
I have been working on a [CAN Jammer](https://github.com/karlyamashita/CAN_Jammer_STM32F105RB) project and need a dual CAN bus analyzer that uses 1 STM32 microcontroller. I am finding it difficult to find a vendor that sells a dual CAN bus analyzer that uses an STM32 that is open source and does not read protect the STM32 at RDP level 2. Most vendors that i've contacted are using NXP or a Chinese brand microcontroller. 
<br><br>
Because of the difficulties of finding a dual CAN bus analyzer, I've decided to create this open source project. Since FDCAN is becoming more mainstream, I've decided to use the STM32G491CE with FDCAN controllers which meet the requirements. 

### PCB
The PBC was designed around the USBCAN-2A, matching the USB and screw terminal connector. I am hoping some Chinese or someone local will start to manufacture this project to make readily available for purchase. Since the plastic case seems to be a dime a dozen, it will make it easier fo manufacturers to have a completely enclosed product without the need to tool for a new case, if I did create a different size PCB.

`USBCAN-2A`
<img width="1400" height="504" alt="Image" src="https://github.com/user-attachments/assets/289c474b-fdd6-44b0-b219-7b2e3e7a5577" />

### Firmware
The FW is being developed and will be open source.

### Software
CAN-X will support the USBCAN-X2 once the Firmware is done.

### Image
This is the 3D image of the USBCAN-X2

`USBCAN-X2`
<img width="1724" height="938" alt="Image" src="https://github.com/user-attachments/assets/2ed79b4e-b676-420d-b28a-e8b00d68451f" />




