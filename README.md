# Network Security Monitoring System

## Overview

The **Network Security Monitoring System** is a tool designed to monitor and analyze network traffic for potential security threats. It captures packets, analyzes them, and helps in identifying unusual patterns or malicious activities on the network. This project can be used for real-time traffic analysis, alerting, and forensic investigation.

## Features

- **Packet Capture**: Capture network packets in real-time.
- **Traffic Analysis**: Analyze captured packets for potential threats.
- **Alert System**: Configure alerts for suspicious network activities.
- **Customizable**: Easily modify settings and configurations for different network environments.
- **Support for Snort/Suricata**: Integrates with tools like Snort or Suricata for advanced intrusion detection.

## Installation

### Prerequisites

- **Python 3.x** or higher.
- **Scapy** library for packet capturing.
- Optional: **Snort** or **Suricata** for advanced analysis.

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/cHINWEdIANNA/Network-Security-Monitoring-System.git
   
2. Navigate to the project directory:
    cd Network-Security-Monitoring-System

3. Install the necessary Python dependecies
   pip install -r requirements.txt

### Usage
1. To start monitoring network traffic, run the packet capture script:
2. The script will capture packets and display them in real-time. You can customize the packet analysis and alerting in the traffic_capture.py file.
3. For more advanced detection, confgure Snort or Suricata with custom rules and integrate them into the system.

### Configuration
Configuration files are located in the config/ directory. You can adjust settings like:

**1. Snort/Suricata Configuration:** Adjust detection rules

**2. Alert Thresholds:** Set the thresholds for packet anomalies

### Conrtibuting
I welcome contribution to improve the system. Here's how you can contribute:
1. Fork the repository
2. Create a new branch (git checkout -b feature-branch).
3. Commit your chnages  (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a pull request with a descritption of your chnages.

### License 
This project is licensed under the MIT License 

### Acknowledgements
Thanks to Scapy for providing the network packet manipulation tools.
Special thanks to Snort and Suricata for offering advanced network monitoring and intrusion detection capabilities.
Thanks to GitHub for providing a platform for version control and collaboration.

### Contact
For any questions or feedback, please contact me at: iwujidiana@gmail.com.

