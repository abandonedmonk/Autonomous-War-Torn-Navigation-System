# Autonomous War-Torn Navigation System

![Banner Image](https://i.ibb.co/G2CGV1R/36e8d6e3-47dc-43a2-b742-08058755eca4.jpg)  

## Overview
The **Autonomous War-Torn Navigation System** is a project designed to enable unmanned vehicles to navigate and operate in war-torn and hazardous environments. Leveraging state-of-the-art machine learning, computer vision, and autonomous decision-making algorithms, this system is optimized to detect obstacles, avoid threats, and ensure safe navigation.

## Features
- **Obstacle Detection and Avoidance**: Real-time detection of obstacles using IR sensors and image processing.
- **Threat Identification**: Recognizes potential threats such as fire, combat, or unsafe terrains.
- **Path Optimization**: Uses algorithms to calculate the safest and most efficient path.
- **Remote Monitoring**: Provides live updates and data to a central command unit.
- **Scalable and Modular**: Easily adaptable to different terrains and scenarios.

## Tech Stack
- **Programming Languages**: Python, C++
- **Libraries/Frameworks**: 
  - OpenCV (Computer Vision)
  - PyTorch (Machine Learning)
- **Hardware**:
  - IR Sensors
  - Camera Module

## Installation
Follow these steps to set up the project on your local system:

1. Clone the repository:
   ```bash
   git clone https://github.com/abandonedmonk/Autonomous-War-Torn-Navigation-System.git
   cd Autonomous-War-Torn-Navigation-System
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the project:
   ```bash
   python main.py
   ```

## Usage
1. **Data Preparation**: Ensure all required input data (e.g., map files, threat markers) are in the appropriate directories.
2. **Switching ON the Bot**: Make sure that the bot is turned on.
3. **Run Navigation System**: Execute the main Python script to initialize the navigation system, then run the path optimization file.
4. **Monitor**: Use the GIS dashboard to monitor progress.

## System Architecture
```
+-----------------+      +------------------+      +-----------------+
|  Sensor Input   | ---> | Data Processing  | ---> | Decision Engine |
+-----------------+      +------------------+      +-----------------+
        |                        |                       |
        v                        v                       v
  Obstacle Data          Threat Analysis          Path Optimization
```


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries or support, feel free to reach out:
- **Author**: [Abandoned Monk](https://github.com/abandonedmonk)
- **Email**: anshujena007@gmail.com

## Acknowledgments
Special thanks to:
- Open-source contributors
- The robotics and AI community

---

https://github.com/abandonedmonk/Autonomous-War-Torn-Navigation-System/assets/66255580/ad918eb1-d96f-4bb1-bb1b-7043775c68ad

