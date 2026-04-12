📌 Overview

This project demonstrates a PLC-based automated car wash system designed to perform a complete vehicle cleaning process through multiple stages. The system is built to simulate real industrial car wash operations with sequential and timed control.

⚙️ System Description

The system automates the full car washing process, starting from vehicle detection to the final drying stage.

Once a vehicle is detected and the system is activated, the process runs through several stages:

- Pre-rinse (water spray)
- Soap application
- Brushing process
- Final rinse
- Drying

Each stage is executed in sequence using timers and control logic to ensure proper cleaning and safe operation. The system operates automatically without manual intervention once started.

🔌 Inputs & Outputs

Inputs :
- Start Button
- Stop Button (Emergency)
- Sensor 1 - Car Detection
- Sensor 2 - Water Spray
- Sensor 3 - Soap Application
- Sensor 4 - Water Wash + Drying
- Sensor 5 - Finish

Outputs :
- Konveyor
- Indikator Lamp
- Water + Soap Spray
- Water Washing Spray
- Dryer

🖥️ Tools & Technologies
- PLC Programming (Ladder Diagram)
- Omron CX Programmer V9.7/ CX Designer
- Industrial Automation Design
