# Phase 1 - Fundamentals and Setup

## 1. Project Overview

This project is created as part of Phase 1 of the internship. The purpose of this project is to verify the Java development environment, understand a professional project structure, practice basic Java execution, and demonstrate the Git and GitHub workflow.

## 2. Objectives

- Verify that Java/JDK is installed correctly.
- Create and run a basic Java application.
- Follow a clean project structure and Java package naming convention.
- Document the project using README.md.
- Track the project with Git.
- Publish the project on GitHub.

## 3. Technologies and Tools

- Java JDK 17 or later
- IntelliJ IDEA / VS Code / another Java IDE
- Git
- GitHub
- Command Prompt / PowerShell

## 4. Project Structure

```text
Phase-1-Fundamentals-and-Setup/
│
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── internship/
│                   └── phase1/
│                       └── Main.java
│
└── README.md
```

### Main.java

Contains the entry point of the Java application and prints a successful setup message.

### README.md

Contains the project documentation, setup instructions, commands, and learning outcomes.

## 5. Prerequisites

Before running this project, install Java JDK 17 or later and Git.

Verify Java:

```bash
java -version
javac -version
```

Verify Git:

```bash
git --version
```

## 6. How to Create the Project

### Step 1: Create the project folder

```bash
mkdir Phase-1-Fundamentals-and-Setup
cd Phase-1-Fundamentals-and-Setup
```

### Step 2: Create the source directories

Create:

```text
src/main/java/com/internship/phase1
```

### Step 3: Create Main.java

Create `Main.java` inside the package directory and add:

```java
package com.internship.phase1;

public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
        System.out.println("Phase 1 - Fundamentals and Setup");
        System.out.println("Java development environment is configured successfully.");
    }
}
```

## 7. Compile the Project

From the project root:

```bash
javac -d out src/main/java/com/internship/phase1/Main.java
```

The `-d out` option places the compiled `.class` files inside the `out` directory.

## 8. Run the Project

```bash
java -cp out com.internship.phase1.Main
```

Expected output:

```text
Hello World!
Phase 1 - Fundamentals and Setup
Java development environment is configured successfully.
```

Take a screenshot of the successful output for the internship report.

## 9. Git Setup

From the project root:

```bash
git init
git status
git add .
git commit -m "Initial Phase 1 project setup"
```

## 10. Create the GitHub Repository

1. Log in to GitHub.
2. Click **New repository**.
3. Repository name: `phase-1-fundamentals-and-setup`
4. Set the repository to **Public** if your internship portal needs public access.
5. Create the repository.
6. Copy the repository URL.

## 11. Connect Local Project to GitHub

Replace `YOUR_USERNAME` with your GitHub username:

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/phase-1-fundamentals-and-setup.git
git push -u origin main
```

Verify:

```bash
git remote -v
git status
```

## 12. Verify the GitHub Repository

Open the GitHub repository in a browser and confirm that `README.md` and the `src` directory are visible.

The final repository URL will look like:

```text
https://github.com/YOUR_USERNAME/phase-1-fundamentals-and-setup
```

## 13. Learning Outcomes

After completing this project, the following fundamentals are demonstrated:

- Java JDK verification and configuration
- Basic Java program execution
- Package and directory organization
- Compilation and execution from the command line
- README documentation
- Git repository initialization
- Git staging and commits
- GitHub remote repository setup
- Pushing a local project to GitHub

## 14. Conclusion

This project establishes the basic development environment required for the internship and demonstrates the complete workflow from creating a Java application to publishing it on GitHub. It provides a foundation for more advanced development tasks in subsequent internship phases.
