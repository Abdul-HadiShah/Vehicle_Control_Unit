# 🚗 Vehicle Control Unit (VCU) for Formula Student Car

Welcome to my repository of the **Vehicle Control Unit (VCU)** designed specially for a **Formula Student** (FS) car! The VCU was designed and fabricated from scratch using a **Raspberry Pi Pico** microcontroller and it was made sure that it was **FS 2025 Hybrid category rules** compliant.

This VCU was used in our university's Formula Student car, which competed in **FS UK 2024 at Silverstone**. The VCU controls major aspects of the vehicle, such as the hybrid powertrain system, safety features, as well as datalogging for assesments and future improvements. 

### 🏁 Overview
The VCU serves as the brain of our car, acquiring data from various sensors, controlling the hybrid system, and ensuring a smooth overall operation of the vehicle. This system was designed with reliability, and safety in mind, meanwhile fulfilling other requirements of the **FS 2025 Hybrid** category.

### 🛠️ Key Features:
- Built on the**Raspberry Pi Pico** 🖥️
- **Custom-designed PCB** 🖲️
- Fully developed **software** (Firmware) for vehicle control and hybrid system management 💻
- Compliancy with **FS 2024 Hybrid category rules** ⚡
- Implemented as the core control unit in our **Formula Student car** 🏎️
- Successfully deployed at **FS UK 2024** in **Silverstone** 🇬🇧

### 🚗 Vehicle Control Capabilities:
- **Hybrid System Management** 🔋: Manages both electric and combustion power sources.
- **Safety Features** 🚨: Monitors essential systems to ensure driver safety and vehicle stability.
- **Data Logging & Diagnostics** 📊: Captures real-time data for performance analysis and troubleshooting.
- **Communication Interface** 🌐: Interacts with other subsystems via I2C or other communication protocols.
- **Torque Vectoring & Traction Control** 🏎️: Adjusts the distribution of power to individual wheels to enhance handling and stability, improving vehicle performance in various driving conditions.
  
### ⚙️ Design & Development:
- **Hardware**: 
  - Designed custom **PCB** for the Raspberry Pi Pico.
  - Components chosen for robustness and performance.
  - Designed to comply with **Formula Student Hybrid** rules.
  
- **Software**:
  - Developed in **C/C++**.
  - Focused on **real-time performance** and **fault-tolerant operation**.
  - Features real-time sensor data processing, control algorithms, and vehicle diagnostics.

### 📸 FS UK 2024 at Silverstone:
Our **Formula Student car** equipped with this VCU successfully participated in the **FS UK 2024** competition at **Silverstone** 🏎️. This was a proud moment for our university's **FS Team** 🏆. The VCU ensured smooth operation during the event and played a critical role in vehicle performance.

---

## 🚀 Requirements:
- **Raspberry Pi Pico** 🌐
- **Custom PCB** (Designed and manufactured specifically for the VCU)
- **External Sensors**: GPS, temperature, accelerometer, etc. (connected via GPIO or CAN bus)
- **Power supply**: Appropriate for your car's hybrid system ⚡
- **Software Development Tools**: 
  - **Thonny IDE** for programming the Raspberry Pi Pico (or your preferred editor).
  - **C/C++ toolchain** for compiling the firmware.

### Setup Instructions:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/vcu-repository.git
Install the required dependencies (if any) to your Raspberry Pi Pico environment.

Flash the firmware onto the Raspberry Pi Pico using Thonny IDE or OpenOCD.

Connect the VCU PCB to the appropriate subsystems (hybrid powertrain, sensors, etc.).

Test the system and ensure proper communication with other vehicle components.

📝 Contributing:  
I welcome contributions to improve and expand the VCU system! If you have ideas for new features or improvements, feel free to fork this repo and submit pull requests.

📝 Guidelines:  
Please ensure that code changes are well-documented.
Ensure compliance with FS 2025 Hybrid category rules.
Include testing for new features and modifications.  

💬 Contact:  
For any inquiries or suggestions, please feel free to reach out to me via GitHub Issues or via email at abdulhadipak122@gmail.com.

🎓 Acknowledgements:  
Special thanks to my university's Formula Student Team for their support throughout the development and during the FS UK competition 🏅.
Thanks to the Raspberry Pi and PCB manufacturing communities for providing tools and resources for such innovative projects! 🙌
📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

⚡ Demo Video & Photos


🔧 Happy coding and good luck with your VCU project! 🔧

### Key Sections in the README:
1. **Project Overview** - General description of the VCU and its purpose in your FS car.
2. **Key Features** - A bullet-point list highlighting major functionalities.
3. **Design & Development** - Hardware and software information.
4. **FS UK 2024 Section** - Mention of the competition and a significant achievement.
5. **Requirements** - Hardware and software components requierd for designing this VCU.
6. **Contributing** - How others can contribute to the project.
7. **Contact Info** - Where to reach out for questions or collaboration.
8. **Acknowledgements** - Recognizing those who helped.
9. **License** - License type.

---

