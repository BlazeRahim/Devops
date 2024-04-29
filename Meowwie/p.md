# Java Program with Jenkins

## Date: April 28, 2024

This project demonstrates building a Java program for the addition of two numbers using Jenkins.

## Instructions

1. Install Jenkins:
    - Download Jenkins from the official website: [https://www.jenkins.io/download/](https://www.jenkins.io/download/)
    - Follow the installation instructions for your operating system.

2. Set up Jenkins:
    - Access Jenkins through your web browser (http://localhost:8080 by default).
    - Follow the on-screen instructions to set up Jenkins, including creating an admin user and selecting plugins to install.

3. Create a New Jenkins Job:
    - Click on "New Item" on the Jenkins dashboard.
    - Enter a name for your job (e.g., "AdditionProgram") and choose "Freestyle project," then click "OK."

4. Configure the Jenkins Job:
    - In the job configuration page, scroll down to the "Build" section.
    - Click on "Add build step" and select "Execute shell" (for Unix-like systems) or "Execute Windows batch command" (for Windows).
    - Write the necessary commands to compile and run your Java program.

5. Write the Java Program:
    - Create a Java program that adds two numbers.
    - Save the program in a file named `AdditionProgram.java`.

6. Add Java Compilation to Jenkins:
    - In the Jenkins job configuration, in the "Execute shell" section, add the necessary commands to compile and run your Java program.

7. Save and Build:
    - Click on "Save" to save the Jenkins job configuration.
    - Click on "Build Now" to run the job.

8. View the Output:
    - Once the job is completed, you can view the console output to see the result of your Java program.

For further enhancements, consider integrating version control (e.g., Git) to automate builds triggered by code changes.
