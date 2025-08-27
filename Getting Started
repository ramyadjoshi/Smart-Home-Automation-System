# Smart Home Automation System

The Smart Home Automation System leverages YOLOv8 (You Only Look Once) object detection to monitor a room using a standard webcam and automate energy-saving recommendations. All detection and logic is done locally without IoT devices.

---

## About the Project

The **Smart Home Automation System** leverages YOLOv8 (You Only Look Once) object detection to monitor a room using a standard webcam and automate energy-saving recommendations. The system uses computer vision to detect if a person is present and can alert the user if energy is being wasted by active devices when no one is detected. This system does not require any IoT hardware—everything runs locally using standard Python libraries and a camera.

---

## Key Features

- **Live Person Detection:** Uses YOLOv8 to detect if a person is present in the camera feed.
- **Energy Waste Alerts:** Warns if lights, fans, or electronics remain on without anyone in the room.
- **User-Friendly GUI:** Simple Tkinter interface for control.
- **Emergency Shutdown:** One-click shutdown for safety and convenience.
- **No IoT Devices Needed:** Operates fully on a standard computer with a webcam.

---

## Installation

1. **Clone the Repository**
    ```
    git clone https://github.com/ramyadjoshi/Smart-Home-Automation-System.git
    cd Smart-Home-Automation-System
    ```

2. **Install Dependencies**
    Make sure Python 3.8+ is installed. Then, install the required Python packages:
    ```
    pip install ultralytics opencv-python
    ```
    *Tkinter* and *threading* are included with standard Python.

---

## Setup and Running the Application

1. **Download Pretrained YOLOv8 Nano Model**

   The application uses the `yolov8n.pt` model for efficient person detection. This will be automatically loaded by the ultralytics package.

2. **Start the Application**
    ```
    python your_main_file.py
    ```
    Replace `your_main_file.py` with the name of your main script.

3. **GUI Controls**
    - **Start Camera:** Begins real-time monitoring using your computer’s webcam.
    - **Stop Camera:** Ends the monitoring session.
    - **Emergency Stop:** Immediately shuts down the application.
    - Device status is simulated and viewable in the GUI.

---

## Usage

- On starting, the system will monitor the camera feed for people.
- If no person is detected for a configurable time (default: 180 seconds), and devices are ON, it shows an energy alert.
- The alert suggests turning off the remaining active devices (light, fan, electronics).

---

## Customization

- Adjust `self.devices` in the code to simulate which devices are ON or OFF at start.
- Modify `self.auto_shutdown` to change the auto-termination period (in seconds).
- Uncomment code in `check_energy_waste()` to automatically turn OFF devices after an alert.

---

## Contributions and Issues

- Fork the repository and submit pull requests for improvements.
- Raise issues for any questions or bug reports via the GitHub Issues tab.

---

**Note:** This project is intended for educational demonstration and not for direct deployment in smart homes. It simulates smart energy management by computer vision, all without hardware dependencies.

