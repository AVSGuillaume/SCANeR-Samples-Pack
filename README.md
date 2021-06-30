﻿![](./doc/assets/Words.90381a63-92c0-4104-83fd-3bfd0a7e49fe.001.png) **SCANeR™studio 2021 Samples Pack– Manual ![](./doc/assets/Words.90381a63-92c0-4104-83fd-3bfd0a7e49fe.002.png)**

# Samples Pack Manual # 

This is the manual for Samples-Pack users.
For devs who want to contribute to the Samples-Pack, check the [Samples Pack Developper's Manual](./README_dev.md)

## 1. INSTALLATION ## 

### Pre-requisites ### 

1. Windows 10 
2. SCANeR™ Licence [(request a trial if needed)](https://www.avsimulation.com/free-download/) 

[//]: # "3. The latest version of[ SCANeR™ Studio 2021 ](http://support.avsimulation.fr/)"

### Installation ### 

1. Download the[ Samples Pack ](http://stockage.scanersimulation.com/Evaluation/2021/SCANeRstudio_SamplesPack.zip)
2. Extract in “.../AVSimulation/SCANeRstudio/2021/” 
3. Edit the configuration file “…/AVSimulation/configurations.cfg” and copy'n paste at the end of the file lines below : 
```
SAMPLE_2021_ADAS = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_ADAS
SAMPLE_2021_ADAS_LKA_ACC = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_ADAS_LKA_ACC
SAMPLE_2021_CAMERACAPTURE = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_CAMERACAPTURE
SAMPLE_2021_CARMAKER = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_CARMAKER
SAMPLE_2021_DATAEXCHANGE = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_DATAEXCHANGE
SAMPLE_2021_FMI = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_FMI
SAMPLE_2021_HEADLIGHTS = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_HEADLIGHTS
SAMPLE_2021_LATERAL_CTRL = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_LATERAL_CTRL
SAMPLE_2021_LONGI_CTRL = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_LONGI_CTRL
SAMPLE_2021_PIXEL_LIGHTING = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_PIXEL_LIGHTING
SAMPLE_2021_SCENARIO_IMPORTER = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_SCENARIO_IMPORTER
SAMPLE_2021_VEHICLE_PLAYER = ${STUDIO_PATH}/SCANeRstudio_2021/config/SAMPLE_VEHICLE_PLAYER
```

## 2. GET HELP ##
- Samples manuals are below ↓
- Read the[ Evaluation FAQ ](SCANeRstudio_Evaluation_FAQ.pdf)
- Contact the[ @Support team ](mailto:support-scaner@avsimulation.fr)

## 3. CONTENTS ##

|**Demo** |**Key words** |**Description** |
| - | - | - |
|[📜EVAL_ADAS ](SCANeRstudio_EVAL_Manual.pdf)|Sensors ScanerAPI C/C++ Simulink **Python** Co-Simulation Vehicle control |<p>Connect C/C++, Simulink and Python ADAS features to SCANeR™ Studio. </p><p>- Pedestrian anti-collision system </p>|
||||
|[📜EVAL_ADAS_LKA_ACC** ](SCANeRstudio_EVAL_ADAS_LKA_ACC_Manual.pdf)|<p>Sensors ScanerAPI C/C++ </p><p>Simulink Co-Simulation **Vehicle control** HMI </p>|<p>Connect C/C++ and Simulink ADAS algorithms to SCANeR™ Studio. </p><p>- Lane Keeping Assist </p><p>- Active Cruise Control </p>|
|[📜EVAL_LATERAL_CTRL ](SCANeRstudio_EVAL_Manual.pdf)|<p>Sensors ScanerAPI C/C++ </p><p>Vehicle control </p>|Connect a C/C++ algorithm to follow the curve of a race track. |
||||
|[📜EVAL_LONGI_CTRL ](SCANeRstudio_EVAL_Manual.pdf)|<p>Sensors ScanerAPI C/C++ </p><p>Python **Vehicle control** </p>|<p>Connect C/C++ and Python algorithms to control the vehicle according to various laws </p><p>- Speed control </p><p>- Acceleration control </p><p>- Pedal command </p>|
|[📜EVAL_DATA_EXCHANGE ](SCANeRstudio_EVAL_Manual.pdf)|**Real-Time** RT-Gateway |<p>Exchange simulation data with a Real-Time platform. </p><p>The demo makes use of the RT Gateway to exchange numerical values with a dummy C program.  </p>|
|EVAL/HEADLIGHTS <p>📜[` `*Demo manual* ](SCANeRstudio_EVAL_Manual.pdf)</p><p>📜[` `*Tutorial* ](SCANeRstudio_EVAL_HEADLIGHTS_Tutorial.pdf)</p>|Night Test Manager AFS |Use the Headlight and Adaptive Frontlight System (AFS) features of SCANeR™ to simulate glare-free headlamps.  |
|📜[EVAL_PIXEL_LIGHTING ](SCANeRstudio_EVAL_PIXEL_LIGHTING_Manual.pdf)|Night Test Manager Image Sharing Visual Plugin |Demonstrates dynamic modification of headlamps photometry in real time in order to simulate a pixel lighting feature. |
||||
|[📜EVAL_CAMERACAPTURE ](SCANeRstudio_EVAL_CAMERACAPTURE_Manual.pdf)|Scenario Sensors ScanerAPI **Image Sharing** C/C++ |Capture each frame of a camera sensor along with radar detection outputs in a CSV. |
|EVAL/SCENARIO/IMPORTER <p>📜[` `*Demo presentation* ](SCANeRstudio_EVAL_SCENARIO_IMPORTER_Presentation.pdf)</p><p> [🎞️ *Demo video* ](SCANeRstudio_EVAL_SCENARIO_IMPORTER_Demo.mp4)</p><p> 📄[` `*Feature documentation* ](http://stockage.scanersimulation.com/Install/SCANeRstudio/Doc/1.9/help/html/SIMULATION/SIMULATION/Simulation%20Mode%20Intro.html?highlight=scenarioimporter#scenarioimporter)</p> |Digitalization **From real-world** Experiment replication |After recording a real-world experiment, import and reproduce the scenario in SCANeR™ simulation environment. |
|[📜EVAL_VEHICLE_PLAYER** ](SCANeRstudio_EVAL_VEHICLE_PLAYER_Manual.pdf)|Vehicle Player **Replay data** |Vehicle Player replays a recorded vehicle trajectory. The sample shows how to convert a source data to use it in Vehicle Player. |
|EVAL/FMI <p>📜[` `*Demo presentation* ](SCANeRstudio_EVAL_FMI_Presentation.pdf)</p><p> [🎞️ *Demo video* ](SCANeRstudio_EVAL_FMI_Demo.mp4)</p><p> 📄[` `*Feature documentation* ](http://stockage.scanersimulation.com/Install/SCANeRstudio/Doc/1.9/help/html/SIMULATION/SIMULATION/FMI%20Handler.html?highlight=fmi#fmi-handler)</p> | FMI, FMU **Model exchange** Co-simulation | Connect an external FMU (Functional Mock-up Unit) to SCANeR™. The physical model of a bouncing ball is run and traced in SCANeR™.|
| EVAL/ROS <p>📜[` `*Tutorial* ](SCANeRstudio_EVAL_ROS_Tutorial.pdf)</p><p> 📁[` `*Tutorial sources* ](SCANeRstudio_EVAL_ROS_Sample.zip)</p> | ROS Linux | Co-simulation with ROS (Robot Operating System) on Linux |
| EVAL/CARMAKER 📜[` `*Tutorial* ](SCANeRstudio_EVAL_CARMAKER_Tutorial.pdf) | IPG CarMaker **Co-simulation** Vehicle Dynamics | Co-simulation with IPG CarMaker  |   

 

