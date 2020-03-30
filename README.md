# QR-code-Scanning
QR code scanning on raspberry pi (3B+/4) using pyzbar
This project is inspired by the post of adrian Rosebrock.
This project aims to detect and decode qr-codes from live video feed on raspberry pi (3B+/4).
 If you have raspbian buster installed then you are good to go.Additionally install opnecv by `sudo pip3 install opencv` (you can also refer to [this](https://github.com/vikaskumareinstein/facial-recognition/blob/master/Prerequisites.txt) and [this](https://github.com/vikaskumareinstein/facial-recognition/blob/master/Dependencies.txt) for dependencies and preparing your raspberry pi.
 
 Install libzbar0 library by  `sudo apt-get install libzbar0` and then `sudo pip3 install pyzbar` followed by installing picamera 
 as `sudo pip3 install picamera`.All the dependencies are satisfied.Go to terminal and follow the steps below:
 
 clone this repository.Navigate to (`cd barcode-scanner`) bar `barcode-scanner` folder and then run `sudo python3 barcode_scanner_video.py`.
 
 The initial preparation and video link can be found [here](https://youtu.be/HPQk-gDUrmM) and [here](https://youtu.be/f_YiK0Hvgvc)
