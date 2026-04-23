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

## ⚠️ Important Notes

* ❌ Remove unrelated or inappropriate files (e.g., `sexy pics.*`)
* ❌ Avoid committing `.git` inside another repo (nested repo issue)
* ✅ Clean project before presenting to employers

---



## HMI Graphical UI Design (Screenshots)


<img width="1011" height="781" alt="image" src="https://github.com/user-attachments/assets/994920c0-b0fe-482e-9d83-80e7fc063791" />

<img width="1011" height="787" alt="image" src="https://github.com/user-attachments/assets/ed2719fd-6b7e-4fd4-bb51-0ac80a1cde48" />


<img width="1013" height="773" alt="image" src="https://github.com/user-attachments/assets/b8a614de-03b7-4906-af17-cb8337ddbd42" />



<img width="1007" height="777" alt="image" src="https://github.com/user-attachments/assets/8a10b89f-d87a-44cc-b9e6-dcec804e2ab5" />


<img width="1017" height="781" alt="image" src="https://github.com/user-attachments/assets/a31c926d-547a-4626-831a-b653cae257a9" />




<img width="1011" height="783" alt="image" src="https://github.com/user-attachments/assets/98e742ef-6fc1-43fe-aef7-cdbf270f9e7a" />

## Function Blocks
 
### Task 1 : 
* System behavior
<img width="3509" height="4961" alt="1_page-0001" src="https://github.com/user-attachments/assets/155b4018-716f-4869-985b-7daf937870d3" />
<img width="3509" height="4961" alt="1_page-0002" src="https://github.com/user-attachments/assets/19b18672-a652-4649-b2e2-df47902b3872" />
---

## 👨‍💻 Author

**Nico Guarnes**

* PLC / Industrial Automation Enthusiast
* Backend Developer (MERN Stack)
* Systems Builder

---

## 📄 License

MIT License

---

