# HT-GE1400C-TPO-CL-Camera-Sensor
![Photo 1](https://github.com/JpnTr/HT-GE1400C-TPO-CL-Camera-Sensor/blob/main/HT-GE1400C-TPO-CL-Camera-Sensor.JPG)
![Photo 2](https://github.com/JpnTr/HT-GE1400C-TPO-CL-Camera-Sensor/blob/main/HT-GE1400C-TPO-CL-Camera-Sensor-1.JPG)
This is How to install and use HT-GE1400C-TPO-CL Camera Sensor on Raspberry Pi 4
* HT-GE1400C-TPO-CL
* Raspberry Pi 4 GB
* 3 Megapixel 1/2" 

## How to install SDK and OpenCV on Raspberry Pi
You can follow these commands on your Raspberry
```bash
git clone https://github.com/JpnTr/HT-GE1400C-TPO-CL-Camera-Sensor/
chmod 777 install_depends.sh
./install_depends.sh
chmod 777 install_OpenCV.sh
./install_OpenCV.sh
```
and it's done! You installed OpenCV

Download SDK https://drive.google.com/file/d/1fwbCycCTRpAaK7uSOssO2eoGTsjSFsjV/view?usp=sharing and move in your repostory directory.
Follow commands on terminal
```bash
chmod 777 install_SDK.sh
./install_SDK.sh
```
I wanna try to get more FPS with Google Coral. If i do that, i will update this repo
![Example](https://github.com/JpnTr/HT-GE1400C-TPO-CL-Camera-Sensor/blob/main/test.gif)
