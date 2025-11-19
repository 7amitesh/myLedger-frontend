
# 📘 myLedger – Billing & Inventory Frontend (Figma → Web)

A responsive billing and inventory management frontend built using **React.js, TypeScript, and Tailwind CSS**, inspired by SME workflows similar to **myBillBook**.  
This project demonstrates **Figma-to-UI conversion**, **component-driven architecture**, and **REST API integration** — making it ideal for modern business dashboards.

---

## 🚀 Features

### 🎨 **Figma → Pixel-Perfect UI**
- Converted Figma mockups into clean, responsive web interfaces.
- Consistent spacing, typography, and layout across all screens.

### 🔧 **Reusable UI Components**
- Invoice Cards  
- Product Table  
- Customer Cards  
- Sidebar Navigation  
- Status Badges  
- Loader & Empty States  

### 🌐 **REST API Integration**
- Integrated mock REST API for invoices, products, and customers.
- Supports real-time UI updates and structured API-driven workflows.

### 📱 **Responsive UI**
- Mobile-first layouts  
- Tablet optimized components  
- Desktop dashboard view  

### ⚙️ **Frontend Architecture**
- Modular folder structure  
- Component-based design  
- State management using React hooks  
- Custom `useFetch` hook for API loading  
- Utility functions for date/currency formatting  

---

## 🧱 Tech Stack

| Category | Technologies |
|---------|--------------|
| **Framework** | React.js + TypeScript |
| **UI Styling** | Tailwind CSS |
| **Routing** | React Router |
| **Data** | Mock REST APIs (JSON) |
| **Development** | Vite / npm |
| **Tools** | VS Code, Chrome DevTools, GitHub |

---

## 📂 Project Structure

```

myLedger-frontend/
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── hooks/
│   ├── utils/
│   ├── mock-api/
│   ├── App.tsx
│   └── main.tsx
│
├── package.json
├── README.md
└── tsconfig.json

````

---

## 🗂 Mock API Structure

Example: `mock-api/invoices.json`

```json
[
  {
    "id": "INV-001",
    "customer": "Rahul Sharma",
    "amount": 12500,
    "status": "Paid",
    "date": "2025-10-12"
  }
]
````

---

## 🖼 Screenshots (Add After Upload)

Add screenshots in a `/screenshots` folder:

* `dashboard.png`
* `invoices.png`
* `products.png`
* `customers.png`

And link them:

```markdown
## 🖼 UI Preview

![Dashboard](./screenshots/dashboard.png)
![Invoices Page](./screenshots/invoices.png)
```

---

## 🏗 Setup Instructions

```bash
# Clone repo
git clone https://github.com/7amitesh/myLedger-frontend

# Navigate
cd myLedger-frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

---

## 📌 Why This Project?

This project shows:

* Strong frontend skills
* Figma → Code ability
* Responsive UI
* Dashboard experience
* Component design thinking
* REST API consumption
* TypeScript mastery

Essential skills for **Frontend Intern roles**, especially at companies like **FloBiz** that build billing & inventory platforms.

---

## 🙌 Author

**Amitesh Kumar**
Frontend Developer | React | TypeScript | UI Engineering
🔗 GitHub: [https://github.com/7amitesh](https://github.com/7amitesh)
🔗 LinkedIn: [https://www.linkedin.com/in/amitesh-k/](https://www.linkedin.com/in/amitesh-k/)

---


