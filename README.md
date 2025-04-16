# Hand Gesture Control System 👋🖥️

A Python-based application that enables computer control through hand gestures using deep learning, MediaPipe for hand tracking, and PyAutoGUI for system control.


## 🚀 Features

- **Real-time Hand Tracking**: Powered by MediaPipe's robust hand landmark detection
- **Intuitive Controls**:
  - 👆 Point to move cursor
  - ✊ Fist for left click
  - 🤚 Open palm for right click
  
- **Customizable**:
  - Adjustable sensitivity
  - Configurable gesture mappings
- **Cross-platform**: Works on Windows, macOS, and Linux

## 📦 Installation

### Prerequisites
- Python 3.7+
- Webcam
- Basic Python environment setup

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hand-gesture-control.git
   cd hand-gesture-control
pip install -r requirements.txt


# Control Sensitivity
MOVEMENT_SENSITIVITY = 2.5  # Higher = more cursor movement
SCROLL_SENSITIVITY = 10     # Scroll speed

# Gesture Thresholds
CLICK_THRESHOLD = 0.05      # Distance for click detection
SCROLL_THRESHOLD = 0.1      # Scroll activation threshold

# document
# 🤝 Contributing
We welcome contributions! Please follow these steps:

1. Fork the project

2. Create your feature branch (git checkout -b feature/YourFeature)

3. Commit your changes (git commit -m 'Add some feature')

4. Push to the branch (git push origin feature/YourFeature)

5. Open a Pull Request

# 📜 License
Distributed under the MIT License. See LICENSE for more information.
