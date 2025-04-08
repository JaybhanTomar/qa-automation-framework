# QA Automation Framework

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
