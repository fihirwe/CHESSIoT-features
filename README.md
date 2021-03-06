# CHESSIoT-features

This repository contains features resources for installing the latest CHESS extension on top of the CHESS1.0.0 version or later. 
The new extension includes the following:

   **---- FINISHED IMPLEMENTATION ----**
   
     - CHESSIoT DSL (CHESSML lanaguage extended with IoT constructs)
     - Perform safety analysis on designed system (cross -domain) 
     - Basic failure probaility assignment and generate probability file.
     - Fully generated FMEA table
     - Fully generate Fault tree
     - Analyse Fault tree (removing unnecessary propagations paths)
     - Conduct quantitative analysis (system's failure rates calculated)
     
   **--- FEATURES UNDER DEVELOPMENT (IoT domain) ----**
   
     - Functional level modeling of IoT systems
     - Platform code generation / emplying ThingML
     - Design of deployment environment of IoT systems
     - Generate deployment artifact
     - Generate deployment autoamtion scripts

The official CHESS1.0.0 can be downloaded from the official downloading [link](https://www.eclipse.org/chess/download.html). The CHESS IoT source code can be accessed through this [link](https://github.com/fihirwe/CHESSIoTplugins_FMEAFTA).

We will show you the steps to follows in order to successfully install the extension:

     Prerequisite: 
     - Jdk/Java 8 not 11
     - Git client (optional)
     - Window OS

- Download CHESS1.0.0 for Window OS from this [link](https://download.eclipse.org/chess/core/releases/1.0.0/CHESS-1.0.0-win32.win32.x86_64.zip) and extract it.

- Clone this repository by issuing the next command
   
``git clone https://github.com/fihirwe/CHESSIoT-features.git``
 
 or you can simply download the source code as a [.zip file](https://github.com/fihirwe/CHESSIoT-features/archive/refs/heads/master.zip).
 
- Launch **CHESS.exe** executable file for the tool

Through eclipse, updates install the CHESSIoT extension by going 
 -  _Help-> InstallNew Software--> Add--> Local -->_ Browse local then you pick all the extracted content and finish.  

![](https://github.com/fihirwe/Readme-resources/blob/main/Install%20CHESSIoT/browse.PNG)

- Click next to continue
Make sure to uncheck the **_`` Group items by category ``_** option and select **_``CHESS with IoT extension``_** features

![](https://github.com/fihirwe/Readme-resources/blob/main/Install%20CHESSIoT/Select%20CHESSIoT.PNG)

- Click next for CHESSIoT updates

![](https://github.com/fihirwe/Readme-resources/blob/main/Install%20CHESSIoT/update.PNG)

- Accepts the license 

![](https://github.com/fihirwe/Readme-resources/blob/main/Install%20CHESSIoT/accept.PNG)

This will take a few seconds to load all the dependencies.
- Agree to install unsigned contents
 
![](https://github.com/fihirwe/Readme-resources/blob/main/Install%20CHESSIoT/last.PNG)

- You will need to restart your CHESS environment after this process.

- If everything goes well, you are ready to explore CHESSIoT
