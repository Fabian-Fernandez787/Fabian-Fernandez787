# Hi there, I'm Fabián!

Computer Engineering student at **Universidad de Puerto Rico, Recinto de Mayagüez**, with an interest in embedded systems and Internet of Things (IoT) applications.

---

### 🛠️ Tech Stack & Specialties

- **Languages:** C, C++, Python, Java, Assembly (AVR / x86)
- **Embedded & Hardware:** ATmega328P, Bare-Metal Drivers, UART, ADC, Hardware Timers, Digital Logic
- **Tools & Environment:** `avr-gcc`, `avrdude`, `make`, Git, Windows/PowerShell
- **GUI & Analytics:** PyQt6, PyQtGraph, NumPy, Raylib

---

### 🚀 Featured Projects

#### 🔬 [Bare-Metal ATmega328P Digital Oscilloscope](https://github.com/Fabian-Fernandez787/atmega328p-digital-oscilloscope)
*A high-performance digital oscilloscope built with zero external libraries using raw register manipulation.*
- **Firmware:** Developed custom C drivers for UART (115.2k Baud), 10-bit ADC sampling, and Timer1 CTC hardware auto-triggering at 1 kHz.
- **Protocol:** Implemented a 2-byte binary streaming protocol (`b1` sync header + `b2` payload) to eliminate framing errors.
- **Host GUI:** Built a 60 FPS real-time desktop visualizer in Python using `PyQt6` and `PyQtGraph` with background thread serial parsing.
