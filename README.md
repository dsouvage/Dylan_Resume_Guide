# Dylan's Resume Guide

> A practical guide for getting interviews at large tech companies. Some advice is big-company specific — it may or may not apply to smaller shops, but the fundamentals transfer anywhere.

<p align="center">
  <img alt="Before and after resume transformation" src="./transformation.png" width="500" />
</p>

---

## Contents

- [Why listen to this?](#why-listen-to-this)
- [Resumizer — AI skill for Kiro](#resumizer--ai-skill-for-kiro)
- [Resume Guide](#resume-guide)
  - [1. Format](#1-format)
  - [2. Content and bullet points](#2-content-and-bullet-points)
  - [3. Projects](#3-projects)
  - [4. Skills](#4-skills)
- [Cover Letters](#cover-letters)
- [LinkedIn](#linkedin)
- [Useful Links](#useful-links)
- [FAQ](#faq)

---

## Why listen to this?

I landed internships coming out of a small Ontario university most people haven't heard of. That led to interviews and offers at Amazon, Microsoft, RBC, OPG, OMERS, and IBM. I've spoken with recruiters directly, attended events like Passport to Google, had my resume torn apart and rebuilt multiple times, and spent an embarrassing number of hours on `/r/cscareerquestions` and `/r/csmajors` so you don't have to.

The most important thing is to apply — a lot, early, and consistently. This guide helps you make sure each application has a real shot.

---

## Resumizer — AI skill for Kiro

This repo ships a **Resumizer** skill for [Kiro](https://kiro.dev), an AI coding and productivity tool. The skill turns weak or AI-generated resume content into tight, metric-driven bullets that pass ATS screening and hold a recruiter's attention.

**Install it in one step:**

Copy `resumizer.md` from this repo into your Kiro skills folder:

```
~/.kiro/skills/resumizer.md        # user-level (available in all workspaces)
.kiro/skills/resumizer.md          # workspace-level (scoped to one project)
```

**What it does:**

- Rewrites vague bullets ("Responsible for…", "Helped with…") into strong STAR-format bullets with action verbs and outcomes
- Flags AI-inflated language ("innovative," "transformative," "passionate about") and removes it
- Enforces ATS best practices: one-column layout, standard section names, .pdf/.docx format
- Asks for missing metrics before rewriting — it will never invent a number
- Handles bullet mode, section mode, full resume mode, and review/audit mode

**Example:**

```
Weak:   Responsible for helping the team improve the customer onboarding process.

Strong: Redesigned customer onboarding flow, cutting time-to-activation from 14 days
        to 3 and reducing support tickets by 40%.
```

See `resumizer.md` for the full skill spec and all modes.

---

## Resume Guide

### 1. Format

Keep it clean and standard. Recruiters process thousands of applications — a dense or flashy layout works against you. Exceptions exist for UI/UX and visual front-end roles.

**Recommended templates:**
- [Jake's Resume (LaTeX)](https://www.overleaf.com/latex/templates/jakes-resume/syzfjbzwjncs) — widely used, clean, ATS-safe
- [Moharnab's template (Overleaf)](https://www.overleaf.com/articles/moharnab-resume/jswvscyqsryt)
- [Rezi.io](https://www.rezi.io/) — online builder with ATS optimization

**Rules:**
- One column, 90% of the time, for companies with 100+ employees
- Submit as `.pdf` or `.docx` only — never `.pages`, `.txt`, or a Google Docs link
- Students and recent grads: **Education → Experience → Projects → Skills**
- No internships yet: **Education → Projects → Skills → Experience**
- One page if you have fewer than 10 years of experience; two pages only if the second page is full

### 2. Content and bullet points

Every experience bullet should follow **STAR format** — Situation, Task, Action, Result — with a data-driven result wherever possible.

**Structure:** `Action verb → what you did → result → metric`

**Resources:**
- [STAR format explained](https://en.wikipedia.org/wiki/Situation,_task,_action,_result)
- [Google's data-driven hiring process](https://www.washingtonpost.com/business/capitalbusiness/an-inside-look-at-googles-data-driven-job-interview-process/2013/09/03/648ea8b2-14bd-11e3-880b-7503237cc69d_story.html)
- [185 resume action verbs](https://www.themuse.com/advice/185-powerful-verbs-that-will-make-your-resume-awesome)

**Rules:**
- Start every bullet with a strong, unique action verb — don't repeat verbs within the same role
- Never start with "Responsible for," "Helped," "Worked on," or "Participated in"
- Include a metric, scope, or concrete outcome on every bullet
- 3–5 bullets per role; each bullet is one to two lines max

**Examples:**

```
Used X technology to solve Y problem resulting in Z achievement.

Engineered internal transcription middleware connected to Five9 API using NodeJS
and GCP to transcribe 10,000s of company voicemails, saving 1,000s of employee
hours monthly.
```

### 3. Projects

Include anything you can talk about in an interview. School projects count. Side projects count. Nothing needs to be 100% complete — it just needs to be real work you can explain.

Treat each project like a job entry: verb → what → result/scope.

**Examples:**
```
Built a Java application to create and traverse binary search trees using Preorder,
Postorder, and Inorder traversal algorithms.

Designed and deployed a personal portfolio site using React and GitHub Pages.
```

### 4. Skills

List anything you could speak to if an interviewer asked about it. Be honest about your depth — it's fine to note in person that something is introductory. A broad, honest list is better than a short curated one.

Group by category for long lists: Languages, Frameworks, Tools, Platforms.

---

## Cover Letters

Skip it if you're applying in bulk. Write one if you genuinely want the role.

A practical approach: write three versions with fill-in-the-blank company/role details so you can customize quickly without starting from scratch each time.

Data shows recruiters prefer cover letters when they exist, so for roles you care about, write one.

Source: [Does a cover letter actually matter?](https://www.reddit.com/r/ITCareerQuestions/comments/nqxfb6/does_a_cover_letter_actually_matter_will_anyone/)

---

## LinkedIn

My own success came mostly from mass applying, not LinkedIn, so take this with a grain of salt. That said:

- Get a good profile photo — [Photofeeler](https://www.photofeeler.com/my-tests) lets you crowdsource feedback; recruiters spend roughly 20% of their time on your photo
- Add lots of skills and get endorsed for them
- Be detailed in your work experience with results, not just job descriptions
- Connect with everyone — there is no downside to more connections
- [What to do on LinkedIn every month, week, and day](https://www.themuse.com/advice/what-you-should-be-doing-on-linkedin-every-month-week-and-day)
- [4 elements of a killer LinkedIn summary](https://www.themuse.com/advice/4-key-elements-of-a-killer-linkedin-summary)

---

## Useful Links

**Communities:**
- [r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/)
- [r/csmajors](https://www.reddit.com/r/csmajors/)
- [r/ITCareerQuestions](https://www.reddit.com/r/ITCareerQuestions/)

**Discords:**
- [CSMajors](https://discord.gg/Zukpvz9E47)
- [CSCareerQuestions](https://discord.gg/vq9VjeBWy9)
- [CS Careers Dev](https://discord.gg/CFuGHcmGCk)
- [UWaterloo](https://discord.gg/sAzqcCqS5W)

**Tools:**
- [ResumeWorded](https://resumeworded.com/) — automated resume feedback
- [CareerCup resume guide](https://www.careercup.com/resume)
- [Successful resume examples](https://www.careeers.org/resumes)
- [Breaking down a successful resume (LinkedIn post)](https://www.linkedin.com/posts/jonathan-wonsulting_resume-jobsearch-jwow-activity-6848632858454695936-CFjV)
- [Best time of day to submit applications](https://www.huffpost.com/entry/best-time-of-day-submit-job-application_l_60ae67d6e4b0d45b7531668c)

---

## FAQ

**What does your resume look like?**

It's probably not up to date, but here it is: [Dylan_Souvage_Resume.pdf](https://www.cosc.brocku.ca/~ds16bz/resume/Dylan_Souvage_Resume.pdf)

**Want a different guide?**

[CareerCup's resume guide](https://www.careercup.com/resume) is solid. [Careeers.org](https://www.careeers.org/resumes) has examples from people at top companies.
