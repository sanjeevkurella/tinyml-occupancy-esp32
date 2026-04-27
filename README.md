# TinyML-Based Occupancy Detection using ESP32-CAM

## Overview

This project implements a low-power occupancy detection system using ESP32-CAM with TinyML-based edge inference. The system detects human presence locally without relying on cloud processing, enabling faster response, reduced latency, and improved privacy.

## Features

* Real-time occupancy detection using ESP32-CAM
* On-device inference using TinyML
* Edge-based inference eliminating cloud dependency
* Low latency and low power consumption
* Trigger-based output (LED / signal) on occupancy detection

## Tech Stack

* ESP32-CAM
* Embedded C / Arduino
* TinyML
* Python (for model training)

## Working

1. Capture image using ESP32-CAM
2. Preprocess input image
3. Run TinyML model on-device
4. Detect occupancy (person present / not present)
5. Trigger output (LED / signal)

## Hardware Components

* ESP32-CAM
* Power supply
* LED / output indicator

## Demo
Setup
<img width="1052" height="564" alt="image" src="https://github.com/user-attachments/assets/472f679d-6915-44c4-9a25-ab40ce8793bb" />
Output
<img width="536" height="830" alt="image" src="https://github.com/user-attachments/assets/fd968525-6905-4c01-b3b1-eb97552b2d6e" />
<img width="828" height="720" alt="image" src="https://github.com/user-attachments/assets/66f3aef1-e651-4d8a-af5b-b1941945369d" />

## Contribution

This project was implemented individually. I handled:

* Development of embedded code on ESP32-CAM
* Integration of TinyML model for on-device inference
* Testing and validation of system performance

## Future Improvements

* Improve model accuracy
* Optimize inference speed
* Add multi-person detection

## Author

Sanjeev Kurella
