# Software Development for an Ultrasonic Scanning Rig
## README File
If not already done so, download the github repository and unzip the repository

### Requirements for the Software
Follow the steps in all 3 sections to ensure all prerequisities are performed to run the software successfully 
* LabVIEW 2020 (Section 1)
* LabVIEW System Drivers (Section 2)
* Software GitHUB Reposotory Files (Section 3)

### Section 1 - Installing LabVIEW 2020
Install the software using the following link : [LabVIEW 2020](https://www.ni.com/en-gb/support/downloads/software-products/download.labview.html#369643)
#### Select the following parameters
* Correct operating system for your machine
* Version: LabVIEW 2020 or LabVIEW 2020 SP1
* Base, Full Professional
* 32-Bit or 64-Bit according to your machine
* Driver Software Included: Yes

### Section 2 - Installing LabVIEW Drivers
1) Unzip the folder: LabView System Drivers.zip
2) Open (KOD LabVIEW Ethernet Sample v1.0.2/software/readme) and follow the steps to install the drivers for the LG Motion LTD PMX-3ET-SA scanning rig
3) Open (LeCroy Wave Series/LeCroy Wave Series Readme) and follows the steps to install the drivers for the LeCroy Osciloscopes
4) Run the following file (lecroyvicppassportinstaller_v1.12.exe) to install the required VISA Passport for the LeCroy Osciloscopes

### Section 3 - GitHUB Reposotory Files
1) Open 'XYZ Ultrasonic Scanning Software v1.3 (Final).vi' from the GitHub Repo
* If it pops up with a message asking you for the location of Sub_Vi's, locate the correct one according to the the file name in either 'Sub-VIs-Osc/Sub-VIs-XYZ/Sub-VIs-XYZ-Osc' folders
2) Click run on the top left corner to operate the software
3) Open up the 'User_Manual.pdf' file from the GitHub Repo on how to operate the software and further information


### Note
The following folders/files can be ignored unless needing to revert to a previous version of the software for debugging purposes:
* XYZ Scanning Software v1.0
* XYZ Scanning Software v1.1
* XYZ Scanning Software v1.2
