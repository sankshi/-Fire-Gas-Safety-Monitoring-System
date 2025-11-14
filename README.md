🔥 Fire & Gas Safety Monitoring System

National Level Winner – SAEINDIA Southern Section (13 Sept 2025)

An embedded safety system designed to detect fire and gas leaks using STM32 and ESP32, with real-time alerts via GSM, IoT, and an OLED display. The project includes a custom double-layer PCB, complete firmware development, and seamless hardware–software integration.


🚀 Features
	•	🔥 Fire Detection using three IR flame sensors
	•	🏭 Gas Leakage Detection using MQ-2 sensor
	•	📡 Real-Time Alerts via GSM (SMS notifications)
	•	🌐 IoT Monitoring using ESP32 (Wi-Fi)
	•	📟 OLED Display for status updates
	•	🔧 Servo-controlled valve cutoff during gas leak
	•	🚨 Buzzer alarm for emergencies
	•	💧 Automatic pump activation using relay during fire
	•	🧩 Custom double-layer PCB built using EasyEDA
	•	⚡ Fast processing using STM32F411 Black Pill

⸻

🛠️ Hardware Used
	•	STM32F411CEU6 Black Pill (Main controller)
	•	ESP32 DevKit (IoT communication)
	•	SIM7600 GSM Module (SMS alerts)
	•	MQ-2 Gas Sensor
	•	IR Flame Sensors (×3)
	•	OLED Display (I2C)
	•	Servo Motor
	•	Relay + Water Pump
	•	Buzzer
	•	Custom 2-layer PCB

⸻

📐 Key Contributions
	•	Designed and implemented a complete embedded fire & gas safety system.
	•	Developed circuit design, double-layer PCB, and firmware programming for STM32–ESP32 control.
	•	Integrated GSM (SIM7600) and IoT (ESP32) modules for real-time alerts and remote monitoring.
  
🖥️ System Architecture
Flame Sensors → STM32 → Pump Control (Relay)
Gas Sensor   → STM32 → Servo Valve + Buzzer
STM32 ↔ ESP32 (UART) → IoT Dashboard
STM32 ↔ GSM (UART)  → SMS Alerts
OLED (I2C) → Real-time Display

🧪 Working
	1.	Sensors continuously monitor fire and gas.
	2.	STM32 makes decisions and activates the buzzer, servo, relay, etc.
	3.	ESP32 sends real-time sensor data to the cloud.
	4.	GSM module sends SMS alerts during emergencies.
	5.	OLED displays live system status.
