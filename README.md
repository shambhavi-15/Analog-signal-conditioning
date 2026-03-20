# Analog-signal-conditioning
Designed an analog signal conditioning system to accurately detect respiration rate using simple hardware.
#  Respiration Rate Detection System (Analog)

## Overview
This project presents the design of an analog signal conditioning system to accurately detect human respiration rate using simple and cost-effective hardware components.

The system processes weak physiological signals and converts them into a measurable output using analog filtering and amplification techniques.

---

## Components Used
- NE555 Timer IC  
- LM358 Op-Amp  
- Thermistor  
- Resistors  
- Capacitors  
- Potentiometers  
- Comparator Circuit  

---

## Working Principle
The system detects respiration by sensing temperature variations caused by inhalation and exhalation using a thermistor.

- The thermistor converts temperature changes into electrical signals  
- These signals are weak and noisy, so they are passed through an **active low-pass filter** to remove high-frequency noise  
- The LM358 op-amp is used for signal amplification and conditioning  
- A comparator is used to convert the analog signal into a digital-like output  
- The NE555 timer helps in generating pulses corresponding to respiration cycles  

The final output can be used to estimate the respiration rate.

---

## Key Concepts Used
- Analog Signal Conditioning  
- Active Low Pass Filter  
- Signal Amplification  
- Comparator Circuits  
- Biomedical Signal Processing (Basic)  

---

## Circuit & Output
(Add your circuit diagram and experimental/simulation results here)

---

## Applications
- Basic health monitoring systems  
- Respiratory rate measurement  
- Low-cost biomedical devices  
- Educational and lab experiments  

---

## Future Improvements
- Integration with microcontroller for digital display  
- Wireless monitoring system  
- Improved sensor accuracy  
- Data logging and analysis  

---

## Author
Shambhavi Srivastava  

---

## Note
This project was implemented as part of an project laboratory, with focus on practical understanding of analog signal conditioning and circuit design.
