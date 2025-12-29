# Java Application using Gradle – Command Documentation  
CodeAlpha DevOps Internship (Task 2)

---

## 📌 Objective
The objective of this task is to understand how to create, build, and run a Java application using **Gradle**, a popular build automation tool.

---

## 🖥️ Environment Details
- Operating System: Windows
- Programming Language: Java
- Java Version: JDK 21+
- Build Tool: Gradle 9.2.1
- Interface: Command Prompt (CMD)

---

## 📂 Project Initialization

### Command:gradle init

### Description:
This command initializes a new Gradle project.  
During initialization, the following selections were made:
- Project Type: Application
- Language: Java
- Build Script DSL: Groovy
- Test Framework: JUnit
- Project Structure: Single application project

### Result:
Gradle generated the complete project structure including:
- `build.gradle`
- `settings.gradle`
- `src` directory
- `gradle` wrapper files

---

## 🔨 Build the Project

### Command:gradle build

### Description:
This command compiles the Java source code, runs tests (if any), and packages the application.

### Result:
The build completed successfully with the message:BUILD SUCCESSFUL

This confirms that the project has no compilation or configuration errors.

---

## ▶️ Run the Application

### Command:gradle run

### Description:
This command executes the main Java class defined in the Gradle configuration.

### Output:Hello World

This confirms that the Java application ran successfully.

---

## ✅ Final Result
- The Gradle project was initialized correctly
- The project was built without errors
- The Java application executed successfully and displayed output

---

## 🏁 Conclusion
This task demonstrates basic knowledge of:
- Java application structure
- Gradle project initialization
- Build automation using Gradle
- Running Java applications from the command line

These skills are essential for DevOps practices and CI/CD pipelines.

