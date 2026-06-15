# Hi there 👋, I'm K Sri Chandan Ashrith

I am an **Electrical and Electronics Engineering (EEE)** student at the **National Institute of Technology Calicut**, passionate about both hardware design and embedded programming. 🚀

- 🎓 Pursuing my B.Tech at **NIT Calicut**.
- ⚡ Strong foundation in **Electronic Circuits, Digital Systems, Signals & Systems, and Microcontrollers**.
- 🔭 Deeply interested in **Analog and Digital Electronics**.
- 💬 Ask me about: **Circuit simulation, Digital Electronics, and Embedded C**.

---

### 🛠️ Hardware & Software Skills
* **Microprocessors & Microcontrollers:** ESP32, PIC18F, 8085/8086, AVR (Arduino)
* **Analog & Digital Electronics:** Circuit Analysis, Op-Amps, Logic Gate Design, HDL
* **Simulation & Hardware Tools:** MATLAB, Simulink, LTSpice, Proteus
* **Programming Languages:** Embedded C, Verilog

---

### 🔌 Key Engineering Projects

#### 📡 [Low-Latency Wireless Morse Code Transceiver](https://github.com)
* **System Architecture:** Designed and prototyped a low-latency, peer-to-peer wireless telegraph system using two ESP32 microcontrollers communicating via the **ESP-NOW protocol**, bypassing traditional Wi-Fi overhead to minimize transmission delay.
* **Edge Processing & Logic:** Developed an edge-side input processing algorithm on the transmitter node to analyze push-button duration. Implemented non-blocking `millis()` tracking to differentiate dots ($<400\text{ ms}$) and dashes ($\ge400\text{ ms}$), dynamically packetizing sequences after 1 second of inactivity.
* **Data Parsing & Digital Signal Outputs:** Programmed a structured lookup-table algorithm on the receiver node to translate incoming raw string buffers into alphanumeric characters on the Serial Monitor, while concurrently driving a GPIO-controlled active buzzer using a calibrated 1:3 pulse-width ratio.
* **Hardware Optimization:** Engineered the circuit layout using internal `INPUT_PULLUP` resistors to eliminate mechanical switch floating and integrated current-limiting safety resistors to protect GPIO pins from inductive loads.

#### 🌡️ [PIC18F-Based Real-Time Temperature Monitoring System](https://github.com)
* **Description:** Designed and developed a hardware-to-software monitoring system that samples analog ambient temperature and handles automated data collection.
* **Hardware & Firmware:** Interfaced an analog LM35 sensor with a PIC18F452 microcontroller. Configured ADC sampling, processed analog voltage data, and established 9600-baud UART communication.

#### ⚡ [DC-DC Buck Converter](https://github.com)
* **Description:** Designed and simulated an efficient step-down voltage regulator circuit.
* **Focus:** Component selection (inductor, capacitor, MOSFET), power efficiency calculations, loop stability, and thermal management.
* **Tools Used:** LTSpice / MATLAB Simulink.

---


### 📫 Connect with Me
* **LinkedIn:** www.linkedin.com/in/srichandan195
* **Email:** srichandan195@gmail.com
