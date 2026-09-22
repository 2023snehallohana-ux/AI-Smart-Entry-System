````markdown
# BE Capstone Project

## Project Title

AI-Based Smart Entry Monitoring System using ID Card Detection and Face Recognition

https://youtu.be/wXiNR2xtQBA

---

## Team Details

| Sr. No. | Name of Student | Roll No. | Branch | Email ID |
|---|---|---|---|---|
| 1 |Snehal Lohana  | 17 | Automation and Robotics  | 2023.snehal.lohana@ves.ac.in |
| 2 |Eshika Makhija | 18 | Automation and Robotics  | 2023.eshika.makhija@ves.ac.in |
| 3 |Ayush Harwande | 03 | Automation and robotics  | 2022.ayush.harwande@ves.ac.in |
| 4 |Shiv Maurya  | 20   | Automation and Robotics  | 2022.shiv.maurya@ves.ac.in  |

---

## Guide Details

**Project Guide: Deepti Khimani**  
**Department:** Automation and Robotics  
**Institute:** VESIT, Mumbai  

---


## Problem Statement

Educational institutions often rely on security personnel to manually verify whether students are wearing their identity (ID) cards while entering the campus. This process is time-consuming, prone to human error, and cannot accurately detect if a student is using another person's ID card or if an unauthorized individual enters the premises. The absence of an automated monitoring system also makes it difficult to maintain digital entry records and analyze campus access patterns.

The aim of this project is to develop an AI-Based Smart Entry Monitoring System that uses computer vision and face recognition to detect students at the entrance, verify whether they are wearing their own ID cards, identify unauthorized entries, and automatically maintain entry records. The system will also generate weekly reports and analytics to improve campus security and administrative efficiency.

## Abstract

Educational institutions often rely on manual verification of student identity cards at campus entrances, which is time-consuming, prone to human error, and inefficient in maintaining accurate entry records. Security personnel may find it difficult to identify students who are not wearing their ID cards, are using another student's ID card, or are unauthorized visitors entering the campus.

This project proposes an **AI-Based Smart Entry Monitoring System using ID Card Detection and Face Recognition** to automate the campus entry verification process. A camera installed at the college entrance captures the image of every individual entering the premises. Using Computer Vision, Artificial Intelligence, and Face Recognition techniques, the system detects the presence of an ID card and verifies the student's identity by comparing the captured face with a registered student database. The system records every entry, identifies students without ID cards, detects identity mismatches and unauthorized visitors, and stores all records in a centralized database.

The stored data is further used to generate daily and weekly reports that provide insights into campus access patterns, the number of valid student entries, students without ID cards, and outsider entries. The proposed system aims to improve campus security, reduce manual effort, maintain accurate digital records, and provide an efficient and scalable smart entry monitoring solution for educational institutions.

## Objectives

The primary objectives of the proposed system are:

- To develop an AI-based smart entry monitoring system for educational institutions.
- To detect whether students are wearing their identity (ID) cards while entering the campus.
- To recognize and verify the identity of students using facial recognition technology.
- To identify unauthorized individuals and detect cases where a student is using another student's ID card.
- To maintain a secure digital database containing student entry records.
- To generate daily and weekly reports showing the number of student entries, outsider entries, students without ID cards, and identity mismatches.
- To reduce manual verification efforts and improve the overall security and efficiency of the campus entry system.

## Scope of the Project

The scope of this project is to develop an AI-Based Smart Entry Monitoring System for educational institutions that automates the student entry verification process. The system will use Computer Vision and Artificial Intelligence to detect students entering the campus, identify whether they are wearing an ID card, and verify their identity using facial recognition.

The system will automatically mark attendance for students whose identity has been successfully verified. It will also maintain a digital database containing student details, entry time, attendance records, and security logs. In cases where a student is not wearing an ID card, uses another student's ID card, or an unknown person attempts to enter the campus, the system will record the event and generate an alert for further verification.

Additionally, the system will generate daily and weekly reports showing attendance statistics, valid student entries, students without ID cards, identity mismatches, and outsider entries. Although the project is designed as a prototype for educational institutions, it can be extended in the future to support multiple campus entrances, cloud-based databases, mobile notifications, and integration with existing college management systems.

## Existing System

Currently, most educational institutions rely on security personnel to manually verify student identity cards at the college entrance. Security guards visually check whether students are wearing their ID cards before allowing them to enter the campus. In many cases, attendance is recorded separately through biometric systems, RFID cards, or manually in classrooms, making the entire process time-consuming and inefficient.

Since the verification process depends on human observation, it is difficult to identify students using another student's ID card or detect unauthorized individuals entering the campus. Manual verification also does not maintain centralized digital records of campus entry, making it difficult to monitor security incidents or analyze entry patterns.

### Limitations

- Manual verification is time-consuming, especially during peak college hours.
- Human errors may occur while checking student identities.
- No automated verification of whether the ID card belongs to the student.
- Attendance and entry records are maintained separately.
- Difficult to identify unauthorized visitors entering the campus.
- No centralized database for maintaining entry history and security records.
- Limited reporting and analytics for college administration.

---

## Proposed System

The proposed system is an AI-Based Smart Entry Monitoring System designed to automate student entry verification, attendance management, and campus security. A camera installed at the college entrance continuously monitors individuals entering the campus.

When a person approaches the entrance, the system first detects the presence of a human using computer vision techniques. It then checks whether an ID card is visible. If an ID card is detected, the student's face is captured and compared with the registered student database using facial recognition technology. The system also verifies whether the detected ID card belongs to the recognized student by matching the student information stored in the database.

If the student's identity is successfully verified, the system automatically records the student's entry and marks attendance. If the student is not wearing an ID card, is using another student's ID card, or is not found in the database, the system records the event as an exception and generates an alert for the security staff.

All entry records are securely stored in a centralized database. The system also generates daily and weekly reports that include student attendance, valid entries, students without ID cards, identity mismatches, outsider entries, and other security-related statistics. These reports help the college administration improve campus security and monitor student attendance efficiently.
---

## System Architecture

Add block diagram or system architecture image here.

```markdown
![System Architecture](images/system_architecture.png)
````

Briefly explain the architecture.

---

## Hardware Requirements

| Sr. No. | Component | Specification | Quantity | Purpose |
| ------- | --------- | ------------- | -------- | ------- |
| 1       |           |               |          |         |
| 2       |           |               |          |         |
| 3       |           |               |          |         |
| 4       |           |               |          |         |

---

## Software Requirements

| Sr. No. | Software / Tool | Version | Purpose |
| ------- | --------------- | ------- | ------- |
| 1       |                 |         |         |
| 2       |                 |         |         |
| 3       |                 |         |         |

---

## Technologies Used

Mention technologies used in the project.

Example:

* Embedded C / Python / JavaScript
* Arduino / STM32 / ESP32 / Raspberry Pi
* ROS / MATLAB / Simulink
* Machine Learning / Computer Vision
* IoT / Cloud / Mobile App
* PCB Design / CAD Design

---

## Methodology

Explain the step-by-step approach.

1. Literature survey
2. Problem identification
3. Requirement analysis
4. System design
5. Hardware/software development
6. Integration
7. Testing and validation
8. Documentation and publication

---

## Project Timeline

| Week / Month | Task Planned          | Status                            |
| ------------ | --------------------- | --------------------------------- |
| Week 1       | Problem finalization  | Pending / In Progress / Completed |
| Week 2       | Literature survey     |                                   |
| Week 3       | Requirement analysis  |                                   |
| Week 4       | System design         |                                   |
| Week 5       | Prototype development |                                   |
| Week 6       | Testing               |                                   |
| Week 7       | Documentation         |                                   |
| Week 8       | Paper writing         |                                   |

---

## Weekly Progress Updates

Students must update this section every week.

| Week   | Date | Work Completed | Work Planned for Next Week | Issues / Challenges | GitHub Commit Link |
| ------ | ---- | -------------- | -------------------------- | ------------------- | ------------------ |
| Week 1 |      |                |                            |                     |                    |
| Week 2 |      |                |                            |                     |                    |
| Week 3 |      |                |                            |                     |                    |
| Week 4 |      |                |                            |                     |                    |
| Week 5 |      |                |                            |                     |                    |
| Week 6 |      |                |                            |                     |                    |
| Week 7 |      |                |                            |                     |                    |
| Week 8 |      |                |                            |                     |                    |

---

## Design Files

Upload and link all design files here.

| File Type       | File Name / Link | Description |
| --------------- | ---------------- | ----------- |
| CAD Model       |                  |             |
| Circuit Diagram |                  |             |
| PCB Design      |                  |             |
| Flowchart       |                  |             |
| Simulation File |                  |             |

---

## Circuit Diagram

Add circuit diagram image here.

```markdown
![Circuit Diagram](images/circuit_diagram.png)
```

---

## Flowchart / Algorithm

Add flowchart image here.

```markdown
![Flowchart](images/flowchart.png)
```

### Algorithm

1. Start
2. Initialize the system
3. Read input from sensors/user
4. Process the data
5. Generate output/control action
6. Display/store/transmit result
7. Stop

---

## Implementation Details

Explain the actual implementation of the project.

### Hardware Implementation

Write details about connections, components, power supply, sensors, actuators, PCB, enclosure, etc.

### Software Implementation

Write details about code structure, libraries used, algorithms, communication protocols, database, app, cloud, etc.

---

## Code Structure

```text
BE-Capstone-Project/
│
├── README.md
├── docs/
│   ├── literature_survey.md
│   ├── project_report.pdf
│   └── presentation.pptx
│
├── hardware/
│   ├── circuit_diagram.png
│   ├── pcb_design/
│   └── cad_model/
│
├── software/
│   ├── src/
│   ├── include/
│   └── tests/
│
├── images/
│   ├── system_architecture.png
│   ├── prototype_photo.jpg
│   └── results.png
│
└── references/
    └── papers/
```

---

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/username/project-name.git
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

or mention specific software/library installation steps.

### Step 3: Upload / Run the Code

```bash
python main.py
```

or

```bash
arduino-cli upload -p COMx --fqbn board_name
```

### Step 4: Observe the Output

Mention the expected output of the project.

---

## Testing and Results

| Test No. | Test Description | Expected Result | Actual Result | Status      |
| -------- | ---------------- | --------------- | ------------- | ----------- |
| 1        |                  |                 |               | Pass / Fail |
| 2        |                  |                 |               | Pass / Fail |
| 3        |                  |                 |               | Pass / Fail |

---

## Result Images / Videos

Add images or videos of the working prototype.

```markdown
![Prototype](images/prototype_photo.jpg)
```

Video Link:

https://youtu.be/wXiNR2xtQBA

## Applications

Mention real-world applications of the project.

1.
2.
3.
4.

---

## Advantages

1.
2.
3.
4.

---

## Limitations

1.
2.
3.
4.

---

## Future Scope

Mention possible improvements.

1.
2.
3.
4.

---

## Research Paper / Publication

| Item                      | Details                                                   |
| ------------------------- | --------------------------------------------------------- |
| Paper Title               |                                                           |
| Conference / Journal Name |                                                           |
| Paper Status              | Not Started / Drafting / Submitted / Accepted / Published |
| Submission Date           |                                                           |
| Paper Link                |                                                           |

---

## References

Add references in IEEE format.

Example:

```text
[1] A. Author, B. Author, "Title of the Paper," Journal/Conference Name, vol. X, no. Y, pp. xx-yy, Year.
[2] Datasheet / Website / Book reference.
```

---

## Repository Update Guidelines

Each student team must update the GitHub repository regularly.

Minimum expected updates:

* Update README every week.
* Push code changes regularly.
* Upload circuit diagrams, CAD files, PCB files, reports and presentations.
* Add weekly progress in the progress table.
* Maintain proper folder structure.
* Do not upload unnecessary temporary files.
* Each major update should have a meaningful commit message.

Example commit messages:

```text
Added problem statement and objectives
Updated system architecture diagram
Added sensor interfacing code
Updated weekly progress for Week 3
Added testing results and prototype images
```

---

## Declaration

We declare that this project work is carried out by our team as part of the BE Capstone Project. The work will be regularly updated on GitHub and all references used will be properly cited.

---

## License

This project is for academic use only.

Optional:

```text
MIT License / Creative Commons / Institute Use Only
```

```
```
