# Smart-Attend Mobile Application

## Project Overview
Smart-Attend is a mobile application designed to automate the process of student attendance using modern technologies. The system uses **Geo-fencing** to detect when a student enters the classroom area and automatically records attendance.

During development, a new requirement was introduced to prevent **proxy attendance**. To address this issue, the system was enhanced with **Biometric Face ID verification**, ensuring that the student physically present in the classroom is the one marking attendance.

The project demonstrates how different **Software Development Life Cycle (SDLC) models** handle requirement changes and how **Agile Scrum methodology** allows teams to adapt quickly to new features.

---

## Agile Development Approach
The project follows the **Agile Scrum framework**, where development is divided into small iterations called **Sprints**.

Each sprint focuses on delivering a working part of the system while allowing continuous improvement based on feedback.

### Sprint 1 – Minimum Viable Product (MVP)
Sprint 1 focuses on building the core functionality of the attendance system.

Features implemented include:

- Basic mobile application interface  
- Student login using university ID  
- Geo-fencing based attendance detection  
- Real-time attendance monitoring for teachers  
- Notification system for attendance confirmation  

### Sprint 2 – Feature Update
Sprint 2 focuses on improving system security and reliability.

Features implemented include:

- Integration of **Biometric Face ID verification**  
- Camera permission and facial recognition workflow  
- Integration with Geo-fencing attendance detection  
- Reporting dashboard for teachers and administrators  
- Bug fixing and performance optimization  

---

## Why CI/CD is Used in This Project

CI/CD stands for **Continuous Integration** and **Continuous Deployment**. It is a DevOps practice used to automate the process of integrating, testing, and deploying new software updates.

In this project, CI/CD helps deliver **Sprint updates automatically to users** without interrupting the application.

When developers complete a sprint and push the new code to the repository, CI/CD pipelines automatically:

- Build the application
- Run automated tests
- Detect integration errors
- Deploy the updated version

This ensures that the system remains stable while new features are added.

---

## Continuous Integration (CI)

Continuous Integration automatically merges new code changes into the main repository and verifies that the system still works correctly.

Whenever developers add new features such as **Face ID authentication**, the CI process automatically:

- Builds the project
- Runs automated tests
- Checks compatibility with existing features like Geo-fencing

This helps detect errors early in the development process.

---

## Continuous Deployment (CD)

Continuous Deployment automatically releases validated updates to the application server.

Once the CI process confirms that the new code passes all tests, the deployment process updates the system automatically.

This allows sprint updates to be delivered quickly to users.

Examples of updates that can be deployed using CD include:

- Improved Geo-fencing accuracy
- Updates to Face ID verification
- Bug fixes in attendance detection
- Performance improvements

---

## Benefits of CI/CD

Using CI/CD in the Smart-Attend project provides several advantages:

- Faster delivery of new features
- Automatic testing of system updates
- Reduced deployment errors
- Continuous improvement of the application
- Faster bug detection and resolution

This ensures that every sprint update can be delivered reliably and efficiently.

---

## CI/CD Pipeline Workflow

The CI/CD pipeline used for delivering sprint updates follows these steps:

1. Developer writes code and pushes it to the repository.
2. The CI system automatically builds the application.
3. Automated tests verify the functionality of the new code.
4. If the tests pass, the CD process deploys the update.
5. The updated version becomes available to users.

This pipeline ensures that new features developed during each sprint can be automatically delivered to users without delays.

---

## Conclusion

The Smart-Attend system demonstrates how modern software development practices help manage changing requirements effectively.

While traditional models like **Waterfall struggle with mid-development changes**, **Agile Scrum combined with CI/CD pipelines** allows teams to continuously improve the system and deliver updates efficiently.

By using CI/CD, sprint updates can be automatically tested and deployed, ensuring reliable and efficient delivery of new features to users.
