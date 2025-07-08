# ✍️ Module 3: Structured Writing Process

> **Goal**: Learn how to plan, draft, and revise professional-quality technical documentation, with a focus on mid-length formats like help articles and tutorials.

---

## 🎯 Objective

Technical writing is not just about recording facts; it’s about **communicating effectively** through a clear, repeatable process. This module presents a structured workflow for writing that reduces confusion, shortens review cycles, and ensures clarity from draft to delivery.

We’ll walk through:

1. Outlining strategies
2. Drafting mechanics
3. Revision techniques
4. Structuring real-world help articles and tutorials

---

## 1️⃣ Documentation Workflow Overview

A professional documentation process typically follows this order:

```plaintext
Research → Outline → Draft → Review → Revise → Publish → Maintain
```

### 🔍 Why Follow a Structured Process?

* Aligns with engineering sprints and product releases
* Makes collaboration easier between writers, SMEs, and devs
* Encourages early feedback and reduces last-minute rewrites
* Enables consistent formatting, tone, and accuracy

🔗 [Read more on Atlassian’s Technical Writing Process](https://www.atlassian.com/team-playbook/plays/documentation)

### 🧪 Test Your Understanding

1. What are the six core phases of a structured writing workflow?
2. Why is the “Review” phase critical to the documentation lifecycle?
3. List two advantages of aligning documentation with product release cycles.

---

## 2️⃣ Phase 1: Outlining

Outlining ensures that a doc has structure **before** it has words.

### 🧱 Components of a Good Outline:

* **Title**: Clear and action-oriented (e.g., “Configure OAuth 2.0 in Your App”)
* **Objective**: What will the reader accomplish?
* **Audience**: Who is this for?
* **Pre-requisites**: What does the reader need first?
* **Steps or Sections**: Core content flow
* **Expected Outcome**: What should they see/do by the end?

### 🛠 Tools for Outlining:

* Google Docs (Headings View)
* Notion / Obsidian / Workflowy
* Markdown checklists in GitHub Issues or PR templates

> ✨ Bonus Tip: Create reusable templates for outlines per doc type.

🔗 [Outlining Techniques from Google Developer Docs Style Guide](https://developers.google.com/style/outlines)

### 🧪 Test Your Understanding

1. Why should outlining come before drafting?
2. Name three tools you can use to create outlines collaboratively.
3. How does defining the audience early affect the structure of the doc?

---

## 3️⃣ Phase 2: Drafting

Once the outline is validated, start drafting with clarity and consistency.

### ✍️ Drafting Best Practices:

* Write in **active voice**: “Click the button” instead of “The button should be clicked.”
* Use **parallel structure**: e.g., all bullet points begin with verbs
* Favor **short paragraphs** and clear lists
* Maintain **consistent terminology** (avoid flip-flopping between terms like “user” and “client”)
* Document **real commands, not placeholders**

### 🧠 Drafting in Layers:

1. First pass: Content structure only (use placeholders)
2. Second pass: Add precise instructions, links, screenshots
3. Third pass: Simplify language, refine tone

> 🔄 Drafting ≠ Finalizing. Focus on flow, not perfection.

🔗 [Read: Microsoft Docs – Writing with Style](https://learn.microsoft.com/en-us/style-guide/welcome/)

### 🧪 Test Your Understanding

1. What is the difference between active and passive voice? Provide an example.
2. Why is parallel structure important in documentation?
3. Describe the three layers of the drafting process.

---

## 4️⃣ Phase 3: Revising

Revisions turn **technically accurate content** into **user-empowering documentation**.

### 👁 Review Techniques:

* Read aloud for rhythm and clarity
* Ask a non-expert to follow the steps
* Use checklists (e.g., is there an intro, prerequisites, output examples?)
* Remove redundancies and filler

### ✨ Self-Review Checklist:

* ✅ Objective is clearly stated
* ✅ Steps are sequential and scannable
* ✅ All acronyms are defined on first use
* ✅ Code and output match live behavior
* ✅ Links, images, and formatting are correct

🔗 [TechWhirl – Revision & Editing Checklist](https://techwhirl.com/editing-checklist-technical-writers/)

### 🧪 Test Your Understanding

1. Why is “reading aloud” an effective review method?
2. What makes a good self-review checklist?
3. How do you ensure code snippets are accurate before publishing?

---

## 5️⃣ Mid-Length Document Structures

### 📄 Help Articles

These explain a single concept, task, or feature.

**Structure:**

1. Title: What the doc is about
2. Summary/Intro: Who this is for, what it does
3. Steps/Instructions: Numbered or bulleted
4. Visuals: Diagrams, screenshots, or UI highlights
5. Troubleshooting tips
6. See also: Related links or docs

**Example:** *“How to Reset Your API Token”*

🔗 [Zendesk Help Center Guide](https://support.zendesk.com/hc/en-us/articles/4408835917082)

### 👩‍🏫 Tutorials

These guide the reader through a **learning experience** or a longer setup process.

**Structure:**

1. Title: What they’ll build or learn
2. Objective: Skill or feature gained
3. Prerequisites: Tools, accounts, access needed
4. Step-by-step tasks:

   * Install / Setup
   * Configure
   * Build
   * Test
5. Final Outcome: What success looks like
6. Summary + What’s Next: Extend, link to other tutorials

**Example:** *“Build a Weather Dashboard Using OpenWeather API”*

🔗 [MDN Web Docs – Writing Tutorials](https://developer.mozilla.org/en-US/docs/MDN/Structures/Tutorial)

### 🧪 Test Your Understanding

1. What is the key difference between a help article and a tutorial?
2. Which document type benefits more from a “Final Outcome” section?
3. How can visuals enhance mid-length documents?

---

## 6️⃣ Tips for Using GitHub for Documentation Drafting

GitHub is a powerful place to draft and manage documentation, especially in teams.

### 💡 Suggested Workflow:

* Create issues for each doc draft
* Use PRs to review content collaboratively
* Use branches to draft docs safely without overwriting main content
* Apply labels like `needs-review`, `technical-approval`, `ready-to-publish`

### 📦 Use GitHub Templates:

```markdown
## Doc Title:
## Target Audience:
## Objective:
## Sections:
- [ ] Introduction
- [ ] Requirements
- [ ] Steps
- [ ] Examples / Output
- [ ] Troubleshooting
- [ ] Related Docs
```

🔗 [GitHub Docs: How to Write Docs](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis)

### 🧪 Test Your Understanding

1. What is the benefit of using PRs for documentation?
2. Name one label you can apply during doc review in GitHub.
3. How do you structure collaborative writing in GitHub safely?

---

## 7️⃣ Structured Writing Exercise: From Idea to Outline to Draft

**Scenario:** Write a help article for users who need to enable Two-Factor Authentication (2FA).

### Step 1 – Outline:

* **Title**: How to Enable 2FA on Your Account
* **Audience**: Account admins and users
* **Objective**: Enable 2FA for added security
* **Prerequisites**: Logged in, mobile device ready
* **Sections**:

  * What is 2FA?
  * Steps to enable
  * Confirming 2FA works
  * Troubleshooting login issues

### Step 2 – Draft:

```markdown
# How to Enable 2FA on Your Account

Two-Factor Authentication (2FA) adds an extra layer of security...

## Step 1: Log into your account
## Step 2: Go to Settings > Security
## Step 3: Click 'Enable 2FA'
## Step 4: Scan the QR code with your authenticator app
## Step 5: Enter the code to verify

🎉 You’ve successfully enabled 2FA!
```

---

## ✅ Wrap-Up: Writing with Intention

A structured writing process doesn’t limit creativity—it **guides it**. Whether you’re creating a quick-start tutorial, a product guide, or a troubleshooting article, following a reliable workflow ensures:

* 🧠 Better planning and fewer blockers
* 👥 Easier reviews and collaboration
* 📦 Faster time to publish with fewer revisions

📘 **Extended Reading**:

* [Google Developer Documentation Style Guide](https://developers.google.com/style)
* [Write the Docs Guide](https://www.writethedocs.org/guide/)

> Coming Next: **Module 4: Information Architecture for Technical Content**

---

*End of Module 3 – Structured Writing Process*
