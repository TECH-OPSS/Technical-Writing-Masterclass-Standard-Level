# 📘 Module 8: Editing and Proofreading

## 🧭 Overview

> “Editing separates good writing from great documentation.”

This module focuses on **advanced editing and proofreading** techniques essential for elevating technical documentation from functional to professional-grade. Great documentation isn’t just written; it’s refined. The process of editing brings clarity, correctness, and consistency, while proofreading ensures polish and reader readiness. Just as production code undergoes code reviews and testing, documentation should be held to similarly rigorous standards.

We'll explore how to:

* Apply deep content reviews for factual and technical accuracy
* Conform to professional style guides like the Microsoft Style Guide
* Detect and correct subtle tone, grammar, logic, and structure issues
* Implement workflows that mimic software QA for docs

---

## 🎯 Learning Objectives

By the end of this module, learners will be able to:

* Apply structural and sentence-level editing techniques
* Conduct full-document audits with attention to logic, flow, and clarity
* Adhere to style guides and brand tone requirements
* Set up effective peer-review, SME-review, and final approval workflows
* Proofread like a QA engineer, catching even hidden or contextual errors
* Track document versions and edits with precision

Each section includes:

* 🧠 Key Concepts
* ✍️ Editing Exercises
* ✅ Hands-On Tasks
* 💡 Brain Teasers

---

## 🧱 Section 1: Levels of Editing

### 🧠 Key Concepts

Editing occurs in layers, much like a software build. Each level refines a different aspect:

1. **Structural Editing (Macro Editing)**

   * Checks information hierarchy, logic flow, task sequence.
   * Is the document organized for its intended audience?
   * Does the user journey make sense?

2. **Content Editing (Substantive Editing)**

   * Clarifies meaning, removes ambiguities, and restructures dense content.
   * Evaluates completeness, accuracy, and user intent.

3. **Stylistic Editing (Tone & Consistency)**

   * Enforces voice and tone guidelines, tense consistency, and parallelism.
   * Matches style to the brand or platform (e.g., GitHub vs. Microsoft).

4. **Copyediting (Line Editing)**

   * Corrects grammar, punctuation, syntax, and mechanics.
   * Optimizes sentence length and phrasing.

5. **Proofreading (Final Polishing)**

   * Spots typos, formatting errors, broken links, UI inconsistencies.
   * Prepares for final publication.

### ✍️ Editing Exercise

Print a 2-page technical guide and do a multi-pass review:

* Pass 1: Restructure into task-first or role-first format
* Pass 2: Rewrite 3 long paragraphs using plain English principles
* Pass 3: Copyedit for grammar, consistency, and terminology

### ✅ Tasks

* Pick any outdated page from open-source docs and perform 5-tier editing
* Build a checklist for each editing layer with examples
* Edit a poorly written internal email using these techniques

### 💡 Brain Teasers

* Which level of editing saves the most time downstream?
* Can you skip a level and still ensure quality?
* How does editing differ between a tutorial and an API guide?

---

## 📘 Section 2: Working with Style Guides

### 🧠 Key Concepts

**Style guides** provide the rules and expectations for grammar, format, and tone. Consistent adherence improves readability and professionalism.

Popular style guides:

* **Microsoft Style Guide** – formal, structured, API-friendly
* **Google Developer Documentation Style Guide** – clean, technical, modular
* **Apple Style Guide** – concise, minimalist, user-first
* **Chicago Manual of Style** – traditional publishing standard

### Key Style Elements

* Voice and Tone: Friendly vs formal, direct vs indirect
* Headings and Lists: Numbered vs bulleted, title case vs sentence case
* Terminology: Consistent use of product names, actions, and UI labels
* Code Formatting: Inline vs block code, syntax highlighting, spacing
* Images and Captions: Alt text, labels, and placement rules

### ✍️ Editing Exercise

Choose 3 conflicting sentences from different docs and rewrite them to match:

* One Google style
* One Microsoft style
* One minimalist informal blog post

### ✅ Tasks

* Create a custom style guide for your team/product
* Implement a markdown linter (e.g., Vale) with a selected guide
* Audit a doc for violations against a chosen style guide

### 💡 Brain Teasers

* Can documentation have multiple tones across formats?
* How strict should enforcement of style guides be?
* Are all rules from big tech style guides applicable in startups?

---

## 🔄 Section 3: Review Workflows for Documentation

### 🧠 Key Concepts

Documentation needs review pipelines just like code:

* **Peer Review**: Fellow writers check for clarity and usability
* **SME Review**: Engineers, architects, and designers validate accuracy
* **Editor Review**: Professional editors apply structural, stylistic, and language cleanup
* **Managerial/Legal Review**: Ensures compliance, policy alignment, and public readiness

Workflow best practices:

* Define roles: Author, Reviewer, Approver
* Track changes using Git or a docs-as-code platform
* Use annotations, comments, or pull requests for collaboration
* Allow time for iterative feedback, not one-shot reviews

### Review Workflow Example:

```
1. Author submits draft via pull request
2. Peer reviews for flow and usability
3. SME confirms technical accuracy
4. Editor applies tone, grammar, and format polish
5. Manager approves final version for release
```

### ✍️ Editing Exercise

* Write a review protocol for your documentation team
* Conduct a peer review of a 1-page doc using a checklist
* Perform a before-and-after transformation on a wiki entry

### ✅ Tasks

* Build a review calendar for recurring doc audits
* Create version-control labels like `needs-SME`, `editorial-review`, `final-ready`
* Compare GitBook, Notion, and GitHub PRs for review management

### 💡 Brain Teasers

* Who has the final say on what gets published?
* Should SMEs be trained in editorial review techniques?
* What is the cost of skipping a peer review?

---

## 🔍 Section 4: Deep Proofreading Techniques

### 🧠 Key Concepts

Proofreading goes beyond spell-check. It includes:

* Visual layout inspection
* Link validation
* Terminology scanning
* Cross-referencing across pages
* Logic errors, e.g., "Step 2" missing or mismatched diagrams

**Error Categories**:

* Visual errors (alignment, spacing, font inconsistencies)
* Logical errors (wrong step order, mismatched code vs text)
* Semantic errors (incorrect terminology, wrong variable name)

**Advanced Tools**:

* **Grammarly / ProWritingAid** – Stylistic suggestions
* **Vale** – Style enforcement for docs-as-code
* **Languagetool + Regex-based scanners** – Custom rule definition
* **Deadlink checkers** – Automate link verification

### ✍️ Editing Exercise

* Create a proofreading checklist for API docs
* Highlight 10 types of errors in a doc and classify them
* Proofread a doc with both Grammarly and manual review, compare outputs

### ✅ Tasks

* Build a CI script that fails builds if style violations exist
* Run a full audit of a 10-page document using all tools
* Create a visual proofreading template (e.g., for UI-aligned screenshots)

### 💡 Brain Teasers

* Can AI tools replace human proofreaders?
* Is it better to proofread backward?
* How do you proofread your own writing objectively?

---

## 📁 Section 5: Version Control and Editorial History

### 🧠 Key Concepts

Tracking edits ensures transparency, collaboration, and rollback safety. Version control systems like Git are essential for maintaining editorial history.

**Best Practices**:

* Commit messages that indicate intent ("clarify endpoint usage")
* Branching for editorial review (`feature/user-guide-revision`)
* Tagging for releases (e.g., `v1.2-content-update`)
* Using changelogs or release notes to track documentation evolution

### Tools:

* GitHub / GitLab / Bitbucket for commits and pull requests
* Docs-as-code platforms like Docusaurus, MkDocs, GitBook
* Google Docs/Notion for revision history in collaborative settings

### ✍️ Editing Exercise

* Simulate a documentation release cycle using Git
* Write a changelog entry for a major documentation update
* Restore a broken document from previous commit history

### ✅ Tasks

* Set up a GitHub repo with `docs/` folder for versioned editing
* Annotate a changelog with what changed, why, and when
* Compare 3 revisions of a document and note the evolution

### 💡 Brain Teasers

* When should you create a new branch vs edit main?
* Should documentation have semantic versioning?
* Can readers benefit from knowing the edit history?

---

## 📌 Contextual Application: Production-Quality Documentation

Professional documentation should:

* Withstand review like code
* Reflect organizational tone and accuracy
* Minimize ambiguity and maximize clarity
* Be version-controlled, reproducible, and reviewable

**Scenarios**:

* **Onboarding Docs**: Help new engineers ramp up with no ambiguity
* **API Guides**: Precision and structure matter for developers
* **Legal & Compliance Docs**: Errors could introduce risk
* **Product Manuals**: Users need quick, clear, and confident directions

Adopt a "CI/CD mindset" for docs:

* Every change gets reviewed
* Style linting is enforced
* Docs are published only when passing all checks

---

## 👩‍🏫 Instructor Guidelines

* Run peer editing workshops using anonymized docs
* Invite SMEs to critique from technical POV, not just correctness
* Conduct side-by-side comparisons of before/after edits
* Grade using a rubric: Clarity, Accuracy, Style, Grammar, Structure

---

## 💡 Final Brain Teasers

* How do you know when editing is “done”? Can it ever be?
* Should proofreading guidelines differ for PDFs, blogs, and in-app docs?
* What’s the editing equivalent of a unit test?
* Can a tool be trained on your editorial voice?

---
