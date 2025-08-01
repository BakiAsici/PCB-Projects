<h2>ESP32-S3-WROOM-1 V1.1 — Custom PCB</h2>

<p>
  <strong>This is the updated Rev 1.1 of the board, improving on the original V1.0 with better routing, GPIO reassignment, and improved antenna layout.</strong>
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

<h3>Images – V1.1</h3>
<div>
PCB 3D Renders  
<div align="center"> <img src="" alt="Front Render" width="450"/> </div>  
<div align="center"> <img src="" alt="Back Render" width="450"/></div>

PCB Photos  
<div align="center"> <img src="" alt="Front Real" width="450"/> </div>  
<div align="center"> <img src="" alt="Back Real" width="450"/></div>

Layer Stackup  
<div align="center"> <img src="" alt="Top Layer" width="450"/></div>  
F.Cu (Front Copper)  
<div align="center"> <img src="" alt="GND plane" width="450"/></div>  
In1.Cu (GND)  
<div align="center"> <img src="" alt="3V3 plane" width="450"/></div>  
In2.Cu (3V3)  
<div align="center"> <img src="" alt="Bottom Layer" width="450"/></div>  
B.Cu (Back Copper)
</div>

<hr/>

<h2>ESP32-S3-WROOM-1 V1.0 — Initial Release</h2>

<p>
  This was the original version of the board. It successfully demonstrated core functionality, but several improvements were identified after testing and review.
</p>

<h3>Overview</h3>

<ul>
  <li>Revision: Rev 1.0</li>
  <li>Designed in: KiCad 9</li>
  <li>Fabricated by: JLCPCB</li>
  <li>Assembly: Hand soldered (Hotplate, Hot Air, Soldering Iron)</li>
</ul>

<h3>Known Issues in V1.0</h3>
<ul>
  <li>Top mounting holes interfered with the ESP32’s antenna performance</li>
  <li>Test LED (D1) was wired to strapping pin GPIO45, leading to boot issues. It had to be left off the board</li>
  <li>Power indicator LED resistor was originally 1 kΩ — brightness was too low</li>
  <li>Routing was functional but not optimal</li>
</ul>

<h3>Images – V1.0</h3>
<div>
PCB 3D Renders  
<div align="center"> <img src="" alt="Front Render V1.0" width="450"/> </div>  
<div align="center"> <img src="" alt="Back Render V1.0" width="450"/></div>

PCB Photos  
<div align="center"> <img src="" alt="Front Real V1.0" width="450"/> </div>  
<div align="center"> <img src="" alt="Back Real V1.0" width="450"/></div>

Layer Stackup  
<div align="center"> <img src="" alt="Top Layer V1.0" width="450"/></div>  
F.Cu (Front Copper)  
<div align="center"> <img src="" alt="GND plane V1.0" width="450"/></div>  
In1.Cu (GND)  
<div align="center"> <img src="" alt="3V3 plane V1.0" width="450"/></div>  
In2.Cu (3V3)  
<div align="center"> <img src="" alt="Bottom Layer V1.0" width="450"/></div>  
B.Cu (Back Copper)
</div>
