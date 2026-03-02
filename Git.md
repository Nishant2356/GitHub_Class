# 🚀 Git & GitHub Masterclass: Basics to Advanced
**Instructor:** Nishant Mishra


### Phase 1: Introduction
- [ ] History
- [ ] what is Git & GitHub
- [ ] Installation and creating account.
- [ ] `git --version` (check if git exists)

### Phase 2: Configuration
- [ ] Creating a Repository in GitHub
- [ ] `git config --global user.name "My Name"` 
- [ ] `git config --global user.email "abcd@gmail.com"` 
- [ ] `git config --list`

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
- [ ] `git init`
- [ ] `git remote add origin <--link>`
- [ ] `git remote -v` (see the origin)
- [ ] `git branch` (see the branch)
- [ ] `git branch -M main` (rename branch)

### Phase 5: Branch
- [ ] `git branch` (see the branch)
- [ ] `git branch -M main` (rename branch)
- [ ] `git checkout <--branchname>` (navigate to branch)
- [ ] `git checkout <--new branchname>` (create a new branch and navigate immediately)
- [ ] `git branch -d <--branch_name>` (delete branch) (cannot delete the current branch you are standing at)

### Phase 4: Merge
- [ ] Method-1 (with git)
      `git diff <--branchname>` (to compare differences in branches)
      `git merge <--branchname>` (to merge 2 branches)
- [ ] Method-2 (with GitHub)
      create a Pull Request

- [ ] Resolving Merge Conflicts

### Phase 4: Undo Changes
- [ ] Staged Changes
        `git reset <--filename>`
        `git reset`
- [ ] One commit
        `git log` - View your commit history (press 'q' to exit)
        `git reset HARD~1`

- [ ] Many commits
        `git reset <-commit hash>`
        `git reset --hard <-commit hash>`

### Phase 5: Fork
- [ ] What is Fork and How to Do it.