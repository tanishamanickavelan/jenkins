# Jenkins CI Pipeline with Maven

A Continuous Integration pipeline built using Jenkins and Maven on AWS EC2.

## Live Jenkins Dashboard
http://54.174.191.201:8080

## Tech Stack
- **CI/CD** — Jenkins
- **Build Tool** — Maven
- **Language** — Java
- **Repo** — GitHub
- **Server** — AWS EC2 (Ubuntu)

## Project Structure
```
jenkins-lab/
├── src/
│   └── HelloWorld.java
└── pom.xml
```

## How It Works
1. Developer pushes code to GitHub
2. Jenkins detects the change
3. Jenkins pulls the source code
4. Maven compiles the Java application
5. Jenkins reports BUILD SUCCESS

## Setup
### Prerequisites
- Java 11+
- Maven
- Jenkins
- Git

### Run Locally
```bash
git clone https://github.com/tanishamanickavelan/jenkins.git
cd jenkins
mvn clean package
```

## Build Result
```
BUILD SUCCESS
Total time: 5.824 s
Artifact: target/jenkins-lab-1.0.jar
```

## Author
Tanisha Manickavelan
