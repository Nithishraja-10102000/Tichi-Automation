# 🚀 Tichi Automation Framework

This project is a **Selenium WebDriver + TestNG automation framework** developed to test the login functionality of the **Tichi web application**.  
It follows the **Page Object Model (POM)** design pattern and uses Maven for build management.

---

## 📌 Project Objective

The main objective of this project is to automate and validate different login scenarios such as:

- Valid login
- Invalid email login
- Empty email submission

This helps ensure the login system behaves correctly under different user inputs.

---

## 🛠️ Tech Stack

- Java (Programming Language)
- Selenium WebDriver (UI Automation)
- TestNG (Test Execution Framework)
- Maven (Build Tool)
- Extent Reports (HTML Reporting)
- Git & GitHub (Version Control)

---

## 📁 Project Structure


Tichi-Automation/
│
├── src/main/java
│ └── pages/ → Page Object Model classes
│ └── utils/ → Driver setup and utilities
│
├── src/test/java
│ └── tests/ → TestNG test cases
│
├── sample-reports/ → Generated test reports (for showcase)
├── pom.xml → Maven dependencies
└── README.md


---

## 🧪 Test Scenarios Covered

### 1. Valid Login Test
- Enter valid email
- Click continue
- Verify successful navigation

### 2. Invalid Email Test
- Enter wrong email
- Validate error message like:
  - "Check"
  - "Invalid"
  - "Email required"

### 3. Empty Email Test
- Click continue without input
- Verify validation message

---

## ⚙️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/Nithishraja-10102000/Tichi-Automation.git
2. Navigate to Project
cd Tichi-Automation
3. Install Dependencies
mvn clean install
4. Run Tests
mvn clean test
📊 Reports

After execution, Extent Reports are generated at:

test-output/ExtentReport.html

This report includes:

Test execution status (Pass/Fail)
Step-by-step logs
Test summary
Execution time
Screenshots (if enabled)
📸 Sample Report

You can find sample reports inside:

sample-reports/
📌 Key Features

✔ Page Object Model (POM) structure
✔ Reusable WebDriver setup
✔ Dynamic XPath locators
✔ Explicit waits for React UI
✔ Clean test separation
✔ Extent HTML reporting
✔ Maven project structure

🚀 How to Run Tests (Simple)
mvn clean test
👨‍💻 Author

Nithish
QA Automation Engineer (Aspiring)

⭐ Future Improvements
Add screenshot on failure
Add CI/CD with GitHub Actions
Add parallel execution
Improve reporting with dashboards
Add more test scenarios (signup, profile, etc.)
📌 Note

This project is designed for QA Internship assignment submission and demonstrates real-world automation framework design using industry best practices.