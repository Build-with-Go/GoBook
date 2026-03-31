# 🤝 Contributing to GoBook

Thank you for considering contributing to **GoBook**! 🎉  
Your help makes this list better for the entire Go community.

> 💡 **Note**: Packages marked with ⭐ in the README are created by [@ez0000001000000](https://github.com/ez0000001000000).

---

## 📋 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [How Can I Contribute?](#-how-can-i-contribute)
- [Adding a New Package](#-adding-a-new-package)
- [Pull Request Guidelines](#-pull-request-guidelines)
- [Style Guide](#-style-guide)
- [Review Process](#-review-process)
- [Questions?](#-questions)

---

## 🧭 Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of-conduct/). By participating, you agree to uphold this code. Please report unacceptable behavior to `hi@snowbasestudio.com`.

---

## 🙌 How Can I Contribute?

### ✨ Add a New Package
Found an awesome Go library that's missing from the list? [Open a PR](#-adding-a-new-package) to add it!

### 🐛 Fix a Typo or Broken Link
Spotted a typo, outdated description, or dead link? We'd love a quick fix!

### 💡 Suggest a New Category
Think a category is missing (e.g., "Networking", "Game Dev", "Embedded")? Open an issue to discuss it first.

### 📝 Improve Documentation
Better descriptions, clearer examples, or improved formatting? All welcome!

### 🔍 Report an Issue
Found a package that's no longer maintained, has a problematic license, or doesn't fit the criteria? Let us know via an issue.

---

## ➕ Adding a New Package

### ✅ Submission Checklist
Before submitting a package, please ensure it meets **all** of these criteria:

| Requirement | Details |
|-------------|---------|
| 🐹 Written in Go | The primary language must be Go (not a wrapper around another language) |
| 📦 Has `go.mod` | Must support Go modules (or be stdlib-compatible) |
| 🔄 Actively Maintained | Recent commits (within last 12 months) OR historically significant/stable |
| 📜 Open Source License | MIT, Apache 2.0, BSD, or similarly permissive license |
| 🔗 Public GitHub Repo | Must be publicly accessible (no private/internal repos) |
| 📖 Clear README | Repo should have basic documentation for users |

### 📝 How to Add an Entry

1. **Fork** the repo and create a new branch:
   ```bash
   git checkout -b feat/add-package-name
   ```

2. **Find the right category** in `README.md` (or propose a new one via issue first).

3. **Add your entry** in **alphabetical order** within that section using this format:
   ```markdown
   | [repo-name](https://github.com/user/repo) | Short, clear description (max ~120 chars). | [![Stars](https://img.shields.io/github/stars/user/repo?style=social)](https://github.com/user/repo) |
   ```

4. **Test your markdown**:
   - Ensure the link works
   - Verify the badge renders correctly
   - Check alphabetical ordering

5. **Commit with a clear message**:
   ```bash
   git commit -m "feat(utilities): add viper for configuration management"
   ```

6. **Push and open a PR**:
   ```bash
   git push origin feat/add-package-name
   ```
   Then open a PR at: https://github.com/Build-with-Go/GoBook/pulls

### 🎯 Example PR Description
```markdown
## What I'm adding
- Package: [viper](https://github.com/spf13/viper)
- Category: Utilities
- Description: Complete configuration solution for Go apps. Supports JSON, YAML, TOML, env vars.

## Why it belongs
- ✅  Many stars, widely used in production (Hugo, Cobra, etc.)
- ✅ Actively maintained with regular releases
- ✅ MIT license, pure Go, module-compatible
- ✅ Fills gap in config management category

## Checklist
- [ ] Entry follows alphabetical order
- [ ] Description is concise and accurate
- [ ] Badge link works correctly
- [ ] Repo meets all submission criteria
```

---

## 🔄 Pull Request Guidelines

### Before You Submit
- [ ] Your PR adds **one package per PR** (keeps reviews simple)
- [ ] You've checked that the package isn't already listed
- [ ] The entry follows the [Style Guide](#-style-guide) below
- [ ] All links and badges render correctly

### PR Title Format
Use this convention for easy triage:
```
feat(<category>): add <package-name>
```
Examples:
- `feat(scrapers): add rod for browser automation`
- `fix(utilities): correct typo in zap description`
- `docs: add messaging category to TOC`

### What Happens Next?
1. ✅ Automated checks run (link validation, markdown linting)
2. 👀 A maintainer reviews your PR within 3-5 days
3. 💬 Feedback may be requested (we're friendly!)
4. 🎉 Once approved, your PR is merged and the list updates

---

## ✍️ Style Guide

### Entry Format
```markdown
| [package-name](https://github.com/user/repo) | Clear, benefit-focused description. | [![Stars](badge-url)](repo-url) |
```

### Description Guidelines
- ✅ **Do**: Focus on *what it does* and *why it's useful*
- ✅ **Do**: Keep it under 120 characters for mobile readability
- ❌ **Don't**: Use marketing fluff ("best", "amazing", "revolutionary")
- ❌ **Don't**: Repeat the repo name unnecessarily

### Good vs. Bad Examples
| ✅ Good | ❌ Avoid |
|---------|----------|
| `Structured logging with JSON output and level filtering.` | `The best logging library ever created for Go!!!` |
| `Generate type-safe Go code from SQL queries.` | `A tool that does code gen stuff for databases.` |
| `Simple retry mechanism with exponential backoff.` | `Retry things when they fail sometimes.` |

### Badge Format
Always use this pattern for star badges:
```markdown
[![Stars](https://img.shields.io/github/stars/user/repo?style=social)](https://github.com/user/repo)
```

---

## 🔍 Review Process

### Maintainer Checklist
When reviewing a PR, maintainers verify:
- [ ] Package meets all [Submission Criteria](#-submission-checklist)
- [ ] Entry is in correct category and alphabetical order
- [ ] Description is accurate, concise, and neutral
- [ ] All links work and badges render
- [ ] License is compatible with open-source listing

### If Your PR Is Delayed
We aim to review all PRs within 5 business days. If it's been longer:
1. Check the PR for any requested changes
2. Politely comment: `@Build-with-Go/maintainers gentle ping on this PR 😊`
3. If still no response after 3 more days, open a brief issue referencing the PR

---

## ❓ Questions?

### Getting Help
- 💬 **Discussions**: https://github.com/Build-with-Go/GoBook/discussions
- 🐛 **Issues**: https://github.com/Build-with-Go/GoBook/issues

### Common Questions

**Q: Can I add my own package?**  
A: Yes! As long as it meets the [Submission Checklist](#-submission-checklist) and provides genuine value to the community. Self-promotion is fine when it's high-quality and relevant.

**Q: What if a package becomes unmaintained?**  
A: Open an issue or PR to add a `⚠️ Unmaintained` note, or suggest removal if no alternatives exist.

**Q: Can I suggest a package without adding it myself?**  
A: Absolutely! Open an issue with the repo link and why you think it belongs. Someone (maybe you!) can pick it up.

**Q: How are categories decided?**  
A: Categories evolve based on community needs. Propose new ones via issue with 3+ example packages that would fit.

---

## 🙏 Thank You!

Every contribution — big or small — helps make GoBook a better resource for Go developers worldwide. We appreciate your time and expertise! 🐹✨

> *"Alone we can do so little; together we can do so much."* — Helen Keller

[🏠 Back to README](README.md) • [📝 Open an Issue](https://github.com/Build-with-Go/GoBook/issues/new)
