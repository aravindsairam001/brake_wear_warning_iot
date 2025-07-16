Reaction Beam Caliper Brake Pad Wear Warning System Using IoT

Authors: Aravind Sairam S (211616115007)
Institution: Rajalakshmi Engineering College, Anna University, Chennai
Department: Mechatronics Engineering
Date: September 2020

⸻

🚗 Project Overview

This project introduces an IoT-based real-time brake pad wear monitoring system for reaction beam caliper brakes. The system detects brake pad wear and alerts the responsible person via SMS and a cloud dashboard, thereby preventing accidents due to worn-out pads.

The project integrates:
	•	Brake pad wear sensor
	•	Arduino Nano microcontroller
	•	GSM module
	•	ThingSpeak IoT platform

⸻

❗ Problem Statement
	•	Brake failure causes ~22% of road accidents globally.
	•	Dashboard indicators for pad wear are often ignored.
	•	Lack of preventive action leads to longer braking distances and higher risk.

⸻

🎯 Objectives
	•	Provide text message alerts on brake pad wear.
	•	Notify users via mobile, improving effectiveness over dashboard indicators.
	•	Enable centralized, cloud-based monitoring via IoT.

⸻

🔄 Existing vs Proposed System

Existing:
	•	Dashboard light indicator
	•	No remote access or persistent logging

Proposed:
	•	Text alerts sent to registered mobile numbers
	•	Real-time data upload to ThingSpeak for historical analysis
	•	Supports remote diagnosis and manufacturer-side failure analysis

⸻

🛠 Methodology

System Architecture
	•	Wear sensor detects pad thickness drop
	•	Arduino Nano processes sensor data
	•	GSM Module sends SMS and pushes data to ThingSpeak
	•	ThingSpeak Dashboard visualizes wear level over time

Flowchart and Algorithm
	1.	Sense brake pad thickness
	2.	Upload data to ThingSpeak
	3.	If critical level is reached:
	•	Confirm after rechecking
	•	Trigger SMS alert
	•	Upload to ThingSpeak

⸻

🧰 Hardware and Software

🔌 Hardware
	•	Brake Pad Wear Sensor: Conductive wire closes circuit when wear limit is breached
	•	Arduino Nano: Controls logic and communication
	•	GSM Module (SIM900A): For SMS and internet connectivity
	•	9V Battery: Portable power source

💻 Software
	•	Arduino IDE: Microcontroller programming
	•	ThingSpeak IoT Platform: Data collection, visualization, and analysis

⸻

🔍 Working Principle
	•	Brake pad wear sensor detects critical thickness
	•	Signal sent to Arduino Nano
	•	GSM sends alert to driver via SMS
	•	ThingSpeak server logs brake condition in real-time

⸻

🌐 ThingSpeak Data Monitoring
	•	Displays “Kilometer Left vs Time” graphs
	•	Alerts when critical thresholds are exceeded
	•	Helpful for predictive maintenance and failure analysis

⸻

✅ Advantages & ❌ Disadvantages

✅ Advantages
	•	Prevents accidents due to unnoticed brake wear
	•	Easily integrates with existing brake caliper systems
	•	Enables data analytics and server-side diagnostics
	•	Cost-effective and scalable

❌ Disadvantages
	•	Requires GSM network and internet
	•	Hardware must be protected from heat and vibrations

⸻

📊 Results & Conclusion

🔎 Results
	•	System detects brake pad wear accurately
	•	Sends SMS alerts in critical scenarios
	•	Successfully logs real-time data to ThingSpeak

✅ Conclusion

A low-cost, IoT-based safety upgrade to conventional braking systems that improves responsiveness, enhances safety, and enables digital diagnostics.

⸻

🚀 Future Scope
	•	Centralized brake monitoring for entire vehicle
	•	Integration with ABS and other braking components
	•	Common control unit for real-time dashboard & mobile alerts

⸻

📎 Appendix
	•	📄 Arduino Code (SMS + ThingSpeak integration)
	•	📊 MATLAB Script for Graph Plotting from ThingSpeak

⸻

📘 References
	1.	Brake Pad Wear Detection System – Willey & Williams, 1978
	2.	Pad Wear Indicator Probe – Ito & Takanashi, 1993
	3.	Brake Pad Wear Sensor – Gronowicz Jr., 2001
	4.	Brake Pad Monitoring System – Philpott, 2014

⸻

🎓 Programme Vision & Outcomes
	•	Promote innovation in Mechatronics for safety-critical systems
	•	Prepare graduates for real-world applications of IoT and automation

Developed as part of MT6811 Final Year Project under the guidance of Dr. M. Balakarthikeyan and Dr. V. Santhanam.
