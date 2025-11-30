# Sheba Bondhu – README

A service management platform built using **JavaScript**, **Next.js**, following the **MVVM architecture**, **Airbnb JavaScript style guide**, and a structured documentation workflow.

---

## 🚀 Project Overview

Sheba Bondhu helps homeowners connect with service providers for both **on‑demand services** and **recurring service packages**. The platform focuses on clean UI, fast performance, and scalable architecture.

---

## 🛠️ Tech Stack

### **Frontend**

* **Next.js** (App Router)
* **JavaScript (ES6+)**


### **Architecture**

* **MVVM (Model‑View‑ViewModel)**

  * Model → API & data
  * View → UI components & pages
  * ViewModel → Logic, state, fetch handlers

### **Coding Standard**

* **Airbnb JavaScript Style Guide**


### **Documentation Tools**
* **JSDoc for code documentation**
* Markdown (.md) for README & Wiki
* Project wiki for UI, features, and flow
* Figma for UI designs

---

## 📦 Features
1. Service Listings  
2. Booking System  
3. Package Booking  
4. User Dashboard  
5. Provider Dashboard  
6. Review & Rating System  
7. Authentication (Login)  
8. Live Tracking of Service Providers  
9. Notifications & Real-time Chat  
10. Personal Profile Management (Homeowner & Service Provider)  

## 📁 Folder Structure (MVVM Friendly)

```
├── app/
│   ├── services/        # View + page rendering
│   ├── packages/        # Package UI
│   ├── dashboard/       # User & provider dashboards
│   └── api/             # API routes (Next.js)
│
├── components/
│   ├── views/           # UI components (View)
│   ├── viewmodels/      # Logic handlers (ViewModel)
│   └── shared/          # Buttons, cards, loaders
│
├── models/              # Data models
├── public/              # Images/icons
└── docs/                # Schemas, diagrams, wiki assets
```

---

## ▶️ Running the Project

### Install dependencies

```
npm install
```

### Start development server

```
npm run dev
```

### Lint the code

```
npm run lint
```

---
## 📝 JSDoc Usage

* Generate documentation for JavaScript code using *JSDoc*

```bash
# Install JSDoc globally
npm install -g jsdoc

# Navigate to project folder
cd shebabondhu-demo

# Add example JS file
mkdir src
echo "/** 
 * Adds two numbers together.
 * @param {number} a - First number
 * @param {number} b - Second number
 * @returns {number} Sum of a and b
 */ 
function sum(a, b) { return a + b; } 
module.exports = sum;" > src/sum.js

# Generate documentation in 'docs' folder
jsdoc src -d docs

# Open the docs/index.html in browser to view
## 🧪 Testing

* Unit Testing with **Jest**
```bash
# Create project folder and navigate
mkdir shebabondhu-demo
cd shebabondhu-demo

# Initialize npm
npm init -y

# Install Jest
npm install --save-dev jest

# Create src folder and example test files
mkdir src
echo "function sum(a, b) { return a + b; } module.exports = sum;" > src/sum.js
echo "const sum = require('./sum'); test('adds 1 + 2 to equal 3', () => { expect(sum(1,2)).toBe(3); });" > src/sum.test.js

# Add test script in package.json
# "scripts": {
#     "test": "jest"
# }

# Run tests
npm test
---

## 🧱 Contribution Guidelines

* Follow Airbnb JS Style
* Write meaningful commit messages
* Use PR branch naming:

  * `feature/ui-service-cards`
  * `fix/dashboard-bug`
  * `docs/readme-update`
* Update wiki if UI changes

---

## 📘 Documentation

Full documentation is available in the **Wiki** including:

* UI Pages
* Use Case Diagrams
* DB Schema
* System Flow

---

## 📄 License

MIT License (or add later)

---

## 👨‍💻 Contributors

* Project team contributors listed in GitHub Insights.
