# Multiwii-2.3-with-BMP180
This is multiwii 2.3 version with baro module bmp180

<h1>BMP180 for Multiwii 2.3 Firmware</h1>
<p>BMP180 is compatible (equivalent) of BMP085. BMP180 is optimized version of BMP085. We don't need to config to use BMP180. Multiwii will recognize BMP180 as BMP085.</p>
<p>In this project, I have already included BMP180 in multiwii 2.3 for LADYBIRD which only supports for brushed ESC and Brushed DC Motor, e.g. 720, 820, 8520, etc.</p>

<h2>WIRING</h2>
<p>As in <a href="https://github.com/ArduJimmy/Multiwii-2.3-with-BMP280" target="_blank">BMP280</a>, BMP180 has 4 pins: VCC (3.3v), GND, SCL, SDA. Connect all pins like you do with MPU6050 (use only 3.3v for both VCCs.</p>

See Video Demo at <a href="https://www.youtube.com/@ardujimmy" target="_blank">Ardujimmy</a>: https://www.youtube.com/@ardujimmy

<p><img src="https://github.com/ArduJimmy/Multiwii-2.3-with-BMP180/blob/main/bmp180_multiwii_ladybird2.png"/></p>
<p><img src="https://github.com/ArduJimmy/Multiwii-2.3-with-BMP180/blob/main/bmp180_multiwii_ladybird1.png"/></p>

DEMO: https://www.youtube.com/watch?v=faujS0-xZDQ

But ATTENTION!
I prefer using BMP280 to BMP180 since BMP280 relatively more stable than BMP180
