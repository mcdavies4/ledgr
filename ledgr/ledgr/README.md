# ⚡ Ledgr — Personal & Business Finance Tracker

A simple, unified finance tracker built for freelancers and small business owners.

---

## 🚀 Getting Started (Local Development)

### Step 1 — Install prerequisites (one time only)
- [Node.js](https://nodejs.org) — download and install the LTS version
- [Git](https://git-scm.com) — download and install
- [VS Code](https://code.visualstudio.com) — your code editor

### Step 2 — Open the project
1. Open **VS Code**
2. Go to **File → Open Folder** and select this `ledgr` folder

### Step 3 — Install dependencies
Open the terminal in VS Code (`Ctrl + `` ` on Windows / `Cmd + `` ` on Mac) and run:
```
npm install
```

### Step 4 — Run the app locally
```
npm start
```
Your browser will open at `http://localhost:3000` automatically.

---

## 📦 Deploy to the Internet (Vercel — Free)

### Option A: Deploy via GitHub (recommended)

1. Create a free account at [github.com](https://github.com)
2. Create a new repository called `ledgr`
3. In VS Code terminal, run:
```
git init
git add .
git commit -m "Initial commit — Ledgr MVP"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ledgr.git
git push -u origin main
```
4. Go to [vercel.com](https://vercel.com) → **New Project**
5. Connect your GitHub account and select the `ledgr` repo
6. Click **Deploy** — your app goes live in ~60 seconds ✅

### Option B: Deploy directly from terminal
```
npm install -g vercel
vercel
```
Follow the prompts — done.

---

## 📁 Project Structure

```
ledgr/
├── public/
│   └── index.html          # App shell
├── src/
│   ├── index.js            # Entry point
│   └── App.js              # Main app (all components)
├── .gitignore
├── package.json            # Dependencies & scripts
└── README.md               # This file
```

---

## ✨ Features (V1)

- **Dashboard** — income, pending, overdue, expenses, net profit at a glance
- **Invoices** — track client invoices, mark paid, add new ones
- **Expenses** — log personal and business expenses by category
- **Alerts** — payment reminders with urgency indicators
- **Business / Personal filter** — toggle the view across all sections

---

## 🔮 Roadmap (Coming Soon)

- [ ] Data persistence (localStorage / database)
- [ ] PDF invoice generator
- [ ] CSV export
- [ ] Monthly trend charts
- [ ] Email/SMS payment reminders
- [ ] Bank sync via Plaid

---

Built with React. Designed for freelancers.
