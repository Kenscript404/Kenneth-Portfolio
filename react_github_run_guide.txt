React.js GitHub Source Code Run Guide

Step 1: Install prerequisites
- Node.js (LTS version recommended) → https://nodejs.org
- npm (comes with Node.js)
- Optional: Git if you want to clone repo → https://git-scm.com

Check installation:
```
node -v
npm -v
git --version
```

Step 2: Get the project
Option A: Clone repo
```
git clone https://github.com/USERNAME/REPO.git
cd REPO
```

Option B: Download ZIP
- Go to GitHub → Code → Download ZIP
- Unzip to a folder
- Open terminal inside that folder:
```
cd path\to\unzipped-folder
```

Step 3: Install dependencies
```
npm install
```

Step 4: Start development server
```
npm start
```
- Opens default browser at http://localhost:3000
- Hot-reload enabled: changes reflect automatically

Step 5: Build for production (optional)
```
npm run build
```
- Creates optimized build in `build/` folder
- Serve production build:
```
npm install -g serve
serve -s build -l 3000
```

Step 6: Common notes
- Ensure `package.json` exists in project root
- Run all commands inside project folder
- Hot-reload works automatically on `npm start`
- Production build (`npm run build`) is for deployment/testing

---

Cheat Sheet Summary:
1. Install Node.js & npm
2. Get project (clone/download)
3. `npm install`
4. `npm start` (dev server)
5. `npm run build` (production, optional)
6. `serve -s build -l 3000` (optional)