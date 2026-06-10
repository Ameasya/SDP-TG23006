# SDP-TG23006
Senior Design Project: PS26251 - Development of a Smart Waste Monitoring System Using IoT and Deep Learning for Institutional Waste Management

Project description: This project aims to develop an IoT-based smart waste monitoring system integrated with deep learning for institutional waste management. The system measures waste bin fill level and weight using embedded sensors and transmits real-time data to a cloud platform for monitoring and analysis. A deep learning model will be developed to predict waste accumulation trends and optimize collection scheduling. The proposed system is designed to improve operational efficiency, reduce overflow issues, and support sustainable waste management practices within institutional environments.

Problem Statement
1. No real-time fill visibility: Current waste collection relies on fixed schedules or visual inspection. There is no mechanism to detect actual fill levels, resulting in unnecessary trips or missed overflowing bins.
2. No predictive capability: Without historical data or trend analysis, collection cannot be optimised. Bins may overflow between scheduled visits, especially during peak periods.
3. Odour and hygiene not monitored: Gas and odour levels from decomposing waste are not tracked, making it impossible to prioritise collection based on hygiene risk.

Project objectives:
1. To design and integrate dual-parameter sensing (fill level and weight) into an embedded IoT-based monitoring system.
2. To develop a cloud-based data acquisition and visualization platform for real-time monitoring and logging of waste bin status.
3. To implement and evaluate a deep learning model for predicting waste accumulation patterns to enhance collection efficiency.

Scopes
1. Hardware: Using ESP32 as microcontroller with HC-SR04 ultrasonic, HX711 load cell, and MQ-135 gas sensor.
2. Software: Using Flask API backend, MariaDB database, HTML/CSS/JS dashboard.
3. Connection: Uses MQTT over Wi-Fi, Node-RED as middleware. Local server (laptop) as cloud substitute for Raspberry Pi.
4. Deep Learning: Uses LSTM deep learning model for fill time prediction. Model is trained on a dummy dataset to serve as a proof of concept.
5. Bin Size: The system is designed specifically to be installed to a 90L sized trash bin.

Block diagram:
<img width="785" height="202" alt="SDP Block Diagram drawio" src="https://github.com/user-attachments/assets/1ef558bf-8c16-4158-a9aa-48a884fc54d8" />

Flowchart:
<img width="1773" height="1212" alt="SDP Flowchart Design 2-3 drawio" src="https://github.com/user-attachments/assets/11a36a99-52bb-43bb-bf62-f5aaa28fe0e1" />

Circuit:
<img width="1362" height="834" alt="image" src="https://github.com/user-attachments/assets/aee88cd4-72d6-4c3e-ad14-6b112b4e502f" />

Expected outcome:
By the end of Semester 1, a fully functional hardware prototype with stable IoT-based data logging capability, validated sensor measurement accuracy, and an operational threshold-based alert system is expected to be successfully developed and demonstrated.
