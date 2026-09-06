# 🛠️ Sheba Protocol — Project Activity

![Team](https://img.shields.io/badge/Team-Queen%20Sheba%20Protocol-2563EB?style=flat-square)
![Type](https://img.shields.io/badge/Type-Projects-EF4444?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-22C55E?style=flat-square)

Longer-term tools, scripts, and security projects built by **Sheba Protocol** members — individually or in small groups. This is where sustained, multi-week/month work lives, as opposed to daily logs or one-off CTF challenges.

---

## 🎯 Purpose

- House real, ongoing security tools/projects (scanners, automation scripts, dashboards, research tooling)
- Give members a place to build portfolio-worthy work with proper version history
- Support collaborative projects with more than one contributor, unlike the personal-folder repos

---

## 📂 Structure

```
Sheba-protocol-Project-Activity/
├── README.md
└── projects/
    ├── network-recon-toolkit/
    │   ├── README.md
    │   ├── src/
    │   └── ...
    ├── phishing-detector/
    │   ├── README.md
    │   └── ...
    └── alice-vuln-scanner/
        ├── README.md
        └── ...
```

- Each project gets **its own folder** with its own `README.md` — treat each like a mini-repo
- Name folders after the project, not the person (unless it's a solo personal tool — then `<name>-<project>` is fine)

---

## 🧾 Project README Template

Every project folder should have its own `README.md`:

```markdown
# <Project Name>

**Author(s):** 
**Status:** Planning / In Progress / Complete / Archived
**Category:** Automation / Detection / Offensive Tooling / Dashboard / Research

## What it does
Short description of the project's purpose.

## Tech stack
- 

## How to run it
```bash
# setup / usage commands
```

## Roadmap
- [ ] 
- [ ] 

## Notes
Anything else worth knowing — known limitations, design decisions, etc.
```

---

## 🏷️ Labels (for Issues — feature requests, bugs, roadmap items)

| Label | Use |
|---|---|
| `planning` | Idea stage, not yet started |
| `in-progress` | Actively being built |
| `help-wanted` | Looking for a collaborator |
| `bug` | Something's broken |
| `enhancement` | New feature idea |

---

## ✅ Contribution Rules

- Keep each project self-contained in its own folder with its own README
- Update project status in the README as it evolves — don't let it go stale
- If a project is abandoned, mark it `Archived` rather than deleting it — it's still useful learning history
- Solo projects are welcome, but tag teammates via `help-wanted` if you want a second contributor

---

## 🔗 Related Repos

| Repo | Purpose |
|---|---|
| `Sheba-protocol-Daily-Progress-Tracker` | Daily/weekly logs and commit tracking |
| `Sheba-protocol-Write-Up-Activity` | Formal, polished writeups |
| `Sheba-protocol-Project-Activity` | *(this repo)* Longer-term tools and projects |
| `Sheba-protocol-CTF-Activity` | Live CTF and practice logs |
