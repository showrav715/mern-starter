# Developer 715

A full-stack project framework combining a Node.js backend and React frontend with modular CLI support.

---

## 🚀 Installation

To create a new project using **Developer 715**, run:

```bash
# Using npm
npx Developer715@latest

# Using Yarn
yarn exec Developer715


# Start backend (runs on port 3000)
npm run node

# Start full stack (frontend + backend on port 3001)
npm run dev

# Using Yarn
yarn run node
yarn run dev


npm run create:model YourModelName
# or
yarn run create:model YourModelName


npm run create:middleware YourMiddlewareName
# or
yarn run create:middleware YourMiddlewareName


npm run create:page YourPageName
# or
yarn run create:page YourPageName


npm run create:component YourComponentName
# or
yarn run create:component YourComponentName


npm run create:loader YourLoaderName
# or
yarn run create:loader YourLoaderName


npm run create:layout YourLayoutName
# or
yarn run create:layout YourLayoutName


Developer715/
│
├── app/                                 # Main application code
│   ├── config/                          # Configuration files
│   ├── controllers/                     # Controller logic
│   ├── middlewares/                    # Middleware logic
│   ├── models/                          # Database models
│   ├── storage/                         # File storage
│   ├── utility/                         # Utility functions
│   ├── dist/                            # Build output
│   ├── node_modules/                    # Installed packages
│   ├── public/                          # Static assets
│   ├── routes/                          # App routing
│   ├── views/                           # Frontend components and views
│   │   ├── assets/css/                  # CSS styling
│   │   ├── components/                  # Reusable components
│   │   ├── layout/                      # Layout templates
│   │   ├── loader/                      # Loading UI components
│   │   ├── pages/                       # Page-level components
│   │   └── main.jsx                     # Frontend entry point
│
├── .gitattributes
├── .gitignore
├── app.js                               # Backend entry point
├── index.html                           # Base HTML
├── LICENSE
├── package.json                         # Project metadata
├── package-lock.json                    # Locked dependencies
├── postcss.config.js                    # PostCSS configuration
├── tailwind.config.js                   # Tailwind CSS setup
├── vite.config.js                       # Vite configuration
├── README.md                            # Project documentation
