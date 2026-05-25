# Version-control-system-git
Version Control System - Git

What is Git?
Git is a Distributed Version Control System (VCS) used to track changes in files and source code during software development. It helps developers collaborate, manage project history, and restore previous versions when needed.

Official Website: Git
Why Use Git?
Tracks Changes in code and files
Collaborate with Teams efficiently
Backup & Restore previous versions
Manage Multiple Features using branches
Maintain Project History
Supports Open Source Contributions

Key Features of Git
1. Distributed System

Every developer has a complete copy of the repository.

2. Fast Performance

Git operations are quick and lightweight.

3. Branching & Merging

Create separate branches for features and merge them later.

4. Secure

Uses SHA hashing for data integrity.

5. Open Source

Free and widely used across the software industry.

Basic Git Workflow
Working Directory → Staging Area → Local Repository → Remote Repository
Common Git Commands
Initialize Repository
git init

Creates a new Git repository.

Check Repository Status
git status

Displays changed and staged files.

Add Files
git add filename

Add a specific file.

git add .

Add all files.

Commit Changes
git commit -m "Initial Commit"

Saves changes permanently.

View Commit History
git log

Shows project commit history.

Create Branch
git branch feature-name

Creates a new branch.

Switch Branch
git checkout feature-name

Moves to another branch.

Merge Branch
git merge feature-name

Combines branches together.

Clone Repository
git clone repository_url

Copies an existing repository.

Push Changes
git push origin main

Uploads code to remote repository.

Pull Latest Changes
git pull origin main

Downloads latest updates.

Git vs GitHub
Git	GitHub
Version Control Tool	Cloud Hosting Platform
Works Locally	Works Online
Tracks Code Changes	Hosts Git Repositories
Command Line Based	Web-Based Collaboration

GitHub Website: GitHub

Advantages of Git
Easy collaboration
Better project management
Efficient version tracking
Safe experimentation with branches
Industry-standard development tool

Applications of Git
Web Development
Open Source Projects
Data Science Projects
Machine Learning Projects
Team Collaboration
DevOps Workflows

Simple Git Upload Workflow
git init
git add .
git commit -m "First Commit"
git branch -M main
git remote add origin REPOSITORY_URL
git push -u origin main
