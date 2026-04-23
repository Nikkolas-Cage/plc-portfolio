---

# ⚙️ PLC & HMI Automation Project (TIA Portal)

A **Siemens TIA Portal-based industrial automation project** demonstrating PLC programming, HMI integration, and real-time control system design.

This project simulates a complete automation workflow including **PLC logic execution, HMI interaction, and system monitoring**, reflecting real-world industrial applications.

---

## 📌 Project Overview

This repository contains a fully configured **TIA Portal project** with:

* PLC program logic
* HMI (Human Machine Interface) configuration
* Runtime simulation files
* System-level configuration data

The project demonstrates how PLCs interact with HMI systems to control and visualize industrial processes.

---

## 🧠 Key Features

* 🔄 **Real-time PLC control logic**
* 🖥️ **HMI interface for monitoring & control**
* 📡 **Data exchange between PLC and HMI**
* ⚙️ **Structured automation workflow**
* 🧪 **Simulation-ready environment**

---

## 🛠️ Technologies Used

* **Siemens TIA Portal**
* **PLC Programming (Ladder Logic / FBD / STL)**
* **WinCC HMI (Integrated)**
* Industrial automation concepts

---

## 📂 Project Structure

```bash
PLC Project/
│
├── IM/                     # Main project configuration (TIA Portal core)
│   ├── HMI/               # HMI runtime and interface files
│   │   ├── Generates/
│   │   ├── qcontrols/
│   │   └── SimWork/
│   │
│   ├── SPL/               # PLC logic configuration
│   ├── System/            # System-level runtime data
│   ├── UserFiles/         # User-defined files (if any)
│   ├── Vci/               # Version control data
│   └── XRef/              # Cross-reference database
│
├── AdditionalFiles/       # Archive and supporting project data
│   └── PLCM/
│
├── Logs/                  # System logs
├── TMP/                   # Temporary files
└── .git/                  # Version control (should not be uploaded ideally)
```

---

## 🖥️ HMI System

The project includes a configured **WinCC HMI interface**:

* Interactive controls (buttons, indicators)
* Real-time process visualization
* PLC variable binding
* Simulation runtime support

HMI files are located in:

```bash
IM/HMI/S/0/Generates/
```

---

## ⚙️ PLC Logic

The PLC program (inside `SPL/`) contains:

* Control logic for automation process
* Input/output handling
* Sequential execution logic
* Possibly timers, counters, and conditions

---

## 🚀 How to Run

### Requirements:

* Siemens **TIA Portal (same or compatible version)**

### Steps:

1. Open **TIA Portal**
2. Import/Open the project folder
3. Load the project
4. Start:

   * PLC simulation (PLCSIM) OR
   * Connect to real PLC hardware
5. Launch HMI Runtime (if configured)
6. Monitor and test the system

---

## 📊 Learning Outcomes

This project demonstrates:

* Integration of PLC and HMI systems
* Real-time industrial control design
* Automation logic structuring
* Simulation-based testing

---

## HMI Graphical UI Design (Screenshots)

### 📺 **Root Screen: **
<img width="1011" height="781" alt="image" src="https://github.com/user-attachments/assets/994920c0-b0fe-482e-9d83-80e7fc063791" />

### ⚙ **PRACTICAL 1 : MOTOR CONTROL **
<img width="1011" height="787" alt="image" src="https://github.com/user-attachments/assets/ed2719fd-6b7e-4fd4-bb51-0ac80a1cde48" />

### ⚙ **PRACTICAL 2 : SEQUENTIAL MOTOR CONTROL **
<img width="1013" height="773" alt="image" src="https://github.com/user-attachments/assets/b8a614de-03b7-4906-af17-cb8337ddbd42" />

### 🛢 **PRACTICAL 3 : SINGLE TANK CONTROL LEVEL **
<img width="1007" height="777" alt="image" src="https://github.com/user-attachments/assets/8a10b89f-d87a-44cc-b9e6-dcec804e2ab5" />

### 🛢 **PRACTICAL 4: CONTROL MIXING IN A TANK**
<img width="1017" height="781" alt="image" src="https://github.com/user-attachments/assets/a31c926d-547a-4626-831a-b653cae257a9" />

### 🚦 **PRACTICAL 5: TRAFFIC LIGHTS**
<img width="1011" height="783" alt="image" src="https://github.com/user-attachments/assets/98e742ef-6fc1-43fe-aef7-cdbf270f9e7a" />

## Function Blocks Documentations
### 🏭 **PRACTICAL 1 : MOTOR CONTROL**

> This project demonstrates the application of the TON (On-Delay Timer) instruction in a PLC-controlled system. The implementation includes configurable preset times and supports both count-up and countdown timer operations, with real-time visualization and interaction through an HMI interface.

* Implements **ON-delay timer (TON)**
* Supports:

  * Start/Stop push buttons
  * Adjustable preset time
  * Count-up and countdown visualization via HMI
* Demonstrates basic PLC timing control

---

<img width="3509" height="2481" alt="plc_automation_guarnes_Task1_page-0001" src="https://github.com/user-attachments/assets/5f577b1d-b043-45dd-a01a-5570a4629a15" />
<img width="3509" height="2481" alt="plc_automation_guarnes_Task1_page-0002" src="https://github.com/user-attachments/assets/790bfe80-c26b-4471-8e57-af233a67da30" />
<img width="3509" height="2481" alt="plc_automation_guarnes_Task1_page-0003" src="https://github.com/user-attachments/assets/44039c89-446d-48ed-8ee0-be3773fe9ca5" />
<img width="3509" height="2481" alt="plc_automation_guarnes_Task1_page-0004" src="https://github.com/user-attachments/assets/094d21d8-67f4-4786-80bc-ab5b5c9d6954" />

---
---

## ⚙️ **PRACTICAL 2 : SEQUENTIAL MOTOR CONTROL**

> This project demonstrates a timer-based sequential control system using multiple TON (On-Delay Timer) instructions. The system automates the step-by-step activation of outputs, simulating a staged industrial process with real-time monitoring through an HMI interface.

* Implements **multiple TON timers for sequential logic**
* Supports:

  * Start/Stop push button control
  * Step-by-step output activation (g2, y2, r2)
  * Configurable timing per stage
  * Count-up and countdown visualization via HMI
* Demonstrates **sequential automation and process timing control**
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0001" src="https://github.com/user-attachments/assets/f1d2945a-1875-401b-9605-3959b4ce844c" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0002" src="https://github.com/user-attachments/assets/d7a80bc2-49fd-40c6-847d-11b427ac3b92" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0003" src="https://github.com/user-attachments/assets/4a972e05-ddd1-413b-8d44-aeb2891f4904" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0004" src="https://github.com/user-attachments/assets/89288c7e-58a9-4a4c-bf80-dd26639ff301" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0005" src="https://github.com/user-attachments/assets/2e12ba98-c11c-4585-9a66-cab80ce19e16" />

---


## 🛢️ **PRACTICAL 3 : SINGLE TANK LEVEL CONTROL**

> This project demonstrates a basic process control system for maintaining liquid levels in a tank using sensor inputs and actuator control. The system integrates PLC logic with HMI for real-time monitoring and manual interaction.

* Implements **level-based control logic**
* Supports:

  * Start/Stop push buttons
  * Low-level sensor detection
  * Inlet valve control
  * Memory-based state retention
* Demonstrates **closed-loop style control and industrial tank automation**
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0006" src="https://github.com/user-attachments/assets/7bf72387-d002-4b1c-aeb4-f28a997cb7fd" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0007" src="https://github.com/user-attachments/assets/ba65296e-7758-4074-af60-3484a0d990ec" />

---

## 🛢️ **PRACTICAL 4 : CONTROL MIXING IN A TANK**

> This project demonstrates analog signal processing and control logic for a mixing tank system. It utilizes scaling functions and conditional logic to control outputs based on sensor values, simulating real-world process automation.

* Implements **analog input processing (NORM_X and SCALE_X)**
* Supports:

  * Conversion of raw analog signals to usable values
  * Threshold-based control logic
  * Timer-assisted output control
  * Start/Stop operation via HMI
* Demonstrates **analog control systems and process automation**
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0008" src="https://github.com/user-attachments/assets/c3455b0d-0b40-4f9a-a7aa-5f82bf64e5a5" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0009" src="https://github.com/user-attachments/assets/aa2145cf-8ed1-44f6-acb6-5088ad6b3f77" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0010" src="https://github.com/user-attachments/assets/0810f992-7e2a-463e-8015-4f7f49a00af0" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0011" src="https://github.com/user-attachments/assets/459b44a1-3f6c-43bc-9894-187d9ae27b5f" />



---

## 🚦 **PRACTICAL 5 : TRAFFIC LIGHTS**

> This project demonstrates a fully automated traffic light control system using timer-based sequencing and interlocking logic. It ensures safe and coordinated operation between multiple traffic signals with real-time visualization via HMI.

* Implements **timer-based traffic sequencing**
* Supports:

  * Start/Stop push button control
  * Dual-lane traffic light coordination
  * Interlocking logic to prevent conflicting signals
  * Timed transitions (Green → Yellow → Red)
* Demonstrates **real-world traffic control logic and safety interlocks**


<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0012" src="https://github.com/user-attachments/assets/9f2b01dd-0f57-433c-8565-b4b516031629" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0013" src="https://github.com/user-attachments/assets/e461b6fe-62be-4c94-9b0c-d9e52df8566e" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0014" src="https://github.com/user-attachments/assets/f7fdcfb8-d61c-4003-9517-7dab7577e196" />
<img width="1755" height="1241" alt="plc_automation_guarnes_Task2_page-0015" src="https://github.com/user-attachments/assets/100aafa0-a43a-4af2-ace2-e47aa39d09d1" />



---


## 👨‍💻 Author

**Nico Guarnes**

---

## 📄 License

MIT License

---

