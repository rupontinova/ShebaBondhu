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

## 🧪 Testing

* Unit Testing with **Jest**

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
