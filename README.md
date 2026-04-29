# Portfolio

📁 Folder Structure
portfolio/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── Loader.jsx
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   ├── Skills.jsx
│   │   ├── Interactive3D.jsx
│   │   ├── Contact.jsx
│   │   ├── Footer.jsx
│   │   ├── CustomCursor.jsx
│   │   └── ParticleBackground.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── vite.config.js


🛠 Setup Instructions

# 1. Create project
npm create vite@latest portfolio -- --template react
cd portfolio

# 2. Install dependencies
npm install three @react-three/fiber @react-three/drei framer-motion react-icons react-tilt

# 3. Install Tailwind
npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p

# 4. Run
npm run dev
