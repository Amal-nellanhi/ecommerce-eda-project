# 🚀 Contributing Guidelines

Thank you for contributing to this project!  
To maintain a clean workflow and avoid conflicts, please follow the guidelines below.

---

## 🛑 1. Do NOT commit directly to `main`
The `main` branch is protected.  
All changes must go through a **feature branch** and a **pull request**.

---

## 📝 2. Start With an Issue
Every task begins with a GitHub **Issue**.

1. Go to **Issues → New Issue**
2. Describe the task clearly
3. Assign yourself or get assigned
4. Discuss requirements in comments if needed

---

## 🌿 3. Create a Feature Branch

Use this branch name pattern:

```
feature/<issue-number>-<short-task-name>
```

Examples:
- `feature/1-readme`
- `feature/3-folder-structure`
- `feature/5-initial-eda`

Create your branch:

```bash
git checkout -b feature/<issue-number>-<task>
```

---

## ✏️ 4. Work on Your Branch
Add your code, files, documentation, or changes only inside your branch.

---

## 💾 5. Commit Your Changes

Use meaningful commit messages:

```bash
git add .
git commit -m "Add README first draft"
```

---

## 🚀 6. Push Your Branch to GitHub

```bash
git push origin feature/<issue-number>-<task>
```

---

## 🔀 7. Open a Pull Request (PR)

1. Go to the repository on GitHub  
2. Click **Compare & pull request**  
3. Add a short title and description  
4. Link your issue:

```
Closes #<issue-number>
```

---

## 👀 8. Review Process

- At least **one approval** is required before merging  
- All comments and requested changes must be resolved  
- No merge allowed if conversations are unresolved

---

## ✅ 9. Merge the Pull Request

Once approved:
- Click **Merge pull request**
- The linked issue will close automatically

---

## 🧹 10. Clean Up Local Branches

After merging:

```bash
git branch -d feature/<issue-number>-<task>
```

---

# 🙌 Thank You!

Following this workflow helps us:
- Avoid merge conflicts  
- Keep the repository organized  
- Maintain clean and readable history  
- Work efficiently as a team  

Happy contributing! 🎉