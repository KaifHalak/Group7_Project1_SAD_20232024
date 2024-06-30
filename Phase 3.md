

![](/images/UTM%20Logo.png)
## Malaysian-Japan International Institute of Technology 
### SECD2613-15 SYSTEM ANALYSIS AND DESIGN\

#### Group Assignment 1
#### Lecturer Name: Dr. SAIDATUL HAMIDAH BINTI ABD HAMID\

| Group Members    | Matric Number |
| -------- | ------- |
| Muhammad Usman  | A23MJ3008    |
| Khobait Uddin Simran | A23MJ3006     |
| Md Arshad Ali Bhuiyan    | A22MJ9007    |


# System Requirement Document for Remote Learning System Implementation (Phase 2)


## 1.0 Overview of the Project
Sekolah Menengah Kebangsaan Taman Tun Dr. Ismail aims to implement a Remote Learning Management System (RLMS) to enhance remote educational delivery. The proposed remote learning system will address current challenges by implementing features such as virtual classrooms and interactive study materials to improve efficiency, transparency, and data security.

## 2.0 Problem Statement
The school currently lacks the following infrastructure:

### Lack of Remote Learning Infrastructure
- Absence of dedicated platforms or systems to support remote learning activities at the school

### Inefficient Communication Channels
- Inefficient student-teacher interaction, collaboration, and feedback mechanisms

### Limited Progress Tracking Capabilities
- Lack of comprehensive tracking tools, data analysis capabilities, and performance evaluation mechanisms to assess student learning outcomes accurately

### Insufficient Interactive Study Materials
- Lack of engaging and interactive study materials available to students in a remote learning setting such as multimedia content, interactive exercises, and adaptive learning tools
@\uc0\u8296 ./.\u8297  

## 3.0 Proposed Solutions
To tackle these problems, the following solutions are proposed:

### Virtual Classrooms
- **Real-time interaction**: Live video streaming allows instructors to deliver lectures and facilitate discussions in real-time. Students can participate through audio, video, or text chat, fostering active engagement
- **Interactive Whiteboard**: Whiteboard features where instructors can annotate slides, draw diagrams, and illustrate concepts during lectures where students can also interact with the whiteboard.
- **Screen Sharing**: Allowing instructors to share presentations, documents, and multimedia content with students.
- **Breakout Rooms**: Enabling instructors to divide students into smaller groups for collaborative activities, discussions, and problem-solving exercises.

### Interactive Study Materials
- **Multimedia Content**: Interactive study materials such as video lectures, simulations, and virtual labs to cater to different learning styles.
- **Interactive Quizzes**: Create interactive quizzes and assessments with various question types, including multiple-choice, fill-in-the-blank, and drag-and-drop.
- **Gamification Elements**: Incorporate gamification elements such as badges, achievements, leaderboards, and progress tracking to motivate students and increase their participation.
- **Adaptive Learning**: Implement adaptive learning algorithms that personalize learning experiences based on individual student progress, preferences, and learning objectives.

### Progress Tracking System
- **Attendance Monitoring**: Develop a system to automatically track student attendance and participation in virtual classes.
- **Assignment Tracking**: Implement features for tracking assignments, including submission deadlines, grades, and feedback.
- **Performance Analytics**: Generate comprehensive performance analytics and reports on student progress, grades, and learning outcomes by using data visualization tools, allowing educators to identify trends, patterns, and areas for improvement in student performance.

### Communication Tools
- **Messaging platforms**: Integrate messaging platforms for asynchronous communication between students, instructors, and support staff.
- **Discussion Forums**: Online discussion forums where students can engage in academic discussions, share resources, and ask questions related to course content.
- **Announcements and Notifications**: Implement announcement and notification features to keep students informed about course updates, assignment deadlines, and important events.
- **Virtual Office Hours**: Schedule virtual office hours where students can meet with instructors for one-on-one assistance, tutoring, and academic advising.

### Co-Curricular Activities Integration
- **Management of co-curricular activities within the RLMS**: Allow for online club meetings and events using video conferencing and collaboration tools.
- **Facilitate registration and participation in various co-curricular activities**: Provide a platform for sharing resources (documents, videos, photos) related to co-curricular activities.
- **Enable communication between club leaders, members, and teachers for activity planning and discussions**: Integrate functionalities for online competitions, showcases, and presentations related to co-curricular activities.\

### Result Management
- **User-friendly interface for teachers to record and update student performance data**: Enable the recording of various types of assessments, including quizzes, assignments, projects, and participation.
- **Allow for flexible grading schemes (e.g., rubrics, points systems) aligned with the school's curriculum**: Integrate with the progress tracking features for a holistic view of student achievement.
- **Secure and informative results portal for parents**: Provide parents with timely access to their child's grades and progress reports.
- **Allow for visualizations of results (e.g., charts, graphs) for easy understanding of strengths and weaknesses**: Offer options for personalized communication with teachers regarding specific subjects or areas needing improvement.\

## 4.0 Information Gathering Process
The information-gathering process involved Interactive Methods such as interviews and surveys accompanied by Unobtrusive Methods like sampling and STROBE with key stakeholders including students, teachers, administrators, and IT staff. Observations of current processes were also conducted to understand existing implementation and pain points.

### Interactive Methods

#### Survey Questions
- **Closed-Ended Questions:**
  - On a scale of 1 to 5, how satisfied are you with the current remote learning tools? (Students, Teachers)
  - How often do technical issues disrupt your learning/teaching experience? (Never, Rarely, Sometimes, Often, Always) (Students, Teachers)
  - Do you have access to reliable internet connectivity for remote learning? (Yes/No) (Students, Teachers)
- **Open-Ended Questions:**\
  - What challenges do you face with the current remote learning setup? (Students, Teachers, Administrators)
  - What features do you think are most critical for a remote learning system? (Students, Teachers, Administrators)
  - How can communication between students and teachers be improved in a remote setting? (Students, Teachers, Administrators)

#### Interview Questions
- **For Students:**
  - What difficulties do you encounter when using the current remote learning tools?
  - How do you feel about the effectiveness of the current communication channels with your teachers?
  - What additional features would make your learning experience better?
- **For Teachers:**
  - What are the main challenges you face in delivering remote lessons?
  - How do you track and manage student progress and attendance?
  - What tools or features would enhance your remote teaching experience?
- **For Administrators:**
  - What are the current challenges in managing remote learning infrastructure?
  - How do you ensure data security and privacy in the current system?
  - What improvements would you like to see in the remote learning system?
- **For IT Staff:**
  - What technical issues do you frequently address with the current system?
  - How scalable and secure is the current remote learning infrastructure?
  - What are your recommendations for technical improvements?

### Unobtrusive Methods
- **Strobe Observations:** Observed actual use of current remote learning platforms during live sessions and noted how often teachers and students faced interruptions or technical difficulties.

### Summary from Surveys and Interviews
The surveys and interviews revealed key areas needing improvement:

#### Functional Requirements
- Real-time interactive tools for virtual classrooms.
- Engaging multimedia content and interactive quizzes.
- Comprehensive progress tracking and performance analytics.
- Effective communication platforms for students and teachers.

#### Non-Functional Requirements
- User-friendly interface.
- Robust security and data privacy measures.
- Scalability to support a large number of concurrent users.


## 5.0 Requirement Analysis

### Current Business Process
The existing workflow involves the following steps:
- Teachers create and share lesson content using tools like Google Drive, Dropbox, or Microsoft OneDrive.
- Students access the lesson materials through links or attachments shared by teachers via email or messaging apps like WhatsApp.
- For live sessions, teachers and students use video conferencing platforms such as Zoom or Google Meet.
- Communication between students and teachers primarily occurs through messaging apps, email, or discussion forums provided by the video conferencing platforms.
- Tracking student attendance, participation, and progress is done manually by teachers, often using spreadsheets or paper-based records.
- Administrators oversee the overall remote learning process, providing support and guidance to teachers and students, but lack comprehensive data on the system's performance.
- The IT staff manages the technical aspects of the remote learning setup, troubleshooting issues and ensuring the availability of the third-party tools.

This approach leads to several challenges, including inefficient communication channels, limited progress tracking capabilities, and insufficient interactive study materials.

### 5.2 Functional Requirement (Input, Process, Output)

#### Virtual Classrooms
- **Input:** User login, lesson content.
- **Process:** Real-time interaction, content sharing.
- **Output:** Recorded sessions, participation data.

#### Interactive Study Materials
- **Input:** Multimedia content, quizzes.
- **Process:** Content delivery, adaptive learning.
- **Output:** Student performance data.
#### Progress Tracking System
- **Input:** Attendance logs, assignment submissions.
- **Process:** Data analysis, performance tracking.
- **Output:** Analytics reports, progress dashboards.
#### Communication Tools
- **Input:** Messages, forum posts.
- **Process:** Message delivery, forum management.
- **Output:** Communication logs, discussion summaries.

### 5.3 Non-Functional Requirement (Performance and Control)

#### Performance
- System must support concurrent users without lag, ensure fast content delivery.

#### Control
- Secure data storage, compliance with data privacy regulations, role-based access control.


### Context Diagram

![](/images/DFD%20Context%20Diagram.jpg)
\
### Diagram 0

![](/images/DFD%20Diagram%200.jpg)

## 6.0 Summary of Requirement Analysis Process
The requirement analysis process involved gathering data through surveys and interviews with stakeholders, analyzing the current business processes, and identifying the functional and non-functional requirements for the new system. This thorough analysis ensures the new RLMS will address existing challenges effectively, providing a seamless and enhanced learning experience.

Overall, the proposed remote learning system for Sekolah Menengah Kebangsaan Taman Tun Dr. Ismail is will to revolutionize education delivery, leveraging technology to enhance learning outcomes and operational efficiency.

##6

## Overview

The Remote Learning Management System (RLMS) aims to provide a comprehensive, secure, and user-friendly web-based application for managing remote education. The system will benefit various stakeholders, including administrators, instructors, students, and technical support teams. The key features will include virtual classrooms, interactive study materials, progress tracking systems, and communication tools. These features enable a flexible and effective remote learning experience tailored to the user's needs.

## System Objectives

This new Remote Learning Management System has specific objectives to improve its functionality and provide better opportunities for its users.

1. The platform will have a user-friendly interface to facilitate navigation and operation.
2. The platform will provide tools for creating and managing virtual classrooms, including scheduling and hosting live sessions.
3. The system will offer tools for creating, managing, and accessing interactive study materials.
4. The system will provide a comprehensive progress tracking system for monitoring student performance.
5. The platform will include communication tools to enhance interaction between instructors and students.
6. The platform will ensure compatibility with different devices and browsers.
7. The platform will be capable of continuous improvement through regular updates and feature enhancements.

## Functional and Non-Functional System Requirements

Functional requirements summarize the essential features and capabilities that the system needs to possess, including tasks like user authentication, virtual classroom management, material creation, and progress tracking. Non-Functional Requirements encompass the system's quality attributes, including performance, usability, reliability, scalability, and security.

### Functional Requirements

1. **User Authentication and Authorization**
   - User login and registration.
   - Role-based access control for administrators, instructors, and students.

2. **Virtual Classroom Management**
   - Create, schedule, and host live virtual classrooms.
   - Record and archive sessions for future reference.
   - Manage attendance and participation

3. **Interactive Study Materials**
   - Create and upload various types of study materials (videos, PDFs, quizzes).
   - Organize materials into courses and modules.
   - Provide tools for interactive content creation (e.g., multimedia presentations, interactive simulations).

4. **Progress Tracking System**
   - Track student progress through courses and modules.
   - Provide detailed analytics on student performance.
   - Generate reports for instructors and administrators.

5. **Communication Tools**
   - Provide chat, email, and forum functionalities.
   - Enable live discussions and Q&A sessions during virtual classes.
   - Integrate with external communication tools (e.g., Slack, Microsoft Teams).

6. **Security and Data Protection**
   - Encrypt sensitive data.
   - Ensure secure transmission of data.
   - Implement backup and recovery procedures.

7. **Mobile Compatibility**
   - Ensure the platform is responsive and works on various devices.
   - Provide mobile apps for iOS and Android.

8. **Continuous Improvement**
   - Regular updates and feature enhancements.
   - Provide user support and troubleshooting.

### Non-Functional Requirements

- **Performance**: The system should be able to support up to 10,000 concurrent users with low latency.
- **Usability**: It should be easy to use and understandable for individuals with different levels of technical proficiency.
- **Reliability**: Ensure high availability with a yearly downtime of less than 1%.
- **Scalability**: The system should scale horizontally to accommodate a growing user base.
- **Security**: Adhere to industry standards for privacy and data security for all users.

## Logical DFD TO-BE System

This part, using Data Flow Diagrams (DFDs), will show the system from both a high-level (context diagram) and a more in-depth perspective (level diagrams).\

### Context Diagram

The context diagram for the RLMS illustrates the system's interactions with various external entities, including users, administrators, and external data sources. It offers a broad perspective on the system's boundaries and important interfaces.\
![Context Diagram - TO - BE](https://github.com/KaifHalak/Group7_Project1_SAD_20232024/assets/79431510/d3086c8a-cfbe-4f6f-b5b9-874675fdd99e)\]

### DFD Level 0
The DFD Level 0 diagram for the RLMS illustrates the major processes within the system, including user management, virtual classroom management, material management, progress tracking, and communication.
![Diagram 0 - TO - BE](https://github.com/KaifHalak/Group7_Project1_SAD_20232024/assets/79431510/830f2ba0-5fd7-40a8-a2f1-26ce5970e380)
### Child Diagram

The child diagram breaks down the main processes into more detailed components, showing the specific functionalities within user management, virtual classroom management, material management, progress tracking, and communication tools.
![Performance Tracking Child Diagram TO-BE](https://github.com/KaifHalak/Group7_Project1_SAD_20232024/assets/79431510/cc683e06-6710-4da9-9fde-f7c3404745bf)

## Process Specifications

1. **User Management**
   - **Authentication and Access Control**: This module manages user login and signup, utilizing a variety of authentication approaches such as username/password and social login. It handles user roles and permissions, implementing access control regulations to guarantee that users can only conduct actions and access resources relevant to their given responsibilities.
   - **User Profile**: This component contains the user's personal information, such as name, email, ID, class, section, faculty, and department. It enables users to update their profile information and interfaces with the authentication and access control systems.
   - **Roles and Permissions**: This section defines and handles various user roles, including administrator, instructor, and student. It sets particular permissions and privileges to each role, ensuring that users can only access and conduct actions that are relevant to their responsibilities.

2. **Virtual Classroom Management**
   - **Create and Schedule Classes**: This part allows instructors to create and schedule virtual classrooms. It includes features for setting class times, recurring sessions, and sending notifications to students.
   - **Host and Record Sessions**: This module manages live virtual classroom sessions, including tools for screen sharing, video conferencing, and recording sessions for future reference.
   - **Attendance Management**: This feature tracks student attendance during live sessions, providing reports for instructors and administrators.

3. **Interactive Study Materials**
   - **Material Creation**: This component offers tools for creating various types of study materials, including videos, PDFs, and interactive quizzes.
   - **Material Management**: This module organizes study materials into courses and modules, allowing easy access and navigation for students.
   - **Interactive Content**: This feature provides tools for creating interactive content such as multimedia presentations and simulations, enhancing the learning experience.

4. **Progress Tracking System**
   - **Student Progress**: This part tracks student progress through courses and modules, providing detailed analytics and reports.
   - **Performance Analytics**: This module analyzes student performance data, identifying strengths and weaknesses to provide targeted support.
   - **Reporting**: This feature generates reports for instructors and administrators, helping them monitor and assess student performance.

5. **Communication Tools**
   - **Chat and Messaging**: This component provides real-time chat and messaging functionalities for students and instructors.
   - **Discussion Forums**: This module enables students and instructors to participate in discussion forums, facilitating knowledge sharing and collaboration.
   - **Live Q&A**: This feature supports live Q&A sessions during virtual classes, enhancing interaction and engagement.

6. **Security and Data Protection**\
   - **Data Encryption**: This module ensures that all sensitive data is encrypted, protecting it from unauthorized access.
   - **Secure Transmission**: This feature guarantees secure data transmission, preventing interception and tampering.
   - **Backup and Recovery**: This component implements backup and recovery procedures, ensuring data integrity and availability.

7. **Mobile Compatibility**
   - **Responsive Design**: This part ensures that the platform is responsive and works seamlessly on various devices, including desktops, tablets, and smartphones.
   - **Mobile Apps**: This module provides mobile applications for iOS and Android, offering a native experience for users.

8. **Continuous Improvement**
   - **Regular Updates**: This feature ensures that the platform receives regular updates and feature enhancements, keeping it up-to-date with the latest technologies and user requirements.
   - **User Support**: This component provides user support and troubleshooting, ensuring a smooth and efficient user experience.

This document outlines the key features, system objectives, and both functional and non-functional requirements for the Remote Learning Management System. It provides a comprehensive overview of the system's architecture and processes, ensuring a secure, user-friendly, and effective remote learning experience.}

## 7

## 8

## [System Wireframe-UI Design of the System](https://www.figma.com/proto/9LfawNpzOXmSymYHnUCDUg/SCHOOL-MANAGEMENT-SYSTEM-(Community)-(Copy)?node-id=1314-3145&t=7r2IMcW7yRQATGvN-0&scaling=contain&content-scaling=fixed&page-id=9%3A0&starting-point-node-id=1314%3A3145&show-proto-sidebar=1)


##9
## Summary of the Online Quiz Platform:

The Online Quiz Platform aims to provide a scalable, secure, and user-friendly web-based application for administering quizzes and assessments online. It benefits administrators, professors, students, and technical support teams with customizable quiz creation tools, comprehensive reporting, robust security measures, integration capabilities, and mobile compatibility. Key features include:

- **User Authentication and Authorization**
- **Quiz Management**
- **Grading and Feedback**
- **Reporting and Analytics**
- **Security and Data Protection**
- **Integration**
- **Mobile Compatibility and User Engagement**
- **Continuous Improvement**

## Conclusion:

The Online Quiz Platform fulfills essential functional requirements such as user authentication, quiz management, and grading, while also addressing critical non-functional aspects like performance, usability, reliability, scalability, and security. By integrating role-based access control, automated grading, and detailed analytics, it ensures a seamless and efficient online learning and evaluation experience. The platform's emphasis on security measures and integration capabilities makes it a modern, reliable, and adaptable solution for educational institutions seeking robust quiz administration software.
}
