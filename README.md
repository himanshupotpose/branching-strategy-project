# branching-strategy-project

# Branching Strategy - SOP

## 1. Purpose
This document defines the standard branching strategy to be followed in this project.

## 2. Branch Types

### main
- Production ready code
- Direct commit not allowed

### develop
- Development and testing branch

### feature/*
- New feature development
- Created from develop
- Merged into develop

### bugfix/*
- Bug fixing
- Created from develop
- Merged into develop

### release/*
- Release preparation
- Created from develop
- Merged into main and develop

### hotfix/*
- Urgent production fix
- Created from main
- Merged into main and develop

## 3. Workflow
1. Create feature/bugfix branch
2. Do changes and commit
3. Create Pull Request
4. Review and merge
5. Delete branch after merge
