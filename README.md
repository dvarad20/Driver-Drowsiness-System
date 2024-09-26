# Driver Drowsiness System
The drowsiness detection system is a cutting-edge solution leveraging Python, OpenCV, and Keras to enhance road
safety by detecting driver fatigue. Powered by a Convolutional Neural Network (CNN), trained on a dataset of open and
closed eyes. In operation, the system continuously monitors a live camera feed of the driver's face using OpenCV. By
analyzing facial features, particularly the eyes, it can detect signs of drowsiness in real-time. If the system detects
prolonged eye closure beyond a set threshold, it triggers an alarm to alert the driver, accompanied by a visual warning
prompt.
Technology Used: Python, OpenCV, NumPy, Keras

## Setup
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git

2. Navigate to the project directory:
```bash
cd your-repository

3. Create a virtual environment:
```bash
python -m venv env

4. Activate the virtual environment:
  On Windows:
  ```bash

  .\env\Scripts\activate

  On MacOS/Linux:
  ```bash
  
  source env/bin/activate

5. Install the required packages:
```bash

pip install opencv-python keras numpy pandas tensorflow playsound

6. Run the project:

```bash

python detect_drowsiness.py



## The Output 
1. Open Eyes<br />

![image](https://github.com/user-attachments/assets/43071b89-fa68-43aa-953e-309db0ab253e)

2. Close Eyes<br />
Here we detect wheater the eyes are closed and count the number of frames for which the eyes were closed (which is 10 frame) greater then that the Alarm will ring and the WARNING sign is displayed.

![image](https://github.com/user-attachments/assets/9038b06a-58bc-49a5-b354-8c24c059188c)
