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

## Hardware Requirements

| Sr. No. | Component | Specification | Quantity | Purpose |
|---------|-----------|---------------|----------|---------|
| 1 | Laptop / Computer | Intel Core i5 or equivalent, 8GB RAM | 1 | To run Python programs and AI models |
| 2 | Webcam | HD Webcam, 720p or above | 1 | To capture live images and video |
| 3 | Student ID Card | College-issued identity card | As required | For ID card detection and verification |
| 4 | External/IP Camera | Network-enabled camera, 1080p | 1 | For final entrance monitoring setup |
---

## Software Requirements

## Software Requirements

## Software Requirements

| Sr. No. | Software / Tool | Version | Purpose |
|---------|-----------------|---------|---------|
| 1 | Python | 3.x | To develop and execute the AI-based application |
| 2 | OpenCV | 4.x | For image processing, face detection, and camera integration |
| 3 | face_recognition | Latest compatible version | For face encoding and face recognition using a pre-trained model |
| 4 | Visual Studio Code | Latest | For writing, editing, and managing Python code |
---

## Technologies Used

Mention technologies used in the project.

## Technologies Used

The following technologies are used in our AI-Based Smart Entry Monitoring System:

- **Python:** Core programming language for system development.
- **OpenCV:** Image processing, face detection, and webcam integration.
- **Dlib:** Facial feature extraction and face encoding.
- **Face Recognition:** Face matching using a pre-trained face-recognition model.
- **Pandas:** Managing student records and entry data.
- **NumPy:** Numerical operations and image data processing.
- **CSV:** Storing registered student information.
- **Visual Studio Code:** Development environment for writing and managing code.
- **Git & GitHub:** Version control and project documentation.
---

## Methodology

Explain the step-by-step approach.

## Methodology

Our project follows a systematic approach to develop an AI-Based Smart Entry Monitoring System using ID Card Detection and Face Recognition.

1. **Literature Survey**
   - Study existing face recognition, ID card detection, and smart entry monitoring systems.

2. **Problem Identification**
   - Identify challenges in manual entry monitoring, identity verification, and maintaining entry records.

3. **Requirement Analysis**
   - Define hardware, software, dataset, and functional requirements of the system.

4. **System Design**
   - Design the system workflow including camera input, ID detection, face recognition, verification, and entry logging.

5. **Software Development**
   - Set up Python, OpenCV, and face-recognition libraries.
   - Prepare the student dataset and generate facial encodings.

6. **Module Development**
   - Develop face detection, face recognition, and ID card detection modules.

7. **System Integration**
   - Integrate ID card detection with face recognition for student identity verification.

8. **Testing and Validation**
   - Test the system using registered and unknown individuals to evaluate detection and recognition performance.

9. **Database and Dashboard Development**
   - Implement automatic date/time entry logging and develop a monitoring dashboard.

10. **Documentation and Publication**
    - Maintain project documentation, record development progress, and prepare the final project report.
---

## Project Timeline

## Project Timeline

| Week / Month | Task Planned | Status |
|--------------|--------------|--------|
| Week 1 | Problem finalization | Completed |
| Week 2 | Literature survey | Completed |
| Week 3 | Requirement analysis | Completed |
| Week 4 | System design and workflow planning | Completed |
| Week 5 | Python, OpenCV, and VS Code setup | Completed |
| Week 6 | Student dataset preparation and CSV database creation | Completed |
| Week 7 | Face detection and face encoding generation | Completed |
| Week 8 | Live webcam face recognition | Completed |
| Week 9 | ID card detection module development | In Progress |
| Week 10 | Face + ID verification | Pending |
| Week 11 | Automatic date/time entry logging | Pending |
| Week 12 | Entry database and monitoring dashboard | Pending |
| Week 13 | External/IP camera integration | Pending |
| Week 14 | System integration and testing | Pending |
| Week 15 | Documentation and project report | Pending |
| Week 16 | Final presentation and project demonstration | Pending |
---

## Weekly Progress Updates

Students must update this section every week.

## Weekly Progress Updates

This section records the weekly progress, completed tasks, upcoming work, and challenges faced during project development.

| Week | Date | Work Completed | Work Planned for Next Week | Issues / Challenges | GitHub Commit Link |
|------|------|----------------|----------------------------|---------------------|--------------------|
| Week 1 | — | Finalized project title and discussed the problem statement. | Conduct literature survey on smart entry monitoring systems. | — | — |
| Week 2 | — | Studied existing face recognition and ID card detection systems. | Analyze project requirements and required technologies. | Identifying suitable detection approaches. | — |
| Week 3 | — | Analyzed hardware, software, and functional requirements. | Design the system workflow and architecture. | Defining the verification process. | — |
| Week 4 | — | Designed the proposed system pipeline and workflow. | Set up Python, VS Code, and OpenCV. | — | — |
| Week 5 | — | Completed Python, VS Code, and OpenCV setup. Tested webcam functionality. | Prepare the student dataset and create the student database. | — | — |
| Week 6 | — | Prepared 21 student images and created students.csv. | Implement face detection and generate facial encodings. | Limited dataset availability. | — |
| Week 7 | — | Successfully tested face detection and generated facial encodings using a pre-trained model. | Integrate the face-recognition model with the live webcam. | Ensuring proper face encoding and matching. | — |
| Week 8 | — | Loaded all 21 student images into the face database and completed live face recognition testing. | Develop the ID card detection module. | Dataset currently covers 21 out of 67 target students. | — |
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

## Algorithm

### AI-Based Smart Entry Monitoring System

1. **Start**
2. Initialize the camera, face-recognition model, and student database.
3. Capture live video frames from the camera.
4. Detect faces and ID cards in the captured frame.
5. Extract facial features and generate face encodings.
6. Compare the detected face with registered student face encodings.
7. Verify whether the detected ID card matches the recognized student.
8. If both face and ID are valid:
   - Mark the entry as valid.
   - Record the student's name, date, and exact entry time.
9. If the face or ID is invalid:
   - Mark the entry as invalid or identify the person as unknown.
   - Generate an alert if required.
10. Store entry records in the database.
11. Display entry details on the monitoring dashboard.
12. Repeat the process for the next person.
13. **Stop**

---

## Implementation Details

## Implementation Details

Our project is being developed using Python and computer vision libraries to create an AI-based smart entry monitoring system.

### 1. Development Environment Setup
- Installed and configured Python and Visual Studio Code.
- Installed OpenCV and required face-recognition libraries.
- Tested the webcam for live image and video capture.

### 2. Student Dataset Preparation
- Collected photographs of registered students.
- Prepared a dataset containing 21 student images out of the target 67 students.
- Created a `students.csv` file to store student identification details.

### 3. Face Detection and Recognition
- Implemented face detection using OpenCV.
- Integrated a pre-trained face-recognition model.
- Generated facial encodings for registered students.
- Loaded all 21 available student images into the face database.
- Implemented live face recognition through the webcam.
- Successfully tested face recognition using Snehal's face.

### 4. ID Card Detection
- Currently developing the ID card detection module.
- The module will be used to identify student ID cards from camera input.

### 5. Planned System Integration
The following modules are planned for further development:
- Face and ID card verification.
- Automatic entry date and exact time recording.
- Entry database management.
- Monitoring dashboard.
- External/IP camera integration.

### 6. Current Implementation Status
The face recognition module has been successfully implemented and tested using the live webcam. ID card detection and the remaining system integration modules are under development or planned.

### Hardware Implementation


Our project currently uses a laptop and webcam as the primary hardware components for developing and testing the AI-Based Smart Entry Monitoring System.

### 1. Laptop / Computer
- Used as the main processing unit for running Python programs, AI models, and image processing operations.
- Handles face detection, face recognition, and database operations.

### 2. Webcam
- Connected to the laptop through a USB interface.
- Captures live video frames of students entering the monitoring area.
- Provides real-time input for face detection and recognition.

### 3. Camera Positioning
- The webcam is positioned to capture clear facial images during testing.
- Proper camera placement is important for accurate face detection and recognition.

### 4. Power Supply
- The laptop and webcam are powered through the laptop's power supply and USB connection.
- No separate external power supply or dedicated PCB is currently required.

### 5. Future Hardware Integration
The following hardware implementation is planned for the final system:
- External/IP camera installation at the college entrance.
- Suitable camera mounting arrangement.
- Network connectivity for IP camera communication.
- Integration with the final monitoring setup.

### Current Status                                                            

The laptop and webcam setup, connection, and testing have been completed successfully. The system is currently being developed using the webcam for real-time face recognition. External/IP camera integration is planned for the final hardware setup.

### Software Implementation


Our project is being developed using Python-based computer vision and artificial intelligence technologies. The software is designed to process live camera input, recognize registered students, and maintain entry records.

### 1. Programming Language and Development Environment
- Python is used as the primary programming language.
- Visual Studio Code is used for writing, debugging, and managing the project code.
- OpenCV is used for image processing and webcam integration.

### 2. Code Structure
The project is organized into modules for:
- Camera input and video capture.
- Face detection and recognition.
- Student dataset and database management.
- ID card detection.
- Entry logging and monitoring dashboard.

### 3. Libraries and Technologies Used

| Library / Technology | Purpose |
|---|---|
| Python | Core application development |
| OpenCV | Image processing and face detection |
| Dlib | Facial feature extraction and face encoding |
| face_recognition | Face matching using a pre-trained model |
| NumPy | Numerical operations and image data processing |
| Pandas | Managing student records and CSV data |
| CSV | Storing registered student information |

### 4. Face Recognition Implementation
- Integrated a pre-trained face-recognition model.
- Generated facial encodings for registered student images.
- Stored and loaded facial encodings for recognition.
- Implemented real-time face recognition using webcam input.
- Successfully tested face recognition with registered student images.

### 5. Database and Data Management
- Created a `students.csv` file to store student identification details.
- Prepared a dataset containing 21 student images.
- Entry database development is planned for storing student entry history.

### 6. Planned Software Development
The following modules are planned for further implementation:
- ID card detection and identification.
- Face and ID card verification.
- Automatic date and exact time entry logging.
- Monitoring dashboard.
- Integration of all modules into a complete entry monitoring system.

### Current Status
Python environment setup, OpenCV integration, face detection, facial encoding generation, and live face recognition have been successfully implemented and tested. ID card detection is currently under development, while entry logging and dashboard development are planned.

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

The AI-Based Smart Entry Monitoring System can be applied in various real-world environments:

1. **Educational Institutions:** Automated monitoring and verification of students entering college premises.

2. **Corporate Offices:** Employee identity verification and secure entry monitoring.

3. **Research Laboratories:** Restricting access to authorized personnel and maintaining entry records.

4. **Industrial Facilities:** Monitoring employee access to restricted or sensitive areas.

5. **Libraries and Examination Centers:** Verifying registered individuals and maintaining automated entry logs.
---

## Advantages


1. **Automated Entry Monitoring:** Reduces the need for manual student entry verification.

2. **Improved Security:** Verifies student identity using ID card detection and face recognition.

3. **Accurate Entry Records:** Maintains student entry date and exact time automatically.

4. **Real-Time Identification:** Identifies registered students and detects unknown individuals.

5. **Centralized Monitoring:** Enables organized management and monitoring of entry records through a dashboard.

---

## Limitations

1. **Lighting Conditions:** Poor lighting or shadows may affect face detection and recognition accuracy.

2. **Face Occlusion:** Masks, sunglasses, or partially covered faces may reduce recognition performance.

3. **Limited Dataset:** Currently, the face database contains only 21 student images out of the target 67 students.

4. **Camera Dependency:** System performance depends on camera quality, positioning, and image clarity.

5. **ID Card Detection Challenges:** Different ID card orientations, damaged cards, or unclear images may affect detection accuracy.
---

## Future Scope

Mention possible improvements.

1. **Advanced ID Card Detection:** Improve ID card detection using advanced AI models for better accuracy under different conditions.

2. **Complete Face + ID Verification:** Integrate face recognition and ID card detection to ensure that the ID card belongs to the detected student.

3. **Cloud-Based Monitoring Dashboard:** Develop a centralized dashboard for real-time monitoring and remote access to entry records.

4. **IP Camera Integration:** Deploy the system using external/IP cameras at multiple college entrances.

5. **Automated Alerts:** Send notifications to administrators when unknown individuals or mismatched identity details are detected.

6. **Scalability:** Expand the system to support more students, multiple entry points, and integration with college management systems.
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
