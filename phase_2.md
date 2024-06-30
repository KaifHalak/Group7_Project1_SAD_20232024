
![](/images/UTM%20Logo.png)

## Malaysian-Japan International Institute of Technology 



### SECD2613-15 SYSTEM ANALYSIS AND DESIGN


#### Group Assignment 1



#### Lecturer Name: Dr. SAIDATUL HAMIDAH BINTI ABD HAMID


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
- Lack of engaging and interactive study materials available to students in a remote learning setting such as multimedia content, interactive exercises, and adaptive learning tools.

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
- **Enable communication between club leaders, members, and teachers for activity planning and discussions**: Integrate functionalities for online competitions, showcases, and presentations related to co-curricular activities.

### Result Management
- **User-friendly interface for teachers to record and update student performance data**: Enable the recording of various types of assessments, including quizzes, assignments, projects, and participation.
- **Allow for flexible grading schemes (e.g., rubrics, points systems) aligned with the school's curriculum**: Integrate with the progress tracking features for a holistic view of student achievement.
- **Secure and informative results portal for parents**: Provide parents with timely access to their child's grades and progress reports.
- **Allow for visualizations of results (e.g., charts, graphs) for easy understanding of strengths and weaknesses**: Offer options for personalized communication with teachers regarding specific subjects or areas needing improvement.

## 4.0 Information Gathering Process
The information-gathering process involved Interactive Methods such as interviews and surveys accompanied by Unobtrusive Methods like sampling and STROBE with key stakeholders including students, teachers, administrators, and IT staff. Observations of current processes were also conducted to understand existing implementation and pain points.

### Interactive Methods

#### Survey Questions
- **Closed-Ended Questions:**
  - On a scale of 1 to 5, how satisfied are you with the current remote learning tools? (Students, Teachers)
  - How often do technical issues disrupt your learning/teaching experience? (Never, Rarely, Sometimes, Often, Always) (Students, Teachers)
  - Do you have access to reliable internet connectivity for remote learning? (Yes/No) (Students, Teachers)
- **Open-Ended Questions:**
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

### Diagram 0

![](/images/DFD%20Diagram%200.jpg)

### Child Diagram
![](/images/Performance%20Tracking%20Child%20Diagram%20AS-IS.jpg)

## 6.0 Summary of Requirement Analysis Process
The requirement analysis process involved gathering data through surveys and interviews with stakeholders, analyzing the current business processes, and identifying the functional and non-functional requirements for the new system. This thorough analysis ensures the new RLMS will address existing challenges effectively, providing a seamless and enhanced learning experience.

Overall, the proposed remote learning system for Sekolah Menengah Kebangsaan Taman Tun Dr. Ismail is will to revolutionize education delivery, leveraging technology to enhance learning outcomes and operational efficiency.