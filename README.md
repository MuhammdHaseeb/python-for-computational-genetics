# 🐍 Python Learning Project

Welcome to my Python learning repository!  
This project is part of my journey to **master Python programming** from scratch, and it's designed to help **beginners** learn how to properly set up, manage, and run a Python project.

---

## 📌 About the Project

This repository contains:
- Sample Python codes and exercises
- A full guide to setting up a clean Python environment
- Instructions to manage packages using `pip`
- Best practices for using `requirements.txt` to track your dependencies

---

## 🚀 Features

- Beginner-friendly instructions  
- Python virtual environment setup  
- Easy package management  
- Reusable and shareable project setup  

---

## 🛠️ Step-by-Step Project Setup Guide

Follow this guide **exactly** to avoid errors and build your confidence.

---

### ✅ Step 1: Install Required Tools

Make sure you have the following installed on your system:

- ✅ **Python**: Programming language  
  👉 [Download Python](https://www.python.org/downloads/)

- ✅ **Visual Studio Code (VS Code)**: Code editor  
  👉 [Download VS Code](https://code.visualstudio.com/)

- ✅ **Git**: Version control to clone projects from GitHub  
  👉 [Download Git](https://git-scm.com/)

---

### 📥 Step 2: Clone This Repository (Download the Code)

1. Open **VS Code** or your **Terminal / Command Prompt**.
2. Navigate to the folder where you want to save the project.
3. Run this command (replace the link with your GitHub repo if needed):

\`\`\`bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
\`\`\`

---

### 🐍 Step 3: Create a Virtual Environment

This will isolate the project’s packages from the global system:

\`\`\`bash
python -m venv venv
\`\`\`

- It creates a folder called `venv` that stores all project-specific packages.

---

### ▶️ Step 4: Activate the Virtual Environment

This step **starts** the virtual Python environment.

- **Windows:**
  \`\`\`bash
  venv\\Scripts\\activate
  \`\`\`

- **macOS/Linux:**
  \`\`\`bash
  source venv/bin/activate
  \`\`\`

You’ll now see `(venv)` in your terminal — that means it's working.

---

### 📦 Step 5: Install Important Python Packages

Inside your virtual environment, install commonly used packages:

\`\`\`bash
pip install numpy pandas matplotlib biopython jupyter
\`\`\`

- `numpy` – numerical computing  
- `pandas` – data handling  
- `matplotlib` – plotting graphs  
- `biopython` – biological computations  
- `jupyter` – for notebooks

---

### 📄 Step 6: Save All Installed Packages

This will create a list of all the installed libraries and versions:

\`\`\`bash
pip freeze > requirements.txt
\`\`\`

- A file named `requirements.txt` will be created.
- This helps **recreate the same setup later**.

---

### 🔁 Step 7: Install from \`requirements.txt\` Later

If you (or someone else) want to install all packages again later:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

Then, everything will be installed automatically.

---

## Using a virtual environment and tracking dependencies helps you:
- Avoid version conflicts  
- Keep your system clean  
- Share your project easily  
- Reproduce your work later  
