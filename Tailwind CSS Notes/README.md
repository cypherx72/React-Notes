# Tailwind CSS: From Zero to Production Notes

📺 **Based on the video series**:  
[![Thumbnail](https://img.youtube.com/vi/elgqxmdVms8/0.jpg)](https://www.youtube.com/watch?v=elgqxmdVms8&list=PL5f_mz_zU5eXWYDXHUDOLBE0scnuJofO0)

## ⚠️ Disclaimer
These notes were created while following the **"Tailwind CSS: From Zero to Production"** tutorial series by Tailwind Labs. 

While core concepts remain valid, some details may be outdated because:
- Tailwind CSS has released new versions since recording
- Best practices evolve over time
- Tooling integrations (Vite, PostCSS) may have changed

**Always refer to the official documentation for the latest information**:  
👉 [tailwindcss.com/docs](https://tailwindcss.com/docs)

---

## 📖 Contents
1. [Setup](#1-setup)  
2. [Utility-First Workflow](#2-utility-first-workflow)  
3. [Responsive Design](#3-responsive-design)  
..... *(all your sections)*  

---

## 🛠️ Project Setup

```bash
# Original tutorial used:
npm install -D tailwindcss@2.x postcss autoprefixer

# Current recommendation (v3.4+):
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init