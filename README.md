# Digital Twin for Power Transformer Condition Monitoring and Performance Analysis

> An engineering project focused on creating a virtual representation (Digital Twin) of a power transformer for real-time condition monitoring, performance evaluation, and maintenance support.

---

## Project Overview

Power transformers are among the most critical assets in electrical power transmission and distribution systems. Their continuous and reliable operation is essential for maintaining a stable electricity supply.

This project aims to develop a Digital Twin of a power transformer that continuously monitors key operating parameters, estimates transformer health, evaluates performance, and assists engineers in maintenance planning.

Instead of relying only on periodic inspections, the Digital Twin provides a virtual representation of the transformer by combining sensor measurements with engineering calculations.

The project demonstrates concepts used in modern smart grids, Industry 4.0, Digital Transformation (DX), and predictive maintenance.

---

## Objectives

- Develop a virtual model of a power transformer.
- Monitor transformer operating conditions.
- Estimate transformer health.
- Analyze transformer electrical performance.
- Detect abnormal operating conditions.
- Improve maintenance planning.
- Visualize transformer status through an interactive dashboard.

---

## Problem Statement

Traditional transformer maintenance is generally based on scheduled inspections or after failures occur.

This approach can result in:

- Unexpected equipment failures
- High maintenance costs
- Reduced transformer lifetime
- Increased downtime
- Power interruptions

A Digital Twin enables continuous monitoring of transformer operating conditions, allowing engineers to detect abnormalities early and make informed maintenance decisions.

---

## Proposed Solution

The proposed system creates a virtual representation of a power transformer by collecting electrical and thermal parameters.

The Digital Twin continuously evaluates transformer performance using engineering calculations and displays the current operating condition through a monitoring dashboard.

The system also provides maintenance recommendations whenever abnormal conditions are detected.

---

## System Architecture

```

        +------------------------+
        |    Power Transformer   |
        +-----------+------------+
                    |
     -------------------------------
     |        |         |          |
 Voltage   Current   Temperature   Oil Temp
     |        |         |          |
     +--------+---------+----------+
                    |
            Data Acquisition
             (STM32 / Simulation)
                    |
          ---------------------
          |                   |
    Engineering Model     Data Logging
          |                   |
          +---------+---------+
                    |
           Digital Twin Engine
                    |
          -----------------------
          |                     |
   Performance Analysis    Health Assessment
          |                     |
          +----------+----------+
                     |
           Python Dashboard
                     |
             User / Engineer

```

---

## Working Principle

1. Measure transformer operating parameters.
2. Transfer sensor data to the Digital Twin.
3. Calculate transformer performance.
4. Estimate transformer operating condition.
5. Display health status.
6. Generate maintenance recommendations.

---

## Parameters Monitored

- Input Voltage
- Output Voltage
- Load Current
- Transformer Loading
- Winding Temperature
- Oil Temperature
- Ambient Temperature
- Power Loss
- Efficiency
- Transformer Health Index

---

## Engineering Calculations

The Digital Twin performs engineering calculations including:

### Copper Loss

Pcu = I²R

---

### Transformer Efficiency

η = Output Power / Input Power × 100

---

### Loading Percentage

Loading (%) = Actual Load / Rated Load × 100

---

### Voltage Regulation

Estimated using transformer equivalent circuit calculations.

---

### Temperature Rise

Estimated using thermal operating conditions.

---

## Health Assessment

Transformer health is classified into:

| Health Score | Condition |
|--------------|-----------|
| 90 - 100 | Excellent |
| 75 - 89 | Good |
| 60 - 74 | Warning |
| Below 60 | Maintenance Required |

---

## Alarm Conditions

### Overload

- Current exceeds rated value.

### Overheating

- Winding temperature exceeds safe operating limit.

### Voltage Abnormality

- Voltage outside allowable range.

### Efficiency Reduction

- Efficiency below expected value.

---

## Dashboard Features

- Live Transformer Status
- Voltage Monitoring
- Current Monitoring
- Temperature Monitoring
- Oil Temperature Monitoring
- Transformer Loading
- Transformer Health
- Alarm Notifications
- Maintenance Recommendation
- Historical Data Visualization

---

## Technologies Used

### Hardware

- STM32 Microcontroller (planned)
- Voltage Sensor
- Current Sensor
- Temperature Sensor

---

### Software

- Embedded C
- Python
- MATLAB / Simulink
- Microsoft Excel
- Git
- GitHub

---

## Project Structure

```

Digital-Twin-Transformer/

│

├── README.md

├── docs/

├── firmware/

├── dashboard/

├── simulations/

├── calculations/

├── images/

├── reports/

└── assets/

```

---

## Future Enhancements

- Partial Discharge Monitoring
- Oil Quality Monitoring
- Dissolved Gas Analysis
- Predictive Maintenance
- Cloud Monitoring
- Mobile Application
- AI-based Fault Diagnosis
- SCADA Integration
- IEC 61850 Communication
- Modbus Support

---

## Applications

- Electrical Utilities
- Smart Grid
- Power Transmission
- Distribution Networks
- Renewable Energy Plants
- Industrial Power Systems
- Substations
- Transformer Manufacturing
- Condition Based Maintenance

---

## Learning Outcomes

This project strengthens understanding of:

- Power Transformers
- Electrical Machines
- Electrical Design
- Power Systems
- Embedded Systems
- Industrial IoT
- Digital Twin Technology
- Condition Monitoring
- Engineering Calculations
- Technical Documentation

---

## Current Status

🚧 Project Status: Planning & Initial Development

The current repository focuses on system architecture, engineering concepts, and project planning. Hardware implementation, software modules, and validation will be developed in future phases.

---

## Roadmap

- [x] Project Planning
- [x] System Architecture
- [x] Engineering Study
- [ ] Transformer Simulation
- [ ] Embedded Data Acquisition
- [ ] Dashboard Development
- [ ] Performance Analysis Module
- [ ] Health Assessment Module
- [ ] Testing
- [ ] Documentation

---

## License

This project is released under the MIT License.

---

## Author

Rahul Sahu

Bachelor of Technology

Electrical and Electronics Engineering

Embedded Systems Enthusiast

Interested in Power Systems, Smart Grid, Industrial IoT, Digital Transformation, and Electrical Design Engineering.
