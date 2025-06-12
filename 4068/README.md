# Learning Plan

## Table of Contents

- [PD Sample QnA LO3.md](PD%20Sample%20QnA%20LO3.md):  
  Example Q&A for students, with multiple questions and model answers covering different perspectives and programming approaches.
- [PD Test Questions.md](PD%20Test%20Questions.md):  
  Tutor-only file with grouped test questions for each P/M/D assessment criterion (choose 1 from each group for full coverage).
- [README.md](README.md):  
  Learning plan, weekly breakdown, and detailed learning outcomes for the module.

---

## About the Files

### PD Sample QnA LO3.md

This file is for students. It contains a variety of sample questions and multiple model answers for each, demonstrating how to approach and defend different perspectives and programming solutions.  
**How to use:**  
- Review the questions and answers to understand different ways to respond.
- Use as a study and revision resource to prepare for assessments.
- Practice defending your answers using the examples provided.

### PD Test Questions.md

This file is for tutors only. It contains grouped test questions for each Pass (P), Merit (M), and Distinction (D) assessment criterion.  
**How to use:**  
- Tutors should select one question from each group to ensure full coverage of all assessment criteria.
- Not intended for student distribution.

---

## How to View These Files

Markdown files are best viewed in a Markdown-compatible viewer or editor, as simple text viewers may not render formatting, tables, or images correctly.

- **Windows:**  
  Use [Visual Studio Code](https://code.visualstudio.com/), [Typora](https://typora.io/), or open directly on [GitHub](https://github.com/) for proper formatting.
- **iOS:**  
  Use apps like [iA Writer](https://ia.net/writer), [Pretext](https://pretext.app/), or the GitHub app.
- **Android:**  
  Use [Markor](https://gsantner.net/project/markor.html), [JotterPad](https://2appstudio.com/jotterpad/), or the GitHub app.

If you open these files in a basic text editor (like Notepad), formatting such as headings, bullet points, and tables will not display as intended.

---

## Open Document Formats Policy

All teaching materials (such as presentations and documents) are shared in **Open Document formats** (e.g., `.odt`, `.odp`).  
**Do not save or push files in Microsoft proprietary formats** (such as `.docx` or `.pptx`) to this repository—this is highly discouraged.

- Microsoft Office programs (Word, PowerPoint, etc.) will show a warning and recommend converting Open Document files to their closed formats.  
  **Always ignore this warning and continue working in the Open Document format.**
- Microsoft Office does not allow saving Open Document files directly to OneDrive.  
  Save your work locally and upload to the repository as needed.
- To disable the conversion warning in Microsoft Office:  
  Go to `File` → `Options` → `Save` → Uncheck "Prompt to convert on open" or similar option.

**Summary:**  
- Only use and share `.odt`, `.ods`, `.odp`, etc.  
- Ignore Microsoft Office prompts to convert files.  
- Do not upload `.docx` or `.pptx` files to the repository.

---

### Learning Outcomes
- **LO2:** Safety standards, hazard/risk assessment, cell safety features
- **LO3:** Robot programming (MATLAB/Simulink), interfacing, hardware implementation

---

## Week 1: Introduction to Safety in Robotics

**Instructor:** Akbar Q  
**Unit:** HND Mechatronics 4068  
**Learning Outcome:** LO2

### Key Topics
- Why safety is critical in industrial robotics
- Risks: collisions, malfunctions, human error
- Legal and ethical responsibilities for ensuring safety

### Activities
- **Video Activity:** Identify safety hazards in a provided video
- **Group Task:** List out the issues and propose solutions (Issue 1 – Solution 1, etc.)
- **Discussion:** What does a good robot workplace look like? (Guard rails, closed-off areas, walled-off control panels, intrusion detection systems, emergency stops, integration of safety systems, physical protection)

### Cell Safety Features & Safeguards
- **Emergency Stops:** Proximity sensors, immediate termination of motion
- **Guarding:** Physical barriers, lateral guards, floating platforms
- **Barriers:** AUTO (Around, Under, Through, Over), customizable and modular
- **Interlocks:** Mechanical systems to prevent movement into restricted areas
- **Advanced Safety Devices:**  
  - Light curtains  
  - Laser scanners  
  - Floor mats (vibration/noise protection)

### Comparison: Barriers vs. Guards
- **Barriers:** Continuous, permanent protection, physically block access
- **Guards:** Temporary, can be activated/deactivated, help stop external forces

### How They Work Together
- Barriers and guards can be combined for layered safety

### Operational Modes and User Interfaces
- Manual, automatic, maintenance modes
- Teach pendants, HMIs, safety controls

### Assignments/Exercises
- Identify good safety practices from images/videos
- List and discuss good practices

---

## Week 2: Hazards and Risks in Mechatronic Systems

**Focus:** Identifying, Assessing, and Mitigating Risks

### Key Concepts
- **What is a hazard?**  
  An event, situation, or object with potential to cause harm or damage
- **What is a risk?**  
  The likelihood and impact of a hazard causing harm

#### Types of Hazards & Risks
- Physical (injury, accidents)
- Financial (loss, theft)
- Reputation (brand/image damage)

#### Examples
- High-speed driving on wet road (high likelihood, low impact)
- Chemical spill in factory (low likelihood, high impact)

#### Hazard Identification Techniques
1. Workshop inspections
2. Checklists
3. Brainstorming sessions
4. Historical data analysis

#### Mitigation Strategies
- Proactive cycle: Identify → Assess → Mitigate → Monitor
- Techniques: Elimination, substitution, engineering controls, admin controls, PPE

#### Activities
- Identify 5 hazards and associated risks from scenarios/images

---

## Week 3: Case Studies on Risk & Hazard Assessment

**Case Studies:**
- Changing a light bulb
- Deep frying
- Hydraulic servicing
- Watering plants
- Office work

**Task:**  
For each, identify hazards, assess risks, and propose mitigation.

---

## Week 4: Programming & Interfacing Basics

**Instructor:** Akbar Q  
**Focus:** MATLAB & Simulink Programming, Arduino, ESP32

### Key Topics
- **MATLAB/Simulink:** Used for diagramming and simulation
- **Arduino/ESP32:** Microcontroller basics, digital/analog I/O, PWM, H-Bridge motor driving
- **Xtensa 32 Bit LX6:** Microprocessor basics

#### Interfacing
- What is interfacing? Connecting devices via digital/analog signals
- Types of signals: Digital input/output, analog input, PWM output

#### Practical Tasks
- Calculate LED resistor values
- Read analog input (potentiometer, light sensor)
- Simulate analog output (PWM for motors/LEDs)
- H-Bridge motor driver simulation

---

## Week 5: PLC Programming Basics

**Instructor:** Akbar Q  
**Focus:** PLC Ladder Logic

### Components
- Power rails, switches (inputs), coils (outputs), variables, function blocks

### Exercises
1. **AND Gate:** Safety door & start button
2. **OR Gate:** Two emergency stop buttons
3. **NOT Gate:** Warning light when no material detected
4. **On/Off Latch:** Motor start/stop with memory
5. **Blinky:** Warning beacon for fault condition

---

## Weeks 6–9: MATLAB/Simulink & Hardware Implementation

- Focus on programming, simulation, and hardware control of a 5-DOF ESP32 robotic arm
- Integration of sensors, actuators, and safety features
- Real-world application and troubleshooting

---

## Week 10: Review & Final Project

- Consolidation of learning outcomes (LO2, LO3)
- Final project: Design, simulate, and present a safe, functional robotic system using MATLAB/Simulink and ESP32 hardware

---

## Notes

- **LO2:** Safety standards, hazard/risk assessment, cell safety features
- **LO3:** Robot programming (MATLAB/Simulink), interfacing, hardware implementation
- **Tutor for LO2 & LO3:** Akbar Q

---

*This plan reflects the actual teaching sequence and content delivered, including all practical and theoretical components. For any clarifications, contact Akbar Q.*