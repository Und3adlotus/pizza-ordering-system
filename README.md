# pizza ordering system

This is the beginning of our full-stack pizza ordering website for CS492.  
We built the planning docs in the previous course, and now this repo is the actual working version of the app.

Right now we have a clean MVP up and running: Express server, EJS layouts, basic routing, and a simple UI skeleton. Nothing fancy yet, but the foundation is solid and everything loads without errors. We’ll build out features a sprint at a time.

---

## 🚀 Project Setup

### Requirements
- Node.js (v18+)
- npm

### Install dependencies
npm install

### Run the server in dev mode
npm run dev

Server runs at:
http://localhost:3000

## 📁 Project Structure
cowabunga-pizza/
  server.js
  package.json
  /routes
    web.js
    api.js
  /views
    layout.ejs
    index.ejs
    menu.ejs
    cart.ejs
    checkout.ejs
    404.ejs
    500.ejs
  /public
    /css
      styles.css
    /js
      main.js
    /img

- Express + EJS handles server-side rendering
- express-ejs-layouts gives us a shared layout template
- public/ holds all static assets
- routes/ contains all page and API logic

## 👥 Team Workflow
We’re using GitHub for version control.
Make sure to:
1. Pull before you start
git pull
2. Create a feature branch
git checkout -b feature/your-feature-name
3. Add commits, then push:
git push origin feature/your-feature-name
4. Open a Pull Request so changes stay clean.

Even if we’re a smaller team this term, the repo history will reflect solid work.
