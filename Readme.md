# EI_CODING_ASSESSMENT

## 1. Design patterns

## i) Behavioral Design Patterns

- Use Case 1: **_State Pattern_**

  **Payment Processing System**

  Description: Different payment methods (Credit Card, PayPal, Bitcoin) can be used interchangeably in a shopping cart system.

  ![State Pattern](./Exercise%201/output/StatePattern.png)

- Use Case 2: **_Strategy Pattern_**

  **Traffic Light System**

  Description: A traffic light system that changes state from Red to Green to Yellow in a cyclic manner.

  ![Strategy Pattern](./Exercise%201/output/StrategyPattern.png)

## ii) Creational Design Patterns

- Use Case 3: **_Abstract Factory Pattern_**

  **GUI Toolkit**

  Description: A factory of factories that creates UI components for different operating systems (Windows, Mac).

  ![Abstract Factory Pattern](./Exercise%201/output/AbstractFactoryPattern.png)

- Use Case 4: **_Builder Pattern_**

  **Meal Preparation System**

  Description: A builder class constructs a complex Meal object with various parts (Burger, Drink).

  ![Builder Pattern](./Exercise%201/output/BuilderPattern.png)

## iii) Structural Design Patterns

- Use Case 5: **_Facade Pattern_**

  **Home Theater System**

  Description: Simplifying the operation of a complex home theater system with a single interface.

  ![Facade Pattern](./Exercise%201/output/FacadePattern.png)

- Use Case 6: **_Proxy Pattern_**

  **Image Viewer**

  Description: Loading an image only when it's actually needed.

  ![Proxy Pattern](./Exercise%201/output/ProxyPattern.png)

## 2. Mini-Project

## Project 8: Virtual Classroom Manager Programming Exercise

### Problem Statement

Imagine you are developing the backend for an EdTech platform that aims to host virtual classrooms. Your task is to create a terminal-based Virtual Classroom Manager that handles class scheduling, student attendance, and assignment submissions.

### Features

- Classroom Management (Add Classroom, List Classroom, Remove Classroom)
- Student Management (Add Student, List Students)
- Asssignment Management (Schedule Assignment, Submit Assignment)
- User Interface (Terminal-Based Input, Command Display)
- Validation and Error Handling (Classroom Existence Validation, Student Enrollment Validation, Command Validation)
- Logging and Exception Handling (Logging, Exception Handling)
- Design Patterns and Principles (Command Pattern, Singleton Pattern, SOLID Principles)
- Application Structure (Modular Design, Scalable Architecture)
- Performance and Efficiency (Optimized Data Structures, Avoiding Hard-Coded Loops)
- User Guidance: Help and Usage Hints

### Classes Used in the Virtual Classroom Application

### Models

1. **Classroom**: Represents a virtual classroom with students and assignments.
2. **ClassroomManager**: Manages the operations related to classrooms, students, and assignments.
3. **Student**: Represents a student enrolled in a classroom.
4. **Observable**: Interface for classes that can be observed.
5. **Observer**: Interface for classes that observe observables.

### Commands

1. **Command**: Interface for encapsulating a command.
2. **AddClassroomCommand**: Command to add a new classroom.
3. **RemoveClassroomCommand**: Command to remove an existing classroom.
4. **ListClassroomsCommand**: Command to list all classrooms.
5. **AddStudentCommand**: Command to add a student to a classroom.
6. **ListStudentsCommand**: Command to list all students in a classroom.
7. **ScheduleAssignmentCommand**: Command to schedule an assignment for a classroom.
8. **SubmitAssignmentCommand**: Command to submit an assignment for a student in a classroom.

### Main

1. **Main**: Entry point of the application that handles user input and command execution.

Each class has a specific role that contributes to the overall functionality and organization of the application, following best practices and design patterns.

## OUTPUT :

**Classroom Commands**

![Add Classroom](./Exercise%202/output/AddClassroom.png)

![List Classroom](./Exercise%202/output/ListClassroom.png)

![Remove Classroom](./Exercise%202/output/RemoveClassroom.png)

**Student Commands**

![Add Students](./Exercise%202/output/AddStudents.png)

![List Students](./Exercise%202/output/ListStudents.png)

**Assignment Commands**

![Schedule Assignments](./Exercise%202/output/ScheduleAssignment.png)

![Submit Assignment](./Exercise%202/output/SubmitAssignment.png)
