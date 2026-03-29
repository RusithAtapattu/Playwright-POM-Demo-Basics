# Playwright Automation with Page Object Model (POM)

This repository demonstrates **Playwright automation using the Page Object Model (POM)**. It covers setup, writing and running tests, locating web elements, performing assertions, and using Playwright features like **Trace Viewer, slow motion execution, video recording, hooks, and tags**. A **demo login test** is included to illustrate how to structure automation code for better **maintainability and scalability**.

---

## 📌 Topics Covered

- What is Playwright
- Installing Playwright
- Running Playwright tests
- Writing your first test
- Recording tests
- Locating web elements
- Assertions
- Demo login test
- Trace Viewer
- Slow motion execution
- Video recording
- Hooks & Groups
- Annotations & Tags
- Page Object Model (POM)

---

## 🛠 Technologies Used

- **Playwright**  
- **Java / JavaScript / TypeScript** (depending on implementation)  
- **TestNG**  
- **Maven / Node.js** (for dependencies)  

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/playwright-pom-demo.git
cd playwright-pom-demo
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Install Playwright browsers
```bash
npx playwright install
```

---

## ▶️ Running Tests

Run all tests:
```bash
npx playwright test
```

Run tests in headed mode:
```bash
npx playwright test --headed
```

Run tests with slow motion:
```bash
npx playwright test --headed --slow-mo=1000
```

---

## 🔍 Viewing Test Trace

```bash
npx playwright show-trace trace.zip
```
Trace Viewer allows you to debug tests by showing **actions, network requests, console logs, and screenshots**.

---

## 📂 Project Structure

```
playwright-pom-demo
│
├── tests
│   └── loginTest.spec.js
│
├── pages
│   └── LoginPage.js
│
├── playwright.config.js
│
└── package.json
```

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## ⭐ If you found this helpful

Give the repository a ⭐ to support the project and help others find it.
