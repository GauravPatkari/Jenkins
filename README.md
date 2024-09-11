 Jenkins
 • What is Jenkins? 
	- Jenkins is an open-source continuous integration/continuous delivery and deployment (CI/CD) automation software DevOps tool written in the Java programming language. It is used to implement CI/CD workflows, called Pipelines.
	- Alternative options of CI/CD tools are GitAction, GitLab, Agro CD, Circle CI
	- To integrate the different types of code from the developers there is a need of a Central Repository for the integration of applications. 
	- Where we use GitHub for creating repositories for collaboration between the developers. 
Source Code >> Compiler/Interpreter >> Executable File >> Execute >> App/Website

- What is BUILD in Jenkins?
	- The process of Compilation and Interpretation is also called build-in CI/CD tools like Jenkins. 
	- Before deployment, we need to check the Errors in that source code where one can use directly Build or Code Checking Review Tools. 
	- Code Review check the optimize the source code for space complexity and time complexity in that code. 
	- After building the different types of files for languages like for 
	- Java use two types of file formats for Standalone Apps .jar and app .war
	- C and C++ is used Object, Android uses APK, IOS uses IP
	- The Test process the errors from the different parts of the application are reviewed where it will revert back to the developers for solving those errors


	• GitHub <-> Jenkins 
	- There are two types of methods to integrate with GitHub to Jenkins which are Polling Tech and Push Tech 
	- Polling tech is old school tech where Jenkins sends the request to the GitHub in every 1 minute to check the changes in the source code of the app before pushing that code on the server. 
	- Push tech is a new optimised tech where source code can be directly pushed automatically to the Jenkins server if any changes are made in that code. 
	- This Auto Pull can be done using WebHook  which we can setup in the repository of that project. 
	- The source code can be pulled in the Folder of Jenkins which is known as Workspace 

	- After all this above process final process is Build which can differ by the language used in that application. 
	- Like for Java - Maven, Gradle, Ant
  - To use the above compiler or interpreter there are different types of Plugins in Jenkins.
