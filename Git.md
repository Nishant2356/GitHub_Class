# 🚀 Git & GitHub Masterclass: Basics to Advanced
**Instructor:** Nishant Mishra


### Phase 1: Introduction
- [ ] History
- [ ] what is Git
- [ ] what is Github
- [ ] Installation and creating account.
- [ ] `git --version` (check if git exists)

### Phase 2: Configuration
- [ ] Creating a Repository in GitHub
- [ ] `git config --global user.name "My Name"` 
      `git config --global user.email "abcd@gmail.com"` 
      `git config --list`

### Phase 3: Clone & Status
- [ ] `git clone <repo link>` 
- [ ] `git status`
- [ ] `ls -h` (see all the files including hidden)

### Phase 4: Add & Commit
- [ ] `git add .` 
- [ ] `git commit -m "msg`
- [ ] `git push origin main` || `git push -u origin main`(to set upstream)  then   `git push`

### Phase 4: Init
- [ ] How to add local project in GitHub
      `git init`
      `git remote add origin <--link>`
      `git remote -v` (see the origin)
      `git branch` (see the branch)
      `git branch -M main` (rename branch)

### Phase 3: Connecting to the Cloud (GitHub)
- [ ] Create a new, empty repository on GitHub.com.
- [ ] Demo `git remote add origin <url>` (link local to cloud).
- [ ] Demo `git push -u origin main` (upload code).
- [ ] Explain `git clone` (how to download an existing repo).
- [ ] Explain `git pull` (how to fetch team members' updates).

### Phase 4: Branching (Intermediate Collaboration)
- [ ] Explain why we branch (isolated testing).
- [ ] Demo `git branch <name>` & `git switch <name>`.
- [ ] Demo the shortcut: `git checkout -b feature-update`.
- [ ] Make a change, commit it, and demo `git merge feature-update` into main.

### Phase 5: Advanced & "Oh-No" Moments
- [ ] Explain Merge Conflicts (when two people edit the exact same line).
- [ ] Demo `git stash` and `git stash pop` (hiding work temporarily).
- [ ] Demo `git revert <hash>` (the safe undo).
- [ ] Explain `git reset --hard` (the dangerous undo - warn them!).
- [ ] Open the floor for the Q&A session.

<br>

---

## 📋 Part 2: Team Cheat Sheet 
*Copy and paste the section below into the Google Meet chat or share as a GitHub Gist.*

**🚀 Git & GitHub Quick Cheat Sheet**

**1. Setup & Basics**
* `git init` - Create a new local repository in your current folder.
* `git clone <url>` - Download an existing repository from GitHub.
* `git status` - Check the state of your files (use this constantly!).

**2. The Daily Workflow**
* `git add .` - Stage ALL modified files to be saved.
* `git commit -m "Message"` - Save your staged changes locally with a note.
* `git push origin main` - Upload your saved local commits to GitHub.
* `git pull` - Download and merge the latest code from GitHub.

**3. Branching (Teamwork)**
* `git branch` - List all your local branches.
* `git checkout -b <branch_name>` - Create a new branch AND switch to it.
* `git merge <branch_name>` - Bring the code from another branch into your current one.

**4. Lifesavers**
* `git log` - View your commit history (press 'q' to exit).
* `git stash` - Temporarily hide your uncommitted changes.
* `git stash pop` - Bring those hidden changes back.
* `git revert <commit_hash>` - Safely undo a commit by creating a reverse commit.