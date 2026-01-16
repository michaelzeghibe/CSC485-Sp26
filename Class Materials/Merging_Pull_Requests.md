# Merging a Pull Request with GitHub Desktop

---

## What is a Pull Request (PR)?
A **pull request** is a request to merge changes from one branch into another (usually into `main`). It lets others review, test, and discuss changes before they become official.

---

## Before You Start
Make sure:
- You have **GitHub Desktop** installed and signed in
- You have **write access** to the repository
- The PR has **no unresolved conflicts** (or you are ready to fix them)

---

## Step-by-Step: Merge a PR in GitHub Desktop

### 1. Open the repository
- Open **GitHub Desktop**
- Select the correct repository from the top-left dropdown

---

### 2. Check out the pull request
- In the menu bar, click **Current Branch → Pull Requests**
- Select the pull request you want to merge
- Click **Checkout Pull Request**

➡️ This downloads the PR branch and switches you to it locally.

---

### 3. Review the changes
- Click the **Changes** tab
- Read through the file diffs
- (Optional) Run or test the project locally

Ask yourself:
- Does this do what it claims?
- Does it break anything?
- Is the code readable?

---

### 4. Merge into `main`
- Click **Branch → Merge into current branch**
- Choose `main` as the branch to merge into
- Click **Merge**

If there are conflicts:
- GitHub Desktop will show them clearly
- Fix the files
- Click **Continue merge** when done

---

### 5. Push the merge
- Click **Push origin**

✅ This completes the merge on GitHub.

---

## Important Notes

### Merge types
- **GitHub Desktop creates a merge commit**
- For *squash* or *rebase* merges, use GitHub.com

### PRs from forks
- GitHub Desktop handles forks automatically
- You can merge them the same way

### If you don’t need to run the code
- You can merge directly on **GitHub.com** instead

---

## Quick Checklist
- ☐ Checked out the PR  
- ☐ Reviewed the changes  
- ☐ Merged into `main`  
- ☐ Pushed to GitHub  

---

## Common Mistakes to Avoid
- ❌ Merging into the wrong branch
- ❌ Forgetting to push after merging
- ❌ Skipping review entirely

---