# SMARTGUARD: ESP32-Based Epilepsy Monitoring and Alert System

SMARTGUARD is an IoT-based healthcare monitoring system designed to assist in
the real-time monitoring of epileptic patients. The system collects
physiological and motion data, analyzes it locally, and transmits relevant
information to the cloud for visualization and alerting.

---

##  Problem Statement
Epileptic seizures often occur unpredictably, placing patients at serious risk
when immediate assistance is unavailable. Continuous monitoring systems can help
detect abnormal physiological patterns and trigger timely alerts to caregivers
or medical personnel.

---

##  System Overview
The system is built around an ESP32 microcontroller that interfaces with multiple
biomedical and motion sensors. Sensor data is processed locally and transmitted
over Wi-Fi to a cloud dashboard for real-time monitoring.

### Sensors Used
- ECG Sensor (AD8232)
- EMG Sensor
- Accelerometer (ADXL335)
- Temperature Sensor (DS18B20)

---

##  Data Processing & Intelligence
- Raw sensor signals are acquired using the ESP32’s 12-bit ADC
- A fuzzy logic–based decision system evaluates seizure likelihood
- Thresholds are tuned based on sensor voltage ranges and physiological limits
- Alerts are triggered when abnormal patterns are detected

---

##  IoT & Communication
- Microcontroller: ESP32 DevKit
- Connectivity: Wi-Fi
- IoT Platform: ThingsBoard
- Data Protocol: MQTT / HTTP
- Local alerts via buzzer
- Real-time cloud visualization via dashboard

---

##  Features
- Continuous physiological monitoring
- Motion-based seizure detection
- Fuzzy logic–based risk assessment
- Real-time IoT data visualization
- Local alert generation
- Scalable and cloud-integrated architecture

---

##  Results
The system successfully acquires and visualizes physiological data in real time.
Abnormal sensor patterns trigger alerts both locally and on the cloud dashboard,
demonstrating the feasibility of low-cost IoT-based seizure monitoring.

---

##  Future Improvements
- Machine learning–based seizure prediction
- GPS-based patient location tracking
- Mobile application integration
- Power optimization using deep sleep modes

---

##  Author
**Vallary Okumu**  
Electrical & Electronics Engineering Graduate  
IoT | Embedded Systems | Healthcare Technology

</footer>
