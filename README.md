IN2201 - Software Engineering

Maven Laboratory Practical Tasks

Student Name: E R Fernando

Student Registration Number: 245028X  

Group:ITM

**Project Overview**

This repository contains the practical laboratory tasks completed during the Maven laboratory sessions. The project demonstrates the use of Apache Maven for Java project management, including project creation, dependency management, build lifecycle, packaging, and execution of Java applications using Maven.

All tasks have been organized into separate folders/packages according to the laboratory activities.

---



## Tasks Completed

### Task 1
- Installed Apache Maven.
- Verified the installation using `mvn -version`.

### Task 2
- Created a Maven project using the Maven Quickstart Archetype.

### Task 3
- Explored the Maven project structure.
- Learned the purpose of `src/main`, `src/test`, and `pom.xml`.

### Task 4
- Learned the basic structure of the `pom.xml` file.
- Added project properties.

### Task 5
- Executed Maven commands:
  - `mvn compile`
  - `mvn test`
  - `mvn package`
  - `mvn install`

### Task 6
- Read application properties from the `pom.xml` file.

### Task 7
- Configured the project to generate an executable JAR file.
- Ran the JAR file successfully.

---

## How to Run

1. Open the project in your IDE.
2. Make sure Java JDK and Maven are installed.
3. Open a terminal in the project folder.
4. Run the following command:

```bash
mvn clean package
```

To run the application:

```bash
java -jar target/<your-jar-file>.jar
```

---
