# MCAD
MCAD - Machine Learning-Based Cyberattack Detector for Healthcare SDNs

## Overview

Healthcare systems, particularly those operating within Software-Defined Networks (SDNs), face increasing cybersecurity threats due to the sensitive nature of patient data and critical infrastructure. MCAD (Machine Learning-based Cyberattack Detector) is an intelligent cybersecurity solution designed to detect and respond to a wide range of cyber threats in real-time. By leveraging machine learning, MCAD ensures adaptive, reliable, and scalable protection tailored to healthcare environments.
## Features

🔐 **Advanced Threat Detection**: Utilizes supervised and unsupervised machine learning algorithms to detect anomalies and attacks.
⚡ **Real-Time Response**: Capable of responding to threats immediately to minimize damage and downtime.
🔄 **Adaptive Security**: Continuously learns from new threats to stay effective in dynamic environments.
📊 **Performance Optimized**: Enhances overall network performance while maintaining high security.
🧠 **Broad Threat Coverage**: Detects a wide spectrum of cyber threats including DDoS, malware, and unauthorized access attempts.

## System Architecture
**Data Collection Module**: Gathers network traffic and system logs.
- **Feature Extraction**: Prepares data for analysis by identifying key indicators of compromise.
- **ML-Based Detection Engine**: Trained on labeled datasets to classify normal vs malicious behavior.
- **Response Module**: Initiates actions such as blocking IPs or isolating infected nodes.
- **Logging & Reporting**: Maintains detailed incident logs for audit and analysis.

## Technologies Used

- 🧠 **Machine Learning**: Scikit-learn, TensorFlow/PyTorch
- 🌐 **Network Monitoring**: Wireshark, Snort
- 🛡 **Security Frameworks**: OpenFlow (for SDN control), Bro/Zeek IDS
- 📊 **Visualization**: Grafana or Kibana for threat monitoring dashboards
- 💻 **Programming Languages**: Python, Bash, JavaScript (for interface)

## System Requirements

- **OS**: Linux (Ubuntu 20.04+ recommended)
- **Memory**: Minimum 8GB RAM
- **Processor**: Quad-core CPU (Intel i5 or better)
- **Disk Space**: At least 20GB of free space
- **Dependencies**: Python 3.8+, pip, virtualenv, Docker (optional)

