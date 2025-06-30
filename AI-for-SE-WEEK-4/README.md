# 🚀 Team Collaboration Guide

## Hey Team! 👋

Welcome to our project! I've put together this guide to help everyone collaborate smoothly on our GitHub repository. Please take a few minutes to read through this — it'll save us all time and prevent headaches down the road.

---

## 📌 **🚨 WEEKLY TASK REMINDER 🚨**

### ✅ **Choose Your Preferred IDE (Jupyter Notebook Strongly Recommended)**

> You are free to use any IDE you're comfortable with, **BUT** we **strongly recommend using [Jupyter Notebook](https://jupyter.org/)** for this project.
> It’s especially helpful for **data science tasks** involving `.ipynb` files, data exploration, and cell-based experimentation.

---

### 👥 **For Those Working in Pairs or Teams:**

> ✅ **All pull requests must be reviewed by your code partner(s)** before merging.

> ⚠️ **Never approve your own pull request!**
> Every PR **must be reviewed and approved by another contributor** to ensure:
>
> * Code readability
> * Functional correctness
> * Smooth integration across the whole team

> This ensures **accountability** and prevents merge issues.

---

## ✅ Before You Begin...

Make sure you have:

* Git installed on your machine → [Download Git](https://git-scm.com)
* Access to our GitHub repository (DM if not)
* Basic Git knowledge (this guide covers what you need)
* **Python and Jupyter Notebook** installed:

```bash
pip install notebook
```

---

## 💻 Using Jupyter Notebooks (Without VS Code)

### 1. After Cloning the Repository:

```bash
cd repository-name
```

### 2. Check for the Notebook:

```bash
ls *.ipynb  # On Linux/Mac
dir *.ipynb # On Windows
```

### 3. Launch Jupyter:

```bash
jupyter notebook
```

Your browser will open the notebook interface.

### 4. Open, Edit & Save:

* Make your edits in the notebook
* Press `Ctrl + S` or use `File > Save and Checkpoint`

### 5. Stop the Server:

* Close your browser
* In terminal: `Ctrl + C`

### 6. Commit & Push Changes:

```bash
git add filename.ipynb
git commit -m "Update notebook with [your changes]"
git push origin your-branch-name
```

> ❗ **Always pull from `main` before starting any work!**
>
> ❗ **Never edit the same cell as your teammate to avoid conflicts.**

---

## 🧩 Our GitHub Workflow — Follow These Steps!

### Step 1: Clone the Repo

```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

### Step 2: Always Pull Latest Main

```bash
git checkout main
git pull origin main
```

### Step 3: Create a Feature Branch

```bash
git checkout -b feature/your-task-name
```

### Step 4: Do Your Work

Edit the notebook or Python code.

### Step 5: Save and Commit

```bash
git add .
git commit -m "Implement feature X"
```

### Step 6: Push Your Code

```bash
git push origin feature/your-task-name
```

### Step 7: Create a Pull Request

Go to GitHub and:

* Click **"Compare & Pull Request"**
* Fill in the title, description, and what was done
* Tag your **code partner for review**

### ✅ **Step 8: Wait for Code Review**

> 🧑‍🤝‍🧑 **Your teammate must review and approve your PR.**
> 🔒 **DO NOT approve your own PR.**

After receiving approval:

```bash
git checkout main
git pull origin main
git branch -d feature/your-task-name
git push origin --delete feature/your-task-name
```

---

## 🛑 Team Rules - Must Follow

❌ **DON'T:**

* Push directly to `main`
* Use `--force` on shared branches
* Commit API keys or secrets
* Approve your own PR

✅ **DO:**

* Work only on your own branches
* Always `git pull origin main` before editing
* Write **clear commit messages**
* Run and test code before pushing
* Get **at least one approval** before merging

---

## 🛠️ Helpful Git Commands

```bash
git status
git checkout branch-name
git branch -a
git log --oneline
git reset --soft HEAD~1
```

### 🔧 Merge Conflict Resolution

```bash
git checkout main
git pull origin main
git checkout your-branch
git merge main
# Resolve conflicts
git add .
git commit -m "Fix merge conflicts"
git push origin your-branch
```

---

## 🤝 If You Forked the Repo

```bash
git remote add upstream https://github.com/original-owner/repository-name.git
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

---

## 🧠 Quick Git + Jupyter Flow Recap

```bash
git checkout main
git pull origin main
git checkout -b feature/your-change
jupyter notebook
# Make changes
git add notebook.ipynb
git commit -m "Describe your update"
git push origin feature/your-change
```

---

## 🆘 Need Help?

* DM me directly ✅
* Open a GitHub Issue 📌
* Ask in our group chat 💬

---

### 👏 Final Thoughts

Thanks for reading this guide! Following the process will keep our project organized and collaborative. Let’s support each other and **ship quality code together 🚀**

> 🧠 *Remember: This project is a learning opportunity — let’s make it smooth and fun!*

---

