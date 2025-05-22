 /
├── index.html                # Main HTML file
├── package.json             # Project dependencies
├── package-lock.json        # Dependency lock file
├── vite.config.ts           # Vite build & dev server config
├── tailwind.config.js       # Tailwind CSS customizations
├── postcss.config.js        # PostCSS setup
├── tsconfig.json            # Main TypeScript config
├── tsconfig.app.json        # TypeScript config for frontend app
├── tsconfig.node.json       # TypeScript config for backend Node.js
├── eslint.config.js         # ESLint rules and setup
├── src/
│   ├── backend/             # Express.js backend API code
│   ├── frontend/            # React + 3D components & pages
│   └── assets/              # Images, 3D models, etc.
└── .gitignore               # Files & folders excluded from git


⚙️ Installation & Setup
Prerequisites
Node.js (v16+)

npm or yarn

MongoDB (local or Atlas cloud)

Steps
Clone the repo:

bash
Copy code
git clone https://github.com/yourusername/3d-portfolio-mern.git
cd 3d-portfolio-mern
Install dependencies:

bash
Copy code
npm install
# or
yarn install
Create a .env file at root:

env
Copy code
MONGODB_URI=your_mongodb_connection_string
PORT=5000
Run development environment:

bash
Copy code
npm run dev
# or
yarn dev
Open the app:

Visit http://localhost:3000 to see your portfolio live locally.

