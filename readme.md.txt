## RF Signal Interference Detection

### Introduction

This project focuses on identifying RF signals that may interfere with one another, addressing the increasing RF congestion in the modern technology era. Specifically, it aims to detect and suppress interference between WiFi and Bluetooth signals.

### Solution

The project utilizes MATLAB and Adalm Pluto to generate and transmit WiFi and Bluetooth signals in real-time, subsequently identifying their presence through a trained machine learning (ML) model. The process involves:

1. **Signal Generation and Transmission**: MATLAB and Adalm Pluto are employed to generate and transmit WiFi and Bluetooth signals. Data is collected at various distances between the transmitter and receiver, with different transmission and reception gains to ensure a diverse dataset.

2. **Data Collection**: Datasets are collected separately for WiFi and Bluetooth signals, including instances where interference is intentionally induced.

3. **Machine Learning Model Development**: A dedicated ML model is developed to classify data into three classes: WiFi, Bluetooth, and both WiFi and Bluetooth signals, based on the received baseband spectrum.

4. **Real-time Testing**: The developed ML model is tested in real-time using Adalm Pluto hardware to sense the presence of WiFi/Bluetooth signals.

### Hardware Setup
Maximum of 3 Adalm Pluto Hardware is used to transmit Wifi and Bluetooth signals simultaneously 
and then receive using a different hardware.
### Description of Files

This GitHub repository contains sub-folders with different MATLAB codes:

- **Transmitter**: MATLAB codes and functions for generating and transmitting WiFi and Bluetooth signals in real-time using Adalm Pluto. Sample spectrogram images of transmitted signals are included.

- **Receiver**: A MATLAB code depicting the receiver structure for capturing RF signals present in the environment. Data collection is facilitated using the codes in the Transmitter and Receiver folders.

- **Training**: MATLAB code for training the ML model using the collected dataset. The trained ML model file is also provided.

- **Testing**: MATLAB program for real-time testing of the developed algorithm using Adalm Pluto.

Feel free to explore the respective folders for detailed implementations and functionalities.

### Contributors

- Aswin Sankesh G S
- Balavadhana B
- Ganeshkumar V
- Velmurugan PGS


