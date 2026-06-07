---
name: 🐛 Bug Report
about: Report a reproducible bug to help us improve
title: "fix: "
labels: ["bug", "needs-triage"]
assignees: ""
---

## 🐛 Bug Description

<!-- A clear and concise description of what the bug is. -->

## 🌿 Branch Info (Gitflow)

| Field | Value |
|---|---|
| **Affected branch** | `main` / `develop` / `release/x.x` / `hotfix/x.x` |
| **Fix target branch** | `hotfix/` (if `main`) or `bugfix/` (if `develop`) |

> **Gitflow note:** If this bug exists on `main`, a `hotfix/` branch should be cut from `main` and merged back into both `main` and `develop` once resolved. If it's only on `develop`, use a `bugfix/` branch off `develop`.

## 🔁 Steps to Reproduce

1. Go to '...'
2. Click on '...'
3. Scroll down to '...'
4. See error

## ✅ Expected Behavior

<!-- What you expected to happen. -->

## ❌ Actual Behavior

<!-- What actually happened. Include screenshots or logs if applicable. -->

## 🖥️ Environment

| Property | Value |
|---|---|
| OS | e.g. macOS 14, Windows 11 |
| Browser / Runtime | e.g. Chrome 124, Node 20 |
| App Version / Commit | e.g. v1.2.3 / `abc1234` |

## 📋 Additional Context

<!-- Add any other context about the problem here. Stack traces, related issues, etc. -->

## ✔️ Definition of Done

- [ ] Bug is reproducible and root cause identified
- [ ] Fix implemented on appropriate branch (`hotfix/` or `bugfix/`)
- [ ] Unit / regression test added to prevent recurrence
- [ ] PR opened targeting correct base branch
- [ ] `hotfix/` merged back into **both** `main` and `develop` (if applicable)
- [ ] Version bumped and `CHANGELOG.md` updated (for hotfixes)
