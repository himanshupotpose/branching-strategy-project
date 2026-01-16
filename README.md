# 📘 Branching Strategy – Standard Operating Procedure (SOP)

## 📌 Purpose
This document defines the standard branching strategy to be followed in this project to ensure smooth development and collaboration.

---

## 🌿 Branch Types

### 🔹 main
- Contains production-ready code  
- Only stable and tested code is merged here  
- Direct commits are not allowed  

### 🔹 develop
- Used for active development  
- All feature and bugfix branches are merged here  

### 🔹 feature/*
- Used for new feature development  
- Created from: `develop`  
- Merged into: `develop`  
- Example: `feature/login`, `feature/dashboard`

### 🔹 bugfix/*
- Used to fix bugs found during development  
- Created from: `develop`  
- Merged into: `develop`  
- Example: `bugfix/header-issue`

### 🔹 release/*
- Used to prepare code for production release  
- Created from: `develop`  
- Merged into: `main` and `develop`  
- Example: `release/v1.0.0`

### 🔹 hotfix/*
- Used to fix critical production issues  
- Created from: `main`  
- Merged into: `main` and `develop`  
- Example: `hotfix/payment-fix`

---

## 🔁 Workflow

1. Create a feature or bugfix branch from `develop`
2. Make code changes and commit
3. Push branch to remote repository
4. Create a Pull Request (PR)
5. Get code review and approval
6. Merge PR into `develop`
7. Delete branch after successful merge

---

## 📝 Commit Guidelines
- Use clear and meaningful commit messages  
- Example: `Add login API`, `Fix navbar alignment`

---

## 👥 Responsibilities
- **Developer**: Create branch, write code, raise PR  
- **Reviewer**: Review code and approve PR  
- **Lead**: Merge to main and handle releases  

---

## 📦 Versioning
Follow Semantic Versioning: `MAJOR.MINOR.PATCH`  
Example: `v1.2.0`


---

## 👤 Author

**Himanshu Potpose**  
DevOps Engineer | AWS | Git | Docker

![Himanshu](himanshu.jpg)
