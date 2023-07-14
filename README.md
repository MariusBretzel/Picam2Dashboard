# 📸 Picam2Dashboard 🖥️

Picam2Dashboard is a real-time camera dashboard for Raspberry Pi. It provides a live video feed from your Raspberry Pi camera, along with system and camera stats. The dashboard is built with Flask and uses the picamera2 library for camera control.

## 🚀 Features

- Live video feed
- Real-time system and camera stats
- Adjustable camera settings

## 📋 Tested On

- Raspberry Pi 4 Model B 8GB
- Raspberry Pi Camera Module 3

## 🛠️ Installation

Follow these steps to install Picam2Dashboard:

1. Clone the repository. Open a terminal and run the following command:
   ```bash
   git clone https://github.com/MariusBretzel/Picam2Dashboard.git
   
2. Navigate to the project directory:
   ```bash
   cd Picam2Dashboard

3. Install the dependencies:
   ```bash
   pip3 install flask picamera2 numpy opencv-python psutil

## 🏃‍♂️ How to Run

1. Run the Python script:
   ```bash
   python3 Picam2Dashboard.py

2. Access the dashboard:
   - If you are using the web browser on the same Raspberry Pi, navigate to http://localhost:5000.
   - If you are using a different computer on the same network, replace localhost with the local IP address of your Raspberry Pi. For example, if the local IP address of your         Raspberry Pi is 192.168.1.10, navigate to http://192.168.1.10:5000.

## 📝 Note

This project has been tested on specific hardware and may not work perfectly with other setups.

## 🙏 Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [picamera2](https://github.com/raspberrypi/picamera2/)
- [OpenCV](https://opencv.org/)
- [psutil](https://psutil.readthedocs.io/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
