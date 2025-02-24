# 📌 Project Setup & Usage Guide

## 🛠️ Pre-requirements
To run this project, you need to have **Node.js** and **npm** installed.

> I used **Node.js v18.15.0** and **npm v9.5.0**. I recommend using the same or later versions for compatibility.

You can check your installed versions by running:
```sh
node -v
npm -v
```

If you need to install Node.js, visit [nodejs.org](https://nodejs.org/).

---

## 📥 Installation
Run the following command to install the necessary dependencies:
```sh
npm install
```
Or, for the short version:
```sh
npm i
```

---

## 🧪 Running Tests

### 🔹 **Important:**
Before running the tests, create a copy of the `cypress.env.example.json` file and rename it to `cypress.env.json`.

```sh
cp cypress.env.example.json cypress.env.json
```

In a real-world scenario, this file would be updated with **valid credentials**.

> ⚠️ The `cypress.env.json` file is included in `.gitignore`, ensuring that confidential information is not versioned.

### 🏃 Running Tests in Headless Mode
```sh
npm test
```
Or, for the short version:
```sh
npm t
```

### 🎭 Running Cypress in Interactive Mode
```sh
npm run cy:open
```
This will open the **Cypress Test Runner**, allowing you to run tests manually.

---

🚀 **Happy coding!** 🎉




