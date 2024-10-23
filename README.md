# UDS implementation over CAN

## Pre-requisites

- NXP S32K144EVB
- USB Cable for NXP board
- 12V Power cable for NXP board
- PCAN cable
- PCAN view (Software)
- Jumper wires for connection between NXP board and PCAN (Check the image for connection: https://www.peak-system.com/fileadmin/images/products/accessories/Wiring_Cable2.jpg)
- S32 Design Studio Platform (Software)

## Run the project
<p>Once you have set up the physical connection between laptop and NXP board, follow the steps below to run the projects.</p>

- Clone the repository
- Open S32 Design Studio Platform
- Select your workspace and click on <b>Launch</b>
- Click on <b>File</b> then <b>Open Projects from File System</b>
- Click on <b>Directory</b>, select the repository folder you have cloned and click on <b>Finish</b>
- Once you see project folder in the <b>Project Explorer</b>, click on the down arrow beside the <b>Debug</b> icon and then click on <b>Debug Configurations</b>
- In the window opened, click on <b>GDB PEMicro Interface Debugging</b> and you will see some configurations will be listed.
- Click on the <b>S32K144_Project_FlexCan_Debug_FLASH_PNE</b> and then click on <b>PEMicro Debugger</b> in the right section of the window
- Make sure
    - <b>OpenSDA Embedded Debug - USB Port</b> selected in the <b>Interface</b> dropdown list
    - <b>USB1 - OpenSDA (XXXXXXX)</b> selected in the <b>Port</b> dropdown list
    - <b>Target</b> is S32K144F512M15
- Click on <b>Debug</b> and you will see S32 Desing Studio Platform compiles and starts execution and once it reaches to first line of <b>main</b> function, it will stop execution.

## Debug the project
TBA
