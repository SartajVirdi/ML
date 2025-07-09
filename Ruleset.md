# Branch Protection & Contribution Rules

This repository is configured with strict rules to maintain a clean commit history and prevent accidental changes to the `main` branch.

---

##  Branch Protection

- **Protected Branch:** `main`
- **Direct Pushes to `main`:** Blocked
- **Force Pushes:** Blocked
- **Branch Deletion:** Restricted
- **Allowed Merge Method:** Squash only (combines all commits into one for a clean history)

---

##  Pull Request Workflow

- **Pull Request (PR):** Required for all changes to `main`
- **Required Approvals:** `0` (solo project; no external reviewers needed)
- **Approval of Most Recent Push:** Not required
- **Conversation Resolution Before Merge:** Not required
- **Code Owner Review:** Not required

---

##  Permissions and Access

- **Only the repository admin (SartajVirdi)** can push, merge, or bypass protection rules
- **No other contributors or collaborators** are currently added
- Anyone else must fork the repository to contribute

---

##  Merge Strategy: Why Squash Only?

Squash merging is enforced because:
- It keeps `main` history clean and linear
- Removes noise from intermediate commits
- Easier to track meaningful changes per PR

---

##  Contribution Guidelines (for future collaborators)

1. Fork the repository or create a new branch
2. Make your changes in a clean, structured notebook or script
3. Submit a pull request to `main`
4. PR will be reviewed by the maintainer (SartajVirdi)

---

> **Note:** This ruleset is designed for a solo-maintained repository. It can be adapted later if external contributors join the project.
