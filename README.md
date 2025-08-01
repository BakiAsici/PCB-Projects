<h2>ESP32-S3-WROOM-1 V1.1 — Custom PCB</h2>

<p>
  <strong>Updated from V1.0 with improved routing, GPIO reassignment, and antenna layout adjustments.</strong>
</p>

<p>
  A custom-designed ESP32-S3 board featuring onboard I²C sensors, GPIO breakout headers, and full custom routing.  
  Designed in KiCad 9, fabricated by JLCPCB, and hand-assembled using hot air, hotplate, and soldering iron.
</p>

<h3>Overview</h3>

<ul>
  <li>Revision: Rev 1.1</li>
  <li>Designed in: KiCad 9</li>
  <li>Fabricated by: JLCPCB</li>
  <li>Assembly: Hand soldered (Hotplate, Hot Air, Soldering Iron)</li>
</ul>

<h3>Features</h3>

<ul>
  <li>ESP32-S3-WROOM-1 Module</li>
  <li>I²C-connected STMicroelectronics LIS2MDL magnetometer and Bosch Sensortec BME280 environmental sensor (Temperature, Humidity, Pressure)</li>
  <li>Sensor libraries used to test functionality, with custom drivers in the works</li>
  <li>GPIO header breakout</li>
  <li>USB Programming and Monitoring</li>
  <li>WiFi and Bluetooth Capabilities</li>
</ul>

<h3>Noted Improvements from Rev 1.0</h3>
<ul>
  <li>Removed top mounting points to improve WiFi and Bluetooth performance, as recommended by the ESP32-S3-WROOM-1 datasheet</li>
  <li>Test LED (marked D1) was originally wired to a strapping pin (GPIO45), which caused unpredictable behaviour. It has now been rewired to a different GPIO</li>
  <li>Improved overall routing</li>
  <li>Followed ESP32-S3-WROOM-1 datasheet more closely regarding antenna clearance and placement</li>
  <li>Note: The current-limiting resistor for the power indicator LED was changed to 180 Ω. It is unclear if it will work reliably with the original 1 kΩ</li>
</ul>

<h3>Images</h3>
<div>
PCB 3D Renders
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/F.CURender.png" alt="Front Render" width="450"/> </div>
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/B.CURender.png" alt="Back Render" width="450"/></div>

PCB Photos
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/FrontRealV1.1.jpg" alt="Front" width="450"/> </div>
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/BackRealV1.1.jpg" alt="Back" width="450"/></div>

Layer Stackup
<div  align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/F.Cu.png" alt="Top Layer" width="450"/></div>
F.Cu (Front Copper)	
<div  align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/GND(In1.Cu).png" alt="GND plane" width="450"/></div>
In1.Cu (GND)	
<div  align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/3V3(In2.CU).png" alt="3V3 plane" width="450"/></div>
In2.Cu (3V3)	
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/B.Cu.png" alt="Bottom Layer" width="450"/></div>
B.Cu (Back Copper)














<h2>ESP32-S3-WROOM-1 V1.0 — Custom PCB</h2>

<p>
  A custom-designed ESP32-S3 board featuring onboard I²C sensors, GPIO breakout headers, and full custom routing.  
  Designed in KiCad 9, fabricated by JLCPCB, and hand-assembled using hot air, hotplate, and soldering iron.
</p>

<h3>Overview</h3>

  <ul>
  <li>Revision: Rev 1.0</li>
  <li>Designed in: KiCad 9</li>
  <li>Fabricated by: JLCPCB</li>
  <li>Assembly: Hand soldered (Hotplate, Hot Air, Soldering Iron)</li>
</ul>

<h3>Features</h3>

<ul>
  <li>ESP32-S3-WROOM-1 Module</li>
  <li>I²C-connected STMicroelectronics LIS2MDL magnetometer and Bosch Sensortec BME280 environmental sensor(Temperature, Humidity, Pressure)</li>
  <li>Sensor libraries used to test functionality with custom drivers in the works</li>
  <li>GPIO header breakout</li>
  <li>USB Programming and Monitoring</li>
  <li>Wifi and Bluetooth Capabilities</li>
</ul>

<h3>Noted Improvements for next revision</h3>
<ul>
  <li>Remove top mounting points to increase Wifi and Bluetooth performance, as recommemnded by the ESP32-S3-WROOM-1 datasheet</li>
  <li>Test led (Marked D1) was wired using a strapping pin GPIO45 and had to be left of the board to ensure predictable behaviour. Rewire led to a new GPIO</li>
  <li>Improve overall routing</li>
  <li>It should be noted that the current limiting resstor for the power indicator led was changed to 180ohms. I am unsure if it will work with the original 1Kohm</li>
</ul>

<h3>Images</h3>
<div >
PCB 3D Renders
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.0/F.Cu Render.png" alt="Front Render" width="450"/> </div>
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.1/B.Cu Render.png" alt="Back Render" width="450"/></div>

PCB Photos
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.0/FrontReal.jpg" alt="Front" width="450"/> </div>
<div align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.0/BackReal.jpg" alt="Back" width="450"/></div>

Layer Stackup
<div  align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.0/F.CU.png" alt="Top Layer" width="450"/></div>
F.Cu (Front Copper)	
<div  align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.0/In1.Cu(GND).png" alt="GND plane" width="450"/></div>
In1.Cu (GND)	
<div  align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.0/In2.Cu(3V3).png" alt="3V3 plane" width="450"/></div>
In2.Cu (3V3)	
<div  align="center"> <img src="assets/ESP32-S3-WROOM-1 V1.0/B.Cu.png" alt="Bottom Layer" width="450"/></div>
B.Cu (Back Copper)	







