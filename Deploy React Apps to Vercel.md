# Complete Beginner’s Guide to Building, Running & Deploying a React App in 2025  
**Your one-stop markdown resource – bookmark this!**  
Created especially for total newbies by a friendly full-stack dev 🚀

---

## 1. First, Understand the Big Picture (Watch These First!)

| Topic                        | Video (Super Short & Clear)                                      | Why Watch It |
|------------------------------|------------------------------------------------------------------|-------------|
| How the Internet Works       | [How the Web Works in 7 min](https://www.youtube.com/watch?v=7_LPdttKXPc) | Understand browsers ↔ servers |
| What is React?               | [React in 100 Seconds](https://www.youtube.com/watch?v=Tn6-PIqc4UM) → then [React Crash Course 2025 – 1 hour](https://www.youtube.com/watch?v=Lcw7i2W4gty) (Net Ninja) | Learn why React is awesome |

---

## 2. Tools You Need (All Free)

| Tool                | Download / Link                                                        | Purpose |
|---------------------|------------------------------------------------------------------------|-------|
| Node.js (LTS)       | https://nodejs.org                                                     | Runs JavaScript on your computer |
| Visual Studio Code  | https://code.visualstudio.com/                                         | Best code editor |
| GitHub Account      | https://github.com                                                     | Stores & versions your code |
| Git (comes with GitHub Desktop or Git for Windows) | https://git-scm.com/                              | Version control |

**Recommended VS Code Extensions** (search inside VS Code → Extensions):
- ES7+ React/Redux/React-Native snippets
- Prettier – Code formatter
- GitLens
- Live Server (to preview built app locally)

---

## 3. Create Your First React App (2025 Way – Vite is the new standard)

### Official Docs
- Vite + React: https://vitejs.dev/guide/#scaffolding

### Best Video (10 minutes)
- [React + Vite in 10 minutes (2025)](https://www.youtube.com/watch?v=MRfguK2a5LU) – Programming with Mosh

### Terminal Commands (copy-paste)
```bash
npm create vite@latest my-react-app -- --template react
cd my-react-app
npm install
npm run dev
```
→ Opens http://localhost:5173 automatically 🎉

---

## 4. Version Control with Git & GitHub (Never lose your code!)

### Best Beginner Video (1 hour – worth every minute)
- [Git & GitHub Crash Course 2025](https://www.youtube.com/watch?v=RGOj5yH7evk) – freeCodeCamp

### Quick Steps (after creating repo on GitHub – no README)
Create your github repo
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin main
```

VS Code makes this even easier – just use the Source Control panel!

---

## 5. Deploy & Host for FREE (Live URL in minutes!)

### Option 1 – Vercel (Recommended & Fastest)
- Docs: https://vercel.com/docs
- 4-min Video: https://www.youtube.com/watch?v=9L4WNj8nqM
- Steps: Sign in with GitHub → Import repo → Deploy (zero config!)

### Option 2 – Netlify (Also Excellent)

#### Correct Settings for Vite + React (copy these!)
| Field                | Value                  | Notes |
|----------------------|------------------------|-------|
| Branch to deploy     | `main`                 |       |
| Base directory       | *(leave blank)*        | Your project is at the root |
| Build command        | `npm run build`        |       |
| Publish directory    | `dist`                 | Vite outputs here |
| Functions directory  | *(leave blank)*        | Only needed later for backend |

Netlify Tutorial: https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/

---

## 6. Test Your Build Locally (Do This Before Deploying!)

In VS Code terminal:
```bash
npm run build
```
→ Creates a `dist` folder with your final website files  
→ Right-click `dist/index.html` → “Open with Live Server” (install the extension first)

---

## 7. Bonus: Easy Database When You’re Ready (Free & Beginner-Friendly)

| Service   | Why It’s Perfect for Newbies                     | Crash Course Video |
|-----------|--------------------------------------------------|----------------------|
| Supabase  | Free PostgreSQL + Auth + Storage + nice dashboard | [Supabase in 20 min](https://www.youtube.com/watch?v=6x3J8pNAkJ4) |

---

## Your 7-Day Learning Roadmap (Copy-Paste This Plan)

1. [ ] Watch “How the Web Works” + “React Crash Course”
2. [ ] Install Node.js + VS Code
3. [ ] Create Vite React app & run locally
4. [ ] Learn Git & GitHub (1-hour video)
5. [ ] Push code to GitHub
6. [ ] Deploy on Vercel or Netlify
7. [ ] Share your live URL & celebrate! 🎉

You now have a complete, professional React workflow – exactly what real developers use in 2025.

Save this file as `react-beginner-guide-2025.md` and keep it in your project folder!

When your site is live, reply with the URL and I’ll help you add login, a database, or anything else you want. You’ve got this! 💪
```
