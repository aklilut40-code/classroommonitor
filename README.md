# Classroom Monitor

Classroom Monitor is a JavaFX desktop application designed to help teachers and administrators manage classroom activities efficiently. It provides a simple and intuitive interface for monitoring student attendance, tracking classroom status, and managing instructional activity in real time.

This project is built using Java and JavaFX, making it a lightweight, cross-platform desktop solution for educational environments.

## Features

- Student attendance tracking
- Real-time classroom status overview
- Teacher dashboard for classroom monitoring
- Student roster management
- Attendance history and reports
- Clean and responsive JavaFX UI
- Easy setup and local database support
- Extensible architecture for future enhancements

## Tech Stack

- Java 17+
- JavaFX
- Maven or Gradle (depending on setup)
- SQLite / MySQL / JDBC (optional, depending on implementation)
- CSS for JavaFX styling

## Project Goals

Classroom Monitor aims to simplify classroom supervision by offering a single dashboard where teachers can:
- view attendance records
- monitor student activity
- manage sessions efficiently
- improve classroom organization
- maintain quick access to student information

## Screenshots

Add screenshots here:
- Dashboard View
- Attendance View
- Student Management View
- Reports View

Example:
![Dashboard](docs/images/dashboard.png)

## Prerequisites

Before running the project, make sure you have the following installed:

- Java JDK 17 or later
- JavaFX SDK
- Maven or Gradle
- IDE such as IntelliJ IDEA or Eclipse

## Project Structure

```text
classroom-monitor/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── classroommonitor/
│   │   │           ├── app/
│   │   │           ├── controllers/
│   │   │           ├── models/
│   │   │           ├── services/
│   │   │           ├── util/
│   │   │           └── views/
│   │   ├── resources/
│   │   │   ├── css/
│   │   │   ├── fxml/
│   │   │   └── images/
│   └── test/
│       └── java/
├── pom.xml
├── README.md
├── LICENSE
└── .gitignore
