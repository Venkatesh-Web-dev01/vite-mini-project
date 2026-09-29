# React + Vite Starter Application

A fast, lightweight web application built using **React 18** and **Vite** with **Hot Module Replacement (HMR)** enabled.

---

## 🚀 Features

* **Vite Integration**: Instant server start and rapid HMR support.
* **React 18**: Built using the modern React `createRoot` API and `StrictMode`.
* **Interactive Counter**: Built-in state management example using `useState`.
* **Responsive Design**: Custom CSS styling supporting both light and dark themes based on system preferences.
* **Modern UI**: Smooth animations, SVG icon integrations, and custom layout styling.

---

## 🛠️ Built With

* [React](https://react.dev/) - UI Library
* [Vite](https://vite.dev/) - Next Generation Frontend Tooling
* CSS3 (Custom Variables & Media Queries)

---

## 📦 Getting Started

### Prerequisites

Ensure you have **Node.js** (v18 or higher) and npm installed.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name

.PORJECT STRUCTURE   
├── public/
│   └── icons.svg
├── src/
│   ├── assets/
│   │   ├── hero.png
│   │   ├── react.svg
│   │   └── vite.svg
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
└── package.json


graph TD
    A[index.html] -->|Loads script| B[src/main.jsx]
    B -->|Wraps with React.StrictMode| C[src/App.jsx]
    C -->|Styles| D[src/App.css]
    C -->|Imports| E[Assets & SVGs]
    
    subgraph Assets Folder
        E --> F[src/assets/react.svg]
        E --> G[src/assets/vite.svg]
        E --> H[src/assets/hero.png]
    end

    subgraph Component State
        C -->|useState| I[Interactive Counter]
    end
    
📦 Getting Started
Prerequisites
Ensure you have Node.js (v18 or higher) and npm (or pnpm) installed on your machine.

Installation & Local Setup
Clone the repository:

Bash
git clone https://github.com/Venkatesh-Web-dev01/vite-mini-project.git
cd vite-mini-project
Install dependencies:

Bash
npm install
# or if using pnpm
pnpm install
Start the development server:

Bash
npm run dev
# or
pnpm dev
Build for production:

Bash
npm run build
# or
pnpm build
