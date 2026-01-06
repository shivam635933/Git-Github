# Git & GitHub Learning Cheatsheets

This repository contains a hand picked and praticed collection of **Git and GitHub cheatsheets, quick references, and visual notes** which i used during my learning journey.
These resources are designed for **practice-oriented learning** — not production documentation.
---

## 📌 Who This Is For
- Beginners starting with **Git & GitHub**
- Visual learners who want interactive demonstrations
- Developers who want **quick command lookups**

## ❌ Who This Is Not For
- Advanced Git internals
- Enterprise workflow documentation
---

## 📂 Repository Contents

This folder includes multiple PDFs that explain Git concepts from different angles:
- **Cheatsheets** – Quick command references
- **Basic Definitions** – Git terminology explained
- **Visual Notes** – Diagrams that build intuition
- **GitHub Notes** – Remote repository workflows
- **GitLab Cheatsheet** – Platform comparison

Each file uses a slightly different explanation style — pick whichever suits you best.
---

## 🧠 How to Learn Git Effectively
Understanding Git happens fastest when you **see it and do it**, not when you only read about it.

### 1) Interactive Visualization
Practice with this visual Git simulator:

👉 https://learngitbranching.js.org/  
*Use this to observe what each command does step-by-step.*

**When to use:** Before trying commands in a real terminal.

### 2) Video Tutorials with Motion Graphics
Watch this animated Git walkthrough playlist:

👉 https://www.youtube.com/watch?v=k0DWmw1nYnM&list=PLfU9XN7w4tFzW200TaCP1W9RTE8jRSHU5&index=1  
*Visual learners: this shows how Git works under the hood with motion graphics.*

**When to use:**  
- When a concept feels abstract  
- After trying a concept interactively  
- To reinforce *why* Git behaves the way it does

---

## 📖 Suggested Practice Flow
Start here:

```bash
git init
git status
git add .
git commit -m "first commit"
git branch
git checkout -b feature
git merge
git log --oneline
```


## Extra tips for printing logs in somewhat visual-mode
- git log --all --topo-order --graph --show-signature
- git log --all --oneline --graph
- git log --oneline
