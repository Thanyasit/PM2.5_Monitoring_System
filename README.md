# PM2.5 Monitoring System
<h2>Description</h2>
This project is an air quality monitoring system using multiple PM sensors including Sensirion SPS30, Honeywell HPMA115S0, Plantower PMS7003, and Nova PM sensor SDS011.<br><b>2020</b>
<h2>Prerequisites</h2>
Before using this program, make sure you have the following libraries installed:<br><br>

- PMS.h<br>
- SDS011-select-serial.h<br>
- sps30.h<br>
- hpma115S0.h<br>
<h2>Setup</h2>
1. Connect all sensors to the Arduino board.<br>
2. Install required libraries.<br>
3. Upload the code to the Arduino board.<br>
4. Open the serial monitor to view the data.<br>
<h2>Functionality</h2>
The code reads data from each sensor and outputs it to the serial monitor. The measurements include PM2.5 and PM10 concentration in µg/m³ from each sensor. The data is printed in CSV format and it includes the timestamp of each measurement.
<h2>Usage</h2>
This code can be used as a starting point for building an air quality monitoring system using different PM sensors. You can modify the code to add or remove sensors, change the sampling frequency, and output format.

## Example

<p align="center">
<img src="https://user-images.githubusercontent.com/77733903/226976608-c96fc652-7d15-4ccb-a988-d948dd44c778.JPG" width="500">
</p>

<h2>License</h2>

This program is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
