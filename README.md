<h1 align="center">
  <b>"Student Performance Tracker in Competitive Programming"</b>
</h1>

---

<h2 align="center" ">
  <em>Course Information</em>
</h2>

<p align="center" >
  <span >Course Title:</span> Software Engineering  
  <br>
  <span >Course Code:</span> CSE 305  
</p>



<h2 align="center" >
  <em>Submitted To</em>
</h2>

<p align="center" >
  <span >Name:</span> Pankaj Bhowmik  
  <br>
  <span>Designation:</span> Lecturer  
  <br>
  <span>Department:</span> Computer Science and Engineering  
</p>



<h2 align="center">
  <em>Submitted By</em>
</h2>

<p align="center">
  <span >Name:</span> Sourav  
  <br>
  <span >Student ID:</span> 2102008  
  <br>
  <span >Level:</span> 3  
  <br>
  <span >Semester:</span> I  
  <br>
  <span ">Department:</span> Computer Science and Engineering  
</p>



<p align="center">
  <img src="./Images/hstu_logo_.png" alt="Hajee Mohammad Danesh Science and Technology University,Dinajpur-5200" width="150">
</p>

<h2 align="center" ">
  <b>Hajee Mohammad Danesh Science and Technology University,</b>
<b>Dinajpur-5200</b>

---



## 🪄Abstract
This project shows student progress by tracking their accounts across various competitive programming platforms and contests.By utilizing the Agile methodology, it ensures flexibility and continuous improvement to meet the evolving needs of the learners.

## 💎Introduction
The "Student Performance Tracker in Competitive Programming" project is designed to provide a comprehensive solution for monitoring and improving student progress in competitive programming. By tracking student accounts across various competitive programming platforms and contests, the project offers valuable insights into their performance, highlighting areas of strength and opportunities for improvement. The use of Agile methodology ensures that the project remains flexible and adaptive, continuously evolving to meet the changing needs of students and educators. With a user-friendly interface, the project facilitates easy access to performance data, fostering a supportive environment for skill development and academic success.

## ✒️Objectives 
- **Monitor Student Progress**: Track and analyze the progress of students in competitive programming by monitoring their performance across various contests and platforms.
- **Platform Integration**: Seamlessly integrate with multiple competitive programming platforms to gather comprehensive performance data.
- **Agile Methodology**: Ensure continuous improvement and adaptability by utilizing the Agile methodology throughout the project's lifecycle.
- **User-Friendly Interface**: Create an intuitive and accessible interface for students and educators to easily navigate and interpret performance data.
- **Provide Tasks**: Offer specific tasks and challenges to help students practice and improve their competitive programming skills.
- **Leaderboard**: Implement a leaderboard feature to rank students based on their performance, encouraging healthy competition and motivation.


---


## 💻SDLC Model: Agile Development Process
---
### 1. **Brainstorming and Backlog Creation**
- **Activities**:
  - Conduct brainstorming sessions with students and teachers.
  - Create user stories that define the functionality from the perspective of students and teachers.
  - Prioritize the user stories based .
  - Develop an initial project backlog, listing all tasks and features required for the project.
- **Backlog Items**:
  - User Athentication
  - Dashboard
  - Leaderboard Integration
  - Reporting & Analytics
  - Performance According to Different Platforms

### 2. **Design**
  - Develop wireframes and prototypes [Class Diagram](#class-diagram).
  - Design the system architecture.
  - Review and refine design documents.
  - Create a database schema using [ER Diagram](#er-diagram).

### 3. **Sprint Planning and Development**
Break down the project into manageable iterations (sprints) and develop functional increments of the project.
  - **Sprint 1**:
      - Implement user authentication
      - Dashboard
      - Show performance progress
  - **Sprint 2**:
      - Leaderboard
      - Integrate with different platforms of competitive programming
  - **Sprint 3**:
      - Role-base acces (Admin, Teacher, Student, Adviser)
      - Task Provider 

### 4. **Testing**
  - Perform unit testing on individual components.
  - [Test Cases for Different Modules](#test-cases-for-different-modules)
  - Conduct integration testing to ensure components work together.
  - Execute system testing to validate the entire system.



### 5. **Deployment**
  - Deploy the final product.
  - Monitor the system post-deployment to ensure stability.

### 6. **Maintenance and Continuous Improvement**
  - Monitor system performance and resolve any issues.
  - Gather ongoing students' and teachers' feedback.
  - Plan and implement enhancements and new features.
  - Conduct regular updates and maintenance activities.

### Benefits of Agile Methodology in This Project:
- **Flexibility**: Agile allows for changes and adaptations based on feedback and evolving requirements.
- **Continuous Improvement**: Regular retrospectives ensure the team continually improves processes and outcomes.
- **User-Centric**: Frequent interactions with stakeholder ensure the product meets their needs and expectations.
- **Transparency**: Regular updates and reviews keep stakeholders informed and engaged throughout the project lifecycle.


---


## 🏞️UML Diagram:
 - ### **ER Diagram**:
  ![ER diagram](https://github.com/Sourav-121/Student-Performance-Tracker-in-Competitive-Programming/blob/main/Images/ER_diagram.png)
  <p align="center"><i>Figure 01: ER Diagram</i></p>
 
 ---
 
 - ### **Class Diagram**:
  ![class diagram](https://github.com/Sourav-121/Student-Performance-Tracker-in-Competitive-Programming/blob/main/Images/class_diagram.png)
  <p align="center"><i>Figure 02: Class Diagram</i></p>

  ---

  - ### **Activity Diagram**:
  ![activity diagram](https://github.com/Sourav-121/Student-Performance-Tracker-in-Competitive-Programming/blob/main/Images/Activity%20Diagram.png)
  <p align="center"><i>Figure 03: Activity Diagram</i></p>


 
  ---



  ## ✨Test Cases for Different Modules 
  The test cases outlined for the "Student Performance Tracker in Competitive Programming" project are designed to ensure that all core functionalities of the system are working as intended. Each test case covers different modules of the project, including user registration, login, profile management, performance tracking, task assignment, leaderboard, user feedback, and notifications.

  

| Module                  | Test ID   | Test Case Description                               | Input Data                         | Expected Output                           | Actual Result                           | Status   |
|-------------------------|-----------|-----------------------------------------------------|------------------------------------|-------------------------------------------|-----------------------------------------|----------|
| Student Registration       | T001      | Verify student registration with valid data            | Username, Password, Email          | Successful account creation message       | Account created successfully            | Pass     |
| Adviser Registration       | T002      | Add adviser with valid data         | Username, Password, Email  | Successful adviser adding message    | successfully added                  | Pass     |
| Login                   | T003      | Verify login with correct credentials               | Username, Password                 | Successful login                          | Logged in successfully                  | Pass     |
| Login                   | T004      | Try to login with incorrect credentials             | Username, Incorrect Password       | Error message indicating login failure    | Error message displayed                 | Pass     |
| Profile Management      | T005      |  can update profile information          | Updated Name, Email etc.          | Successful update message                 | Profile updated successfully            | Pass     |
| Performance Tracking    | T006      |  data tracking from integrated platforms      | User ID, Platform Credentials      | Accurate performance data displayed       | Performance data displayed accurately   | Pass     |
| Teacher Registration         | T007      | Adding teacher by admin to manage student and adviser                  | ID ,password          | Successful account creation                | Account created successfully              | Pass     |
| Leaderboard             | T008      | Verify leaderboard displays correct rankings        | Performance Data                   | Correct ranking based on performance data | Leaderboard rankings displayed correctly| Pass     |
| Task Provide           | T009      | check adviser and teacher can provide task                    | Task Details                      | Task submission confirmation          | Task submitted successfully         | Pass     |
| Notification            | T010      | Verify system sends notification to user            | Notification Trigger Event         | User receives notification                | Notification received                   | Pass     |



---



## 🛠️Limitations:
  - ### **System Integration**:
    It is a technical barrier. Integrating diverse data sources may increase technical challenges
  - ### **Technological Constrains**:
     The tools, programming languages ​​or platforms we are using may have limitations that prevent us from implementing some advanced features or functionality.
  - ### **System Integration**:
    It is the most hard task in this project.
  - ### **Dependency on External Platforms**:
    System performance depends on the availability and reliability of external competitive programming platforms. Any changes or interruptions in this platform may affect system performance.
  - ### **Scalability Issues**:
    As the number of users and amount of data increases, the system may face scalability challenges. Ensuring that the system can handle increasing numbers of users and large datasets without compromising performance is critical.
  - ### **Real-Time Data Accuracy**:
    The accuracy of performance data depends on the timely and reliable retrieval of information from integrated platforms. Delays or errors in data synchronization can affect the accuracy and usefulness of the system.
  - ### **Data Security**:
    Handling sensitive data such accounts of different platforms which may limit the scope of our analysis.


---


## ❄️Conclusion
The project "Student Performance Tracker in Competitive Programming" successfully addresses the need for a comprehensive solution to monitor, analyze and improve student performance in competitive programming.By combining data from various competitive programming platforms, the system provides valuable insights into student progress, identifies strengths and weaknesses, and provides targeted feedback and resources for improvement.

Overall, this project represents an important step forward in leveraging technology to support academic growth and achievement in competitive programming.
