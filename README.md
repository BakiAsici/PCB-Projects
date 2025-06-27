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
  <li>I²C-connected STMicroelectronics LIS2MDL magnetometer and Bosch Sensortec BME280 environmental sensor(Temperature(°C), Humidity(%), Pressure(Hpa))</li>
  <li>Sensor libraries used to test functionality with custom drivers in the works</li>
  <li>GPIO header breakout</li>
  <li>USB Programming and Monitoring</li>
  <li>Wifi and Bluetooth Capabilities</li>
</ul>

<h3>Noted Improvements for next Rev</h3>
<ul>
  <li>Remove top mounting points to comply fully with the keepout area as recommended by the ESP32-S3-WROOM-1 datasheet</li>
  <li>Test led (Marked D1) was wired using a strapping pin GPIO45 and had to be left of the board to ensure predictable behaviour. Rewire led to a new GPIO</li>
</ul>

<div >
PCB 3D Renders
<div align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/F.Cu Render.png" alt="Front Render" width="450"/> </div>
<div align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/B.Cu Render.png" alt="Back Render" width="450"/></div>

PCB Photos
<div align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/FrontReal.jpg" alt="Front Render" width="450"/> </div>
<div align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/BackReal.jpg" alt="Back Render" width="450"/></div>

Layer Stackup
<div  align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/F.CU.png" alt="Top Layer" width="450"/></div>
F.Cu (Front Copper)	
<div  align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/In1.Cu(GND).png" alt="GND plane" width="450"/></div>
In1.Cu (GND)	
<div  align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/In2.Cu(3V3).png" alt="3V3 plane" width="450"/></div>
In2.Cu (3V3)	
<div  align="center"> <img src="assests/ESP32-S3-WROOM-1 V1.0/B.Cu.png" alt="Bottom Layer" width="450"/></div>
B.Cu (Back Copper)	





