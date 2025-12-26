# Git and GitHub Instructions

## How to add existing folder to Github:

**Step 1:** Go to existing directory/ folder which you need to upload on github
**Step 2:** `git init`
**Step 3:** `git add .`
**Step 4:** `git commit -m "initial commit"`
**Step 5:** `git remote add origin https://github.com/your-username/your-repo-name.git`
**Step 6:** `git branch -M main`
**Step 7:** `git push -u origin main`

---

## Context Specific Commands:

### Pushing changes to a different branch instead of main:
**Step 1:** `git branch`
**Step 2:** `git checkout your-branch-name`
**Step 3:** `git add .`
**Step 4:** `git commit -m "Your commit message"`
**Step 5:** `git push origin your-branch-name`

*If the branch doesn't exist on GitHub yet:*
`git push -u origin your-branch-name`

---

### Handling Error: "error: pathspec 'develop' did not match any file(s) known to git"
If you created the `develop` branch on GitHub first and get this error locally:

**Step 1:** `git fetch origin`
**Step 2:** `git checkout -b develop origin/develop`

---

### To push changes into develop branch:
**Step 1:** `git branch`
**Step 2:** `git add .`
**Step 3:** `git commit -m "Your commit message"`
**Step 4:** `git push origin develop`
