# Task-8 (Hello Java Maven with Jenkins)

## Project Overview
This is a simple Java application (`HelloWorld.java`) built with Maven and integrated into Jenkins using a **Freestyle Job**.  
The goal was to demonstrate setting up Jenkins, configuring Maven, pulling code from GitHub, and verifying a successful build.

---

## Tools & Technologies
- **Java** (OpenJDK 11)
- **Maven** (Build automation)
- **Git & GitHub** (Version control & repository hosting)
- **Jenkins** (Continuous Integration server)
- **Ubuntu** (Development environment)

---

## Project Structure
```bash
hello-java-maven/
├── pom.xml
├── src/
│ └── main/
│ └── java/
│ └── HelloWorld.java
├── README.md
└── screenshots
```

## Steps Performed
1. **Created Java application**
   - Added `HelloWorld.java` with a simple print statement.
   - Created `pom.xml` with Maven compiler plugin targeting Java.
 
2. **Pushed code to GitHub**
   - Initialized Git repo.
   - Committed and pushed all files to a GitHub repository.

3. **Configured Jenkins**
   - Installed suggested plugins.
   - Added Maven in **Manage Jenkins → Global Tool Configuration**.
   - Created a Freestyle Job.
   - Linked the GitHub repository.
   - Added build step: `clean package` using Maven.

4. **Built project in Jenkins**
   - Clicked **Build Now**.
   - Verified **BUILD SUCCESS** in the Console Output.
   - Captured screenshot for submission.

---

## Screenshot are available

---

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/hello-java-maven.git
   cd hello-java-maven
   ```
2. Build with maven:
   ```bash
   mvn clean package
   ```
3. Run the program:
   ```bash
   java -cp target/hello-1.0.jar HelloWorld
   ```
# THANK YOU
