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

1. Clone the repository:

git clone https://github.com/MariusBretzel/Picam2Dashboard.git

2. Navigate to the project directory:

cd Picam2Dashboard

3. Install the dependencies:

pip3 install flask picamera2 numpy opencv-python psutil


## 🏃‍♂️ How to Run

1. Run the Python script:

python3 Picam2Dashboard.py

2. Open your web browser and navigate to `http://localhost:5000`.

## 📝 Note

This project has been tested on specific hardware and may not work perfectly with other setups.

## 🙏 Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [picamera2](https://github.com/iizukanao/picamera2)
- [OpenCV](https://opencv.org/)
- [psutil](https://psutil.readthedocs.io/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
