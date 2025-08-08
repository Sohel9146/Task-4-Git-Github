# 🚀 Task 4 – Git & GitHub Version-Controlled Project

## 📌 About
This project is part of my **DevOps Internship – Task 4** to learn and demonstrate Git & GitHub best practices.  
It includes:
- A simple HTML & CSS homepage
- Multiple branch workflow
- Pull Requests & merging
- Merge conflict creation & resolution
- Adding tags for version control

---

## 🎯 Features
- 🌐 Responsive, modern HTML homepage
- 🎨 Attractive CSS with gradient & glassmorphism effect
- 🔀 Branching strategy (`main`, `dev`, `feature`)
- ⚔ Merge conflict handling in GitHub
- 🏷 Tagging releases for milestones

---

## 🗂 Project Structure
```
├── screenshots/       # Screenshots
|   ├──Branches.png
|   ├──Conflict Resolved.png
|   ├──Dev Pull Requests.png
|   ├──Homepage.png
|   ├──No Conflict While Mrging.png
|   ├──Tags.png
|   ├──The Merge Conflict.png
├── index.html       # Homepage
├── style.css        # Stylesheet
├── .gitignore       # Ignored files
└── README.md        # Documentation
```

---

## 📷 Screenshots

### 1️⃣ Final Homepage
![Homepage](https://github.com/Sohel9146/Task-4-Git-Github/blob/main/screenshots/Homepage.png?raw=true)

### 2️⃣ Branches
![Branches](https://github.com/Sohel9146/Task-4-Git-Github/blob/main/screenshots/Branches.png?raw=true)

### 3️⃣ Pull Request from dev
![Dev Pull Request](https://github.com/Sohel9146/Task-4-Git-Github/blob/main/screenshots/dev%20Pull%20Requests.png?raw=true)

### 4️⃣ Merge Conflict Encountered
![Merge Conflict](https://github.com/Sohel9146/Task-4-Git-Github/blob/main/screenshots/The%20Merge%20Conflict.png?raw=true)

### 5️⃣ Conflict Resolved
![Conflict Resolved](https://github.com/Sohel9146/Task-4-Git-Github/blob/main/screenshots/Conflict%20Resolved.png?raw=true)

### 6️⃣ No Conflicts While Merging
![No Conflicts](https://github.com/Sohel9146/Task-4-Git-Github/blob/main/screenshots/No%20Conflicts%20While%20Merging.png?raw=true)

### 8️⃣ Tags Created
![Tags](https://github.com/Sohel9146/Task-4-Git-Github/blob/main/screenshots/Tags.png?raw=true)

---

## ⚙️ Git Process Followed

### 1️⃣ Initialize Repo & First Commit
```bash
git init
git add .
git commit -m "Initial commit with HTML homepage"
```

### 2️⃣ Create .gitignore
```bash
# for Example
echo "node_modules/" >> .gitignore
echo "*.log" >> .gitignore
```

### 3️⃣ Create Branches
```bash
git checkout -b dev
git checkout -b feature
```

### 4️⃣ Push to GitHub
```bash
git remote add origin https://github.com/Sohel9146/Task-4-Git_Github.git
git branch -M main
git push -u origin main
```

### 5️⃣ Feature Work & PR
- Work done in `feature` branch  
- Pushed changes → PR to `feature` → PR to `main`

### 6️⃣ Creating Merge Conflict
- Edited the **same line** in `main` and `feature` differently  
- PR from `feature` to `main` triggered conflict

### 7️⃣ Resolving Merge Conflict
- Used GitHub Web Editor → Removed conflict markers → Kept final version

### 8️⃣ Adding Tags
```bash
git tag -a v1.0 -m "First stable version with HTML & CSS homepage"
git push origin v1.0
```

---

## 🏷 Tags
- **v1.0** → First stable release

---

## 🧠 Learning Outcomes
Through this task, I learned:
- Proper Git branching strategy
- How to create and merge PRs
- Resolving merge conflicts in GitHub
- Tagging releases
- Maintaining clear documentation

---

## 👤 Author
**Sohel Shaikh**  
📧 Email: suhailshaikh7866@gmail.com  
🔗 [Naukri](https://www.naukri.com/mnjuser/profile) | [GitHub](https://github.com/Sohel9146)
