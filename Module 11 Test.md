## 🧪 Test Assignments & Brain Teasers

### 🎯 Objective

To assess your understanding of advanced version control concepts as they apply to documentation, and to challenge your ability to apply Git in high-velocity, real-world writing environments.

---

### 🧠 Brain Teasers

> These puzzles are intended to stretch your thinking and simulate real documentation scenarios under constraints.

---

#### 🔍 Teaser 1: The Vanishing Merge

You and a colleague both create branches and work on the same file. You merge your branch first. When your colleague tries to merge theirs, Git reports "already up to date" — but their changes never appear in `main`.

* ❓ What’s the most likely cause?
* 🔧 How would you verify and recover the missing work?

---

#### 🧩 Teaser 2: The Forked Fork

Your team is contributing to an upstream open-source project. You fork the repository, write docs, and submit a pull request. Mid-review, the original repo force-pushes changes to `main` that rewrite its history.

* ❓ What Git command(s) can help you rebase or realign your branch safely?
* 💡 What lessons can you draw about force-push policies in collaborative documentation?

---

#### 🛠 Teaser 3: The Commit Storm

A junior writer pushes 120 commits in one PR, each with messages like “fix typo,” “minor edit,” and “update.” Reviewers are overwhelmed and refuse to merge until the history is cleaned.

* ❓ How can you collapse these commits while preserving the author’s contribution?
* 🧬 What does this teach you about atomic commits and commit etiquette?

---

### ✅ Test Assignments

---

#### 📄 Assignment 1: PR-Driven Docs Workflow

> **Task:** Create a documentation repository that uses a feature-branch → PR → main merge model.

**Requirements:**

* Use GitHub Actions to lint Markdown.
* Create a pull request template.
* Demonstrate branching and merging best practices.
* Submit a changelog entry documenting your update.

✅ Deliverable: A link to your GitHub repository and PR example.

---

#### 🔐 Assignment 2: Secure and Auditable Documentation

> **Task:** Implement a secure documentation workflow with signed commits and traceable issue linking.

**Requirements:**

* Enable GPG commit signing on your machine.
* Link each commit to a corresponding GitHub Issue.
* Generate a `CHANGELOG.md` from commit messages using `auto-changelog` or a similar tool.

✅ Deliverable: A repository showcasing signed commits, linked issues, and changelog.

---

#### ⚙️ Assignment 3: CI/CD Docs Deployment

> **Task:** Configure a CI/CD pipeline that builds and deploys your docs to GitHub Pages using MkDocs or Docusaurus.

**Requirements:**

* Create a `.github/workflows/deploy.yml` file.
* Include a markdown linter and broken link checker.
* Automatically publish docs on `main` merge.

✅ Deliverable: A working GitHub Pages link and the CI YAML file.

---

#### 🔄 Assignment 4: Handling Complex Merge Conflicts

> **Task:** Simulate a merge conflict with another contributor and resolve it cleanly.

**Requirements:**

* Create two branches editing the same section of the same file.
* Trigger a merge conflict.
* Resolve the conflict using CLI or visual merge tools.
* Document the process and resolution rationale in a Markdown report.

✅ Deliverable: A `.md` report and Git log screenshot post-resolution.

---

### 📌 Submission Instructions

* Fork the `techopsapex/version-control-module` GitHub repository *(or create your own)*.
* Create a new branch named `assignment/<your-name>`.
* Complete the task in that branch.
* Open a pull request to merge it into your own `main`.
* Include a `README.md` explaining your implementation and learnings.
