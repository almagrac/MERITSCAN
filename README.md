# MERITSCAN
Thesis Documentation

Youtube Video: https://www.youtube.com/watch?v=gXvaNycMqc0  
- this video was the older version of the implementation of meritscan during the testing phase  <img src="https://media.infosec.exchange/infosec.exchange/custom_emojis/images/000/170/743/original/6327e5e7ae427cbe.gif" alt="Description" width="50" height="50">


### [ARDUINO ESP32](https://github.com/almagrac/MERITSCAN/tree/main/CameraWebServer)
``` txt
Board: AI Thinker ESP32-CAM
Port: /dev/ttyUSB0
Upload Speed: 115200
Partition Scheme: Huge APP

or

GPIO0 → GND
5V → 5V
GND → GND
FTDI TX → ESP32-CAM U0R
FTDI RX → ESP32-CAM U0T

Disconnect GPIO0 from GND
Press RST again
Open Serial Monitor at 115200 baud

"#define CAMERA_MODEL_AI_THINKER"

SETTINGS ESP32-CAM WEBPAGE
Resolution: QVGA (320x240) or CIF
Quality: 12–20
XCLK MHz: 10
```
