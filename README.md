# Overheat-Detections-and-Protection-system
Dual Stage analog overhead detection and protection system designed using operational amplifier in NI Multisim

## Concepts Used
- operational amplifier as a comparator
- thermister based temperature sensing
- Voltage divider network concepts
- Transistor switching operation
- Thermal threshold detection

## Features
- thermal alert indication
- Automatic load cutoff protection
- Dual threshold operation

## Software Used
- NI Multisim

## System Operation
- The system operates using a dual-threshold analog protection mechanism. 
- An NTC thermistor is used within a voltage divider network, where its resistance decreases with increasing temperature.
- The resulting voltage variation is applied to operational amplifier comparator stages to generate temperature-dependent switching responses.
- The first comparator stage is configured for a 60°C threshold condition, where a transistor switching stage is used to drive the buzzer alert operation during overheating indication.
- The second comparator stage is configured for a 90°C critical threshold condition, where another transistor switching stage performs automatic load cutoff operation for thermal protection.
- An indicator LED is incorporated after the cutoff stage to visually indicate that the system has entered the critical protection condition after load disconnection.
- The project demonstrates the implementation of analog comparator circuits, thermistor-based resistance variation, voltage divider network operation, transistor switching behavior, and multi-stage thermal protection using discrete electronic components in NI Multisim.

## Simulation Results
- The circuit was analyzed in NI Multisim under different thermal operating conditions to observe the behavior of the dual-stage protection mechanism.
### 1. Normal Operating Condition
- The system operates normally below the predefined thermal threshold conditions, with the load remaining active and no alert indication triggered.
### 2. Alert Threshold Condition – 60°C
- At 60°C, the first comparator stage activates the transistor switching circuit to drive the buzzer indication for overheating alert operation.
### 3. Critical Protection Condition – 90°C
- At 90°C, the second comparator stage activates the load cutoff protection mechanism through transistor switching operation. 
- An indicator LED is triggered after load disconnection to indicate the critical overheat condition.

## Applications
- Industrial thermal protection systems
- Analog temperature monitoring circuits
- Power electronics safety systems
- Hardware-based thermal shutdown mechanisms
- Semiconductor and electronic protection applications

## Repository Contents
- Complete circuit schematic
- Normal operating condition
- 60°C alert threshold condition
- 90°C critical load cutoff condition
- Simulation demonstration video

## Conclusion
This project demonstrates the implementation of a dual-stage analog overheat detection and protection system using operational amplifier comparator circuits and transistor switching concepts. The system performs thermal alert indication and automatic load cutoff operation based on predefined temperature threshold conditions using discrete analog electronic components in NI Multisim.
