
# 🌐 Static Website Deployment using GitHub Pages

This guide explains how to deploy a static HTML + CSS website using **GitHub Pages**, **Visual Studio Code**, and **Git**.

---

## ✅ Objective

Host a static website for free by pushing your HTML and CSS files to a GitHub repository named:

```
https://github.com/Premsagariith/prem27.github.io
```

Once done, your site will be live at:

```
https://premsagariith.github.io/prem27.github.io/
```

---

## 🔧 Tools Required

- GitHub Account
- Visual Studio Code (VS Code)
- Git installed on your system
- Static website files (`index.html`, `style.css`, etc.)

---


Both files must be in the **root directory** of your project (not inside a subfolder).

---

## 🪜 Step-by-Step Process

### 🔹 Step 1: Create a GitHub Repository

1. Go to [https://github.com](https://github.com)
2. Click on `+ > New repository`
3. Set the repository name to:
   ```
   your-username.github.io
   ```
4. Choose:
   - Public repository
   - Do NOT initialize with README, .gitignore, or license
5. Click **Create repository**

---

### 🔹 Step 2: Prepare Files in VS Code

1. Open **VS Code**
2. Go to `File > Open Folder` and choose your website folder
3. Add your website files:
   - `index.html`
   - `style.css`


git init
git remote add origin https://github.com/your-username/your-username.github.io
git branch -M main
git add .
git commit -m "Initial commit"
git push -u origin main
```

---

### 🔹 Step 4: Enable GitHub Pages

1. Go to your GitHub repository
2. Click **Settings > Pages**
3. Under **Source**, choose:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

---

### 🔹 Step 5: View Live Website

After 1–2 minutes, your website will be live at:

```
https://your-username.github.io
```

---

## 🔁 To Update Your Website

1. Make changes in VS Code
2. Run the following in terminal:

```bash
git add .
git commit -m "Update website"
git push
```

---

## 🛠️ Troubleshooting

- ✅ Ensure file names are lowercase and correctly linked
- ✅ CSS link in HTML must be:
  ```html
  <link rel="stylesheet" href="style.css" />
  ```
- 🔄 Force refresh browser with `Ctrl + Shift + R`
- 🔍 Check GitHub Pages is using the `main` branch and root folder

---

## 📄 Credits

This project was created and deployed as part of a web development learning task using GitHub Pages and VS Code.
