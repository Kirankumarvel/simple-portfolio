
# 📘 Simple Portfolio Website – Git Practice Project

Welcome to the **Simple Portfolio Website**, a beginner-friendly project designed to help you practice and understand the basics of Git, including:

- Initializing a Git repository
- Adding files to the staging area
- Using `.gitignore` to exclude specific files and folders
- Committing changes cleanly

This mini-project simulates a basic personal portfolio site using HTML and CSS.

---

## 🚀 Project Structure

```
simple-portfolio/
├── index.html         # Basic homepage
├── style.css          # Styling for the homepage
├── scripts/app.js     # Basic JavaScript logging
├── images/            # (ignored) profile image or assets
├── debug.log          # (ignored) debug file example
├── notes.txt          # (ignored) internal notes
└── .gitignore         # Files/folders to exclude from Git
```

---

## 🛠️ How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/simple-portfolio.git
cd simple-portfolio
```

### 2. Initialize Git (if not already initialized)
```bash
git init
```

### 3. View Git Status
```bash
git status
```

### 4. Stage Files
```bash
git add index.html style.css
```

### 5. Ignore Unwanted Files
Edit the `.gitignore` file and add:
```
*.log
notes.txt
images/
```

### 6. Stage All Remaining Files (Respecting `.gitignore`)
```bash
git add .
```

### 7. Commit Changes
```bash
git commit -m "Initial commit with basic portfolio files"
```

---

## 📦 What You’ll Learn

- How to stage files for commits
- When and how to use `.gitignore`
- Difference between tracked, staged, and ignored files
- Clean commit practices for real-world projects

---

## ✨ Live Preview (Optional)

If you'd like to deploy this project:

- Use **GitHub Pages**
- Or connect it with **Netlify**, **Vercel**, etc.

---

## 🤝 Contributing

This is a learning project. Feel free to fork and expand:

- Add sections like **About**, **Contact**
- Improve the styling
- Add JS interactivity

---

## 📄 License

This project is released under the **MIT License**.
