---
name: 📖 Documentation
about: Report missing, incorrect, or outdated documentation
title: "docs: "
labels: ["documentation", "needs-triage"]
assignees: ""
---

## 📖 Documentation Issue Summary

<!-- A clear description of what is missing, wrong, or unclear in the documentation. -->

## 🌿 Branch Info (Gitflow)

| Field | Value |
|---|---|
| **Base branch** | `develop` |
| **Docs branch name** | `docs/<short-description>` |

> **Gitflow note:** Documentation changes that don't touch production code should branch from `develop` using a `docs/` prefix. If the docs fix accompanies a hotfix on `main`, it may be included in the `hotfix/` branch instead.

## 📍 Location of Issue

<!-- Where exactly is the documentation problem? Provide links, file paths, or section names. -->

- **File / URL:**
- **Section / Heading:**
- **Line(s):** (if applicable)

## 🔍 Type of Documentation Issue

<!-- Check all that apply -->

- [ ] Missing documentation (topic not covered at all)
- [ ] Incorrect information (something is factually wrong)
- [ ] Outdated content (was correct, but no longer reflects the current state)
- [ ] Unclear or ambiguous wording (hard to understand)
- [ ] Broken links or missing images
- [ ] Typos or grammar errors
- [ ] Other: ___

## 📝 Current Content (if applicable)

<!-- Paste or describe the existing content that needs to be changed. -->

```
(paste current content here)
```

## ✅ Suggested Improvement

<!-- What should it say instead? Provide a draft or clear description of the desired content. -->

```
(paste suggested content here)
```

## 📋 Additional Context

<!-- Any other relevant information — related issues, PRs, release that introduced the change, etc. -->

## ✔️ Definition of Done

- [ ] Docs branch `docs/<name>` created from `develop`
- [ ] Content updated and verified for accuracy
- [ ] All links checked and working
- [ ] Spelling and grammar reviewed
- [ ] PR opened targeting `develop`
- [ ] Reviewed and approved by at least one maintainer
