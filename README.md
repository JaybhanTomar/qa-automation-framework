# QA Automation Framework
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF6C37?style=for-the-badge)
![REST Assured](https://img.shields.io/badge/REST--Assured-009688?style=for-the-badge)
![JDBC](https://img.shields.io/badge/JDBC-007396?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

![GitHub Repo stars](https://img.shields.io/github/stars/JaybhanTomar/qa-automation-framework?style=social)
![GitHub forks](https://img.shields.io/github/forks/JaybhanTomar/qa-automation-framework?style=social)

A powerful end-to-end automation framework built with **Selenium**, **TestNG**, **REST Assured**, and **JDBC**.  
Designed for real-world testing needs including **API validation**, **UI automation**, and **database verification** — all in one flow.

---

## 🚀 Features

- **Modular framework** with Page Object Model (POM)
- **API testing** with dynamic data extraction (e.g. `convoUid`)
- **Database validation** using JDBC
- **Reusable utilities** for clean, maintainable code
- **Integrated with Maven** for easy dependency management
- **Cross-browser ready** (currently Chrome)

---

## 🛠 Tech Stack

- Java (Core)
- Selenium WebDriver
- TestNG
- REST Assured (API Testing)
- MySQL + JDBC (DB Validation)
- Maven

---

## 📁 Folder Structure

```
qa-automation-framework/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── base/           # BaseTest setup
│   │       ├── api/            # API client using RestAssured
│   │       └── utils/          # DB utilities
│   └── test/
│       └── java/
│           └── tests/          # End-to-end test logic
│
├── pom.xml                    # Maven dependencies
└── README.md
```

---

## ✅ How to Run

1. Clone the repo:

```bash
git clone https://github.com/JaybhanTomar/qa-automation-framework.git
cd qa-automation-framework
```

2. Update DB credentials in `DBUtils.java`:

```java
private static final String USER = "your_mysql_user";
private static final String PASSWORD = "your_mysql_password";
```

3. Run tests via TestNG from Eclipse or command line.

---

## ✨ Sample Flow

- Trigger API ➡️ Capture `convoUid` ➡️ Query DB ➡️ Assert result ➕ Log details

---

## 📬 Contact

Want custom automation services or freelance collaboration?

- **Email:** [Jaybhantomar@gmail.com](mailto:Jaybhantomar@gmail.com)  
- **LinkedIn:** [View Profile](https://www.linkedin.com/public-profile/settings)

---

## ⭐️ Like This Project?

Leave a ⭐️ if this repo helped you or inspired your own framework!
