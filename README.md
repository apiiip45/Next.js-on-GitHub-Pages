# ⚡ Next.js on GitHub Pages

> Deploy **dynamic Next.js apps** directly on **GitHub Pages** — no Vercel, no Netlify, no static-only hacks. Just push your code and click a few buttons.

![nextjs](https://img.shields.io/badge/Next.js-15+-000000?logo=nextdotjs&logoColor=white)
![github-pages](https://img.shields.io/badge/GitHub%20Pages-Live-222222?logo=github&logoColor=white)
![stars](https://img.shields.io/github/stars/scorchinghot/Next.js-on-GitHub-Pages?style=social)
![forks](https://img.shields.io/github/forks/scorchinghot/Next.js-on-GitHub-Pages?style=social)

---

## ✨ Why this repo?

Until now, most guides said you could **only deploy static Next.js sites** on GitHub Pages using `next export`.  
That meant **no SSR, no API routes, no real Next.js experience**.  
You had to push your code to GitHub, then deploy it on Vercel or Netlify. 🤦‍♂️

But guess what?  
> In 2025, GitHub added **native Next.js support with Actions + Pages**.  
That means you can host your **dynamic Next.js app** right here on GitHub.  

---

### 🧩 **How to use**

## 1. Create a Next.js app  
   Run the usual:
   ```bash
   npx create-next-app@latest
   ```
   Build your site, and commit your code.

## 2. Push to GitHub
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

## 3. Enable GitHub Pages

* Go to your repo on GitHub

* Navigate to Settings → Pages

* Under Source, choose GitHub Actions

## 4. Auto-generate workflow

* Just click Configure
  
* GitHub will suggest a Next.js workflow (deploy.yml) → then Commit changes
  
---
**✅ Done!**
GitHub Actions will now:

* ✅ Install dependencies

* ✅ Run next build

* ✅ Deploy your app automatically to GitHub Pages

Your site will be live at:
> https://your-username.github.io/<repo-name>/
(or at https://your-username.github.io/ if your repo is named username.github.io).
---   

## 🧪 Demo

This repo is a simple starter Next.js app with Tailwind CSS.
🔗 Live demo: [https://scorchinghot.github.io/Next.js-on-GitHub-Pages/](https://scorchinghot.github.io/Next.js-on-GitHub-Pages/)  

## 🎖️ Credits

- [Next.js](https://nextjs.org/)  
- [GitHub Pages](https://pages.github.com/) 

---

⭐ Drop a star, and let’s make it easier for everyone to deploy Next.js apps on GitHub Pages!
