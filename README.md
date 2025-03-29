# **Maven Build Pipeline using Jenkins**

## **Project Overview**  
This project automates the **build and testing** process of a Java-based application using **Jenkins and Maven**.  
The pipeline ensures continuous integration by pulling the latest code, compiling, testing, and archiving artifacts for deployment.  


## **Steps to Complete the Project**  

### **1. Set Up GitHub Repository**  
- Create a **GitHub repository** and push the Java project files.  
- Ensure the repository contains:  
  - **Source code (`.java` files)**  
  - **`pom.xml` file** (Maven build configuration)  
  - **Jenkinsfile** (For pipeline automation, if using Jenkins)  

### **2. Set Up Jenkins Server**  
- Install **Jenkins** on a server or local machine.  
- Install required **plugins**:  
  - **Git Plugin** (To pull code from GitHub)  
  - **Pipeline Plugin** (To define automated stages)  
  - **Maven Integration Plugin** (To run Maven commands)  

### **3. Configure Maven in Jenkins**  
- Navigate to **Manage Jenkins** → **Global Tool Configuration**.  
- Add **Apache Maven 3.6.3** (or another version).  

### **4. Create a Jenkins Pipeline Job**  
- In Jenkins, create a new **Pipeline Job**.  
- Add the **GitHub repository URL** under the **Source Code Management** section.  
- Define the build steps in a **Jenkinsfile** (optional).  

### **5. Run the Build Process**  
- Compile and package the Java project using:  
  ```bash
  mvn clean package
## **Conclusion**
This project demonstrates how to automate the build and testing process for a Java application using Jenkins and Maven.
By following these steps, you can efficiently integrate continuous integration (CI) practices, ensuring a stable and reliable development workflow.
