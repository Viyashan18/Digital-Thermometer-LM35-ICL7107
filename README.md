# 🌡️ Digital Thermometer Using LM35 and ICL7107

A digital thermometer project designed using the LM35 temperature sensor and ICL7107 ADC to measure and display temperature on dual 7-segment displays without using a microcontroller.

---

# 📌 Project Overview

This project implements a temperature measurement system capable of displaying temperatures from 0°C to 99°C.

The LM35 sensor generates an analog voltage proportional to temperature, while the ICL7107 converts the analog signal into a digital output for the 7-segment display.

The system was designed, simulated, and tested as part of an analog electronics project.

---

# 🎯 Objectives

- 🌡️ Measure temperature from 0°C to 99°C
- 📟 Display temperature using 7-segment displays
- 🔌 Use LM35 as the temperature sensor
- ⚡ Perform analog-to-digital conversion using ICL7107
- 🛠️ Design and test the complete hardware system

---

# ⚙️ Main Components Used

- 🌡️ LM35 Temperature Sensor
- 🔢 ICL7107 ADC and Display Driver
- 📟 Dual 7-Segment Displays
- 🎚️ Potentiometer
- 🔋 DC Power Supply
- 🔌 Resistors and Capacitors

---

# 🧠 Working Principle

- The LM35 outputs 10 mV per °C
- The ICL7107 converts the analog voltage into digital values
- The temperature is directly displayed on the 7-segment displays

### Example:

- 250 mV → 25°C
- 500 mV → 50°C
- Maximum range → 99°C

---

# ⚡ Project Development Stages

## 🔹 Proteus Simulation

- Simulated the complete circuit
- Verified temperature readings
- Tested voltage scaling and display output

---

## 🔹 PCB Design

- Designed PCB using EasyEDA
- Improved grounding and layout design
- Generated Gerber files for PCB fabrication

---

## 🔹 Hardware Prototype

- Built the circuit on a breadboard
- Tested real hardware behavior
- Observed display issues during practical testing

---

# 📊 Results

✅ Successful Proteus simulation  
✅ PCB design completed  
✅ Accurate temperature scaling achieved  
⚠️ Breadboard prototype showed unstable display behavior  

---

# ⚠️ Hardware Issue Observed

During hardware testing, the display continuously showed “66” regardless of the input temperature.

### Possible Reasons:

- Improper grounding
- Noise in analog section
- Incorrect reference voltage
- Oscillator instability
- Breadboard connection issues

---

# 📈 Key Learnings

- Practical hardware behaves differently from simulation
- Analog circuits are sensitive to noise and grounding
- PCB design improves circuit stability
- Importance of proper ADC reference voltage configuration
- Real-world debugging skills in analog electronics

---

# 🚀 Applications

- 🌡️ Temperature Monitoring Systems
- 🏭 Industrial Instrumentation
- 🔬 Electronics Laboratory Experiments
- 📟 Digital Measurement Systems

---

# 👨‍💻 Author

**Viyashan.K**  

---

# 📌 Conclusion

This project demonstrates the design and implementation of a digital thermometer using analog electronic components. It highlights analog-to-digital conversion, PCB design, hardware testing, and real-world debugging challenges.
